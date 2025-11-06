from collections import deque

graph = {
    "Company A": ["Company B", "Company C"],
    "Company B": ["Company D"],
    "Company C": ["Company D"],
    "Company D": ["Company E", "Company F"],
    "Company E": [],
    "Company F": [],
    "Company G": []
}

def bfs_influence(graph, start_company, max_depth=2):
    queue = deque([[start_company, 0]])
    visited = set([start_company])
    impacted_companies = []
while queue:
        current_company, depth = queue.popleft()
        if depth == max_depth:
            continue

  for neighbor in graph.get(current_company, []):
            if neighbor not in visited:
                visited.add(neighbor)
                impacted_companies.append(neighbor)
                queue.append([neighbor, depth + 1])

   return impacted_companies

starting_company = "Company A"
impacted = bfs_influence(graph, starting_company, max_depth=2)
print(f"If {starting_company} experiences a significant event, companies may be impacted:")
for company in impacted:
    print(company)

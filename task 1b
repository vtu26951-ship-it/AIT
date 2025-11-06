weather_graph = {
    'station A': ['station B', 'station C'],
    'station B': ['station D'],
    'station C': ['station F'],
    'station D': ['station E'],
    'station E': [],
    'station F': [],
    'station P': []
}

weather_data = {
    'station A': 'sunny',
    'station B': 'cloudy',
    'station C': 'rainy',
    'station D': 'stormy',
    'station E': 'windy',
    'station F': 'snowy'
}

def dfs(graph, node, visited):
    if node not in visited:
        print(f"{node} reports: {weather_data[node]}")
        visited.add(node)
        for neighbor in graph[node]:
            dfs(graph, neighbor, visited)

if __name__ == "__main__":
    visited = set()
    print("Weather forecast (DFS):")
    dfs(weather_graph, 'station A', visited)

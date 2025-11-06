# Define a list of facts
facts = [
    "john_is_cold.",              # John is cold
    "raining.",                   # It is raining
    "john_Forgot_His_Raincoat.",  # John forgot his raincoat
    "fred_lost_his_car_keys.",    # Fred lost his car keys
    "peter_footballer.",          # Peter plays football
    "foggy.",                     # It is foggy
    "Cloudy.",                    # It is cloudy
    "john_went_outside.",         # John went outside
    "mary_is_happy.",             # Mary is happy
    "sunny."                      # It is sunny
]

# Function to check if a fact is true
def verify_fact(fact):
    # Remove the trailing period
    fact = fact.rstrip(".")

    # Verify the fact using simple logic
    if fact == "john_Forgot_His_Raincoat":
        return True
    elif fact == "raining":
        return True
    elif fact == "foggy":
        return True
    elif fact == "Cloudy":
        return False
    elif fact == "john_is_cold":
        return False
    elif fact == "fred_lost_his_car_keys":
        return False
    elif fact == "peter_footballer":
        return False
    elif fact == "john_went_outside":
        return True
    elif fact == "mary_is_happy":
        return True
    elif fact == "sunny":
        return False
    else:
        return False

# Verify each fact and print result
for fact in facts:
    if verify_fact(fact):
        print(f"{fact} - Yes")
    else:
        print(f"{fact} - No")

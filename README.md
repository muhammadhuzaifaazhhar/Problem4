# Problem4
# Problem 4: Appliance Warranty

# Get user input for name and cost of an appliance
appliance_name = input("Enter the name of the appliance: ")
appliance_cost = float(input("Enter the cost of the appliance: "))

# Determine warranty cost based on appliance cost
if appliance_cost > 1000:
    warranty_cost = 0.10 * appliance_cost
else:
    warranty_cost = 0.05 * appliance_cost

# Calculate total cost
total_cost = appliance_cost + warranty_cost

# Display results
print(f"\nAppliance: {appliance_name}")
print(f"Appliance Cost: ${appliance_cost:.2f}")
print(f"Warranty Cost: ${warranty_cost:.2f}")
print(f"Total Cost: ${total_cost:.2f}")

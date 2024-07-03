# Waste Removal Simulation
This repository contains a waste removal simulation model where a truck collects waste from farms and transports it to waste drop-off sites. The goal is to optimize fuel consumption and maximize waste collected by implementing different strategies for the truck's movement and collection decisions.

## Strategies
Three primary strategies are implemented in the simulation:

1. Random Strategy
2. Greedy Fuel Strategy
3. Greedy Waste Strategy

Refer to the detailed report for explanations of each strategy's rules and assumptions.

## Parameters
The simulation's behavior and performance are affected by the following parameters:

- num_waste_sites: Number of waste sites in the simulation.
- num_farms: Number of farms in the simulation.
- max_truck_cap: Maximum waste capacity of the truck.
- max_fuel_cap: Maximum fuel capacity of the truck.
- max_time_steps: Maximum number of steps allowed for the simulation.
- fig_on: Boolean to indicate whether to display the animation or not.

## Output Measurements
The performance of the waste removal strategies is evaluated using the following output measurements:

- Total Waste Collected: Represents the total amount of waste collected by the truck during the simulation.
- Total Fuel Consumed: Represents the total amount of fuel consumed by the truck during the simulation.

By analyzing these output measurements, we can draw insights into the performance of each strategy under various conditions and evaluate their effectiveness in the waste removal simulation.

For a more in-depth explanation of the strategies, rules, assumptions, and parameters, please refer to the full report in the repository.

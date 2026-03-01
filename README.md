# simulation.py

import random

print("Republic AI Economic Simulation Started")

agents = 5
market_price = 100

for i in range(agents):
    decision = random.choice(["buy", "sell", "hold"])
    print(f"Agent {i+1} decision: {decision}")

print("Simulation completed.")
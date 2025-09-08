# Ex-1-Developing-AI-Agent-with-PEAS-Description
### Name:
### Register Number:
### Aim:
To find the PEAS description for the given AI problem and develop an AI agent.
### Theory :
PEAS stands for:

Performance measure

Environment

Actuators

Sensors

It’s a framework used to define the task environment for an AI agent clearly.

### Algorithm:
Step 1: Initialize:

Set agent’s location to A

Set environment dirt status for locations A and B (True = dirty, False = clean)

Step 2 :Repeat until all locations are clean (no dirt):
a. Sense if current location has dirt
b. If current location has dirt:
- Suck dirt (set dirt status at current location to False)
c. Else:
- If current location is A, move right to location B
- Else if current location is B, move left to location A
d. Print the agent’s current location and dirt status (optional for debugging)

Step 3: Stop when all locations are clean

Step 4: Print total steps taken (optional)

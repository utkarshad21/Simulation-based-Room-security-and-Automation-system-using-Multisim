# Simulation-based-Room-security-and-Automation-system-using-Multisim

SCENARIO

A room has a Digital Lock requiring a 5-digit binary pin. A correct pin unlocks the door. Inside, a Motion Detector turns on the Light Bulb and checks the temperature; if high, the Air Conditioner activates. Three incorrect pin attempts trigger an alarm and notify the owner, but the counter resets if a correct pin is entered beforehand. If the door is unlocked and movement is detected, the alarm will go off, and the owner will be notified.

FLOWCHART FOR PROJECT

![image](https://github.com/user-attachments/assets/42511d0a-0f3f-480b-966b-b63136896a11)

CIRCUIT SIMULATION SCREENSHOT

![image](https://github.com/user-attachments/assets/e20e926e-6977-4925-ad45-fe276160c32a)

PROBLEM BREAKDOWN

Step 1: Generate a password-checking system that checks 5-digit inputs.
Step 2: Make a Counter that can check several times if a wrong pin is entered.
Step 3: Make an alarm that goes off if n number of times the wrong pin is given or there's unexpected movement.
Step 4: Make a light bulb and AC that can be turned on conditionally.
Step 5: Combining all the above-mentioned small systems.

SOLUTION

Step 1: To check whether all the inputs are the same using the XNOR gate.
Step 2: Can make a Counter using JK flip-flop. 
Step 3: An alarm system can be made using a few logic gates. 
Step 4: The light bulb and AC can be turned on with logic gates.


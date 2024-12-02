# Car-Dealer
Car selection - Python Interactive Program




This Python script simulates a car dealership experience, allowing users to select a car based on their preferred brand and model. The program is interactive and uses a loop to ensure customer satisfaction before completing the transaction. Below is a breakdown of the script's functionality:

Features
Welcome Message: The program greets users with a friendly message, setting a welcoming tone.
Company Selection: Users can choose from four car brands:
Honda
Toyota
Suzuki
Nissan
Model Selection: Each company offers four car models for the user to select.
Satisfaction Check: After a car is selected, the user is asked if they are satisfied with their choice. If not, they can restart the selection process.
Loop for Multiple Attempts: The program uses a while loop to allow users to explore various options until they are satisfied.
Input Validation: The program ensures valid input at each step, providing error messages for invalid choices.
Code Highlights
Interactive Inputs: The program uses input() for user interaction at each step.
Nested Conditions: It employs if-elif-else statements to handle user choices for brands and models.
Repeat Mechanism: The program re-prompts users until a satisfactory decision is made, ensuring a user-friendly experience.
Personalized Feedback: After selecting a car, the user is thanked or allowed to explore further options.
Usage
This script is perfect for beginners to understand:

Nested conditions
Loops
User interaction in Python
Simulation of a real-world scenario



###Example Run



welcome to YM Car Dealers
which company car do you want to buy? 
a=Honda 
b=Toyota 
c=Suzuki 
d=Nissan
> a
which Honda car are you interested to buy? 
a=Civic 
b=City 
c=Vezel 
d=CRZ
> a
have your Civic
Are you satisfied with the car? (y/n)
> y
Thanks for buying the car!

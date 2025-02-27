🚗 DrivingSimulator

DrivingSimulator is a Java-based application that simulates the basic functionalities of a car. This project allows users to start the car, change gears, accelerate, brake, and exit the simulation.

✨ Features
Turn on/off the engine: Start or stop the car engine.
Change gear: Switch between Park (P), Drive (D), and Reverse (R) gears.
Accelerate: Increase the speed of the car.
Brake: Decrease the speed of the car.
Exit: Terminate the simulation.
🛠️ Installation
Clone the repository:
sh
Copy
Edit
git clone https://github.com/MichelleMotlana/DrivingSimulator.git
Navigate to the project directory:
sh
Copy
Edit
cd DrivingSimulator
Compile the Java source files:
sh
Copy
Edit
javac com/example/DrivingSimulator.java
Run the application:
sh
Copy
Edit
java com.example.DrivingSimulator
🚀 Usage
Upon running the application, you will be presented with a menu that allows you to control the car. The following options are available:

Turn on/off the engine
Change gear (P, D, R)
Accelerate
Brake
Exit
📄 Code Overview
The main class DrivingSimulator contains the following methods:

startSimulation(): Starts the car simulation.
displayDashboard(): Displays the car dashboard with the current state and menu options.
getUserChoice(): Gets the user's choice from the menu.
processChoice(int choice): Processes the user's choice from the menu.
toggleEngine(): Toggles the engine state.
changeGear(): Allows changing the gear according to user input.
accelerate(): Accelerates the car based on the condition.
brake(): Applies the brake according to the condition.
exitSimulation(): Terminates the simulation.

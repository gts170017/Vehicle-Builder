Vehicle Builder CLI Application
Description
A TypeScript-based command-line application that allows users to create, manage, and interact with different types of vehicles (Car, Truck, Motorbike).
Features

Create vehicles (Car, Truck, Motorbike)
Perform actions on vehicles:

Start/stop vehicle
Accelerate/decelerate
Turn left/right
Reverse
Tow (for Trucks)
Wheelie (for Motorbikes)

Installation

Clone the repository

How to Run

Navigate to the src directory:

cd Develop/src

Install dependencies:

npm install

Run the application:

npm start

src/: TypeScript source files
dist/: Compiled JavaScript files
interfaces/: TypeScript interface definitions
classes/: Vehicle and utility class implementations

Technologies Used

TypeScript
Inquirer.js (for CLI interactions)

Development Notes
During development, I encountered a significant challenge when I accidentally deleted some critical files from the GitHub repository due to misconfigured Git settings and folder structure. After several hours of troubleshooting, I was able to recover and reconstruct the project by carefully merging branches and restoring the correct file hierarchy. This experience reinforced the importance of proper Git workflow practices, especially when working with nested directory structures and TypeScript compilation.

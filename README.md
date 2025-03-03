# calculator_demo
calculator app for teaching DevOps

Explanation of classes:

|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Class	                                             | Purpose                                                                                                  |
|----------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| Calculator                                         | Core logic — receives inputs and coordinates calling the right operation class.                          |
| CalculatorApp	                                     | Main class — handles the program entry point (e.g., command line input).                                 |
| InputHandler	                                     | Handles reading user input (to decouple input logic from core logic).                                    |
| ResultFormatter	                                 | Formats the result for printing (good intro to separating concerns).                                     |
| Addition / Subtraction / Multiplication / Division | One class per operation (shows OOP nicely).                                                              |
| Tests	                                             | Each operation and main calculator logic gets its own test class — shows how to do unit testing in Java. |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
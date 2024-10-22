# Birthday Simulator

This Python program simulates the birthdays of a specified number of people and calculates the probability that at least two individuals share the same birthday. 
The program generates random birthdays while considering the variations in the number of days in different months, including a weighted approach for February to account for leap years.

## Features

- **Random Birthday Generation**: Assigns random birthdays to each person, ensuring correct day limits based on the month.
- **Probability Calculation**: Computes the probability that at least two people in a room share the same birthday using the Birthday Paradox formula.
- **Duplicate Detection**: Checks for any shared birthdays and lists the individuals who share the same date.

## How to Run the Program

1. Ensure you have Python installed on your machine.
2. Clone this repository or download the code file.
3. Open your terminal (or command prompt) and navigate to the directory containing the script.
4. Run the program using the following command:

   ```bash
   python birthday_simulator.py

5.Input the number of people when prompted.

## Example Output

How many people? 23
Here's how our room looks like:
Person 1's birthday: January 15
Person 2's birthday: March 2
...
The probability that at least two people have the same birthday is nearly 50.73%
In our simulation, no two people have the same birthday.

## Requirements
Python 3.x
No external libraries are required.
## Author
Amani Daroui

## License
This project is licensed under the MIT License.

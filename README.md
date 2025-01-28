# Tip Calculator Program
This Python program calculates the tip based on the cost of a meal and the percentage you want to tip. The program takes the price of the meal and the tip percentage as input, then outputs the exact amount to leave as a tip.

Requirements:
Python 3.x

How to Use:
Run the script.
When prompted, enter the cost of the meal in dollars (e.g., $45.00).
Enter the tip percentage you would like to leave (e.g., 15%).
The program will calculate and print the tip amount, formatted to two decimal places.

Example:
Input:
How much was the meal? $50.00
What percentage would you like to tip? 20%
Output:
Leave $10.00

Input:
How much was the meal? $30.25
What percentage would you like to tip? 18%
Output:
Leave $5.45

How It Works:
The program prompts the user for the cost of the meal and the desired tip percentage.
The dollars_to_float function strips the dollar sign ($) and converts the string to a float.
The percent_to_float function strips the percent sign (%), converts the string to a float, and divides by 100 to get the percentage as a decimal.
The program calculates the tip by multiplying the meal cost by the percentage.
The tip amount is then printed, rounded to two decimal places.

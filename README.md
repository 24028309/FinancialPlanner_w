# FinancialPlanner_w
# Personal Budget Planning Application
# Overview
# This Java-based command-line application is designed to help users manage their personal budget by tracking monthly income, tax deductions and  expenses, and making informed decisions about accommodation and vehicle purchases. The application provides functionalities for calculating home loan repayments, monitoring expenses, and ensuring that total expenses stay within a reasonable limit of the user's income.

# This project is implemented using Java and developed in NetBeans IDE, with a focus on following internationally acceptable coding standards, utilizing object-oriented principles like inheritance, and employing advanced Java features such as generic collections and delegates.

# Features
# Part 1 —Budgeting Features
# 1.User Input:

# Gross monthly income, before deductions.
# Estimated monthly tax deductions.
# Monthly expenditures in the following categories:
# Groceries
# Water and lights
# Travel costs (including petrol)
# Cell phone and telephone
# Other expenses

# 2.Accommodation Selection:
# Option to choose between renting accommodation or buying a property.

# 3.Renting:
# If renting, the user enters the monthly rental amount.

# 4.Buying Property (Home Loan):
# a. Input values:
#  Purchase price of the property.
#  Total deposit.
# Interest rate (percentage).
#  Number of months to repay (between 240 and 360 months).
# b. The application calculates the monthly home loan repayment.
# c. It notifies the user if the home loan repayment exceeds one-third of their gross monthly income, suggesting that loan approval might be unlikely.

# 5.Budget Summary:
# After accounting for tax, accommodation, and other expenses, the software calculates the available monthly money.

# Part 2 — Advanced Features
# 1.Vehicle Purchase Option:

# a. Option to buy a vehicle and input the following details:
# Make and model.
#  Purchase price.
# Total deposit.
#  Interest rate (percentage).
#  Estimated insurance premium.
# b. The application calculates the total monthly vehicle cost (loan repayment + insurance).

# 2.Expense Monitoring:
# The software notifies the user if total monthly expenses exceed 75% of their income.

# 3.Sorting Expenses:
# Displays all expenses to the user, sorted in descending order by value.

# Non-Functional Requirements
# a. Code follows international coding standards.
# b. Comprehensive comments are included to explain variable names, methods, and logic.
# c. Inheritance is used, with an abstract class Expense for expenses such as home loan and vehicle purchases.
# d. Expenses are stored in a generic collection, allowing for flexibility and easy manipulation.
# e. A delegate is implemented to notify the user when expenses exceed 75% of their income.

# Installation Instructions
# 1.Prerequisites:

# a. Java Development Kit (JDK) version 8 or higher.
# b. NetBeans IDE (or any other compatible IDE).
# d. Basic command-line interface (CLI) knowledge.

# 2.Clone the Repository:
# Use the following command line to clone the project repository
# git clone <repository-URL>

# 3.Compile the Application:
# a. Open the project in NetBeans or any other Java IDE.
# b. Build the project using the IDE's build tools, or do it manually .java files using the command line:
# javac build/*.java (bash)

# 4.Run the Application:
# a. Inside NetBeans, right-click the main class and select Run.
# java build/part1I (bash)

# #Usage Instructions
# 1.Run the Application:
# Start the application from the terminal or IDE.

# 2.Follow the Prompts:

# a. Enter your gross monthly income, tax deductions, and expenses when prompted.
# b. Choose whether you are renting or buying a property, and enter the necessary details accordingly.
# c. If applicable, choose to buy a vehicle and input the relevant financing information.

# 3.Review Results:
# a. The application will display:
# b. Monthly home loan repayment or rental cost.
# c. Total expenses.
# d. Available monthly money after all deductions.
# e. Notification if loan approval is unlikely or if expenses exceed 75%  
#   of  your income.

# Project Structure

# build/
#   Part1I.java                - Main class, entry point for the program
#  expenses/                  - Package containing all expense-related classes
#       Expense.java           - Abstract class for expense management
#      Groceries.java         - Class for grocery expenses
#       Utilities.java         - Class for utilities expenses (water and lights)
#       Travel.java            - Class for travel-related expenses
#      Communication.java     - Class for communication-related expenses
#       otherExpenses.java     - Class for other expenses
#      Renting.java           - Class for managing rental expenses
#       Buying.java            - Class for managing home loan expenses

# License
# https://github.com/24071968
# https://github.com/23007306
# https://github.com/24028309
# https://github.com/23018897

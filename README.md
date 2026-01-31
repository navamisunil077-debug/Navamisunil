Expense Analyser App
Overview

The Expense Analyser App is a mobile application developed using MIT App Inventor that helps users categorize their daily expenses by selecting their daily spending items. The application records each expense and calculates the total expense for these daily items on a monthly basis, allowing users to easily track, analyze, and manage their spending.

Features

Add daily expenses with category and amount

Secure user registration and login

Record and categorize daily expenses

Monthly expense calculation

Easy expense tracking and analysis

Problem Statement

Managing daily expenses manually is time-consuming and often leads to inaccurate tracking of personal finances. Many individuals find it difficult to categorize their daily spending, calculate monthly expenses, and analyze where their money is being spent. Traditional methods such as handwritten notes or basic spreadsheets do not provide an efficient, user-friendly, or secure way to track expenses regularly.

The Expense Analyser App addresses this problem by providing a structured and secure mobile solution for expense categorization and monthly expense calculation.

Components Used
TinyDB
Used for storing user login and signup details
Stores expense records locally for each user
 User Interface Components
Labels – Display text and headings
TextBoxes – Input fields for username, password, amount, and descriptions
Buttons – Used for login, signup, saving expenses, calculating totals, and sharing reports

ListPicker – Allows users to select expense categories and daily items easily

 Sharing Component

Enables users to share expense data via messaging applications

 Web Component

Used for integrating Google Sheets

Helps in storing and syncing expense data online

 Map Component

Shows the location of expenses using latitude and longitude

Helps users track where expenses are incurred

Working Flow of the Expense Analyser App

.User Registration

New users create an account using the Signup option.

User credentials are stored securely using TinyDB.

.User Login

Registered users log in using their username and password.

Authentication is verified using data stored in TinyDB.

Upon successful login, the user is redirected to the main dashboard.

.Location Tracking

The app get by entering latitude and longitude.

Expense location is displayed using the Map component.

Monthly Expense Calculation

The app filters expenses based on the selected month.

Category-wise and total monthly expenses are calculated.

Results are displayed for user analysis.

.Data Sharing 

Expense data can be shared using the Sharing component.


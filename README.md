1. Getting Current Date:
userInput.max = new Date().toISOString().split("T")[0]
sets the maximum allowable date to today's date.

2. Splitting Input Date:
The birthdate entered by the user is split into year, month, and day.

3. Calculating Age:
- Years: The difference in years is calculated by subtracting the birth year from the current year.
- Months: The difference in months is calculated, adjusting for negative values by decreasing the year count and adding 12 to the month count.
- Days: If the day difference is negative, it adjusts the month count and calculates the days in the previous month.

4. Display Age:
The calculated age in years, months, and days is displayed in an output element.

5. Function for Days in Month:
The getDaysInMonth function returns the number of days in a specific month and year, useful for correcting day differences when the current day is earlier in the month than the birthday.

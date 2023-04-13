# lab-7_202001207

Based on the given input ranges and possible output dates, the following equivalence class test cases can be designed:

1. Valid input for a non-leap year:
Input: day = 15, month = 2, year = 2000
Expected Output: Invalid date (February 15 is not a valid date in a non-leap year)

2. Valid input for a leap year:
Input: day = 29, month = 2, year = 2000
Expected Output: February 28, 2000 (previous date)

3. Valid input for a non-leap year, end of the month:
Input: day = 31, month = 3, year = 2001
Expected Output: March 30, 2001 (previous date)

4. Valid input for a leap year, end of the month:
Input: day = 31, month = 12, year = 2012
Expected Output: December 30, 2012 (previous date)

5. Valid input for the earliest possible date:
Input: day = 1, month = 1, year = 1900
Expected Output: Invalid date (January 1, 1900 is the earliest possible date)

6. Valid input for the latest possible date:
Input: day = 31, month = 12, year = 2015
Expected Output: December 30, 2015 (previous date)

7. Invalid input for day:
Input: day = 0, month = 6, year = 2005
Expected Output: Invalid date (day must be between 1 and 31)

8. Invalid input for month:
Input: day = 15, month = 13, year = 1999
Expected Output: Invalid date (month must be between 1 and 12)

9. Invalid input for year:
Input: day = 10, month = 9, year = 1899
Expected Output: Invalid date (year must be between 1900 and 2015)

10. Invalid input for day and month:
Input: day = 0, month = 13, year = 2022
Expected Output: Invalid date (day must be between 1 and 31, month must be between 1 and 12)

11. Invalid input for day and year:
Input: day = 0, month = 5, year = 2018
Expected Output: Invalid date (day must be between 1 and 31, year must be between 1900 and 2015)

12.Invalid input for month and year:
Input: day = 29, month = 13, year = 1899
Expected Output: Invalid date (month must be between 1 and 12, year must be between 1900 and 2015)

These test cases cover various combinations of valid and invalid input values, including edge cases, to thoroughly test the program's ability to determine the previous date based on the given input ranges.

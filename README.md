# Get-Season

Input: 1

Output: Winter

Question Explanation:

This program is designed to determine the season associated with a given month number. The program takes an integer input representing the month number (e.g., 1 for January, 2 for February, etc.) and outputs the corresponding season based on the following criteria:

"Winter" for November, December, and January.
"Spring" for February and March.
"Summer" for April, May, and June.
"Rainy" for July and August.
"Autumn" for September and October.
Logical Approach:

Read Input:
Read the month number as an integer.

Determine Season:
Use conditional statements (if, elif) to check the month number and determine the corresponding season.
Print the name of the season based on the month number.

Implementation Details:
For the months of November and December (month number 11 and 12), and January (month number 1), the season is "Winter".
For February and March (month numbers 2 and 3), the season is "Spring".
For April, May, and June (month numbers 4, 5, and 6), the season is "Summer".
For July and August (month numbers 7 and 8), the season is "Rainy".
For September and October (month numbers 9 and 10), the season is "Autumn".

Example for Clarity:

If the input month number is 1 (January):
The condition for "Winter" is met (since January is one of November, December, or January).
The output will be "Winter".
If the input month number is 4 (April):
The condition for "Summer" is met (since April is one of April, May, or June).
The output will be "Summer".

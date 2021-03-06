# How dateUtil.js Works? 

- The function isLeapYear(year) returns true if year is a leap year.
- The function getDaysInMonth(year, month) returns the number of days in the given month (1-12) of the year (4-digit). Take note that JavaScript represents a month in the range     of 0-11 (for Jan to Dec), instead of 1-12.
- The function getDayInWeek(year, month, day) returns the day of the week (Sunday to Saturday). It constructs a built-in object Date with the given year, month and day, and use     the getDay() function of the Date object to obtain the day of the week in the range of 0-6.
 
 # How JSDatePicker.js Works?
 
 - The form consists of 5 input elements: a text field for the year, pull-down menus for month and day, a read-only text field for the day of the week, and a button to set the      display to today. When the page is first loaded, the current date is display. 
 - If you change the year, month or day, the day of the week changes. 
 - If you change the year or month, the options in day adjust automatically, e.g., there are 28/29 days in Feb for non-leap and leap years.

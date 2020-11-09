# HPC-Hackathon-2020-COVID-19-Hospital-Statistics
Team Members: Caleb Anderson, Nia Blake, Trent Gaylord, Kobe Lawson-Chavanu
---
Overview:
Program is intended to process csv files that consist of hospital staffing and care coordination data, this data is then processed and turned into a graph with a prediction of the amount of employees needed for a given date
---
Functions:

Works to handle exceptions such as leap years and process the date string into a usable format:
determine_day_of_the_year(month_day_year)
find_index_of_year(table, month_day_year, index_table)

Calculates total needs:
total_needs_on_a_given_day(table, hospital_number, shift, day_of_the_year, number_of_days)
---
Output:
Displays the number of needs on each date in a bar graph, with the final date being a prediction of hospital needs, with parameters that specify the nurse specialty (ICU, ED etc.), the hospital, and the shift, also sends data to a webapp which can enter parameters and produce an analagous ouput on the website

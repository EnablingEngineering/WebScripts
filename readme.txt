
jQuery Fundamentals: http://jqfundamentals.com/chapter/jquery-basics

The goal of this project is to display dashboard-style information about Enabling Engineering by accessing our data with the Airtable API. To get started, it will be structured like this: 

STATS INDEX
    - a list of links to the dashboard pages available

ACTIVITY
    - total number of active projects (number)
    - total number of students participating 

NEEDS
    - list of current project needs (defined by field in Reports)

STUDENTS (all excluding students that have graduated)
    - total number of people in database
    - labeled pie chart of majors
    - labeled pie chart of ages 
    - bar chart showing new submissions by month
    - line plot showing cumulative registrations over time


    - total amount spent on active projects
    - reports submitted in last week
    - reports submitted to date per project

<!-- 
    the two script lines came from: http://stackoverflow.com/questions/7496789/how-to-include-jquery-in-another-javascript-file 
    which says to use the first line to pull in the jquery library from Google, which hosts it. 
    It sounds like that should expose it to the second script line.

    another documentation source here: https://www.w3schools.com/jquery/jquery_get_started.asp

    added line for airtable as source after seeing: https://github.com/kasrak/airtable-api-guide/blob/master/index.html
-->
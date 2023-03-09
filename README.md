# Makin-A-Scheduler
This project is to create a workday scheduler using jquery and moment APIs that saves data to the local storage and features dynamically updated HTML and CSS.


# Steps
Using Javascript and JQueryand the skills from class, I used arrays, If functions and loops, and the Moment.js APIs to create a dailr workday scheduler.

The first step was to learn moment.js functions in order to both generate the current day and output it in the header, and to generate the current hour.

My second step was to analyse the CSS provided code to determine what classes were required to change the colour scheme based on the time during the day. Using JQuery I created a function that added the class to the row based on whether or not the corresponding time was in the past/ present or future, by comparing it to the current hour.

Finally, after the template was corrected, I assigned a variable to an array that collected all the information typed into a text field when the corresponding save button was clickes. This array then pushed the data to the local storage.

Whenever the page is opened, I created a function that would check for any existing local storage, and transfer it back to the array and into the corresponding text boxes, ensuring that all saved data would remain on screen.

To make the project my mine, I made a few additions:

A clear function activated by a button that would erase all the data within the table.
A function that stores the current date every time the application is run in the morning, and compares it with the date that is already there (if one exists). If the dates do not match, it sends an alert to the user letting them know the day has change and asks if the user wants to clear all the data.
A save all function so you can save all the inputs.
I ran the functions a few times and manually altered the system time to ensure it met all acceptance criteria.

# Built With
Visual Studio Code
Bootstrap
J Query
Moment.js

# Versioning
1.0.0

# Workday Scheduler by Ashley Feese

Link to deployed application: https://apollodragon13.github.io/Day-Planner/

The workday scheduler helps organize your day! 
When the page is loaded, the document shows the title, current day as well as time of the day in real-time. Segments are divided into a standard work day and hours to the left are written in military time. The document compares the left-hand hour times to the current real time and changes the background of the text fields according to time of day. 

For example:
Listed time is past the current real time: Textbox background turns gray. 
Listed time is within the SAME hour as the current real time: Textbox background turns red/pink. 
Listed time is in the FUTURE compared to the current real time: Textbox background turns green. 


User can enter their "to-do's" into the corresponding textboxes according to their preferred listed hour. When the save button is clicked, the user's input is saved to local storage and remains when the page is refreshed. The user can clear the entries by deleting the text and saving that same box once more. 


Thank you for viewing my program! 
-Ashley F





-----------------------------------------





# - ORIGINAL INSTRUCTION - 

# 05 Third-Party APIs: Work Day Scheduler

Create a simple calendar application that allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

You'll need to use the [Moment.js](https://momentjs.com/) library to work with date and time. Be sure to read the documentation carefully and concentrate on using Moment.js in the browser.

## User Story

```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

The following animation demonstrates the application functionality:

![day planner demo](./Assets/05-third-party-apis-homework-demo.gif)

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

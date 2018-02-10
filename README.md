# Assignment Tracker - iOS

## Technical Task

You are to create an application for iPad (all models). You are free to choose the style and look and feel of the applications but they must conform to the functional and non-functional requirements stated below.

### General Functionality

You are to create a University assignment planning tool. To help students manages their assignments and assignment sub-task efficiently and in a timely manner. The app shall use a split view pattern with the key assignment details in a 'master' UITableView and the corresponding 'Detail' view will detail the assignment plus related tasks. The detail view shall give a graphical indication of task progress and the task details. The detail view shall also allow the user to add add/delete/edit tasks. When a assignment is created it should also put the due date into the iPad Calendar. The user can indicate when a task is completed or can set an estimate of the percentage completed. The application shall calculate the total progress as a percentage to the user based on the progress of all the subtasks. All the data entered and state of a assignment shall be persistently stored using core data.

The user can enter assignment details into the app as below:
  -	Module Name
  -	Level (4,5,6, or 7)
  -	Assignment name
  -	Value (% of overall module)
  -	Mark awarded (actual)
  -	Due Date
  -	Notes
  -	Assignment reminder

Once a assignment is entered the user can then enter one or more tasks that must be done in order to compete the assignment. Tasks details are as below: 
  -	Task name
  -	Start time (date it will commence)
  -	Estimated length of time (in units of days) - this can be defined by an end date or a length of time in hours or days.
  -	Notes - some text about the task.
  -	Task due date
  -	Task reminder

## User Requirements

R1:   The software shall allow the user to enter details of an assignment. 
R2:   The software shall allow the user to enter task details for an assignment. 
R3:   The user shall allow the user to be able to delete an assignment. 
R4.   The user shall allow the user to be able to delete a task. 
R5:   The user shall allow the user to edit an assignment. 
R6:   The user shall allow the user to edit a task. 
R7:   The software shall allow the user to view progress of an assignment. 
R8:   The software shall allow the user to set a reminder for an assignment. 
R9:   The software shall allow a user to set the percentage complete for a task. 
R10:  The software shall allow a user to set (edit/delete) the actual mark for the assignment.

## System Requirements 

RS1:  The software shall notify the user when a task schedule has not been met. 
RS2:  The software shall place the due date of an assignment in the Calendar app. 
RS3:  The software shall give a graphical2 indication of individual task progress. 
RS4:  The software shall give a graphical indication of assignment task progress. RS5: The software shall give a graphical indication of the days remaining before the assignment due date.

## Non Functional Requirements 

NF1: The software shall adhere to Apple design guidelines as regards fonts and layout and general usability. 
NF2: All user data shall be persistent. 
NF3: The software shall persist the state of the UI in the event of back-grounding or the application quitting. 
NF4. The software shall persist all coursework data even after the due date. NF5: The software shall be intuitive and simple to use.

Once you are done with the task upload your source code and documents to the this GitHub repository (Fork the master branch). Try to implement as much as possible within the given deadline.

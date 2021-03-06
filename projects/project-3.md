---
layout: project
type: project
image: images/access.png
title: UHM Scheduling Office scheduling reports
permalink: projects/scheduling
# All dates must be YYYY-MM-DD format!
date: 2019-01-15
labels:
  - SQL
  - Database
  - Microsoft Access
summary: A database for scheduling reports for the UHM Scheduling Office.
---

<img class="ui medium right floated rounded image" src="/images/schedulingdb.png">

I was asked to design, write, and test a new version of a legacy database system in Microsoft Access for the UHM Scheduling Office. The purpose of the database is to allow the Scheduler a quick method of generating reports of current course schedules. The reports are then distributed to departments for feedback on the next semester course schedule. The end result is the <a href="https://www.sis.hawaii.edu/uhdad/avail.classes?i=MAN">UHM Class Availability</a>.

For several weeks, I met with the end user to gather and understand the functional requirements of the database system. The end user provided the guidelines and sample paper reports that the system needed to generate. The end user also performed extensive testing to catch things I may have overlooked.

The final system functionalities using a main menu:
end user selects a Microsoft Excel file to import
the SQL code imports the data and adds the records in the appropriate tables
based on course(s) selected, generate reports that can be exported as PDF or displayed on screen

This was the first project I worked on with an external UHM department. I gained skills on conducting client meetings as well as learning about how courses are scheduled. Since the first iteration of the database, I have been asked to create additional functionalities.

---
layout: project
type: project
image: images/nursing.png
title: Nursing Internship Scheduler
permalink: projects/nursingInternship
# All dates must be YYYY-MM-DD format!
date: 2020-04-30
labels:
  - Javascript
  - Laravel
  - MySQL
  - GitHub
summary: Example Capstone project. A full-stack Laravel and mySQL application that  automatically schedules student nursing internships.
---

<img class="ui medium right floated rounded image" src="../images/nursing.png">

AU’s Nursing spends hours manually assigning clinicals each semester
This tool  autamatically schedules students to clincal locations and it allows for specific cases.
This will save valuable time each semester for the Nursing department. Developed by David Carpenter, Matthew McCarthy, Chris Stockton and Thomas Slezak.

Currently the scheduling process for the Nursing Department is done exclusively on excel spreadsheets. We wanted to leave this process behind and create a Web based application that can easily handle schedule creation, record manipulation, generate reports, autofill class schedule, and provide a clear overview of all schedule details. 
<br />
Core functionality:
<ol>
  <li>
    Users should be able to login using a custom login. Any non user not logged in will not be able to view the other pages with precious student data.
  </li><li>
  Users should be able to create/delete/edit sites, clinicals, assignments, instructors, students, etc. All of this will be possible using clean and easy to use CRUD pages.
</li><li>Be able to assign students to clinical sites and lab classes. This should be done either manually or through the automatic assignment function we have implemented for this project.
</li><li>A user should be able to bulk upload student information for the semester using an acceptable CSV file (excel sheet). Students can be put into a single class or even multiple automatically!
</li><li>Users should be able to view individual reports of all students, labs, clinicals, and assignments simply by clicking the ‘View’ button. This will detail all important information associated to the selected record. 
</li></ol>

The tool usese Laravel, mysql and JavaScript. 
 
Main Documentation: <a href="https://docs.google.com/document/d/1A81BZKhSDrkUNhHy4P1q_K3bNwyQrbsJv1YrVKFPFI0/edit">Tool Documentation</a>
<br />
Live Site: <a href="http://45.55.136.114:8000/"> Nursing Inventory </a>

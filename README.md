# Irctc clone project by nxtwave 


# Problem Statement

Technologies : Python, NodeJs, ReactJs and SQL

Statement for Candidates:

Below is the problem statement for your project.

Your task is to create an API that supports the requirements mentioned in Problem Statement
You have 3 hours to develop the API.
You have another 1.5 hours to create a Front-End for the same
You can use Google to find solutions, however, copying an existing project is not allowed.

Problem Statement

Hey there, Mr. X. You have been appointed to design a railway management system like IRCTC, where users can come on the platform and check if there are any trains available between 2 stations.
The app will also display how many seats are available between any 2 stations and the user can book a seat if the availability > 0 after logging in. Since this has to be real-time and multiple users can book seats simultaneously, your code must be optimized enough to handle large traffic and should not fail while doing any bookings.
If more than 1 users simultaneously try to book seats, only either one of the users should be able to book. Handle such race conditions while booking.
There is a Role Based Access provision and 2 types of users would exist :

Admin - can perform all operations like adding trains, updating total seats in a train, etc.
Login users - can check availability of trains, seat availability, book seats, get booking details, etc.

Tech Stack:

Python Django
Database: MySQL/PostgreSQL (Compulsory)
Front-end: React JS

Requirements

Register a User
Create an endpoint for registering a user.

Login User
Provide the ability to the user to log into his account


Add a New Train
An endpoint for the admin to create a new train with a source and destination

Get Seat Availability
Create an endpoint for the users where they can enter the source and destination and fetch all the trains between that route with their availabilities

Book a Seat
Create an endpoint for the users to book a seat on a particular train

Get Specific Booking Details
Create an endpoint for the users to book a seat on a particular train


Mandatory requirement:

You need to protect all the admin API endpoints with an API key that will be known only to you and the admin so that no one can add false data to your system.
For booking a seat and getting specific booking details, you need to send the Authorization Token received in the login endpoint.


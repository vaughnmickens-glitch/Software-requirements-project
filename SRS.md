# Software Requirements Specification (SRS)

Existing Software Landscape/Research 
Several software systems currently are being used for managing gyms and fitness facilities. Software systems such as these include features like , community with gym members, billing , membership management and class scheduling. 

Current software landscape encompasses billing, scheduling , programming , communication, member management

My software intends to build upon the already standardized features that most gyms already have. Adding 

## 1. Introduction
My company BodyPeakPro Gym management aims to increase the capabilities of current gym management software systems. My application will not only help the gym owner run the business, but also help the member manage their actual fitness journey in the gym. We hope to make managing the business of gyms easier, and also bridge the gap between the business and the average gym goer. Our mission is to make gym management more efficient while also helping members stay proactive in achieving their fitness goals . 
### 1.1 Purpose
This project was acquired after careful examination of the gym management industry. We noticed that there were many different fitness facilities using separate applications to manage memberships , payments and scheduling. We saw a need for an all encompassing software that integrates all the necessities of a gym business , that also caters to the gym goers as well. We want to provide gym owners, employees, trainers, and members with one platform for managing daily gym operations and fitness related activities. 

### 1.2 Scope
BodyPeakPro Gym management will include major functions required to manage a fitness facility and it's members. The system will include, Member account registration and login, membership plan management, membership payments and renewals, gym check in and attendance tracking, fitness class scheduling and registration, personal trainer scheduling, member fitness goals and workout tracking , gym capacity info, equipment availability and waitlists, equipment maintenance reporting , notifications and reminders and many more features.
Out of Scope 
BodyPeakPro will focus specifically on gym management and member fitness activities. The system will not provide medical diagnosis, medical treatment recommendations, or replace professional medical advice.

## 2. Overall Description
Users: Gym management , trainers ,
System Environment: Web based/ desktop / mobile application
Constraints: Must be able to run on Wifi and via data 

## 3. Functional Requirements
Membership account management 
FR1: The system shall allow new members to create an account using their personal information, email address, and password. 
FR2: The system shall allow members to view available membership plans
FR3: The system should allow members to make membership payments 
FR4: The system shall display current gym capacity to members and staff

## 4. Non-Functional Requirements
NFR1: The system should be operating at full efficiency at 99.5% of the time
NFR2: The system should require users to authenticate before accessing protected account info 
NFR3: The system should only collect info necessary for gym membership, fitness management, scheduling and system operation
NFR4: The system should provide readable text for important interface elements 

## 5. Use Cases
1. Register Member Account
    Actor: New Member
    Precondition: The user does not already have a BodyPeakPro account
    Steps:
    1. The user selects Create Account
    2. User enters name, email address, phone number, date of birth and password
    3. The user accepts the required terms and conditions
    4. the system validates the information, creates the member account and displays a confirmation message
    User Story: As a new gym member , I want to create an account so that I can access BodyPeakPro services and manage my membership. 
2. Purchase membership plan
     Actor: Member

  Preconditions:
The member is logged into their account and does not currently have the selected membership.

    Steps:

    1. The system displays available membership options and prices.
    2. The member selects a membership plan.
    3. The system displays the plan details and total cost.
    4. The member enters or selects a payment method.
    5. The system processes the payment, The system activates the membership,
    The system provides a payment confirmation.

Postcondition:
The selected membership is active on the member's account.

User Story:
As a member, I want to purchase a membership plan so that I can access the gym and its services.
3. Renew membership
    Actor: Member
Preconditions:
The member has an existing or recently expired membership.

Steps:

1.The member opens their membership information and selects Renew Membership.
2.The system displays the renewal price and membership terms.
3.The member selects a payment method and confirms the renewal.
4.The system processes the payment and updates the membership expiration date.

Postcondition:
The member's membership period is extended.

User Story:
As a member, I want to renew my membership so that I can continue using BodyPeakPro without interruption.
4. Check into gym
Actor: Member

Preconditions:
The member has an active membership.

Steps:

1.The member scans their BodyPeakPro ID or QR code.
2.The system identifies the member and verifies membership status.
3.The system records the member's check-in date and time.
4.The system updates gym capacity and confirms successful check-in.

Postcondition:
The member's attendance is recorded.

User Story:
As a member, I want to check into the gym quickly so that my visit is recorded and I can access the facility.
5. View gym capacity
View Gym Capacity

Actor: Member

Preconditions:
The member has access to BodyPeakPro.

Steps:

1.The member opens BodyPeakPro and selects Gym Capacity.
2.The system retrieves current gym attendance information.
3.The system compares attendance with the gym's maximum capacity.
4.The system displays the current gym capacity to the member.

Postcondition:
The member can view the current gym capacity.

User Story:
As a member, I want to view gym capacity so that I can decide when I would prefer to visit.
6. View equipment list
Actor: Member
View available gym equipment and its status.

Preconditions:
The member is logged into BodyPeakPro.

Steps:

1.The member selects Equipment.
2.The system displays the gym's equipment list and current statuses.
3.The member searches, filters, or selects a piece of equipment.
4.The system displays additional information about the selected equipment.

Postcondition:
The member can view gym equipment information.

User Story:
As a member, I want to view the equipment list so that I can plan my workout.
7. Register for fitness class
Actor: Member

Preconditions:
The member is logged in and has an eligible active membership.

Steps:
1.The member views available fitness classes and selects one.
2.The system displays the class details and remaining availability.
3.The member selects Register and confirms the registration.
4.The system reserves the member's place and sends confirmation.

Postcondition:
The member is registered for the fitness class.

User Story:
As a member, I want to register for fitness classes so that I can participate in group workouts.
8. Schedule personal training session
Actor: Member

Preconditions:
The member is logged in and eligible for personal training.

Steps:
1.The member selects a personal trainer.
2.The system displays the trainer's available dates and times.
3.The member selects and confirms an available appointment.
4.The system schedules the session and notifies the member and trainer.

Postcondition:
A personal training session is scheduled.

User Story:
As a member, I want to schedule a personal training session so that I can receive individualized fitness assistance.
9. Track workout
Actor: Member

Preconditions:
The member is logged into BodyPeakPro.

Steps:
1.The member selects Track Workout and enters completed exercises.
2.The member records details such as sets, repetitions, weight, distance, or duration.
3.The member reviews and submits the completed workout.
4.The system saves the workout and updates fitness progress.

Postcondition:
The workout is stored in the member's fitness history.

User Story:
As a member, I want to record my workouts so that I can monitor my fitness activity and progress.
10. View fitness progress
Actor: Member

Preconditions:
The member has recorded workout or fitness-goal information.

Steps:
1.The member selects Fitness Progress.
2.The system retrieves the member's workout and goal data.
3.The member selects a goal or time period to review.
4.The system displays the member's progress and workout history.

Postcondition:
The member can review their fitness progress.

User Story:
As a member, I want to view my fitness progress so that I can determine whether I am reaching my goals.
11. Trainer assigning workout plan
Actor: Personal Trainer

Preconditions:
The trainer is logged in and authorized to work with the selected member.

Steps:
1.The trainer selects a member and chooses Create Workout Plan.
2.The trainer adds exercises, instructions, and workout details.
3.The trainer reviews and assigns the workout plan.
4.The system saves the plan and notifies the member.

Postcondition:
The workout plan appears in the member's account.

User Story:
As a personal trainer, I want to assign workout plans so that I can guide my clients' fitness activities.
12. Report broken equipment feature
Goal: Report damaged or malfunctioning equipment.

Preconditions:
The user has identified equipment that may be damaged or unsafe.

Steps:
1.The user selects Report Equipment Problem and identifies the equipment.
2.The user enters a description of the problem.
3.The user submits the report.
4.The system creates a maintenance report and alerts staff for review.

Postcondition:
A maintenance report is created for the equipment.

User Story:
As a gym user, I want to report broken equipment so that staff can repair it and maintain a safe facility staff accounts 
13. Manage staff accounts
Actor: Administrator
Goal: Create and maintain staff accounts.

Preconditions:
The administrator is logged in with appropriate permissions.

Steps:
1.The administrator selects Staff Management.
2.The administrator chooses to create, edit, deactivate, or view a staff account.
3.The administrator enters or updates staff information and permissions.
4.The system validates and saves the changes.

Postcondition:
The staff account information is updated.

User Story:
As an administrator, I want to manage staff accounts so that authorized employees have appropriate system access.


14. Generate reports
Actor: Administrator or Gym Manager
Goal: Generate reports about gym operations.

Preconditions:
The user is logged in with reporting permissions.

Steps:

1.The user selects Reports and chooses a report type.
2.The user selects a date range or other filters.
3.The system retrieves the appropriate data and generates the report.
4.The system displays the completed report to the user.

Postcondition:
The requested report is generated.

User Story:
As a gym administrator, I want to generate reports so that I can evaluate gym performance and make informed decisions.

15. Change billing information 
Actor: Member
Goal: Update billing information associated with the member's account.

Preconditions:
The member is logged into BodyPeakPro.

Steps:

The member selects Billing and Payments and chooses Update Billing Information.
The member enters new billing or payment information.
The system validates the submitted information.
The system securely saves the changes and confirms the update.

Postcondition:
The member's billing information is updated.

User Story:
As a member, I want to update my billing information so that future payments use my current payment method.


## 6. Constraints
1. Necessary wifi connectivity
2. Device and browswer compatibility
3. Payment processing dependency
4. Gym Capacity Accuracy
5. Privacy Training Access 

## 7. Assumptions
1. Users have internet access
2. Users have compatible devices
3. Members maintain valid accounts
4. Trainers maintain their availability
5. External Payment services remain available

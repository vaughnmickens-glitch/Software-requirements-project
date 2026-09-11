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
3. Purchase membership plan
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
4. Renew membership

5. Check into gym

6. View gym capacity

7. View equipment list

8. Register for fitness class

9. Schedule personal training session

10. Track workout

11. View fitness progress

12. Trainer assigning workout plan

13. Report broken equipment feature

14. Manage staff accounts 

15. Generate reports 

16. Change billing information 



## 6. Constraints
Project constraints will be added here.

## 7. Assumptions
Project assumptions will be added here.

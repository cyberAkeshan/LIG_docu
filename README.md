# listItGrocery - Software Requirements Specification 

## Table of contents
- [Table of contents](#table-of-contents)
- [Introduction](#1-introduction)
    - [Purpose](#11-purpose)
    - [Scope](#12-scope)
    - [Definitions, Acronyms and Abbreviations](#13-definitions-acronyms-and-abbreviations)
    - [References](#14-references)
    - [Overview](#15-overview)
- [Overall Description](#2-overall-description)
    - [Vision](#21-vision)
    - [Use Case Diagram](#22-use-case-diagram)
	- [Technology Stack](#23-technology-stack)
- [Specific Requirements](#3-specific-requirements)
    - [Functionality](#31-functionality)
    - [Usability](#32-usability)
    - [Reliability](#33-reliability)
    - [Performance](#34-performance)
    - [Supportability](#35-supportability)
    - [Design Constraints](#36-design-constraints)
    - [Online User Documentation and Help System Requirements](#37-on-line-user-documentation-and-help-system-requirements)
    - [Purchased Components](#38-purchased-components)
    - [Interfaces](#39-interfaces)
    - [Licensing Requirements](#310-licensing-requirements)
    - [Legal, Copyright And Other Notices](#311-legal-copyright-and-other-notices)
    - [Applicable Standards](#312-applicable-standards)
- [Supporting Information](#4-supporting-information)

## 1. Introduction

### 1.1 Purpose

Welcome to our Software Requirements Specification (SRS). Here we will describe all specifications for our android app "listItGtovrtx". This SRS will include an overview about our project and what we plan for it in the future. We will also mention and describe information about the planned features and general conditions of the development process.
We want to develop this app to keep grocery shopping easy. A simple grocery shopping list app without any kind of ad. We want to keep it simple so we have some necessary and some enhanced features. These will include adding lists, adding items to the list, view icons next to items, find the nearest supermarket, search and view chefkoch recipes with ingredients.

### 1.2 Scope

The listItGrocery app, as mentioned in "1.1 Purpose", is going to be an android app.

Actors of this app can only be users.

The different features we want to include are:

* add a List: 
  The List feature is one of the key features. Users should be able to create lists with a list name, a progress bar in the list View, amount of items in the list and  a settings menu for each list
* add items to a list: 
  The user should be able to add items to his grocery shopping list
* see item icons: 
  The user should see a little icon next to his grocery item.
* nearest supermarket: 
  The user should see the nearest supermarket based on his location.
* search chefkoch recipes: 
  The user should be able to search for a chefkoch recipe and add the ingredients to a list 
  

### 1.3 Definitions, Acronyms and Abbreviations

| Abbrevation | Explanation                            |
| ----------- | -------------------------------------- |
| SRS         | Software Requirements Specification    |

### 1.4 References

| Title                                                              | Date       | Publishing organization   |
| -------------------------------------------------------------------|:----------:| ------------------------- |
| [listItGrocery Blog](https://listitgrocery.wordpress.com/)    | 20.10.2022 | listItGrocery Team    |
| [GitHub](https://github.com/cyberAkeshan/listItGrocery)              | 20.10.2022 | listItGrocery Team    |
| [YouTrack](https://listitgrocery.youtrack.cloud/)              | 20.10.2022 | listItGrocery Team    |
### 1.5 Overview

The following chapter provides an overview of this project with vision and Overall Use Case Diagram. The third chapter (Requirements Specification) delivers more details about the specific requirements in terms of functionality, usability and design parameters. Finally there is a chapter with supporting information.

## 2. Overall Description

### 2.1 Vision

Inspired and also annoyed by current grocery shopping list apps sometimes flooded with ads. So we want to create a simple not distracting app where you can do what you want - add grocery lists with items

### 2.2 Use Case Diagram
Here we will add the Use Case Diagram

### 2.3 Technology Stack

Languages: Java, XML

IDE: Android Studio

Source Control Management: GitHub

Project Management: Youtrack

## 3. Specific Requirements

### 3.1 Functionality

#### 3.1.1 Dashboard

The start page of DHBWorld should consist of small information-blocks from all parts of the app. This will be realised in form of customizible dashboard. User can configurate visible blocks there.

**Use Cases:**
* *[View personal Information:](https://github.com/inFumumVerti/DHBWorld-Docu/blob/main/Use%20Cases/View%20personal%20information.md)* User can save important personal Information and view his personal information he saved earlier
* *[Configure Dashboard:](https://github.com/inFumumVerti/DHBWorld-Docu/blob/main/Use%20Cases/Configure%20visible%20information%20on%20dashboard.md)* Configure the visible information of the dashboard

#### 3.1.2 Schedule
This part of the app will be an interface to connect with Rapla-Service to provide information about the DHBW-Schedule.

**Use Cases:**
* *[View schedule:](https://github.com/inFumumVerti/DHBWorld-Docu/blob/main/Use%20Cases/View%20schedule.md)* User can view his upcoming classes
* *Filter classes:* User can filter classes he want to see in the calender

#### 3.1.3 Meal plan
This feature will be an interface for connecting with the OpenMensa-Plattform to provide information about the meal plan for the DHBW.

**Use Cases:**
* *[Show day-plan:](https://github.com/inFumumVerti/DHBWorld-Docu/blob/main/Use%20Cases/Show%20daily%20mealplan.md)* User can see the meal plan for today
* *[Show weekly-plan:](https://github.com/inFumumVerti/DHBWorld-Docu/blob/main/Use%20Cases/Show%20weekly%20meal%20plan.md)* User can see the meal plan for the current week

#### 3.1.4 Organizer
This part of the app will consist of some organisational topics of DHBW, which are important specially for new students. Quick access to this information will save time of student's because they dont need to search on the DHBW-Website oder around the DHBW-Building. 

**Use Cases:**
* *View routes to specific room:* User can view the route to a selected room
* *View organizer:* User can view information about professors, rooms and courses like e-mail-address, phone number or room for a selected professor.

#### 3.1.5 User interaction
This feature will give all of the students a possibility to communicate anonymously with each other to optimize the dealing with problems like a broken coffee machine.

**Use Cases:**
* *Reporting events:* User can report specific events like a broken coffee machine
* *Receiving notifications:* User get a notification if a event gets reported enough

#### 3.1.6 Dualis
This part of the app will be an interface to connect with the Dualis-Service to provide information about personal grades.

**Use Cases:**
* *Logging in:* User can log in with their dualis credentials
* *Receive notifications:* User get a notification if a new grade gets published
* *Show grades in different views:* User can view the grades in a detailed view and in an overview

#### 3.1.7 Tram departure
This feature will be an interface to provide information about public transport near the DHBW through the KVV-API.

**Use Cases:**
* *View departures:* User can view the next tram departures of the DHBW station
* *View disruption:* User can view canceled trams

#### 3.1.8 Settings
The user can configure and personalise the app. 

**Use Cases:**
* *Configure notifications:* Change settings about app-notifications
* *Change design:* Change the design of the app
* *View information about App:* View information about the App like version, developers, etc.

### 3.2 Usability

#### 3.2.1 Familiar Feeling
With the use of the standatized Material UI design the App will be intuitive to use. Users can nagivate through the app in a familiar way.

#### 3.2.2 minimal setup for specific functions
For functions like dualis or the schedule the user only has to provide their credentials in order to get these functionalities.

### 3.3 Reliability

#### 3.3.1 Availability
The App will depend on quite a lot of external APIs in order to provide all of the funcitons. But all of these are well-known and need to function all the time, so they do have some high availability functions build in.

#### 3.3.2 Defect Rate
We will test the external APIs very extensively to make sure they meet our requirements.

### 3.4 Performance

#### 3.4.1 Capacity
Some of the external APIs are limeted to a specific amout of requests per timeunit. If the app will get more user than we expected we can always install a simple caching-server to slow down these requests.

#### 3.4.2 Storage 
We expect out app to be 40-50 MB in size which is no problem for phones with even limited storage like 16 GB.

#### 3.4.3 App perfomance / Response time
Because the app doesn't have to do a lot of calculations, searching, etc. we expect out app to run without any problems on nearly any phone.

### 3.5 Supportability

#### 3.5.1 Coding Standards
We will be using the language specific coding standards to make out code as clean and uniform as possible. We will also implement different "helper classes" in order to provide some translation for specific data.

#### 3.5.2 Testing Strategy
[Test Plan](https://github.com/inFumumVerti/DHBWorld-Docu/blob/main/Test%20plan.md)

### 3.6 Design Constraints
We use the standartized Material UI in order to keep our app clean looking for our users.
Internally we will use the MVC-architecture provided with the android framework.
Our minimum android version will be API Level 26 (Android Version 8.0) in order to support a wide range of devices.

### 3.7 On-line User Documentation and Help System Requirements
Our GitHub-Repository will be linked so users can ask for help, report bugs, or ask for more features. The functions inside the app will be well described.

### 3.8 Purchased Components
Nothing

### 3.9 Interfaces

#### 3.9.1 User Interfaces
n/a

#### 3.9.2 Hardware Interfaces
n/a

#### 3.9.3 Software Interfaces
Android API Level 26 (Android Version 8.0)

#### 3.9.4 Communication Interfaces
Ethernet

### 3.10 Licensing Requirements
[License](https://github.com/inFumumVerti/DHBWorld/blob/main/LICENSE.md)

### 3.11 Legal, Copyright, and Other Notices
[License](https://github.com/inFumumVerti/DHBWorld/blob/main/LICENSE.md)

### 3.12 Applicable Standards
TRIAS-Standard for Tram departures

## 4. Supporting Information
For more information check out our blog at: https://dhbworldka.wordpress.com/ 

# Made with ❤️ by:
| Name                                       | Username              |
| ------------------------------------------ | ----------------- |
| [Daria Kodolova](https://github.com/dk1553) | dk1553 and linus.pust@gmail.com | 
| [Linus Pust](https://github.com/inFumumVerti) | inFumumVerti	|
| [Christian Zäske](https://github.com/blitzdose) | blitzdose |
| [Adrian Kohl](https://github.com/KadrioL) | KadrioL |

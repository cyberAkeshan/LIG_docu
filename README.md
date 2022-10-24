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

#### 3.1.1 List Overview

The start page of listItGrocery will be an empty page only with an action bar and an add button at the beginning. The user can add lists via the add button with a name.

**Use Case:**
As a User i want to add serveral lists for my grocery shopping (Effort Medium)
is done when...
* ... you can add a list with name and save it
* ... you see the amounts of items in the list on the list view
* ... you see a progress bar on the list view 
* ... you have settings for the list (export, share, rename, delete....)
* ... you go into the actual list when clicking on it

#### 3.1.2 in List View
This part of the app will be an activity where the user can add items to the list. Later on we plan on showing icons next to the items.

**Use Case:**
As a User i want to add items to my list to keep an overview over my next grocery shopping (Effort Low)
is done when...
* ... you can add items with their amount and save them
* ... you can change items and their amount
* ... you can delete items

#### 3.1.3 show icons next to items
This feature will be a simple icon for each category. So for example for bread a little wheat icon.

**Use Case:**
As a User i want to see icons next to my listitems to get a quick overview (Effort Medium)
is done when...
* ... see icons next to the list items
* ... see the fitting icon for the item (for tomato and cucumber a vegetable icon, for bread a wheat icon)

#### 3.1.4 search for Chefkoch recipes and add ingredients
This part of the app will enable the user to search for chefkoch recipes and show it with the pictures and ingredients. The user should also be able to add the ingredients to one chosen list.

**Use Case:**
As a User i want to search for chefkoch recipes and add the ingredients to my list to shop convenient for my next meal (Effort high)
is done when...
* ... you can search chefkoch recipes through their pictures
* ... you can select a recipe and add the ingredients with their amount to the list

#### 3.1.5 nearest Supermarket
This feature will give the suer the opportunity to search for a supermarket near to him based up on his location

**UseCase**
As a User i want to see the nearest supermarket based up from my location to know where I can shop my groceries (Effort hight)
is done when...
* ... you can see the nearest supermarket
* ... you can filter your favourite supermarkets
* ... you can open and navigate in google maps

#### 3.1.6 Settings
The user can configure and personalise the app. 

**Use Case:**
As a User i want to change some settings the why i want to personalize the app usage for me (Effort low)
is done when...
* ... you can change the theme (day/night mode)
* ... you can see the app version
* ... you see the licenses listItGrocery uses

### 3.2 Usability

#### 3.2.1 Familiar Feeling
With the use of the standardized Material UI design the App will be intuitive to use. Users can nagivate through the app in a familiar way.

#### 3.2.2 minimal setup for specific functions
For functions like the nearest supermarket to user has to allow us to access his location.

### 3.3 Reliability

#### 3.3.1 Availability
The App will depend on two external APIs in order to provide all of the functions.

#### 3.3.2 Defect Rate
We will test the external APIs very extensively to make sure they meet our requirements.

### 3.4 Performance

#### 3.4.1 Capacity
n/a

#### 3.4.2 Storage
Currently we cannot estimate how much storage the app will need.

#### 3.4.3 App perfomance / Response time
Because the app doesn't have to do a lot of calculations, searching, etc. we expect out app to run without any problems on nearly any phone.

### 3.5 Supportability

#### 3.5.1 Coding Standards
We will be using the language specific coding standards to make out code as clean and uniform as possible.

#### 3.5.2 Testing Strategy
n/a

### 3.6 Design Constraints
We use the standartized Material UI in order to keep our app clean looking for our users.
Internally we will use the MVC-architecture provided with the android framework.

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
n/a

#### 3.9.4 Communication Interfaces
n/a

### 3.10 Licensing Requirements
n/a

### 3.11 Legal, Copyright, and Other Notices
n/a

### 3.12 Applicable Standards
n/a

## 4. Supporting Information
For more information check out our blog at: https://dhbworldka.wordpress.com/ 

# Made with ❤️ by:
| Name                                       | Username              |
| ------------------------------------------ | ----------------- |
| [Akeshan](https://github.com/cyberAkeshan) | Akeshan | 
| [Fezaan](https://github.com/Fezaaan) | Fezaaan	|
| [Wassim](https://github.com/Wassim067) | Wassim067 |
| [Adrian](https://github.com/KadrioL) | KadrioL |

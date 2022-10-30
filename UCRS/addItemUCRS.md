# Use-Case-Realization Specification: addItem

## Table of contents
- [Table of contents](#table-of-contents)
- [Introduction](#1-introduction)
    - [Purpose](#11-purpose)
    - [Scope](#12-scope)
    - [Definitions, Acronyms and Abbreviations](#13-definitions-acronyms-and-abbreviations)
    - [References](#14-references)
    - [Overview](#15-overview)
- [Flow of Events](#2-flow-of-events)

## 1. Introduction

### 1.1 Purpose

The addItem UC is one of the key features of listItGrocery. As a user of this app you want to add grocery items to your shopping list. You want to add items to the list you chose with the amount you want to buy.

### 1.2 Scope

This UCRS is associated with the 3.1.2 in List View. There is a brief description of the use case in our [SRS](https://github.com/KadrioL/LIG_docu/blob/main/docs/SRS.md#31-functionality) .


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
| UIList         | User Interface List    |

### 1.4 References

| Title                                                              | Date       | Publishing organization   |
| -------------------------------------------------------------------|:----------:| ------------------------- |
| [listItGrocery Blog](https://listitgrocery.wordpress.com/)    | 20.10.2022 | listItGrocery Team    |
| [GitHub](https://github.com/cyberAkeshan/listItGrocery)              | 20.10.2022 | listItGrocery Team    |
| [YouTrack](https://listitgrocery.youtrack.cloud/)              | 20.10.2022 | listItGrocery Team    |

### 1.5 Overview

The following chapter provides an overview of this project with vision and Overall Use Case Diagram. The third chapter (Requirements Specification) delivers more details about the specific requirements in terms of functionality, usability and design parameters. Finally there is a chapter with supporting information.

## 2. Flow of Events

![alt text](https://i.imgur.com/JgnTRav.png "Flow of Events addItem")

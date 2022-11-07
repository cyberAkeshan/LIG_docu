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

The addItem UC is one of the key features of listItGrocery.

As a User i want to add items to my list to keep an overview over my next grocery shopping (Effort Low)
is done when...
* ... you can add items with their amount and save them
* ... you can change items and their amount
* ... you can delete items

### 1.2 Scope

This UCRS is associated with the 3.1.2 in List View. There is a brief description of the use case in our [SRS](https://github.com/KadrioL/LIG_docu/blob/main/docs/SRS.md#31-functionality) .

### 1.3 Definitions, Acronyms and Abbreviations

| Abbrevation | Explanation                            |
| ----------- | -------------------------------------- |
| SRS         | Software Requirements Specification    |
| UIList         | User Interface List    |
| UCRS        | Use Case Realization Specification    |

### 1.4 References

| Title                                                              | Date       | Publishing organization   |
| -------------------------------------------------------------------|:----------:| ------------------------- |
| [listItGrocery Blog](https://listitgrocery.wordpress.com/)    | 20.10.2022 | listItGrocery Team    |
| [GitHub](https://github.com/cyberAkeshan/listItGrocery)              | 20.10.2022 | listItGrocery Team    |
| [YouTrack](https://listitgrocery.youtrack.cloud/)              | 20.10.2022 | listItGrocery Team    |

### 1.5 Overview

The following chapter provides a view over the flow of events for the addItem UCRS

## 2. Flow of Events

In the following picture you see the procedure of the addItem use case.

The user has the android app open and chooses a list.

After he chose one list the view of the app changes from the main "list" view where the user sees a list of the lists to the "in list" view 
where the user is in one specific list.

There he adds an item over the button, an insert field pops up and he gives it a name.

After he confirms the name of the item the item will be added to the list storage and the user sees an updated view of all the listitems for this list.


![alt text](https://i.imgur.com/JgnTRav.png "Flow of Events addItem")

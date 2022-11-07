# Use-Case-Realization Specification: nearestSupermarket

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

The nearest Supermarket UC is one of the advanced features of listItGrocery which we plan to implement in the fourth semester if we are in time with our key features. 

As a User i want to see the nearest supermarket based up from my location to know where I can shop my groceries (Effort hight)
is done when...
* ... you can see the nearest supermarket
* ... you can filter your favourite supermarkets
* ... you can open and navigate in google maps

### 1.2 Scope

This UCRS is associated with the 3.1.5 nearest Supermarket. There is a brief description of the use case in our [SRS](https://github.com/KadrioL/LIG_docu/blob/main/docs/SRS.md#31-functionality) .

### 1.3 Definitions, Acronyms and Abbreviations

| Abbrevation | Explanation                            |
| ----------- | -------------------------------------- |
| SRS         | Software Requirements Specification    |
| UIMap        | User Interface Map    |
| UCRS        | Use Case Realization Specification    |
| API        | Application Programming Interface    |

### 1.4 References

| Title                                                              | Date       | Publishing organization   |
| -------------------------------------------------------------------|:----------:| ------------------------- |
| [listItGrocery Blog](https://listitgrocery.wordpress.com/)    | 20.10.2022 | listItGrocery Team    |
| [GitHub](https://github.com/cyberAkeshan/listItGrocery)              | 20.10.2022 | listItGrocery Team    |
| [YouTrack](https://listitgrocery.youtrack.cloud/)              | 20.10.2022 | listItGrocery Team    |

### 1.5 Overview

The following chapter provides a view over the flow of events for the nearest Supermarket UCRS

## 2. Flow of Events

In the following picture you see the procedure of the nearestSupermarket use case.

The user has the android app open and chooses over a navigation drawer the supermarket view.

The view changes and he needs to insert a supermarket. After he confirms his input a request will be sent to the google maps api.

The api searches for the supermarket and gives a respond. The Respond will be processed in the background and the user will see a route to this supermarket


![alt text](https://i.imgur.com/XO5sSpc.png "Flow of Events findNearestSupermarket")

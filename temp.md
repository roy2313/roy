# Design Document


**Author**: 6300Fall20Team002

## 1 Design Considerations

### 1.1 Assumptions

* This app is designed to run on Android devices
* All data for user is saved locally on the cellphone
* All job related information is stored locally

### 1.2 Constraints

* User must have Android smart phone
* The App should only rely on local data
* In case a network service is not available, the App should work normally


### 1.3 System Environment

* Operating system: Android
* Plateform: Android SDK

## 2 Architectural Design

### 2.1 Component Diagram

picturexxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx


The component diagram presents the major parts of the App and their relationship. 
The major components are:
* System - a class stores the user login information
* User - a class provides functions, i.e., EnterCurrentJob, SaveCurrentJob, EnterJobOffer, etc
* Job - a class provides detailed job informations, i.e., title, company, location, etc
The relationship behind the components are:
* the system component is the entry point of the App
* user will be guided to from system to user if the correct login information are entered
* functions behind job class can be reached by users via clicking buttons on a interface

### 2.2 Deployment Diagram

The App will be deployed on an Android device. Since no network service is required, the deployment diagram would not be necessary.

## 3 Low-Level Design

### 3.1 Class Diagram


## 4 User Interface Design



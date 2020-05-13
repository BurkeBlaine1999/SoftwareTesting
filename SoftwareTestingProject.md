# <div align="center"> Test Plan </div>



## 1.0 INTRODUCTION

The product we are testing is called 'The Pixel Wizard'.
It is a 2D game inspired from games such as Shovel Knight and skyrim. In the game the player will play as a Pixel Wizard who will have to navigate his/her way through increasingly difficult levels featuring new enemies and boss stages. 

> The players weapon will be magic fireballs that they will shoot using Left mouse click or the R key. On mobile it will be done using a dedicated button.

> The player will have 5 HP meaning they can be hit 5 times before dying.

> Each level will have health pickups in order for the player to regenerate health increasing the players survivability.

> The player will be able to pause the game at any time and be able to edit game settings , exit , save and resume the game.

> The player will be able to move , jump and crouch using the generic 'WASD' controls. There will be dedicated buttons for the movement on the mobile verison.



## 2.0 OBJECTIVES AND TASKS
### 2.1 Objectives

We devided our team into small groups and assigned them all different tasks as listed in section 2.2. We will use microsoft teams and github to communicate and share work. With our service agreement we agreed to have it due by the end of 2020.

### 2.2 Tasks

There are several taks to be done in the project.

* Testing the UI to ensure it functions as expected.
* Testing the enemies in game to ensure they function as expected. e.g. Follow the player , Attack the player
* Post testing the game by releasing the game as a beta to the public , granting us user acceptance testing. This black box testing allows us to get more views on the game.
* Set up a bug reporting system for the beta in order to get feedback from the public.

## 3.0 SCOPE
### General

*In game..*

>Upon picking up health items the players health will be increased if not on full health.

>If the player touches an enemy or is hit by a projectile they will receive damage.

>If the player gets to 0 HP they will receive a Game over screen.

>The players controls will work as intended.

>Upon pressing the fire button the player will fire a fire ball projectile instantly.

*In Menus..*

>Game exits when 'Quit' button is selected.

>Music volume adjusts when lowered or raised.

>When the pause button is selected the game freezes and displays the UI.

>When the resume button is pressed the game resumes and the pause menu disapears.

>When the 'save game' button is selected the games state is saved and can be reloaded.

### Tactics

We will divided into two teams , one team taking in game testing and one taking in menu testing. We will then have daily scrum meetings to ensure progress is being made. We will use user acceptance testing  and white box testing methods as if a wider audience uses it we are more likely to find errors/bugs.

Tactics
List here how you will accomplish the items that you have listed in the "Scope" section. For
example, if you have mentioned that you will be testing the existing interfaces, what would be the
procedures you would follow to notify the key people to represent their respective areas, as well as
allotting time in their schedule for assisting you in accomplishing your activity?

## 4.0 TESTING STRATEGY

Our testing strategy is to attempt to rid the game of bugs/errors so we can release our game to the public and receive feedback.
We will be testing all the main aspects and functions of the game as stated in the scope (3.0).

We will be using several types of testing such as Unit Testing , System and Integration Testing ,Performance and Stress Testing,User Acceptance Testing , Batch Testing,Automated Regression Testing,Beta Testing Participants.

### 4.1 Unit Testing

We will use unit testing in our app in order to ensure individual components function correctly.
We will use this for the main mechanics of the game and upon an error being discovered it will be recorded and noted to our developers.

Members from both the 'in game' team and the 'menu' team will partake in unit testing then some of our developers will write up test scripts for the application.

### 4.2 System and Integration Testing

This method involves us taking each component and combining them together one by one until they are all integrated. This way we will catch any errors and know where it is caused easily.

Both teams will be using this method as it is a universal method of error checking.
We will begin by the Menu team going first and building the menu. Then once finished the Game team can add the game onto the menu as the menu is required to get into the game.

### 4.3 Performance and Stress Testing

We will use stress testing to see how far the game can be pushed before it breaks. Our in game team will carry this activity out as in game will be the most intensive part of the game with many seperate entities and projectiles. This is very important as it will help us know if our code is optimized or not.

### 4.4 User Acceptance Testing

User acceptance will be used to get another insight to our game . It will be granted to people such as other staff members. 
This will help us confirm that the game is ready for beta testing. 

A member from either team will be keeping track of this and will be in charge of receiving feedback.

### 4.5 Batch Testing

Wtih batch testing we will have several testers run and play the game several times in order to see how stable the game is and to see if it will crash or get any errors.
### 4.6 Automated Regression Testing

All team members will be using regression testing as it is vital to enusre that if you edit something that it does not break the application.

### 4.7 Beta Testing Participants:
With beta testing we will be releasing it to several popular streamers and figures to test it. This will be effective as the streamers will provide feedback on the game and also they would be streaming the game to a wide audience will provide a lot of feedback and will hopefully spread hype for the games release increasing profits.




## 5.0 TEST SCHEDULE

**Unit Testing : 5 Days**
We have alloted 5 days to Unit testing as it is vital all individual components function as intended.


**System and Integration Testing : 5 days**
We have alloted 4 days to system and integration testing as we appreciate it is tedious work to assemble an entire application.

**Performance and Stress Testing : 3 days**
We have alloted 3 days to Performance and Stress Testing because it should not take too long to test this aspect and also the game should not be too intensive due to its pixel art style making the game less intensive.


**User Acceptance Testing : 8 days**
We have alloted 8 days to User Acceptance Testing as we need to take into account that people may not sit down and play the game immediately and may have busy schedules.


**Batch Testing : 3 days**
Bathc testing should only take 3 days due to it being a fairly fast process when having multiple members actively doing it.

**Automated Regression Testing : If something is changed**
Automated Regression Testing has no time limit as once anything has been updated it must be tested imeediatly to ensure it has not began making errors throughout the application.

**Beta Testing Participants : 20 days**
We have alloted 20 days to out beta test as again people may be busy and cannot play it immediatly , we also want people to have time to play and complete the beta. It is also important we dont rush people into playing it as this may impact the user experience.
We would prefer them to take their time and enjoy the game. 


## 6.0 CONTROL PROCEDURES

If any problems occur thoughout the testing proccess we would take note of the problem and forward it to the test leader who would then pass the information onto the development team. Once the devlopers have fixed the issue the testers will once again test the project.
This proccess wil reoccur until the issue is resolved.


## 7.0 FEATURES TO BE TESTED

We will be testing many features in the game such as..
* Player mechanics 
* Enemy mechanics
* Game physics
* Game mechanics
* UI mechanics
* Volume slider function
* Save Game function

## 8.0 FEATURES NOT TO BE TESTED

There are not many features we will not be testing.

**Game Assets**

We will not be testing out art assets as they have been thoroughly examined by our art team.



## 9.0 RESOURCES/ROLES & RESPONSIBILITIES
 
**Menu Team**

*Lauren Smith*
* Team Leader
* Responsible for System and integration testing and  Unit testing and Performance.
* Working on System and integration testing and Unit testing.

<hr>

*David Burke*
* Responsible for Batch Testing and Beta Testing.
* Working on Batch Testing , Beta Testing and User acceptance testing.

<hr>

*Noel Keogh*
* Responsible for Batch Testing and Beta Testing.
* Working on Batch Testing , Beta Testing and Unit testing.

<hr>

*Thomas Quinn*
* Responsible for Automated Regression Testing and User Acceptance Testing .
* Working on User Acceptance Testing , Unit testing and system integration testing.
<hr>

*Eamonn Joyce*
* Responsible for Performance and Stress Testing .
* Working on User Performance and Stress Testing and Unit testing .

**Game Team**

Aaron Kenny - In Game Team
Ciaran Shortt -In Game Team
Arnas Moran -In Game Team
Joe Loughanne - In Game Team


Specify the staff members who are involved in the test project and what their roles are going to be
(for example, Mary Brown (User) compile Test Cases for Acceptance Testing). Identify groups
responsible for managing, designing, preparing, executing, and resolving the test activities as well as
related issues. Also identify groups responsible for providing the test environment. These groups
may include developers, testers, operations staff, testing services, etc.



## 10.0 SCHEDULES
Identify the deliverable documents. You can list the following documents:
- Test Plan
- Test Cases
- Test Incident Reports
- Test Summary Reports


## 11.0 RISKS/ASSUMPTIONS
Identify the high-risk assumptions of the test plan. Specify contingency plans for each (for example,
delay in delivery of test items might require increased night shift scheduling to meet the delivery
date).


## 12.0 TOOLS
List the Automation tools you are going to use. List also the Bug tracking tool here. 

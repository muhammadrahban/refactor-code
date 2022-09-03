# Coding Task 

## Refactor App

#### Booking Controller

``` getPotentialJobs() ```  method is optimized in booking Controller.

```distanceFeed() ``` method optimize IF/ELSE conditions. 

``` resendNotifications() ``` & ``` resendSMSNotifications() ``` methods Remove and declare single method to handle 1 or more services with repository pattern. 

Booking Controller in a lot of IF/ELSE Conditions we can handle trait and helper methods. the reason is that we want to follow a proper pattern to clear a code understandably for other Developers.

Also, we used sync methods, ``` updateOrCreate() ``` method & Proper Declare Validator Request Classes to Handle routing Data Requests.

## unit-test

Create a Unit test for ``` updateOrCreate() ``` user data in test\feature\UserTest.

Further, check testing operation by giving static data for running of assert status 200.

Another creating a Case for helper method ```willExpireAt()``` in test\feature\ExpireAtMethodTest 

the test case will check the expiry behavior by assert status 200
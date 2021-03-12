# User Guide

## Table of Contents
- [Overview](#overview)
  - [Main Page More](#main-page-more)
  - [The Scene](#the-scene)
- [Quiz](#quiz)
- [Level 01](#level-01)
  - [Functionality Introduction](#functionality_introduction)
  - [House Feature](#house_feature)
- [Level 02](#level-02)
  - [Notice](#notice)
  - [Issue House Capability](#issue-house-capability)
  - [Revoke House Capability](#revoke-house-capability)

## Overview
This app is a simulate to demonstrate how capability based access control works.

### Main Page More
In the top right of the main page, you can click "__...__" to view more options, here are some of the options you might want to know:

#### About
Briefly introduces some information about this app

#### Help
Introduces the functionality of this app.

You can always get to the "__Help__" page through the main page by clicking the "__...__" icon and then select the "Help" option!

#### Functionality
Provides an overview of the functionality of this app, you are strongly recommended to have a look after reading this "__Help__" page.

#### Learn
Gives a short introduction of how you can achieve some capability concepts using this app.

#### Reset
Reset the demo, clear all the data and progresses.

#### Share
Share this app by sending a text message containing the website where this app can be downloaded and installed on an Android phone.

[Back to Top](#top)

### The Scene
There are three people and two buildings in the scene.

#### The three people are
- __[Owner]__: the owner of the house
- __[Servant]__: the servant of the __[Owner]__
- __[Friend]__: the friend of the __[Owner]__

#### The two buildings are
- __House__: the Owner's house

- __Bank__: the bank where people could do some basic services such as open an account, delegate the account access and view the account

#### Note
There are three levels in this app and you can progress through answering quiz questions.

The higher the level, the more features will be unblocked.

[Back to Top](#top)

## Quiz
By clicking the __quiz image__ in the main page, you would enter the quiz page.

There are _5_ quiz questions in total and you can only progress to next question when you have answered the current one.

By giving the correct answer, you can get _20_ points for each question, otherwise you get 0.

Each question can only be answered __ONCE__.

- _Level 01_: the level you initially in
- _Level 02_: get 20 points (get 1 correct answer)
- _Level 03_: get 60 points (answer 3 questions correctly)

[Back to Top](#top)

## Level 01
In Level 01, the feature unblocked is the __House__.

### Functionality Introduction
There are few buttons you may want to know in the main page:

#### Capability overview
Shows the capabilities of all the three persons.

If you want to see the individual capabilities, you can click each person's image.

The capability is shown like this, for example _"house (infinite)"_ means one person has _infinite_ capability of entering the _House_.

There are _three_ types of capabilities:

1. infinite capability by the word "infinite"

2. the number of capabilities shown by a number, which specifies the number of times the person can use this capability

3. the time period capability by the word "period", which mean the person can have that capability within a given time period

#### Role
You can switch your role, in default, the role is set to be the __[Owner]__.

#### House
You can click the house image, if you have the capability to enter the house, you will directly enter the house.

#### Bank
Go to the bank by clicking the bank image, however it's currently blocked, you will need to reach _Level 03_ to unblock this feature.

[Back to Top](#top)

### House Feature
Once you enter the house, you can leave it by clicking the "__leave__" button.

Note that the Blacklist and Whitelist button can only be used by the __[Owner]__ and the "issue capability" function will be unblocked in _next level_.

#### Blacklist
As the __[Owner]__, you can decide the person to be added into the blacklist, the person in the blacklist will have all their house capability removed.

You can also find "__blacklist__" option when you select "__...__" on top right of the house page.

#### Whitelist
When you put the person in whitelist as the __[Owner]__, the person would have infinite house capability.

When you put a person in the whitelist you could also choose where to allow the person _further delegates_ your house capability.

You can also find "__whitelist__" option when you select "__...__" on top right of the house page.

#### Note
One person can not be in the white and black list spontaneously
[Back to Top](#top)

## Level 02
The __capability issuing__ for house is unblocked!

### Notice
Note that, from now on, the "__blacklist__" and "__whitelist__" options can only been view when select "__...__" on top right of the house page!

Their functionality remains the same, the only change is that the previous two buttons will no longer appear at the house page.

[Back to Top](#top)

### Issue House Capability
In this level, you can issue capability for House entry when you are in the role of __[Owner]__ or you are given the right to _further delegate_ your capability.

There are two types of capability you can issue: capability by _number of times_ and the capability by _a period of time_.

__Note__

1. for the demonstrate purpose, there are limits for you to set the capabilities, for example the maximum time capability issued is 120 seconds

2. the person who received that capability should in neither black nor white list

3. if the person already got the house capability, you cannot issue him house capability again until the previous one is used up, expired or been removed

[Back to Top](#top)

### Revoke House Capability

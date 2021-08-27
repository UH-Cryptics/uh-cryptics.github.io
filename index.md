# UH Cryptics

## Table of contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)

## Overview

_**The problem**_: Inventory management of products used for patients is tedious and time consuming.

_**The solution**_: Create a website that can handle inventory management of products with ease.

## Deployment

A live deployment of Zeus is available at [https://github.com/uh-cryptics/zeus](https://github.com/uh-cryptics/zeus). (change this link later when deployment is live)

## User Guide

This section provides a walkthrough of the Zeus user interface and its capabilities.

### Landing Page

The landing page is presented to users when they visit the top-level URL to the site.

![](doc/landingpage.png)

### Sign in and sign up

Click on the "Login" button in the upper right corner of the navbar, then select "Sign in" to go to the following page and login. You must have been previously registered with the system to use this option:

![](doc/sign-in.png)

Alternatively, you can select "Sign up" to go to the following page and register as a new user:

![](doc/register.png)

### User Home page

After logging in, you are taken to the home page, which presents the welcome message and guidelines what you can see and do.

### Admin

After admin login, can manage and maintain the website.

#### Admin page
To do

## Developer Guide

This section provides information of interest to Meteor developers wishing to use this code base as a basis for their own development tasks.

### Installation

First, [install Meteor](https://www.meteor.com/install).

Second, visit the [UH Cryptics application github page](https://github.com/uh-cryptics/zeus), and click the "Use this template" button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo.  However you do it, download a copy of the repo to your local computer.

Third, cd into the zeus/app directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

### Application Design

UH Cryptics is based upon [meteor-application-template-react](https://ics-software-engineering.github.io/meteor-application-template-react/) and [meteor-example-form-react](https://ics-software-engineering.github.io/meteor-example-form-react/). Please use the videos and documentation at those sites to better acquaint yourself with the basic application design and form processing in UH Cryptics.

## Initialization
To do

#### End to End Testing

UH Cryptics uses [TestCafe](https://devexpress.github.io/testcafe/) to provide automated end-to-end testing.

To do

## From mockup to production

UH Cryptics is meant to illustrate the use of Meteor for developing an initial proof-of-concept prototype.  For a production application, several additional security-related changes must be implemented:

* Use of email-based password specification for users, and/or use of an alternative authentication mechanism.
* Use of https so that passwords are sent in encrypted format.
* Removal of the insecure package, and the addition of Meteor Methods to replace client-side DB updates.

## Continuous Integration
To Do

## Development History

The development process for UH Cryptics conformed to [Issue Driven Project Management](http://courses.ics.hawaii.edu/ics314f19/modules/project-management/) practices. In a nutshell:

* Development consists of a sequence of Milestones.
* Each Milestone is specified as a set of tasks.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
* Tasks should typically consist of work that can be completed in 2-4 days.
* The work for each task is accomplished with a git branch named "issue-XX", where XX is replaced by the issue number.
* When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
* The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

The following sections document the development history of UH Cryptics.

### Milestone 1: Mockup development
To do

### Milestone 2: Data model development
To do

### Milestone 3: Fixes
To do

## Team

UH Cryptics is designed, implemented, and maintained by [UH Cryptics Organization](https://github.com/uh-cryptics/).

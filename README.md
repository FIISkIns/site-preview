# FII Skill Instructor - Site Preview [![Build Status](https://travis-ci.org/FIISkIns/site-preview.svg?branch=master)](https://travis-ci.org/FIISkIns/site-preview)

FIISkIns is a modular web app intended to be used as a virtual instructor.

Site-preview is a repository created for showcasing the front-end of the application.
For this part we chose three courses: Origami, Self-Defence and Survival.

All the pages are currently just templates:

- the Learn page shows how the courses' description will be organized
- the Profile page features a fictional user
- the Course page highlights how the information will fit in page.

## Structure

FIISkIns will provide valuable resources structured as tasks. Each area of interest
will have its own course, with different levels of difficulty: beginner, intermediate
and advanced, each level having a number of tasks available.

## Use

Visitors will be able to see the courses' description (available in the Learn page).
After registration or login, an user will have the possibility of enrolling in a
course.

## Course

A course is a collection of tasks related to a subject. All courses will be
displayed in the Course dropdown of the navigation bar. After choosing a course,
a corresponding page will show, displaying the current taks and the list of all
tasks in the course.

## Profile page

Each user will have a profile page, divided in two sections: statistics and achievements.
Achievements can be obtained by completing a number of tasks, enrolling in a course,
sharing a course, etc.

## Implementation

Each course will be implemented by an independent Web microservice.

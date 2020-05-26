---
title: "Projects"
template: "page"
socialImage: "/media/projects/habitinator/categories.png"
---

A show case of bunch of open source projects that I developed.

## Handover Tool

**Source:** https://github.com/hoomand/HandoverTool

**Website:** http://handovertool.hoomand.com/

If you over worked in a team that's spread around the globe and you needed to handover tickets to other teams, you probably felt the need for such a tool.

HandoverTool can clearly define the state of handover items, if they are fresh or thorough investigation is needed; it can also show the number of handover items between teams:

![homepage.png](/media/projects/handovertool/homepage.png)

It can also show the stats of users and number of their handovers, with break down details:

![user_stats.png](/media/projects/handovertool/user_stats.png)

Stack used is DERN! Yeah, DynamoDB, Express, ReactJS and NodeJS.

## Habitinator

Source: https://github.com/hoomand/habitinator

A multi user Ruby on Rails application for goal tracking.

You can sign up and start defining categories:

![categories.png](/media/projects/habitinator/categories.png)

There are 3 supported category types:

Number: Goals of this category type allow you to enter a numerical value for progress.
Percent: You should enter a percentage (a value less than 100) for any goal progress that you define of this category type.
True/False: Goals of this category type only let you record whether you did achieved that goal today or not; i.e. did you go to Gym today?
After defining a category, you can have your goals defined. For each goal you should mention what category it belongs to and define an optional target value:

![goals.png](/media/projects/habitinator/goals.png)

For instance you can define a goal named BodyPump, of category True/False and specify that you want to do 12 BodyPump sessions a month. You can save your progress and see how you did by clicking on BodyPump:

![goal_progress.png](/media/projects/habitinator/goal_progress.png)

This shows you your progress during the time frame you specified (monthly for this goal) and the days that you logged in.

# Use: track your chores and tasks!

## Goal
Grocy helps you remember your recurring chores and your tasks. It also allows you to split them between the members of your household. Grocy gives you reminders about your upcoming activites.

## Before you start
You will need:
- a working Grocy app or installation
- chores or tasks you want to track

## Chores

Chores are tasks that you want to perform over and over again. Such as cleaning, doing dishes, mow the lawn, etc.

### Manage master data

All chores are defined under _Manage master data_. You can see all your chores and edit them by pressing the cyan button and delete them by pressing the red button. You can see basic information regarding the chores in the list for _Manage master data_ (and also in _Chores overview_ described below).

![Master Data Chores](/images/choresmasterdata.png)

When you create a new chore you have to provide Grocy with information about how to treat the chore.

- **Name:** Name of the Chore.
- **Description:** A description of the chore.
- **Period Type:** How often the chores will be scheduled,
    - **Manually:** You have to manually schedule the chore
    - **Dynamic Regular:** After you have performed the task it is scheduled again a set number of days after you last performed it. You get the new option **Period Days** to set how many days after the last execution the chore should be rescheduled.
    - **Daily:** With daily you get the new option **Period Interval**. It is scheduled as often as the period inter val is set. If it is to *3*, the chore is scheduled every three days.
    - **Weekly:** Similar to *Daily* but the period interval is in weeks instead of days. You also get to set which day of the week the chore should be scheduled.
    - **Monthly:** Similar to *Weekly* and *Daily* but the period is in month and you get to set the day of the month instead of day of the week.
    - **Yearly:** Similar to *Daily* but the period is in years.
- **Assignment Type:** How should the assignment of the chore be setup.
    - **No Assignment:** The task is not assigned to anyone.
    - **Who least did it first:** The user who did the chore the least will be assigned the chore.
    - **Random:** The Chore gets assigned to a random person in the *Assign to* list.
    - **In Alphabetic Order:** The Chore gets assigned in alphabetic order.
- **Assign To:** The person or persons the chore will be assigned to according to assignment type.
- **Track date only:** When enabled only the day of an execution is tracked, not the time.
- **Due date rollover:** When enabled the chore can never be overdue, the due date will shift forward each day when due
- **Consume product on chore execution:** The product and the amount of that product that should be consumed when the chore is executed (For example dishwasher tablets when the dishwasher gets loaded.).

![Create Chores](/images/chorescreate.png)

### Chores overview

The _Chores overview_ screen gives you an overview of all chores you have, when they should be done, who they are assigned to and if any are soon to be due or overdue.

By pressing the green `Play` button, you register the chore as having been performed by the user who is signed in at this moment.

![Chores Overview](/images/choresoverview.png)

### Chore tracking

With chore tracking you can execute a chore and select which user executed the chore and at what time and date. The _Last tracked_ time is the time that user most recently performed the task.

![Chore Tracking](/images/choretracking.png)

## Tasks

Tasks are similar to chores but are intended for non-recurring tasks. Such as *Update Grocy Docs* or *Repair the lawn mower*.

### Manage master data

Under _Manage master data_, task categories can be created. Task categories are used to group and sort tasks.

![Task Categories](/images/taskcategories.png)

### Tasks

Under _Tasks_, tasks can be added, viewed and executed. You can review how many tasks you have, who they are assigned to, when they are due, and how many are due soon or overdue.

![Tasks](/images/tasksoverview.png)

By pressing `Add` you can create new tasks. You then have to provide some information.

- **Name:** Name of the task.
- **Description:** Description of the task.
- **Due:** When the task is due.
- **Category:** What category the task belongs to.
- **Assign to:** Who should perform the task.

![Create Task](/images/taskcreate.png)

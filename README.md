# many-to-many-Team-Creation-and-ProjectCreation

# version 0

Foreign key in followings contain both email and userID. But it should be only userID. This is improved in next version.

- projects collection
- teams collection

# Version 1

## Changes

1. Removed the teamLeader as object now teamLeader is a String type and stores the userID of the TeamLeader as an arry.
2. Removed the members as array of objects now it is an array of string. now it only stores string values i.e User-ID of the members.

## Work

-In order to make it work you have to delete the Projects,teams,register_users collections from the team_management_db

# Version 2

## Updation

1. Added Assign Project Page and route.
2. Also added the button on the Profile page of Project Manager named: Assign Project.

## Work

1.  Simply click on assign Project button this will open a page on which you can assign a Project to a Team.
    What this is doing is that it is adding assigning a project to a team by filling Assignedto field of the project with the team it is assigning to.

# Team Creation and Project Creation by Project Manager

# version 0

Foreign key in followings contain both email and userID. But it should be only userID. This is improved in next version.

- projects collection
- teams collection

Moreover, members in teams collection is object-of-array type is used. But it should be array. This will also imroved in version 1.

# Version 1

## Changes

1. teamLeader in "teams" collection is of Array type
2. members in "teams" collections is of Array type

## Work

-In order to make it work you have to delete the Projects,teams,register_users collections from the team_management_db

## issues in this version

- "createdBy" in "projects" collection, contains both userEmail and userID. Here, there should be only one foreign key i.e., userID. **This issue can be ignored at this stage, because we will not allowed to create same project by more than one user**.

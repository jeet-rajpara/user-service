# Backlog

- [ ] Project users [POST] route: only authorize use can create other users.

## Role

- should protect get Roles, Update, & delete role
- Default roles can't be deleted
- Only the role created by user can be deleted
- Add a flag `canBeDeleted`. If it is true then only alow to deleted
- Even admin can't deleted if the role is `isSystemRole`
- Add proper description about the role

## Permission

- export only one Get /permission route
- protect Get /permission route

## Role-Permission

- make a route for get, put, & deleted role-permission
- default role-permission can't be deleted
- Only the role-permission created by user can be deleted
- Add a flag `canBeDeleted`. If it is true then only alow to deleted
- Even admin can't deleted if the role-permission is `isSystemRole`
- Add proper description about the role-permission

## User-Role

- make a route for get, put, & deleted role-permission
- default role-permission can't be deleted
- Only the role-permission created by user can be deleted
- Add a flag `canBeDeleted`. If it is true then only alow to deleted
- Even admin can't deleted if the role-permission is `isSystemRole`
- Add proper description about the role-permission

## RBAC Permission

- Define the default permissions for `admin` since super-admin have all the permission and we can't give all permission to admin. (e.g. super-admin is like a president and admin is like a PM)
- Find a mechanism to allow user to switch their role. (Low priority).

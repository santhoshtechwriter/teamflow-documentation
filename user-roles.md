# User Roles and Permissions

## Overview

TeamFlow uses role-based access control to manage user permissions and ensure secure access to workspace resources.

## Available Roles

### Owner

Owners have complete access to all workspace settings and resources.

Permissions include:

* Manage billing
* Manage users
* Delete workspace
* Configure security settings
* Manage projects

### Administrator

Administrators help manage workspace operations.

Permissions include:

* Invite users
* Manage projects
* Configure workspace settings
* View reports

### Member

Members can participate in project activities.

Permissions include:

* Create tasks
* Update assigned work
* Comment on projects
* View reports

### Guest

Guests have limited access.

Permissions include:

* View shared resources
* Comment on assigned items

## Permission Matrix

| Permission       | Owner | Admin | Member | Guest   |
| ---------------- | ----- | ----- | ------ | ------- |
| Manage Users     | Yes   | Yes   | No     | No      |
| Create Projects  | Yes   | Yes   | No     | No      |
| Create Tasks     | Yes   | Yes   | Yes    | No      |
| View Reports     | Yes   | Yes   | Yes    | Limited |
| Delete Workspace | Yes   | No    | No     | No      |

## Best Practices

* Grant the lowest level of access necessary.
* Review permissions regularly.
* Remove inactive users promptly.
* Use administrator privileges sparingly.

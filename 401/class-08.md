# class 08 notes

## 5 steps to RBAC

What is Role Based Access Control (RBAC) and why do we care?

RBAC is the idea of assigning system access to users based on their role in an organization. We care because we dont want somebody who has no permissions to make changes.

Describe a Role/Permission heirarchy that you might implement using RBAC.

Admin -> Managers -> Supervisors -> Employees -> customer (no permission)

What approach might you take to implement RBAC?

find out what the roles are and their permissions.


## wiki - RBAC

If Authentication is “you are who you say you are,” what is Authorization?

access to be somewhere

Name three primary rules defined for RBAC.

Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.

Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.

Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

Describe RBAC to a non-technical friend.

assigns roles and access.

## RBAC tutorial

What Are access rights Associated with? The User? or The Role? Explain.

The role and user can have more than 1 role which give him/her more access rights

Access Rights, or Authorization, is activated after a user successfully does what?

Assigned a role.

Explain how RBAC might benefit a business.
Reflection

Security

## Sources

[RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)
[RBCA](https://en.wikipedia.org/wiki/Role-based_access_control)
[RBCA Tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)
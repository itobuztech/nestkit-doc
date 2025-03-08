---
title: Authentication
weight: 1
---
# Authentication 



## Auth Features Included 
- Login 
- Forget password 
- Change password 
- Register User 
- Verify Sign up with Email 
- Account lockout if wrong password attempt certain times 
- Two factor auth can be configured with email 
- JWT token verification with refresh token 


## Roles 

Application has three types of user roles
- Super Admin 
- Workspace Admin 
- User 
  
Additionally custom role can be created by super admin, workspace admin and who have role privileges.

Workspace Admin role can be automatically applied who have workspace owner privileges

## Privileges  
Fix set of privileges can be added by "db:seed" and based on privileges role guard and privileges guard implemented 

## Guards 
Application has few guards for authentication
- JWT Auth guard
- Role guard 
- Membership Guard 

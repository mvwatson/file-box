# file-box

## Overview

This is a tutorial project. It is intended to be implemented in many technologies.  This particular repository is for documentation and project management.

The overall functionality is a multi-user file sharing server. The clients can be web apps, mobile apps and desktop apps. Other repositories will be used for the 
various servers and clients.

Architecure is a SQL database for the metadata with a file store for the actual files. An app server provides the main functionality. A web server would support the web app, 
a web services server would support mobile and desktop apps. Failover and load balancing may not be implemented but will not be designed out. Serverless implementation 
will also not be designed out.

The initial technologies will be Java 8 and Java 11+ (currently 17, soon to be 18) with suitable application servers. Python, C# (.Net Core) and other languages will also 
be used for portions.

Automated testing will be an integral part of the development and DevOps will also be used for build/test/deploy.

## User Stories

As a SysAdmin, I need to lock users out from the site for maintenance and other purposes.

As a SysAdmin, I need to backup/restore the user data.

As a SysAdmin, I need to freeze/unfreeze/delete user accounts.

As a SysAdmin, I need to put quotas on user accounts.

As a user, I need self-service account creation/maintenance/password change.

As a user, I need to login/logout.

As a user, I need to upload/view lists of/download/delete files.

As a user, I need to grant permission for others to download files.

As a user, I need to send links to others who have been granted file download permission.
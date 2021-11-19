# file-box

This is a tutorial project. It is intended to be implemented in many technologies.  This particular repository is for documentation and project management.

The overall functionality is a multi-user file sharing server. The clients can be web apps, mobile apps and desktop apps. Other repositories will be used for the 
various servers and clients.

Architecure is a SQL database for the metadata with a file store for the actual files. An app server provides the main functionality. A web server would support the web app, 
a web services server would support mobile and desktop apps. Failover and load balancing may not be implemented but will not be designed out. Serverless implementation 
will also not be designed out.


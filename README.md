# MediWikiDeployment

Application, Database and Server: Apache Httpd with PHP, on CentOS 6 and the database will be MySQL running in Amazon RDS. 

Criteria: 
•	We'll have two instances of MediaWiki running on two t2.micro EC2 instances
•	These will be load balanced using HAProxy on one t2.micro
•	They'll be backed by a MySQL server running on a separate t2.micro

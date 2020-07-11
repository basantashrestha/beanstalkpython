Warning : The documentation is not complete .......
Steps to run this app using AWS Elastic Beanstalk and creating Codepipeline 

Summary: This follwing steaps create a elastic beanstalk environment in python environment.
Then creates a pipeline to pull code from github. 
The code also containers .ebextensions scripts which pulls the required python library.
Then launches the app

Prerequisits: ( This steps can also be done later after creating Beanstalk)  
keypair on the region you wish to work on. Eg. Mumbai, North virginia
Security group with ports  22, 80, 8501 - 8505 open.  



Repo
https://github.com/basantashrestha/beanstalkpython


Check app on. One one of the following port range.  
http://IP:8501 - 8505



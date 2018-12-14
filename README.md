# awscicd
aws ci/cd demo

This is a demo project to illustrate mvn - jenkins - aws integration CI/CD

A jenkins job is created to poll SCM and then do a mvn build and deploy it to AWS Elastic Beanstalk.

Before triggering a jenkins job, create an application in AWS Elastic Beanstalk and then create an environment with Tomcat.
Use the same app and enivronmnet configurations in your jenkins so that it would deploy to your AWS beanstalk.



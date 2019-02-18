# Continuous Integration Continuous Deployment

## Tools: 
Chef, Jenkins, AWS Services, GIT

## Role 
### Chef Workstation+ Jenkins Server on EC2 instance. 
Manages whole integration process
        
### Chef
Chef will manage creation of servers and maintanance of any perticular server.Let's say we have 100 servers then chef will identify server based on its attributes. No need to worry about ip addresses of servers to deploy
### AWS        
AWS S3 and EC2 are main services we are using to maintain builds and servers. Other services like IAM, Cloud Watch, Cloud front etc can also useful.
### GIT
Git is for version control.

## Summary
In consequence, from our project “Build automation using continuous integration and continuous deployment”, it can be determined that we can automate the “Software Development Life Cycle” also known as “SDLC” commencing Source-code Development to
Deployment on different servers. This new change would bring many enhancements in overall throughput by integrating line-ups and processes with a unified pipeline. This would bring improved quality in a reduced amount of time and with former troubleshooting technique.

In overall, this project will deploy the code on develpment/testing server just after developer commits the code on Git. The whole process of Developer to Production environment can be automated.

<h1>Continuous Integration Continuous Deployment</h1>
<h2>Tools:</h2>
Chef, Jenkins, Amazon Web Services, GIT</h2>
<h2>Role</h2>
<h3>Chef Workstation+ Jenkins Server on EC2 instance</h3>
Manages whole integration process</h4> 
<h3>Chef</h3> 
Chef will manage creation of servers and maintanance of any perticular server.Let's say we have 100 servers then chef will identify         server based on its attributes. No need to worry about IP addresses of servers to deploy.
<h3>AWS</h3>
AWS S3 and EC2 are main services we are using to maintain builds and servers. Other services like IAM, Cloud Watch, Cloud front etc         can also useful.
<h3>GIT</h3> 
Git is for version control.
<h2>Summary</h2>
In consequence, from our project “Build automation using continuous integration and continuous deployment”, it can be determined that we can automate the “Software Development Life Cycle” also known as “SDLC” commencing Source-code Development to Deployment on different servers. This new change would bring many enhancements in overall throughput by integrating line-ups and processes with a unified   pipeline. This would bring improved quality in a reduced amount of time and with former troubleshooting technique.  In overall, this project will deploy the code on develpment/testing server just after developer commits the code on Git. The whole process of Developer to Production environment can be automated.

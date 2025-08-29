# AWS Web Demo (using ELB+Rc2+RDS)
<img src="/diagrams/AWS_Cloud_Architecture.png">
Simple overview of use/purpose.

## Description
some description

## Getting Started

### Dependencies
AWS Management Console Account (free tier use optional)
Git bash (or your favourite CLI)
Internet access (to access your http website in real-time)

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program
PART 1) SECURITY GROUPS
* 3 security 
PART 2) INITIAL EC2 INSTANCE
PART 3) RDS CONNECTION
PART 4) AUTO-SCALING GROUP
* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help
Website not loading?
- Use "http" instead of "https"
ELB not loading?
1.
- Add "My ip" http connection to Web-Server security group
- Open public ip of EC2 on your laptop, see if working
2.
   1. If Ec2 works
      - Check ELB + Web-Server security groups & double-check connections are INBOUND & correctly set up as in the diagram
   2. If Ec2 doesnt work
      - Add "My ip" ssh connection to Web-server security group
      - SSH into ec2 w/ its public ip
      - Check to see that index.php is correct
My Auto-scaling-group isn't working?
- Delete your previous Launch template & AMI
- Recreate your AMI with a working EC2 web-server
- Recreate Launch template & run ASG

## Authors
Leonardo Paredes - All work (updated all from deprecated tutorial)

My SamplePageWithInstanceId.php, modified from AWS SamplePage.php code
https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Tutorials.WebServerDB.CreateWebServer.html

Learned from...
LinkedIn Learning Tutorial - "AWS Essential Training for Architects 2019"
https://www.linkedin.com/learning/aws-essential-training-for-architects-2019/amazon-web-services-essentials?u=67682169


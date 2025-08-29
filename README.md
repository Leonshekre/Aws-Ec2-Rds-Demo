# AWS Web Demo (using ELB+Rc2+RDS)
<img src="/diagrams/AWS_Cloud_Architecture.png">
Simple overview of use/purpose.

## Description
some description

## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help
Website not loading?
- Use "http" instead of "https"
ELB not loading?
1) 
- Add "My ip" http connection to Web-Server security group
- Open public ip of EC2 on your laptop, see if working
2.1) If Ec2 works
   - Check ELB + Web-Server security groups & double-check connections are INBOUND & correctly set up as in the diagram
2.2) If Ec2 doesnt work
   - Add "My ip" ssh connection to Web-server security group
   - SSH into ec2 w/ its public ip
   - Check to see that index.php is correct
My Auto-scaling-group isn't working?
- Delete your previous Launch template & AMI
- Recreate your AMI with a working EC2 web-server
- Recreate Launch template & run ASG

## Authors
Leonardo Paredes - All work (updated all from deprecated tutorial)

   Learned from
LinkedIn Learning Tutorial - "AWS Essential Training for Architects 2019"
https://www.linkedin.com/learning/aws-essential-training-for-architects-2019/amazon-web-services-essentials?u=67682169

* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)

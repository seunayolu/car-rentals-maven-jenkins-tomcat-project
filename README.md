# CLASS PROJECT: MAVEN, TOMCAT, & JENKINS

### Instructions:

## GIT Repository Setup

1. Create a Private Repository on your GitHub Account

2. Create three branches [Dev, Test, Prod]

3. Enable Collaboration on your repository by inviting at least one team member. NB: You may have to create one more GitHub account

4. Enable SSH Based authentication on your repository, adding each collaborator's public key.

5. Protect the Test and Prod Branches - 1 Approval is needed to merge code from Dev to Test, and 1 or 2 approvals are required to merge code from Test to Prod.

6. After a Successful Build and Deploy to Dev Tomcat Server, then submit a pull request to merge code into Test and from Test to Prod.

7. Every change you make follows that iterative process dev==>test==>prod

#### Pull Request Image

<img
  src="https://github.com/seunayolu/car-rentals-maven-jenkins-tomcat-project/blob/main/GitHub%20Pull%20Request.png"
  alt="Image"
  title="Pull Request"
  style="display: inline-block; margin: 0 auto; max-width: 30px">

### Project Modules:

1. Homepage
2. Fleet
3. Offers
4. More
5. About us
6. Contact us

NB: When you clone/fork the Repository into your Dev branch, three of the modules are visible namely: Home, Fleet, and Offers. Edit the index.html
to enable other modules, push the changes to Dev and Deploy to Tomcat using Jenkins.

## Setup Tomcat, Maven Server, & Jenkins

1. Setup Three Tomcat Server: Dev, Test, and Prod

2. Setup your Maven Server and Connect it to Jenkins 

3. Setup Your Jenkins Server to Build and Deploy artifact to Tomcat Server

4. Instruction on how to setup tomcat & maven can be found here: https://github.com/seunayolu/maven-build-website






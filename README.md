## CLASS PROJECT: MAVEN, TOMCAT, & JENKINS

### Instructions:

## GIT Repository Setup

1. Create a Private Repository on your GitHub Account

2. Create three branches [Dev, Test, Prod]

3. Enable Collaboration on your repository by inviting at least one team member. NB: You may have to create one more GitHub account

4. Enable SSH Based authentication on your repository, adding each collaborator's public key.

5. Protect the Test and Prod Branches - 1 Approval is needed to merge code from Dev to Test, and 1 or 2 approvals are required to merge code from Test to Prod.

6. After a Successful Build and Deploy to Dev Tomcat Server, then submit a pull request to merge code into Test and from Test to Prod.

#### Pull Request Image

![ARC](GitHub Pull Request.png)

### Project Modules:

1. Homepage
2. Fleet
3. Offers
4. More
5. About us
6. Contact us

NB: When you check-in the code into your Dev branch, three of the modules are visible namely: Home, Fleet, and Offers. Edit the index.html
to enable other modules, push the changes to Dev and Deploy to Tomcat using Jenkins.

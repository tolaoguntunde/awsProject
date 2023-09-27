# awsProject
aws project

## create AWS accounts for the project
 - serah.majekodunmi+prod@gmail.com will be used for production account
 - tolaoguntunde@gmail.com will be used for general account
 - enable biling access on both accounts

### create user account and attach admin policy
- create IAM account for both general and prod AWS account called iamadmin and attach admin policy


### install AWS CLI 

[AWS CLI INSTALL DOCUMENTATION](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)


### Create access key for the iadmin user in both account

- Create access key for iamadmin user and set aws configure in vscode

```aws configure --profile iamadmin-prod```
```aws configure --profile iamadmin-general```

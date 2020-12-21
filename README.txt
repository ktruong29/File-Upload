GROUP PROJECT 454

********************************************************************************
                                INTRODUCTION
********************************************************************************
  The purpose of this program is to implement an app where users can create an
account and upload their files to a cloud storage S3. In order to manage
user accounts we will have a MySQL database that will act as an identity provider
when new users make an account. The user's information and password (encrypted)
of a newly created account will be stored in MySQL RDS. The program shall be able
to authenticate user's credentials before using the services — uploading files
and viewing all the uploaded files.

********************************************************************************
                                PREREQUISITES
********************************************************************************
  - A VM running Ubuntu 20.04
  - AWS account + having these services configured:
    o- MySQL RDS instance
    o- AWS CLI
    o- AWS access keys
    o- S3 bucket
  - Install important dependencies
    o- Enter this command on the terminal to download packages
      o-- $sh pkgs.sh OR $./pkgs.sh
  - Change the values in config.py corresponding do your current end-point addresses/values

********************************************************************************
                              PROGRAM EXECUTION
********************************************************************************
$python3 app.py

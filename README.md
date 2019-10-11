# Stressy-Test-with-AWS-Life-Cycle-Hooks
Installs stressy via bash in a launch group configuration for AWS Linux instances with a complete lifecycle action hook to release the instance once stressy is installed. Stressy can then be used to max out an instance thereby testing the functionality of the associated auto scaling group
This is to be installed as plain text in the launch group's User Data section. 

Note: This is written as if the name of the autoscaling group is "devops-pro" launched in US East 1. Edit accordingly.

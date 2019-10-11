# Stressy-Test-with-AWS-Life-Cycle-Hooks
Installs stressy via bash in a launch group configuration for AWS Linux instances with a complete lifecycle action hook to release the instance once stressy is installed. Stressy can then be used to max out an instance thereby testing the functionality of the associated auto scaling group
This is to be installed as plain text in the launch group's User Data section. 

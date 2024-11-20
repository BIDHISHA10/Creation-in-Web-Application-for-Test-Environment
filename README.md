 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
## AIM
To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.

## ALGORITHM
 ## Step 1:
Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.

## Step 2:
Connect to the instance using SSH and install a web server like Apache

## Step 3:
Create a simple HTML file in the server's default directory with basic content for testing.

## Step 4:
Access the instance's public IP in a browser to verify the HTML page is displayed.
## COMMANDS
### webserver
To install httpd:
```
yum install httpd -y
```
To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
Create a simple HTML page :
```
cd /var/www/html
```
test.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
```
## OUTPUT
### REG NUMBER:212223040048
### NAME:GOGINENI BIDHISHA
 
### TERMINAL:
![image](https://github.com/user-attachments/assets/32eeaab4-8be7-45d7-b805-298b198183e3)
![image](https://github.com/user-attachments/assets/f7a8e732-3645-4d51-8497-01f0292ac790)
![image](https://github.com/user-attachments/assets/f302de7f-9584-4148-a8e3-3516265f86e8)
### WEBPAGE:
![image](https://github.com/user-attachments/assets/ff661815-79c9-4bc7-b0cf-bb34620f208d)

## RESULT
 
Thus the web application for test environment has successfully been created and executed.
  



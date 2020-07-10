# phdRepo
this is a simple application for sending simple text mail and attacments mail to any accaount using spring boot mail in  java .

in application folder you have to provide the following details :-
--------------------------------------------------------------------------------------

spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=<enter your email id>// here you have to enter your email accaount by which you want to send the mail
spring.mail.password=<password for this email id>//password for the above entered email id
# Other properties
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.connectiontimeout=5000
spring.mail.properties.mail.smtp.timeout=5000
spring.mail.properties.mail.smtp.writetimeout=5000
spring.mail.properties.mail.smtp.starttls.enable=true


NOte :
-----------------------

if in your account 2 factor authentication is enabled then please turn off this first and follow the below steps :

1.Login to Gmail. 
2.Access the URL as https://www.google.com/settings/security/lesssecureapps 
3.Select "Turn on"

after that try to run MailDemoApplication.java file you will get the below output 

Sending Email...
Done

else you will get an error like filenotfound Exception or Authentication failed in case of wrong username password and invalid file location 

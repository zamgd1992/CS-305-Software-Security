# CS-305
Artemis Financial had a skeleton for an online application. They needed to make it more secure. 

This was done by adding a CA so that it could run using HTTPS. This would be done by purchasing or using a free CA that is registered, 
however for the purpose of this application this is accomplished using a self-signed CA created locally and utilizing a local host through the browser.

The data transferred through the web application is sensitive and therefore needs to be encrypted. 
This is demonstrated through a hash algorithm. When accessed through local host the page shows the data that is encrypted 
as well as the algorithm used and the encrypted data. 

The other thing that was done to increase security is the use of static testing. The report generated through this can be used to find vulnerabilities 
such as outdated APIs. A suppression.xml file is used to suppress false positives as well has hide vulnerabilities that do not have fixes currently.

Though the refactored code for this assignment is mostly used to demonstrate how each security layer would be implemented, 
it is useful to know how each of these work. The steps taken in this project can be used in future projects. 

Security is a very important part of software development and should be part of the development process throughout each step. 
It is also important to note that if everyone has the mentality that you are responsible for the security of all the code you write, 
we will always develop more secure software. 

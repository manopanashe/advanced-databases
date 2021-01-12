## J Clarke Management Report
[Link to Hosted Website](https://dry-journey-02805.herokuapp.com/) <br>
[Link to Website GitHub Repoitory](https://github.com/manopanashe/assignment) <br>

## Introduction
J Clarke is a global retail Company that has over 40 store branches across the world. Its stores are very unique in many ways however the Adminstration for the comapny keeps logs for the store branches based on their numbers and locations and other various information and at the moment these logs are stored into separate CSV files. Due to Covid-19, it has become less efficient for the company to have their store detail logs in these separate file and this has also made the data they need  less accessible for them. 

To solve this problem i developed a proof of concept Web-application that moves these processes online. The site will be used only by the Company Managers and also the store branches managers. The store managers should be able to Create, Read,Update, Delete store logs into a dataset that contains the previuos logs. 

# System Overview
![alt text](C:\Users\manop\Downloads\System-diagram.png)
The system for this web-application will contain 
a mongoDb database that has three collections which will be derived from the existing CSV files that stored the  previous store logs. 

it also contains a MCV stack which contains the file system that handles all the CRUD operations and shapes the databases data. 
 
   ## INTERNET SERVICE PROVIDER MANAGEMENT SYSTEM
   
The project Internet Service Provider Management system includes registration of 
users, storing their details into the system.

The software has the facility to give a unique id for every customer who wants to take internet plan or dth plan and stores 
the details of every user. Users also contact with administrator without registration. 

The Internet Service Provider Management System can be entered using a username 
and password.
It is accessible either by an administrator .Only they can add data into 
the database.
The data can be retrieved easily. The interface is very user-friendly.

The data are well protected for personal use and makes the data processing very 
fast.

Internet Service Provider Management System is powerful, flexible, and easy to use 
and is designed and developed to deliver real conceivable benefits to internet and 
dth service provider companies. 

Internet Service Provider Management System is designed for internet and dth 
service provider companies, to cover a wide range of internet and dth service 
provider companies and management processes. 

Internet Service Provider Management System is a software product suite designed to improve the quality and 
management of internet and dth service provider companies.

Internet Service Provider Management System enables you to develop your organization and improve 
its effectiveness and quality of work.

Managing the key processes efficiently is critical 
to the success of the internet and dth service provider companies helps you manage 
your processes 
In proposed system we do not have to maintain record manually.

## ADMIN 
 
 Admin is the super user of the website who can manage everything on the 
website. 
Admin can log in through the login page 
 Dashboard: In this section, admin can see all detail in brief like new dth 
request, Assign dth request, rejected dth request, completed dth request, new 
broadband request, Assign broadband request, rejected broadband request, 
completed broadband request. 

 Broadband Plans: In this section, admin can mange Broadband Plans 
(add/update/delete). 

 DTH Plans: In this section, admin can mange DTH Plans (add/update/delete). 
 
 Pages: In this section, admin can manage about us and contact us pages. 
 
 Technicians: In this section, admin can mange technicians(add/update/delete) 
 Broadband Booking Request. 
 
 In this section, admin can manage broadband 
booking request and assign request to technicians.

 DTH Booking Request. In this section, admin can manage broadband DTH 
request and assign request to technicians. 

 Reported Issues: In this section, admin can manage the reported issues of the 
customers. 

 Reports: In this section, admin can generate between dates reports of 
broadband booking request and dth booking request in particular time 
periods. 

 Search: In this section, admin can search booking requests of broadband and 
dth by the help of booking number. 

 Reg Users: In this section, admin can view the details of registered users. 

 Admin can also update his profile, change the password and recover the 
password.  

## Software Requirement:- 
 
1. OS : Windows XP 
 
 
2.PHP Triad (PHP, MySQL, Apache, and PHPMyAdmin)

## PHP
		
PHP is a scripting language originally designed for producing dynamic web pages.

 It has evolved to include a command line interface capability and can be used in 
standalone graphical applications.

While PHP was originally created by Rasmus 
Lerdorf in 1995, the main implementation of PHP is now produced by The PHP Group 
and serves as the de facto standard for PHP as there is no formal specification.

PHP is free software released under the PHP License, however it is incompatible with the 
GNU General Public License (GPL), due to restrictions on the usage of the term PHP. 

It is a widely-used general-purpose scripting language that is especially suited for 
web development and can be embedded into HTML. 

It generally runs on a web server, taking PHP code as its input and creating web pages as output.

It can be deployed on most web servers and on almost every operating system and platform 
free of charge. 

PHP is installed on more than 20 million websites and 1 million web 
servers.

## SYNTAX

<html> 
 
<head> 
 
<title>PHP Test</title> 
 
</head> 
 
<body> 
 
<?php  echo  “<p>  Hello  World  </p>”;  ?> 
 
</body></html>

## Azure services:

## Virtual Machine:
Sign in to Azure Portal: Go to portal.azure.com and sign in with your Azure account.

Navigate to Virtual Machines: Once you're logged in, you'll be in the Azure dashboard. In the left-hand menu, select "Virtual machines" under the "Create a resource" section.

Click on Add: In the virtual machines pane, click on the "+ Add" button at the top.

Select Basics: In the "Create a virtual machine" page, you'll be prompted to fill out details for your virtual machine. Start by selecting "Basic" under the "Basics" tab.

Fill Out Basics: You'll need to provide basic information such as:

Subscription: Select the subscription to use for this virtual machine.
Resource group: Create a new resource group or use an existing one.
Virtual machine name: Enter a name for your virtual machine.
Region: Choose the region where you want to deploy your virtual machine.
Availability options: Choose availability options if needed.
Image: Select the operating system image you want to use (e.g., Windows, Linux).
Size: Choose the size of the virtual machine based on your requirements.
Configure Settings: Click on the "Next: Disks >" button to configure disks, networking, management, etc., if you need to customize these settings. Otherwise, you can leave them as default.

Review + Create: Review your configuration settings to ensure everything is correct. Click on the "Review + create" button.

Create the Virtual Machine: After reviewing, click on the "Create" button. Azure will now begin deploying your virtual machine based on the settings you provided.

Monitor Deployment: You can monitor the deployment progress in the Azure portal. Once the deployment is complete, you'll see a notification.

Access Your Virtual Machine: Once your virtual machine is deployed, you can access it using remote desktop (for Windows) or SSH (for Linux) depending on the operating system you selected.
Review your settings, and when you're ready, click on the "Review + create" button.
After validation passes, click on the "Create" button to create your VNet.

## Azure Vnet :

Sign in to the Azure portal at https://portal.azure.com/.
Click on the "Create a resource" button in the upper left corner.
In the search bar, type "Virtual Network" and press Enter.
Select "Virtual Network" from the search results.
Click on the "Create" button to begin the creation process.
Fill in the required details such as subscription, resource group, name, and region.
Configure the address space for your VNet.
Optionally, add one or more subnets to your VNet by specifying a name and address range for each subnet.
Configure additional settings if needed, such as DDoS protection, service endpoints, etc.

## Monitor in Azure:
Sign in to the Azure portal: Go to https://portal.azure.com/ and sign in to your Azure account.

Navigate to Monitor service: Once you're logged in, click on the "More services" option in the left-hand menu and search for "Monitor" in the search bar. Click on "Monitor" from the search results.

Create a new monitor: In the Monitor service, you'll typically find options to create various types of monitors such as metrics, alerts, or logs. Select the type of monitor you want to create (e.g., metric alert, activity log alert, diagnostic settings, etc.).

Configure monitor settings: Depending on the type of monitor you're creating, you'll need to configure specific settings. For example, if you're creating a metric alert, you'll need to select the resource, metric, condition, and action group. If you're setting up diagnostic settings, you'll need to choose the resource, logs/metrics to collect, and destination.

Review and create: Once you've configured the monitor settings, review them to ensure they're accurate. Then, click on the "Create" or "Save" button to create the monitor.

Verify monitor creation: After creating the monitor, you may want to verify that it's working as expected. You can do this by checking the monitor's status or triggering test events/alerts to ensure it's properly configured.

By following these steps, you can create monitors in the Azure portal to track various metrics, events, and activities within your Azure resources.

User
create monitor in azure
ChatGPT
To create a monitor in Azure, let's create a metric alert for a virtual machine as an example:

Sign in to the Azure portal: Go to https://portal.azure.com/ and sign in to your Azure account.

Navigate to the virtual machine: Use the search bar at the top of the portal to find and select your virtual machine.

Set up a metric alert:

In the left-hand menu for the virtual machine, under Monitoring, select "Alerts."
Click on the "+ New alert rule" button.
Define the condition:

In the "Condition" tab, click on "Add condition."
Choose the metric you want to monitor (e.g., CPU percentage).
Set the threshold and the condition for triggering the alert (e.g., greater than 90% for 5 minutes).
Configure other settings such as the time aggregation, period, and operator.
Define the action group:

In the "Actions" tab, click on "Create action group."
Enter a name for the action group.
Add notification methods (e.g., email, SMS) and details for each recipient.
Click on "OK" to save the action group.
Define the alert details:

In the "Alert details" tab, provide a name and description for the alert rule.
Choose the action group you created earlier.
Optionally, configure other settings such as severity and tags.
Review and create:

Review all the settings to ensure they are correct.
Click on the "Create alert rule" button to create the metric alert.
Verification:

Once created, you can verify the alert by monitoring the metrics of your virtual machine. If the conditions specified in the alert rule are met, an alert will be triggered, and the action group will be notified according to the defined notification methods.

 ## AI Bot  :
    In the Azure portal, Artificial Intelligence (AI) is utilized in various services and offerings across different categories. Here are some key areas where AI is prominently featured:

Azure Cognitive Services: Azure Cognitive Services provide a set of APIs and services for building intelligent applications using machine learning and AI. These services include Computer Vision, Speech Services, Language Understanding (LUIS), Translator, and more. You can access and manage these services in the Azure portal under the "AI + Machine Learning" category.

Azure Machine Learning: Azure Machine Learning is a cloud-based platform for building, training, and deploying machine learning models. It provides tools and services for data scientists and developers to collaborate on machine learning projects. You can create and manage machine learning workspaces, experiments, datasets, models, and deployments in the Azure portal.

Azure Bot Service: Azure Bot Service allows you to build, connect, deploy, and manage intelligent bots that interact with users across multiple channels. You can create and manage bot resources, channels, and channels registrations in the Azure portal.

Azure Cognitive Search: Azure Cognitive Search enables you to build AI-powered search solutions for your applications. It provides capabilities for indexing, searching, and analyzing structured and unstructured data. You can create and manage search services, indexes, data sources, indexers, and skillsets in the Azure portal.

Azure Databricks: Azure Databricks is an Apache Spark-based analytics platform optimized for big data and machine learning. It provides collaborative notebooks, interactive data exploration, and machine learning capabilities. You can create and manage Databricks workspaces, clusters, notebooks, andjobs in the Azure portal.

Azure AI Gallery: The Azure AI Gallery is a collection of AI models, solutions, and templates that you can deploy and use in your applications. You can browse, discover, and deploy AI resources from the Azure AI Gallery in the Azure portal.


## How to run Internet Service Provider Management Project using PHP and MySQL

Download the zip file
Extract the file and copy ispms folder
Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)
Open PHPMyAdmin (http://localhost/phpmyadmin)
Create a database with name ispmsdb
Import ispmsdb.sql file(given inside the zip package in SQL file folder)
Run the script http://localhost/ispms  (frontend)



User Credential

Username: anujk30@gmail.com

Password: Test@123

or Register a new user



Admin Credential

Username: admin

Password: Test@123


## screenshort

![image](https://github.com/sandy170303/ispms1/assets/154214673/93929ed6-ce3e-4cd1-ab34-b8130cd9df39)
![image](https://github.com/sandy170303/ispms1/assets/154214673/a111f8ba-0815-4e13-bb01-bd602167a5b3)
![image](https://github.com/sandy170303/ispms1/assets/154214673/9f262eb0-f6fc-47b2-bf2b-3d5df22e2753)
![image](https://github.com/sandy170303/ispms1/assets/154214673/8263d3ee-4236-47af-aa2a-ca72a5db6141)
![image](https://github.com/sandy170303/ispms1/assets/154214673/4fd6cccd-1271-48e9-a8f9-6f46e9885e20)
![image](https://github.com/sandy170303/ispms1/assets/154214673/08aa7d69-0d5e-48d7-b201-845ced9a001b)
![image](https://github.com/sandy170303/ispms1/assets/154214673/71cf8bba-82b4-41fa-8665-a440ee8db930)
![image](https://github.com/sandy170303/ispms1/assets/154214673/9ea95afa-c3aa-4a1e-9c38-0d53eed6aacd)
![image](https://github.com/sandy170303/ispms1/assets/154214673/407f65c8-348a-4731-8d3c-239cc70349ee)
![image](https://github.com/sandy170303/ispms1/assets/154214673/0037b402-d7af-4bec-8252-c23eb6fb7e6f)
![image](https://github.com/sandy170303/ispms1/assets/154214673/99315fff-1339-407f-98ad-3f19f3820da4)
![image](https://github.com/sandy170303/ispms1/assets/154214673/d8ed0d40-1713-4c60-87d1-07850956ea88)
![image](https://github.com/sandy170303/ispms1/assets/154214673/d21e50cb-3ba8-4df9-b850-29418d8c39e5)
![image](https://github.com/sandy170303/ispms1/assets/154214673/b9f8a496-72b4-4600-a962-59285f081ecf)
![image](https://github.com/sandy170303/ispms1/assets/154214673/3a62fbf6-209d-4e10-98fb-813465e2146a)
![image](https://github.com/sandy170303/ispms1/assets/154214673/93106cda-240e-4192-b22b-a8f0fbcc0558)
![image](https://github.com/sandy170303/ispms1/assets/154214673/18e52e00-81c2-4f83-9f3c-807519080253)
![image](https://github.com/sandy170303/ispms1/assets/154214673/78b0277d-18cd-42e9-b8c4-008b85f13c9e)
![image](https://github.com/sandy170303/ispms1/assets/154214673/7b146870-ef1a-44e4-8cfd-383f0b8c2934)
![image](https://github.com/sandy170303/ispms1/assets/154214673/d312386c-f2fb-4269-995b-4c1f9b6f203b)
![image](https://github.com/sandy170303/ispms1/assets/154214673/a2419323-3f99-48ae-a764-fde01b4c2f80)
![image](https://github.com/sandy170303/ispms1/assets/154214673/8f25238f-d9be-4129-8b74-16b8282cdcc7)
![image](https://github.com/sandy170303/ispms1/assets/154214673/7d1dd2e6-0c97-4b63-b7c1-279ab0c46fa8)
![image](https://github.com/sandy170303/ispms1/assets/154214673/c3813c7f-08f3-4652-b854-1f83679009c7)
![image](https://github.com/sandy170303/ispms1/assets/154214673/691af5ac-9b4c-4a9a-a976-aedd60e9a38e)
![image](https://github.com/sandy170303/ispms1/assets/154214673/14fbaf68-5fb3-4f45-935c-992ef9d133ee)
![image](https://github.com/sandy170303/ispms1/assets/154214673/53384986-00e8-44c1-a60c-117392292b4e)
![image](https://github.com/sandy170303/ispms1/assets/154214673/452aa509-9e16-40ff-b1a4-97271a375ba6)
![image](https://github.com/sandy170303/ispms1/assets/154214673/e49b4029-e197-435c-a0f1-d052599a83b5)
![image](https://github.com/sandy170303/ispms1/assets/154214673/c5315ed7-183a-442b-b0e8-e2cc46978038)
![image](https://github.com/sandy170303/ispms1/assets/154214673/1d8fcd60-7e68-4814-9c8a-f614eac814f1)
![image](https://github.com/sandy170303/ispms1/assets/154214673/3505cb3b-4843-4349-8b9a-0d676c86a4e1)
![image](https://github.com/sandy170303/ispms1/assets/154214673/bcc594e8-9f74-4f3e-a500-ffc743b5c42c)

## 


















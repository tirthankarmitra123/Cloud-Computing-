# Cloud-Computing
COMPANY: CODTECH IT SOLUTIONS

NAME: Tirthankar Mitra 

*INTERN ID*: CT12OAU

*DOMAIN*:: Cloud Computing

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

*Task 2* SET UP MONITORING FOR A CLOUD BASED APPLICATION USING AWS CLOUDWATCH, GOOGLE CLOUD MONITORING, OR AZURE MONITOR. 
DELIVERABLE: CONFIGURED ALERTS AND A DASHBOARD SHOWCASING METRICS.

Azure Monitor is a comprehensive monitoring solution for collecting, analyzing, and responding to monitoring data from your cloud and on-premises environments. You can use Azure Monitor to maximize the availability and performance of your applications and services. It helps you understand how your applications are performing and allows you to manually and programmatically respond to system events.

Azure Monitor collects and aggregates the data from every layer and component of your system across multiple Azure and non-Azure subscriptions and tenants. It stores it in a common data platform for consumption by a common set of tools that can correlate, analyze, visualize, and/or respond to the data. You can also integrate other Microsoft and non-Microsoft tools.

An alert rule monitors your data and captures a signal that indicates something is happening on the specified resource. The alert rule captures the signal and checks to see if the signal meets the criteria of the condition.

An alert rule combines:
The resources to be monitored.
The signal or data from the resource.
Conditions.
An alert is triggered if the conditions of the alert rule are met. The alert initiates the associated action group and updates the state of the alert. If you're monitoring more than one resource, the alert rule condition is evaluated separately for each of the resources, and alerts are fired for each resource separately.

Azure Monitor Metrics is a feature of Azure Monitor that collects numeric data from monitored resources into a time-series database. Metrics are numerical values that are collected at regular intervals and describe some aspect of a system at a particular time.

*Steps*
I have followed these following steps-

Step 1: Create a Windows Virtual Machine 

Step 2: Create a Azure Storage Account

Step 3: Create alert group and alert rule 
Go to 'azurestorage8563' > select alert in monitoring section > Create > Alert Rule > Select list storage account keys > apply > next > 
Create an action group > Signal name- Availibility, Threshold <100, Alert action group name- alertactiongroup1, Display name- alertgroup1 > Save > alert rule name- rule1 > Review + create > create 

Step 4: Create another alert rule 
Go to 'azurestorage8563' > select alert in monitoring section > Create > Alert Rule > Select list storage account keys > apply > next > 
Create an action group > Signal name- Used capecity, Threshold 100, Alert action group name- alertactiongroup2, Display name- alertgroup2 > Save > alert rule name- rule2 > Review + create > create 

Step 5: Create metrics
Go to Metrics > Scope- select virtual machine > apply > select server1 > apply > metric- percentage CPU > review + create > create 

*OUTPUT*

![Image](https://github.com/user-attachments/assets/e39d5ec3-09fd-4122-a5a2-e677fda48933)
![Image](https://github.com/user-attachments/assets/1fd80da5-aaa9-4fc8-9298-cc90da98facb)
![Image](https://github.com/user-attachments/assets/c427975c-f0d8-4756-800f-1f4c25dd8157)
![Image](https://github.com/user-attachments/assets/1681a2b7-6e3b-4cef-86cd-6c87e1ded410)
![Image](https://github.com/user-attachments/assets/d77dd3ca-d432-482d-81fb-63962f00bc8b)



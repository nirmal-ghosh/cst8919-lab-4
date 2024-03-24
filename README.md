CST8919 LAB 4 

REPORT

Name: Nirmal Ghosh

Task 1: Prepare Ubuntu Server

![](Aspose.Words.b97a40c9-447b-4042-8838-f3fae4b7d50e.001.png)

Task 2: Install Grafana 

![](Aspose.Words.b97a40c9-447b-4042-8838-f3fae4b7d50e.002.png)

Grafana step 2: 

![](Aspose.Words.b97a40c9-447b-4042-8838-f3fae4b7d50e.003.png)

Task 3: Install Monitor agent

3\.1 installing dependencies

![](Aspose.Words.b97a40c9-447b-4042-8838-f3fae4b7d50e.004.png)

3\.2 import Microsoft repository key

![](Aspose.Words.b97a40c9-447b-4042-8838-f3fae4b7d50e.005.png)

3\.3 Add azure monitor agent repository

![](Aspose.Words.b97a40c9-447b-4042-8838-f3fae4b7d50e.006.png)

3\.4 install azure cli

![](Aspose.Words.b97a40c9-447b-4042-8838-f3fae4b7d50e.007.png)

Task 4 : Connect Grafana to azure monitor 

![](Aspose.Words.b97a40c9-447b-4042-8838-f3fae4b7d50e.008.png)

**Report**
**
`	`For this lab, I had tried different methods to get to the result but in the end, I had to stop at Grafana deployment. At first, I tried to do everything in my own local virtual box Linux OS, I got as far as deploying Grafana and the deployment worked. I could access the dashboard using <http://localhost:3000> URL. But I could not get it to connect to the online Azure Monitor because certain conditions had to be met and couldn’t do one part of it because I lacked the necessary permissions in the Azure portal. 

In the old tenant, I could assign user roles, but I could not create app registrations, both of which are necessary for connecting with the Grafana dashboard. 

In the new tenant, I could create app registrations, but I could not assign user roles. Kind of like the exact opposite of my predicament with the old tenant.

The second time I tried to deploy the Grafana dashboard to an online Linux VM in azure hoping it would bypass the restrictions, but that did not work either. I found the documentation on how to connect the azure monitor to the Grafana dashboard within Grafana official website. I’ve provided a snapshot of the same below: 

![](Aspose.Words.b97a40c9-447b-4042-8838-f3fae4b7d50e.009.png)

In the new tenant, I don’t have a reader role and in the old tenant I don’t have permission to create app registrations. So I have submitted screenshots of all the steps that I could complete.











































































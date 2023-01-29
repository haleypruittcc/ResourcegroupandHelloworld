<p align="center">
<img src="https://logos-world.net/wp-content/uploads/2021/05/Azure-New-Logo.png"/>
</p>

<h1>Microsoft Azure</h1>
Azure is a platform for cloud computing and an online portal that you may use to access and administer Microsoft's cloud resources and services. 
The creation of a virtual machine and an Azure account will be demonstrated in this guide.
<h2>Tools and Requirements used </h2>

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)
- Microsoft Azure

<h2>Configuration Steps</h2>


<h3>Step 1: Create Azure Account</h3>


Create an Azure account [here](https://azure.microsoft.com/en-us/free/).

<p align="center">
<img src="https://i.imgur.com/riowusG.png" height="80%" width="80%" alt="Azure Free Account"/>
  


- Click on Start Free
- Follow the prompt to create the account. 
     - You must enter your credit card information, but in exchange, you will receive $200 in Azure credits that you have 30 days to utilize. Up until then, no charges will be applied.
- Finish prompt, click on  Go to Azure Portal and you are all done and ready to start with Azure!
     - You may also go to [portal.azure.com](https://www.portal.azure.com) to start



<h3>Step 2: Create Resource Group</h3>

- Go to search bar at the top and search "resource group"
- Select create resource group
- You will then need to name the resource group and select the region 
- Select review + create
    - For the example, we will be using RG-Lab-1 for the name and (US) West 3 for the region

<p align="center">
<img src="https://i.imgur.com/Afnk87u.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/yBBln5a.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>

<h3>Step 3: Create a storage Account</h3>

- Go to search bar and search "storage account"
- Select Create storage account
- You will need to select the resource group, the region, and create a name for the storage group
    - For the example we will name the storage group rglab1
    - Use same resource group and region as step 2
- Select review, then create.

<p align="center">
<img src="https://i.imgur.com/zhb3GHZ.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/7ryNBQg.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 4: Create Virtual Machine</h3>
     
- Go to search bar and search "virtual machine"
- Select create, then select Azure virtual machine
- You will need to select the resource group, the region, and create a name for the virtual machine
    - For the example we will name the virtual machine virtualmachine
    - Use same resource group and region as step 2/3

<p align="center">
<img src="https://i.imgur.com/y0RafHM.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/PCJ3QAr.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 



* You will then need to select image and size
    - For image we will use Windows 10 Pro
    - For size, select see all sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use labuser
    - Create your own password
* Click the box under licensing and finally click Review + Create 


<p align="center">
<img src="https://i.imgur.com/p9UJXND.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/GHBDae0.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 
     

<h3>Step 5: Connect to Virtual Machine</h3>

- First you will need to find the Public IP address of your virtual machine
   - Select the virtual machhine we created in step and the IP address will be on the right hand side 
   - Copy the IP address

Create a Virtual Machine on Azure 

<p align="center">
<img src="https://i.imgur.com/T4Oc2RX.png" height="80%" width="80%" alt="Azure Free Account"/>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Open application and click add PC
   - Paste IP address and select Add
   - Double click on the virtual machine and enter username and password from step 4
   - Select continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste IP Address and select Connect
     - Enter username and password from step 4
     - Select OK
  
     
     
 <p align="center">
<img src="https://i.imgur.com/14pPOdv.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/Og3LKyd.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>





🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img src="https://i.imgur.com/rEBpL8Y.png" height="80%" width="80%" alt="Azure Free Account"/>

<h3>Tip</h3>

-  If you want to save your free $200 credits, make sure you delete ALL resource groups after finishing!    
  

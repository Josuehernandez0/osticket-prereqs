# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<p align="center">
<img src="https://imgur.com/GxaTTh2.png)"/>
</p>
<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- OsTicket 

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- HeidiSQL
- MySQL
- OsTicket
- PHP Manager
- php
- Rewrite
- VC_redist

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/FfLLuvi.png"/>
</p>
<p>
First go to Microsoft Azure and type Resource Group then click create Resource Group
</p>
<br />

<p>
<img src="https://i.imgur.com/Lpk4qRU.png"/>
</p>
<p>
Now type RG-osticket for the name of the Resource Group. Next for the region click US West US 3 
</p>
<br />

<p>
<img src="https://i.imgur.com/IH0h9rm.png"/>
</p>
<p>
Now go to the review and create tab and click the create button on the bottom left 
</p>
<br />

<p>
<img src="https://i.imgur.com/y4vDMeP.png"/>
</p>
<p>
Now type Virtual Machines and click create azure virtual machine 
</p>
<br />

<p>
<img src="https://i.imgur.com/VUpuKrP.png"/>
</p>
<p>
Now select the resource group we created RG-osticket then the virtual machine name type VM-osticket and the region select the same as the resource group US West US 3 
</p>
<br />

<p>
<img src="https://i.imgur.com/6HSDPZn.png"/>
</p>
<p>
Now for the image select windows 10 pro version. For the size select standard Ec2 and the username type labuser and the password type a unique password remember to copy all this down on a notepad or physical paper
</p>
<br />

<p>
<img src="https://i.imgur.com/gU5W2sl.png"/>
</p>
<p>
Next click the licensing box and then click review and create 
</p>
<br />

<p>
<img src="https://i.imgur.com/l5Woq2y.png"/>
</p>
<p>
Now go to the networking tab and make sure virtual network, subnet, and public ip all says (new)
</p>
<br />

<p>
<img src="https://i.imgur.com/4ivyyJu.png"/>
</p>
<p>
Next create the virtual machine and you will see the deployment process start 
</p>
<br />

<p>
<img src="https://i.imgur.com/0UlHOQO.png"/>
</p>
<p>
Now the process will be done when you see a green check mark 
</p>
<br />

<p>
<img src="https://i.imgur.com/9GGUqUv.png"/>
</p>
<p>
Next go back to the virtual machine home page and click VM-osticket then copy the public IP address
</p>
<br />

<p>
<img src="https://i.imgur.com/oIvrUSd.png"/>
</p>
<p>
Next type Remote Desktop Connection in the search bar of your PC then click to open the app
</p>
<br />

<p>
<img src="https://i.imgur.com/kwpekMo.png"/>
</p>
<p>
Paste the public IP of VM-osticket into the computer section then click connect 
</p>
<br />

<p>
<img src="https://i.imgur.com/nOounVO.png"/>
</p>
<p>
<img src="https://i.imgur.com/xPmXf4U.png"/>
</p>
<p>
now for the user name type labuser and the password type the password you made for the VM
</p>
<br />

<p>
<img src="https://i.imgur.com/gADq5sY.png"/>
</p>
<p>
Next click yes to connect to the VM
</p>
<br />

<p>
<img src="https://i.imgur.com/pI6DhIL.png"/>
</p>
<p>
Now you will see the virtual machine log into labuser load
</p>
<br />

<p>
<img src="https://i.imgur.com/lMKl6nK.png"/>
</p>
<p>
Now click no for all the following in the image above 
</p>
<br />

<p>
<img src="https://i.imgur.com/jhRDu2J.png"/>
</p>
<p>
Now once the networks tab shows on the right side of the screen then click yes 
</p>
<br />

<p>
<img src="https://i.imgur.com/jIsjpOT.png"/>
</p>
<p>
Next right click the windows icon on the bottom left then click run 
</p>
<br />

<p>
<img src="https://i.imgur.com/XAItnC9.png"/>
</p>
<p>
Now type control type then click ok 
</p>
<br />

<p>
<img src="https://i.imgur.com/IKbOzBn.png"/>
</p>
<p>
Now click programs 
</p>
<br />

<p>
<img src="https://i.imgur.com/QYjBO3n.png"/>
</p>
<p>
Click programs and features
</p>
<br />

<p>
<img src="https://i.imgur.com/4e8qWzP.png"/>
</p>
<p>
Now click Internet Information Services
</p>
<br />

<p>
<img src=""/>
</p>
<p>
Now click world wide web services 
</p>
<br />

<p>
<img src="https://i.imgur.com/gllKSBr.png"/>
</p>
<p>
Next click application development features 
</p>
<br />

<p>
<img src="https://i.imgur.com/55sqEO6.png"/>
</p>
<p>
Next click the box for CGI
</p>
<br />

<p>
<img src="https://i.imgur.com/YgamoYY.png"/>
</p>
<p>
Next click Common HTTP Features 
</p>
<br />

<p>
<img src="https://i.imgur.com/NFaEeiV.png"/>
</p>
<p>
Now in Common HTTP Features click the box for everything then click ok 
</p>
<br />

<p>
<img src="https://i.imgur.com/fjlRXHs.png"/>
</p>
<p>
Then you will see a loading screen process 
</p>
<br />

<p>
<img src="https://i.imgur.com/gYpNeSI.png"/>
</p>
<p>
Now open up microsoft excel and click start without your data
</p>
<br />

<p>
<img src="https://i.imgur.com/imfxzL3.png"/>
</p>
<p>
Now click continue without this data 
</p>
<br />

<p>
<img src="https://i.imgur.com/vBIVXds.png"/>
</p>
<p>
Next click confirm and continue 
</p>
<br />

<p>
<img src="https://i.imgur.com/B0baAtj.png"/>
</p>
<p>
Finally click continue and start browsing 
</p>
<br />

<p>
<img src="https://i.imgur.com/LqQLAo4.png"/>
</p>
<p>
Next once the process is complete click close 
</p>
<br />

<p>
<img src="https://i.imgur.com/y8tNZPJ.png"/>
</p>
<p>
Now in order to see if the process worked type 127.0.0.1 in the search bar and you will see the same image above 
</p>
<br />

<p>
<img src="https://i.imgur.com/vKwfau3.png"/>
</p>
<p>
Next open the link and download PHP Manager for IIS click the download symbol on the side
</p>
<br />

<p>
<img src="https://i.imgur.com/lDgekwz.png"/>
</p>
<p>
Now open up file explorer and go to your downloads folder then double click PHP manager 
</p>
<br />

<p>
<img src="https://i.imgur.com/PP7AS3i.png"/>
</p>
<p>
Next click next 
</p>
<br />

<p>
<img src="https://i.imgur.com/vpbruIC.png"/>
</p>
<p>
Next click I agree and then next 
</p>
<br />

<p>
<img src="https://i.imgur.com/3DHoN99.png"/>
</p>
<p>
Finally click close 
</p>
<br />

<p>
<img src="https://i.imgur.com/hEDLHRg.png"/>
</p>
<p>
Next go back to the link and download Rewrite Module click the download symbol 
</p>
<br />

<p>
<img src="https://i.imgur.com/c1OInEq.png"/>
</p>
<p>
Go back to file explorer and double click rewrite 
</p>
<br />

<p>
<img src="https://i.imgur.com/PfaLBqO.png"/>
</p>
<p>
Click I accept then install 
</p>
<br />

<p>
<img src="https://i.imgur.com/uIvVWNM.png"/>
</p>
<p>
Now let the process start 
</p>
<br />

<p>
<img src="https://i.imgur.com/4P0G5A1.png"/>
</p>
<p>
Next click finish
</p>
<br />

<p>
<img src="https://i.imgur.com/NRjYek1.png"/>
</p>
<p>
Next go back to the link and download PHP 7.3.8 click the download symbol 
</p>
<br />

<p>
<img src="https://i.imgur.com/U0b4Brl.png"/>
</p>
<p>
Go back to file explorer and you will see the file in the download folder 
</p>
<br />

<p>
<img src="https://i.imgur.com/B2k4ALc.png"/>
</p>
<p>
Now click on Windows (C) 
</p>
<br />

<p>
<img src="https://i.imgur.com/HSjtjff.png"/>
</p>
<p>
From here right click anywhere and click new then select folder 
</p>
<br />

<p>
<img src="https://i.imgur.com/S6eiMCm.png"/>
</p>
<p>
Now name the folder PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/zOGdeuB.png"/>
</p>
<p>
Go back to the download folder and right click php folder then click Extract All
</p>
<br />

<p>
<img src="https://i.imgur.com/xQtIyqC.png"/>
</p>
<p>
Now click browse 
</p>
<br />

<p>
<img src="https://i.imgur.com/WORzo0E.png"/>
</p>
<p>
Next go to Windows (C) then click the PHP folder we created 
</p>
<br />

<p>
<img src="https://i.imgur.com/ao4kf1q.png"/>
</p>
<p>
Now once you are in the folder click select folder on the bottom right 
</p>
<br />

<p>
<img src="https://i.imgur.com/yRftp6b.png"/>
</p>
<p>
Now click the extract button
</p>
<br />

<p>
<img src="https://i.imgur.com/G2YyWsC.png"/>
</p>
<p>
Next you will see all the files load into the PHP folder
</p>
<br />

<p>
<img src="https://i.imgur.com/k1f3xCC.png"/>
</p>
<p>
Next go to the link and click the link to download VC RedistX86.exe click the download symbol
</p>
<br />

<p>
<img src="https://i.imgur.com/u6SeSam.png"/>
</p>
<p>
Now go to file explorer and double click VC_redist 
</p>
<br />

<p>
<img src="https://i.imgur.com/m6Os30Q.png"/>
</p>
<p>
Click Install 
</p>
<br />

<p>
<img src="https://i.imgur.com/UETxXLC.png"/>
</p>
<p>
Now once the process is done click close 
</p>
<br />

<p>
<img src="https://i.imgur.com/yIYvKjj.png"/>
</p>
<p>
Next click the link an download MySQL 5.5.62 then click the download symbol 
</p>
<br />

<p>
<img src="https://i.imgur.com/0nJLJmI.png"/>
</p>
<p>
Now go to file explorer and double click mysql to open the program 
</p>
<br />

<p>
<img src="https://i.imgur.com/qpCsSNu.png"/>
</p>
<p>
Next click next 
</p>
<br />

<p>
<img src="https://i.imgur.com/ytdoReA.png"/>
</p>
<p>
Next click next 
</p>
<br />

<p>
<img src="https://i.imgur.com/zBasKVo.png"/>
</p>
<p>
Now click Typical 
</p>
<br />

<p>
<img src="https://i.imgur.com/3Jq4MiR.png"/>
</p>
<p>
Next click install 
</p>
<br />

<p>
<img src="https://i.imgur.com/8PY9wno.png"/>
</p>
<p>
Now click finish 
</p>
<br />

<p>
<img src="https://i.imgur.com/tx9WwHk.png"/>
</p>
<p>
Now click next 
</p>
<br />

<p>
<img src="https://i.imgur.com/9K1OWZb.png"/>
</p>
<p>
Now click Standard Configuration then click next 
</p>
<br />

<p>
<img src="https://i.imgur.com/PhgvASW.png"/>
</p>
<p>
Now click Install as Windows Service then click next 
</p>
<br />

<p>
<img src="https://i.imgur.com/P97ViWS.png"/>
</p>
<p>
Now type the password. For this example I'm going to type Password1 then click next 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/43cc6062-a91c-45b0-8a92-6a6a54352a95"/>
</p>
<p>
Next click execute to finish the process
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/e3da9c2f-3f14-4be1-9257-7655551e44fa"/>
</p>
<p>
You will then see the process finish 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/cadedd65-6d83-4410-a35d-80498ddc9a08"/>
</p>
<p>
Now type IIS or Internet Information Services then right click then click run as administrator 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/5f0a0fe5-14b6-4fcb-be1a-de682dce0d72"/>
</p>
<p>
Now click PHP Manager 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/4a0bfe9a-840e-48fa-ac4e-428cb082281f"/>
</p>
<p>
Next click Register new PHP version 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/ebbc52d3-3b98-4d04-923d-bb8db0565ef2"/>
</p>
<p>
Now you will see this tab, click the three dots on the right side  
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/37ab34e9-80f1-489a-9b61-f52032aed5b0"/>
</p>
<p>
Now go to Windows (C) then click the PHP folder we created earlier 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/2145448d-3c40-41be-b8e0-d148f17f4ab4"/>
</p>
<p>
Now click the PHP foler then click php-cgi 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/2088c3cf-6797-45f8-a674-e6378ce5abd5"/>
</p>
<p>
Now you will see the path before you on the white bar then click ok 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/20c27225-d41e-4637-8edd-27bc194c39e1"/>
</p>
<p>
Now you will see that the caution sign disappeared from PHP Setup
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/6640a965-fdfe-4a0f-b1e1-3d247d23993d"/>
</p>
<p>
Go back to Microsoft Azure and click VM-osticket then click restart. Then click yes to restart the VM
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/3a46f250-37fd-4d70-847a-22b7f7b16f17"/>
</p>
<p>
Now you will see that the VM is loading 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/c78817ef-dd63-4454-b60f-39eac21ff56e"/>
</p>
<p>
Now go to the link and download osTicket then click the download symbol
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/628b7a9f-2c18-4acd-a0d0-e4e556907578"/>
</p>
<p>
Next open file explorer and you will see osTicket was installed as a zip file 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/0fda9fa0-2436-496a-9c11-69cb9dacb6ee"/>
</p>
<p>
Next go to Windows (C)
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/45b9b90a-84c1-45aa-b7e6-2ea1c0aa785f"/>
</p>
<p>
Next click inetpub folder 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/bbf29450-52f0-41ff-ad80-53c9c17caf42"/>
</p>
<p>
Now click the wwwroot folder
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/df9cc101-2472-40d4-be92-54ee43ef90c7"/>
</p>
<p>
Now you will be in the wwwroot folder and see the following 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/2393e12c-ada5-4532-8ed5-af6f456cad69"/>
</p>
<p>
Next go back to the osTicket folder and click the upload folder 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/8ab5c340-0c96-4c88-bc5b-8e407b26c4c4"/>
</p>
<p>
Now drag the upload file to the wwwroot folder
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/e498f010-8092-4e5b-9fe1-a223e392605f"/>
</p>
<p>
Once the files are done copying over rename the file osTicket in wwwroot folder
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/1bdebc35-ffc8-421e-a1a5-f82d0750f6a2"/>
</p>
<p>
Next type IIS or Internet Information Services then right click and open as administrator
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/8f159bee-0b7b-4625-9a7f-f8987bdbea71"/>
</p>
<p>
Now click the VM-osticket and then click restart on the right side 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/ac9a6e67-47a2-4e1c-b8d2-0774756155fc"/>
</p>
<p>
Next click the sites folder 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/b53533a6-5499-495b-9d12-2888c9fe441c"/>
</p>
<p>
Next click the osTicket folder 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/0b312203-94be-4dfc-b1f6-b8003c65afb8"/>
</p>
<p>
Now click Browse *80 (http) 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/075cdf14-74d8-48db-932f-ebcfb99cdce3"/>
</p>
<p>
You will see the page load with alot of green check and red checks 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/9e4cd293-049d-4e3e-bfc1-b3384f31798a"/>
</p>
<p>
Next go to PHP Manager 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/09fd821f-6935-4610-a48b-86d3e49b3528"/>
</p>
<p>
Next click enable or disable an extension 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/bbb4ad96-ae43-4098-97b8-0460b4258dea"/>
</p>
<p>
Now find php_imap.dll we can see its disbale then click, then go to the top right then click enable 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/d272733a-a8f5-42e6-a104-a8acf1d87e06"/>
</p>
<p>
Now find php_intl.dll then click, then go to the top right then click enable 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/76650fea-0640-49b0-a41a-e40fbf2d3456"/>
</p>
<p>
Now find php_opcache.dll then click, then go to the top right then click enable
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/f56f70f5-6900-4801-aa07-578c9e2a9855"/>
</p>
<p>
Now go back to the osTicket home page 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/07f2bf28-3b75-4b93-9d9c-b93c420cb762"/>
</p>
<p>
Next click continue 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/a2a60e2c-1ff6-4bcf-96ae-cc58edbae2ea"/>
</p>
<p>
Now go back to the osTicket folder from wwwroot
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/3ea95a96-51ad-4e58-b83a-b0efefa789bd"/>
</p>
<p>
Next click the include folder 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/42c79898-b086-4a31-9fb0-1fec407d6a2c"/>
</p>
<p>
Now click ost-sampleconfig.php
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/7fc88de0-5eca-4a5d-9256-4c6bc2407a9b"/>
</p>
<p>
Now rename the file to ost-config.php
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/811492d9-ef0b-47d5-b51f-e11fc80f25ab"/>
</p>
<p>
Next right click the file then go to properties 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/fa970fff-95f5-4221-b56c-94db11a0d440"/>
</p>
<p>
Now click the security tab 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/a46381c5-d906-481f-bec0-f9cb3783d8ed"/>
</p>
<p>
Next click the advanced button
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/55a113f1-bffb-4338-9bc9-5621c7368e77"/>
</p>
<p>
Now click disable inheritance 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/cffb17c6-f381-4187-af58-93ae40460bf0"/>
</p>
<p>
Next click remove all inherited permission from this object 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/8ad6d188-2cbd-44fb-8509-fe4ba7176163"/>
</p>
<p>
Next click add 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/176efbeb-5fdc-4a70-9a44-1c9c59d0ac4e"/>
</p>
<p>
Next click select a principal
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/85fc3f75-b2ad-46d6-83a4-63d26dc9e2ce"/>
</p>
<p>
Now type everyone 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/a857d05b-234a-475c-9f9b-55cfc4368e3c"/>
</p>
<p>
Now click ok 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/4c34624d-f5e2-48df-8b73-e9fb157fafe2"/>
</p>
<p>
Now click all the permissions then click ok 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/1c591885-b33f-484d-aafe-f2ac5f5768ce"/>
</p>
<p>
Now click apply 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/7be67c43-7a1e-4804-985d-a2c216d5c44b"/>
</p>
<p>
Next click ok 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/3c17f685-1f6e-4e1b-9b23-8d4eab55626b"/>
</p>
<p>
Now click ok 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/3998f1b6-1ca6-43c2-bc39-bc7b02703444"/>
</p>
<p>
Next go back to the OsTicket home page and click continue
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/0563e86f-5b37-4e20-97e5-28762d41a552"/>
</p>
<p>
For the helpdesk name type josh help desk, the deafult email type josh@help.com. Now for admin user the first name type josh then the last name type garcia. For email address type josh@gmail.com. For the username josh then type the password I will type Password1. 
</p>

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/f76320fc-4ab9-41f5-b3c4-a057330a89a1"/>
</p>
<p>
Now go to back to the link and download HeidiSQL then click the download symbol
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/28b301f0-e839-4cbd-8aea-f1d5bcdceb40"/>
</p>
<p>
Now go to file explorer and double click HediSQL
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/c8d7d7ea-f9e5-483a-84ba-42fc48c34c14"/>
</p>
<p>
Next click I accept the agreement then click next 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/4c09d5e1-a1ec-4ecd-b351-cff2644c9352"/>
</p>
<p>
Next click install
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/052ad3b3-ab82-4479-88bf-859a28d2f721"/>
</p>
<p>
You will see the process start 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/e52fd989-0735-449d-ac63-32d03400e29d"/>
</p>
<p>
Next click finish 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/93171893-f444-4e2c-a3ef-6ec6fa81f7ac"/>
</p>
<p>
Next click skip 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/02baf490-ba6b-4042-a825-0088e7c583ff"/>
</p>
<p>
Now type root
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/1c84cfb4-97d7-4014-a1ec-3dffb2c1c4c7"/>
</p>
<p>
Next for the password section type Password1 then click open
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/a4b4daff-d66e-4e86-b894-212d91c6f0f8"/>
</p>
<p>
Now you will see the unamed tab 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/ece476ab-ebc7-4c51-8fdb-6e20f89202e0"/>
</p>
<p>
Next type root for the MySQL Username then for the MySQL Password type Password1
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/5f2e5a35-ed90-497b-a8ff-d500552d2923"/>
</p>
<p>
Now right click Unamed then go to create new then click Database
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/27cf046b-9eb5-453b-8701-2b9be2d8b24e"/>
</p>
<p>
Next type osTicket then click ok 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/b8f9d0ff-d1d1-458b-8ba0-5fc79b270f6f"/>
</p>
<p>
Next type osTicket for MySQL Database
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/735b889b-91fb-4865-bc1e-d641db847f10"/>
</p>
<p>
Now you will see the process load 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/c0f2ae4e-4f2a-4ac4-bbdb-de5a3f21ba22"/>
</p>
<p>
Next you will see the process finish and osTicket was installed
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/76cd532d-f6ff-4f51-bae1-ff8e87505bf3"/>
</p>
<p>
Next go to the osTicket folder and delete the setup folder
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/5ed0cb3e-3f8b-4fcf-84c4-be1930ca41ed"/>
</p>
<p>
Now click ost-config.php
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/be19e868-c931-4ca5-b3f7-fa3d257cf0c6"/>
</p>
<p>
Right click and go to properties 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/6db9f04f-224a-4c5f-9cd4-92a9c6638a20"/>
</p>
<p>
Next click advanced 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/92146206-b6cc-416b-af36-8120cef97380"/>
</p>
<p>
Now click permissions
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/06516cbe-e712-4a18-b380-d183d9363823"/>
</p>
<p>
Next click allow everyone then click edit 
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/405cc032-a569-40d3-a20b-a56bf757217a"/>
</p>
<p>
Now uncheck full control, modify, and write then click ok  
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/c28422dc-faf8-40aa-9408-334738c1d909"/>
</p>
<p>
Now click apply
</p>
<br />

<p>
<img src="https://github.com/josuehernandez0/osticket-prereqs/assets/143027686/20df729d-6052-413c-ba38-c9048da1ca23"/>
</p>
<p>
Finally click ok then click the link to continue the Post-Installation Configuration https://github.com/josuehernandez0/post-install-config
</p>
<br />

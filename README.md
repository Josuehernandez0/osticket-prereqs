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

- Microsoft Azure (Virtual Machines/Computer)
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
<img src="https://i.imgur.com/KkpXSJK.png"/>
</p>
<p>
Next click execute to finish the process
</p>
<br />

<p>
<img src="https://i.imgur.com/FgzpIap.png"/>
</p>
<p>
You will then see the process finish 
</p>
<br />

<p>
<img src="https://i.imgur.com/BGCFHsD.png"/>
</p>
<p>
Now type IIS or Internet Information Services then right click then click run as administrator 
</p>
<br />

<p>
<img src="https://i.imgur.com/EoIAN1C.png"/>
</p>
<p>
Now click PHP Manager 
</p>
<br />

<p>
<img src="https://i.imgur.com/u8hV3Ma.png"/>
</p>
<p>
Next click Register new PHP version 
</p>
<br />

<p>
<img src="https://i.imgur.com/9PPZuWc.png"/>
</p>
<p>
Now you will see this tab, click the three dots on the right side  
</p>
<br />

<p>
<img src="https://i.imgur.com/pVIW6xL.png"/>
</p>
<p>
Now go to Windows (C) then click the PHP folder we created earlier 
</p>
<br />

<p>
<img src="https://i.imgur.com/w2xWnbT.png"/>
</p>
<p>
Now click the PHP foler then click php-cgi 
</p>
<br />

<p>
<img src="https://i.imgur.com/9FaeP0W.png"/>
</p>
<p>
Now you will see the path before you on the white bar then click ok 
</p>
<br />

<p>
<img src="https://i.imgur.com/kO939J1.png"/>
</p>
<p>
Now you will see that the caution sign disappeared from PHP Setup
</p>
<br />

<p>
<img src="https://i.imgur.com/VCuiFyp.png"/>
</p>
<p>
Go back to Microsoft Azure and click VM-osticket then click restart. Then click yes to restart the VM
</p>
<br />

<p>
<img src="https://i.imgur.com/11uvo9h.png"/>
</p>
<p>
Now you will see that the VM is loading 
</p>
<br />

<p>
<img src="https://i.imgur.com/vqFssDO.png"/>
</p>
<p>
Now go to the link and download osTicket then click the download symbol
</p>
<br />

<p>
<img src="https://i.imgur.com/4m9qzlH.png"/>
</p>
<p>
Next open file explorer and you will see osTicket was installed as a zip file 
</p>
<br />

<p>
<img src="https://i.imgur.com/Hb7VSOo.png"/>
</p>
<p>
Next go to Windows (C)
</p>
<br />

<p>
<img src="https://i.imgur.com/kVKw9uM.png"/>
</p>
<p>
Next click inetpub folder 
</p>
<br />

<p>
<img src="https://i.imgur.com/IGbq7Cw.png"/>
</p>
<p>
Now click the wwwroot folder
</p>
<br />

<p>
<img src="https://i.imgur.com/VtbvteT.png"/>
</p>
<p>
Now you will be in the wwwroot folder and see the following 
</p>
<br />

<p>
<img src="https://i.imgur.com/03W4GNd.png"/>
</p>
<p>
Next go back to the osTicket folder and click the upload folder 
</p>
<br />

<p>
<img src="https://i.imgur.com/2RUSNBA.png"/>
</p>
<p>
Now drag the upload file to the wwwroot folder
</p>
<br />

<p>
<img src="https://i.imgur.com/IfXIAgn.png"/>
</p>
<p>
Once the files are done copying over rename the file osTicket in wwwroot folder
</p>
<br />

<p>
<img src="https://i.imgur.com/myuhkb3.png"/>
</p>
<p>
Next type IIS or Internet Information Services then right click and open as administrator
</p>
<br />

<p>
<img src="https://i.imgur.com/HMnxF2Y.png"/>
</p>
<p>
Now click the VM-osticket and then click restart on the right side 
</p>
<br />

<p>
<img src="https://i.imgur.com/urd7qTb.png"/>
</p>
<p>
Next click the sites folder 
</p>
<br />

<p>
<img src="https://i.imgur.com/Rh9DnPy.png"/>
</p>
<p>
Next click the osTicket folder 
</p>
<br />

<p>
<img src="https://i.imgur.com/P4dRIzl.png"/>
</p>
<p>
Now click Browse *80 (http) 
</p>
<br />

<p>
<img src="https://i.imgur.com/ZYts3VL.png"/>
</p>
<p>
You will see the page load with alot of green check and red checks 
</p>
<br />

<p>
<img src="https://i.imgur.com/Zlut5pV.png"/>
</p>
<p>
Next go to PHP Manager 
</p>
<br />

<p>
<img src=""/>
</p>
<p>
Next click enable or disable an extension 
</p>
<br />

<p>
<img src="https://i.imgur.com/bAwCveu.png"/>
</p>
<p>
Now find php_imap.dll we can see its disbale then click, then go to the top right then click enable 
</p>
<br />

<p>
<img src="https://i.imgur.com/oArK1AX.png"/>
</p>
<p>
Now find php_intl.dll then click, then go to the top right then click enable 
</p>
<br />

<p>
<img src="https://i.imgur.com/JCXerWJ.png"/>
</p>
<p>
Now find php_opcache.dll then click, then go to the top right then click enable
</p>
<br />

<p>
<img src="https://i.imgur.com/dd4dzUc.png"/>
</p>
<p>
Now go back to the osTicket home page 
</p>
<br />

<p>
<img src="https://i.imgur.com/9VqSnFX.png"/>
</p>
<p>
Next click continue 
</p>
<br />

<p>
<img src="https://i.imgur.com/HZMFMyQ.png"/>
</p>
<p>
Now go back to the osTicket folder from wwwroot
</p>
<br />

<p>
<img src="https://i.imgur.com/lkNAMps.png"/>
</p>
<p>
Next click the include folder 
</p>
<br />

<p>
<img src="https://i.imgur.com/M9iWACh.png"/>
</p>
<p>
Now click ost-sampleconfig.php
</p>
<br />

<p>
<img src="https://i.imgur.com/U9lfhJ9.png"/>
</p>
<p>
Now rename the file to ost-config.php
</p>
<br />

<p>
<img src="https://i.imgur.com/foHfpMR.png"/>
</p>
<p>
Next right click the file then go to properties 
</p>
<br />

<p>
<img src="https://i.imgur.com/f8npPLS.png"/>
</p>
<p>
Now click the security tab 
</p>
<br />

<p>
<img src="https://i.imgur.com/6Ym5ikw.png"/>
</p>
<p>
Next click the advanced button
</p>
<br />

<p>
<img src="https://i.imgur.com/X9Ptavd.png"/>
</p>
<p>
Now click disable inheritance 
</p>
<br />

<p>
<img src="https://i.imgur.com/kDmMHFN.png"/>
</p>
<p>
Next click remove all inherited permission from this object 
</p>
<br />

<p>
<img src="https://i.imgur.com/a5BR6Qt.png"/>
</p>
<p>
Next click add 
</p>
<br />

<p>
<img src="https://i.imgur.com/6tzVHdP.png"/>
</p>
<p>
Next click select a principal
</p>
<br />

<p>
<img src="https://i.imgur.com/Wip4Xsj.png"/>
</p>
<p>
Now type everyone 
</p>
<br />

<p>
<img src="https://i.imgur.com/RJ4EwW0.png"/>
</p>
<p>
Now click ok 
</p>
<br />

<p>
<img src="https://i.imgur.com/DR7D1sK.png"/>
</p>
<p>
Now click all the permissions then click ok 
</p>
<br />

<p>
<img src="https://i.imgur.com/zqdVFh0.png"/>
</p>
<p>
Now click apply 
</p>
<br />

<p>
<img src="https://i.imgur.com/iyr1NZU.png"/>
</p>
<p>
Next click ok 
</p>
<br />

<p>
<img src="https://i.imgur.com/mRfhtZy.png"/>
</p>
<p>
Now click ok 
</p>
<br />

<p>
<img src="https://i.imgur.com/hqRagGe.png"/>
</p>
<p>
Next go back to the OsTicket home page and click continue
</p>
<br />

<p>
<img src="https://i.imgur.com/OKnJXfb.png"/>
</p>
<p>
For the helpdesk name type josh help desk, the deafult email type josh@help.com. Now for admin user the first name type josh then the last name type garcia. For email address type josh@gmail.com. For the username josh then type the password I will type Password1. 
</p>

<p>
<img src="https://i.imgur.com/t9ceyCO.png"/>
</p>
<p>
Now go to back to the link and download HeidiSQL then click the download symbol
</p>
<br />

<p>
<img src="https://i.imgur.com/yTRonxp.png"/>
</p>
<p>
Now go to file explorer and double click HediSQL
</p>
<br />

<p>
<img src="https://i.imgur.com/5R3jRlp.png"/>
</p>
<p>
Next click I accept the agreement then click next 
</p>
<br />

<p>
<img src="https://i.imgur.com/idkFGSE.png"/>
</p>
<p>
Next click install
</p>
<br />

<p>
<img src="https://i.imgur.com/LHVIG47.png"/>
</p>
<p>
You will see the process start 
</p>
<br />

<p>
<img src="https://i.imgur.com/nHpurgy.png"/>
</p>
<p>
Next click finish 
</p>
<br />

<p>
<img src="https://i.imgur.com/ElwcyFp.png"/>
</p>
<p>
Next click skip 
</p>
<br />

<p>
<img src="https://i.imgur.com/hUWMEba.png"/>
</p>
<p>
Now type root
</p>
<br />

<p>
<img src="https://i.imgur.com/9qRVwk3.png"/>
</p>
<p>
Next for the password section type Password1 then click open
</p>
<br />

<p>
<img src="https://i.imgur.com/CicD6WG.png"/>
</p>
<p>
Now you will see the unamed tab 
</p>
<br />

<p>
<img src="https://i.imgur.com/QLYkU8U.png"/>
</p>
<p>
Next type root for the MySQL Username then for the MySQL Password type Password1
</p>
<br />

<p>
<img src="https://i.imgur.com/zFX3bw4.png"/>
</p>
<p>
Now right click Unamed then go to create new then click Database
</p>
<br />

<p>
<img src="https://i.imgur.com/uSTt3fz.png"/>
</p>
<p>
Next type osTicket then click ok 
</p>
<br />

<p>
<img src="https://i.imgur.com/rVitYii.png"/>
</p>
<p>
Next type osTicket for MySQL Database
</p>
<br />

<p>
<img src="https://i.imgur.com/jg9xKBs.png"/>
</p>
<p>
Now you will see the process load 
</p>
<br />

<p>
<img src="https://i.imgur.com/W6xSS8i.png"/>
</p>
<p>
Next you will see the process finish and osTicket was installed
</p>
<br />

<p>
<img src="https://i.imgur.com/dyVrcAk.png"/>
</p>
<p>
Next go to the osTicket folder and delete the setup folder
</p>
<br />

<p>
<img src="https://i.imgur.com/R724ddT.png"/>
</p>
<p>
Now click ost-config.php
</p>
<br />

<p>
<img src="https://i.imgur.com/cdsVGJZ.png"/>
</p>
<p>
Right click and go to properties 
</p>
<br />

<p>
<img src="https://i.imgur.com/ycNAXZI.png"/>
</p>
<p>
Next click advanced 
</p>
<br />

<p>
<img src="https://i.imgur.com/oW2DAlJ.png"/>
</p>
<p>
Now click permissions
</p>
<br />

<p>
<img src="https://i.imgur.com/oe2Cvif.png"/>
</p>
<p>
Next click allow everyone then click edit 
</p>
<br />

<p>
<img src="https://i.imgur.com/vtAXNnA.png"/>
</p>
<p>
Now uncheck full control, modify, and write then click ok  
</p>
<br />

<p>
<img src="https://i.imgur.com/z3rAzqF.png"/>
</p>
<p>
Now click apply
</p>
<br />

<p>
<img src="https://i.imgur.com/D239flD.png"/>
</p>
<p>
Finally click ok then click the link to continue the Post-Installation Configuration https://github.com/josuehernandez0/post-install-config
</p>
<br />

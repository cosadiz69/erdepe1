[![Mybot](https://telegra.ph/file/6d340ffda39990e5bae3c.png)](https://t.me/joinchat/uXnRjVgw9iw5ZWZl)
# Virtual Machine 🍁
> **[ Windows, MacOS, Linux ]  [ CPU 3core - 7GB Ram - 256 SSD ]**     
> ## Windows 10: [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/TranCongVinh1/VPS/blob/main/.github/workflows/Windows10.yml) | MacOS: [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/TranCongVinh1/VPS/blob/main/.github/workflows/MacOS.yml) | Linux Desktop: [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/TranCongVinh1/VPS/blob/main/.github/workflows/Linux-Desktop.yml) | Linux SSH: [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/TranCongVinh1/VPS/blob/main/.github/workflows/Linux-ssh.yml) 
<br>

 ### Windows and Linux:
 **If u luck= CPU:    Intel(R) Xeon(R) Plantium 8272CL CPU @ 2.60Hz 64-bit AES**     
 **If u not luck= CPU: Intel(R) Xeon(R) CPU E5-2673 v4 @ 2.30Hz 64-bit AES**
 
- 2-core vCPU
- 7 GB RAM
- 14 GB SSD Disk **(Excluded System used)**
### MacOS 10.15
- 3-core vCPU
- 14 GB RAM
- 14 GB SSD Disk **(Excluded System used)**

## Setting up:
* Click Fork in the right corner of the screen to save it to your Github.
* Visit https://dashboard.ngrok.com to get **NGROK_AUTH_TOKEN**
* In Github go to ⚙ Settings> Secrets> New repository secret
* In Name: enter **NGROK_AUTH_TOKEN**
* In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into
* Press Add secret

Secrets Name | Uses | Notes
----- | ----- | -----
**MAC_REALNAME** | For MacOS User Display Name | Type any name you want
**MAC_USER_PASSWORD** | For MacOS System Admin Password | Type any password you want
**VNC_PASSWORD** | For the login password of VNC remote authentication | Type any password you want
**LINUX_USERNAME** | For linux system username | Type any name you want
**LINUX_USER_PASSWORD** | For linux shell and root password | Type any password you want
**LINUX_MACHINE_NAME** | For Linux System Computer name | Type any name you want
**CHROME_HEADLESS_CODE** | For remoting linux desktop using google remote | Copy Codes from [here](https://remotedesktop.google.com/headless) and login with your google account, and then copy the code below **Debian Linux** blank. :warning: Each code can only be used for once, generate another code when u have used that one.

## Deloy and Run
<details>
    <summary>MacOS Install and Run</summary>
<br>
    
* Go to **Actions** Tab and select one of system workflow.

* Click **Run Workflow** button on the left of **This workflow has a workflow_dispatch event trigger** line.

* Wait until a few minutes.

* Copy the link(**without tcp://**) and go to VNC Viewer(Download and install it [here](https://www.realvnc.com/download/file/viewer.files/VNC-Viewer-6.21.406-Windows.exe)), input the link to connect that u copied from the website.

* Fill in those login info, within username **TCV** and password from **VNC_PASSWORD** in Secret that you typed.

* Enjoy!

</details>

<details>
    <summary>Windows 10</summary>
<br>

* First, start the actions of Windows 10 System.    
* Second, Go to https://dashboard.ngrok.com/status/tunnels and check if theres a one online tunnel running.
* Go to Windows Remote Desktop Connection app or Microsoft Remote Desktop software to connect to windows 10 VPS.
* ENJOY!

</details>

<details>
    <summary>Linux</summary>
<br>

* First, start the actions of Linux System.     
* Second, Copy the link from the console    
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/0F804C5F-FE8F-45FA-9720-F91F212597DF.png?raw=true" >         
* Go to MacOS Terminal or Windows CMD Terminal or else ssh client and enter command provided       
* Enter your ssh password then.     
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/78FE6C5A-7270-4986-AB8F-57EC4C9B4F44.png?raw=true" >       
* ENJOY!    

</details>

---

### Screenshots:
<details>
    <summary>Windows 10</summary>
<br>
    
- Windows 10 Version
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/268600af-c8b9-47cf-b5dd-d1c1ed6d9ce9.png?raw=true">

- Windows 10 Task Manager
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/0cf98258-a6fe-46bb-ac9a-ee4bb3037e3a.png?raw=true" >

- Windows 10 Device Manager
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/d32cf285-5ecf-4cce-a52a-5cb54fb130c7.png?raw=true">

- Windows 10 Device Specification
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/e1852b80-d550-44f3-b619-86ea82902bb4.png?raw=true">
    
</details>

<details>
    <summary>Ubuntu (SSH Version)</summary>
<br>

* Click **Run Workflow**
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/96644176-D760-47D4-BED2-C47E62A6763F.png?raw=true" >

* Copy ssh with url
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/0F804C5F-FE8F-45FA-9720-F91F212597DF.png?raw=true" >

* Open cmd or Terminal from your windows/MacOS or Linux, and type command provided by github actions boxes.
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/78FE6C5A-7270-4986-AB8F-57EC4C9B4F44.png?raw=true" >

type **yes** from the connect, and then type your ssh password by secrets of LINUX_USER_PASSWORD u have set.

* Type **sudo -i** for root permission and type your password.
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/E5527744-1ED1-4550-8867-EF4EC76D6895.png?raw=true" >

* Enjoy having your FREE linux SSH VPS and type any command you want.(but only 6 hours)
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/E6E9EA63-AC24-4FDB-AAF9-8B509658440A.png?raw=true" >

</details>

<details>
    <summary>Ubuntu (Desktop Remote Version)</summary>
<br>

- Desktop Screenshot
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/4EB9C2FF-9D03-4998-A440-D7716A0F7CD0.png?raw=true" >

- Linux Chrome
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/09F0A4CF-9B30-44CD-8DC4-139D03DFC2CC.png?raw=true" >

- Install any apps you want :)
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/A0886141-DF1E-4379-88E7-F00EDAD87D0E.png?raw=true">

</details>

<details>
    <summary>MacOS</summary>
<br>

- Desktop Screenshot
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/Screenshot%202021-02-23%20at%207.32.41%20AM.png?raw=true" >

- Settings
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/Screenshot%202021-02-23%20at%207.32.21%20AM.png?raw=true" >

- RAM
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/Screenshot%202021-02-23%20at%207.32.58%20AM.png?raw=true" >

- Storage
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/Screenshot%202021-02-23%20at%207.33.18%20AM.png?raw=true" >

- Pre-Installed Apps
<img src="https://github.com/TranCongVinh1/VPS/blob/main/pics/Screenshot%202021-02-23%20at%207.34.10%20AM.png?raw=true" >

</details>


<details>
    <summary>⚠ Warnings </summary>
<br>
    
```py
THIS IS ONLY FOR EDUCATIONAL PURPOSES

DON'T USE FOR MINING OR ILLEGAL USE

DON'T RECODE THIS SC!
```


:warning: Dont install big sur updates on your macos virtual machine, it will break your remote process!
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.35.57%20AM.png">
</details>

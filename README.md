# Ancora-Education-Ucertify-Lab46
# Creating a Network Policy for 802.1X

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=7]

## Objective of the Lab 
In this lab, you will learn to create a network policy for 802.1X. IEEE 802.1X is an IEEE Standard for port-based Network Access Control. It provides authenticated network access to wired Ethernet networks and wireless 802.11 networks. 
## Instructions 
### STEP 1 
From the bottom-left bar, click the WIN16 tab, and then click On/Connect to power on the machine. 
### STEP 2 
Click the Start menu and open Windows Administrative Tools. 
### STEP 3 
If DirectAccess is not installed and configured, then perform the following steps to install and configure it:show steps 
### STEP 4 
In the Windows Administrative Tools window, from the right pane, scroll down and open the Network Policy Server. 
### STEP 5 
In the Network Policy Server window, from the middle pane, under Standard Configuration, from the Select a configuration scenario list, select RADIUS server for 802.1X Wireless or Wired Connections. 
### STEP 6 
In the middle pane, click the Configure 802.1X link. 
### STEP 7 
In the Configure 802.1X window, perform the following steps: 

a.At the Select 802.1X Connections Type step, under Type of 802.1X connections, select Secure Wired (Ethernet) Connections radio and click Next.

b.At the Specify 802.1X Switches step, click Add. 

c.In the New RADIUS Client dialog box, type the following details: 

   1.Friendly name: NPS User 
   
   2.Address (IP or DNS): 192.168.1.243 
   
d.Click OK and then click Next. 

e.At the Configure an Authentication Method step, from the Type (based on method of access and network configuration) list, select Microsoft: Protected EAP (PEAP) and click Next thrice. 

f.At the Completing New IEEE 802.1X Secured Wired and Wireless Connections and RADIUS clients step, click Finish.
### STEP 8 
Close all windows.
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.


## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.

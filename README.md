[![](https://dcbadge.vercel.app/api/server/hw3j3RwfJf) ](https://discord.gg/hw3j3RwfJf)
 [![Donate](https://img.shields.io/badge/donate-$-brown.svg?style=for-the-badge)](http://paypal.me/mtpsilva)
 [![Say Thanks](https://img.shields.io/badge/Say%20Thanks-!-yellow.svg?style=for-the-badge)](https://saythanks.io/to/mtpsilva)
![](https://img.shields.io/github/last-commit/aeonSolutions/AeonLabs-Smart-Indoor-Environement-GSM-4G-Cell-Tower-Identification?style=for-the-badge)
<a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/l5m5z1845s10s47cuyl5" alt="trackgit-views" />
</a>
![](https://views.whatilearened.today/views/github/aeonSolutions/AeonLabs-Smart-Indoor-Environement-GSM-4G-Cell-Tower-Identification.svg)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/aeonSolutions/AeonLabs-Smart-Indoor-Environement-GSM-4G-Cell-Tower-Identification.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/aeonSolutions/AeonLabs-Smart-Indoor-Environement-GSM-4G-Cell-Tower-Identification/fork)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)
[<img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" data-canonical-src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="30" />](https://www.buymeacoffee.com/migueltomas)

<p align="center">
   <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/general-guide-mental-health-students.jpg" height="300">
</p>

[PCB-Prototyping-Catalogue](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue)  >>   [Home-Automation](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Home-Automation)  >>  [Safety & Health](https://github.com/aeonSolutions/AeonLabs-Safety-Health)   >>   Smart Indoor Environement GSM 4G Cell Tower Identification

<br>

⚠️ **Start by reading the documentation first**. [Click here to open it](https://github.com/aeonSolutions/AeonLabs-Safety-Health/wiki) 

# Smart Indoor Environment GSM 4G Cell Tower Identification

**The Problem**
Nowadays is very convenient to have a wireless 4G internet connection everywhere, including at home, or at the office. Also, a widely known technique for stealing one's GSM communications data includes some kind of hidden GSM/4G device repeater able to perform Man-in-the-middle attacks. This attack technique allows one to collect and intercept data communications between a GSM/4G device, for instance, a smartphone or a tablet by impersonating a GSM Cell tower. 

**The Idea**

This Smart Indoor Env. GSM Cell Tower Monitor is built to do active monitoring of GSM Cell Towers nearby to look for any kind of hidden GSM/4G device repeater. Known to be used for stealing one's GSM communications data using some kind of Man-in-the-middle attack. This smart device is able to retrieve each GSM Cell tower Radio Signal strength, and the corresponding GPS coordinates (latitude, longitude), and do a Cell Tower Location match using a service called “OpenCellID”. OpenCellID.org is an open source database of CellID, serving two purposes:

- Everybody can create an application gathering information about cell locations, and send this information to the OpenCellID server, improving the coverage
- The database can be used by other applications to get the location of a cell, according to its cell id.


<p align="center">
<img src="https://github.com/aeonSolutions/AeonLabs-Smart-Indoor-Environement-GSM-4G-Cell-Tower-Identification/blob/main/designs/GSM%20locator%20network.jpg" height="350"> <br>
 source: https://arduino-projects4u.com/gsm-locator/
 
</p>

Basically it means you can use this info to create a GSM locator. So where can you find the location of the antennas. There are two sites worth mentioning although the second one seems to be going under.
- ~~[http://www.opencellid.org/cell/map](http://www.opencellid.org/cell/map)~~
- [www.celldb.org](http://www.celldb.org)

This smart device is able to do GSM/4G radio frequency (RF) measurements in a room and send data measurements to a local home server, alternatively to a public cloud server, for instance, to the authorities on a data repository ( see http://wwww.dataverse.org). Another important characteristic of this smart device is in the ability to deliver data to a server with a Unique Data Fingerprint Identification (UDF-ID), which makes collected data more trustworthy of its origins.
<br>

### Status

![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/working_red.png) Still being prototyped

<br>

### Known PCB bugs
This public revision of the PCB electronics is expected to have a few known small errors. 

<br>


<p align="center">
<img src="https://github.com/aeonSolutions/AeonLabs-Smart-Indoor-Environement-GSM-4G-Cell-Tower-Identification/blob/main/designs/pcb_front.png" height="350">
</p>

<br>
  ## Compatibility

<p align="center">
 <a href"https://www.apple.com/shop/accessories/all/homekit">
<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_apple_home.png" height="50">
 </a>
<a href="https://home.google.com"> 
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_google_home.png" height="50">
 </a>
<a href="https://www.home-assistant.io">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_home_assistanr.png" height="50">
 </a>
<a href="https://csa-iot.org/all-solutions/matter/">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_matter.png" height="50">
 </a>
<a href="https://csa-iot.org/all-solutions/matter/">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_zigbee.jpg" height="50">
 </a>
</p>

<br>

## What one additionally needs
- [USB to UART/USB TTL firmware burner for 5V and 3.3V MCUs ](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/DIY-Maker/README.md) 
<br />
<br />

**Get a Notification on every PCB update**

| [<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/mailing-list_orig.png" alt="" width="80">](https://www.tindie.com/stores/aeonlabs/) | You can fill in your [email here (Google form)](https://docs.google.com/forms/d/e/1FAIpQLScErMgQYRdA-umvCjvTPPrCO7Lg1QYowTxb7vfa8cTfrcPEAA/viewform?usp=pp_url) and I'll send a reminder when a new PCB prototype is made available here or a new revision for an existing PCB. Stay tuned! |
|-------------|------|

<br />

## Buy the PRO version on Tindie

| [<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/tindie_sell.png" alt="" height="60">](https://www.tindie.com/stores/aeonlabs/) | To all those not into electronics and still liked and want to own any of the listed PCB for smart devices can buy the PRO version on Tindie ready to install and use. |
|-------------|------|

### Useful links 
Below is a list of links with useful information about these kinds of abusive and many times criminal and terrorist usages.
[continue reading ...](https://github.com/aeonSolutions/AeonLabs-Safety-Health/wiki/Useful-Links)

<br />
<br />

**Get a Notification on every PCB update**

| [<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/mailing-list_orig.png" alt="" width="80">](https://www.tindie.com/stores/aeonlabs/) | You can fill in your [email here (Google form)](https://docs.google.com/forms/d/e/1FAIpQLScErMgQYRdA-umvCjvTPPrCO7Lg1QYowTxb7vfa8cTfrcPEAA/viewform?usp=pp_url) and I'll send a reminder when a new PCB prototype is made available here or a new revision for an existing PCB. Stay tuned! |
|-------------|------|

<br>

**Hire AeonLabs** <br>
If you like my work here and are looking to design and deploy your own smart device find [here](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/How-to-Hire-AeonLabs) how to hire me. 

<br>

## Author

You can get in touch with me on my LinkedIn Profile:

#### Miguel Tomas

[![LinkedIn Link](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect)](https://www.linkedin.com/in/migueltomas/)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/aeonSolutions)

<br>

### Be supportive of my dedication and work towards technology education and buy me a cup of coffee
The PCB Design Files I provide here for anyone to use are free. If you like this Smart Device or use it, please consider buying me a cup of coffee, a slice of pizza, or a book to help me study, eat, and think new PCB design files.

[<img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" data-canonical-src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" />](https://www.buymeacoffee.com/migueltomas)

<br />

### Make a donation on Paypal
Make a donation on PayPal and get a TAX refund*.

[![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/paypal_small.png)](http://paypal.me/mtpsilva)


### License

Before proceeding to download any of AeonLabs open source code for software solutions and/or open hardware electronics for smart devices and data acquisition make sure you are choosing the right license for your project. See [AeonLabs Solutions for Open Hardware & Open Source Code](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/AeonLabs-Solutions-for-Open-Hardware-&-Source-Development) for more information. For commercial business solutions contact AeonLabs for more information ℹ️ using the contacts above. Thank you 🙏.



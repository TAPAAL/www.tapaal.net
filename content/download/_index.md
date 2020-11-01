---
title: "Download"
date: 2019-05-28T14:45:55+02:00
draft: false
menu: "main"
weight: 4
---


# Prior to Download

TAPAAL provides a standalone editor, simulator and verifier (called verifytapn) of timed-arc Petri nets. Optionally, for running an automated translation to timed automata, the user should install the ***latest development version of UPPAAL***. 
Download UPPAAL from [www.uppaal.org](http://www.uppaal.org) in the [download section](http://www.it.uu.se/research/group/darts/uppaal/download.shtml), and follow the instalation instructions from [www.uppaal.org](http://www.uppaal.org). You will need to locate the file ***verifyta*** that comes with the UPPAAL distribution and point TAPAAL to its location in the engine selection dialog from the Tools menu.
		
# Download

***Before running TAPAAL make sure that [JRE 11.0](http://java.sun.com/javase/downloads/) or higher is installed on your system. Additionally, for Mac users we support only Mac OS X 10.9 and higher; on Mac OS X remember to allow applications downloaded from anywhere (in System Preferences and Security & Privacy tab or right-click on the application and choose "open").***

Binarier for Windows/Linux/Mac OS X:

  * [TAPAAL 3.7.1 for Windows Download (64 bit)](http://download.tapaal.net/fileadmin/download/tapaal-3.7/tapaal-3.7.1-win64.zip)
  * [TAPAAL 3.7.1 for Linux Download (64 bit)](http://download.tapaal.net/fileadmin/download/tapaal-3.7/tapaal-3.7.1-linux64.zip)
  * [TAPAAL 3.7.1 for Mac Download (64 bit)](http://download.tapaal.net/fileadmin/download/tapaal-3.7/tapaal-3.7.1-mac64.dmg)
  
[**Older Releases**](older-releases/)

-----------------------

Source download:

  * [Download TAPAAL GUI from Launchpad Source](https://code.launchpad.net/tapaal/)
  * [Download Continuous-Time TAPAAL Engine from Launchpad Source](https://code.launchpad.net/verifytapn)
  * [Download Discrete-Time TAPAAL Engine from Lauchpad Source](https://code.launchpad.net/verifydtapn)
  * [Download Untimed P/T TAPAAL Engine from Launchpad Source](https://code.launchpad.net/verifypn)

Please report any bugs that you might discover to our [bug tracker](https://bugs.launchpad.net/tapaal).

# Changelog

See the [tapaal changelog](changelog).

# Installation Guide
To install TAPAAL unpack the files for your platform and follow instructions in README.txt.

# License 
TAPAAL is licensed under tree licenses: 

  * The GUI tool is licensed under the [Open Source Licence 3.0](http://www.opensource.org/licenses/osl-3.0.php)
  * The reduction lib, used for automatic translation of TAPN models into UPPAAL Timed Automata and the discrete verification engine verifydtapn are licensed under the [BSD License](http://www.opensource.org/licenses/bsd-license.php). 
  * The continuous-time verification engine verifytapn is licensed under GPL v2 license: http://www.gnu.org/licenses/gpl-2.0.txt
  		
# Other Downloads

* beta release of TACPN GUI and unfolding engine ([Win64](http://download.tapaal.net/fileadmin/download/tapaal-3.5/tapaal-dev-beta1-win64.zip "Initiates file download"), [Linux64](http://download.tapaal.net/fileadmin/download/tapaal-3.5/tapaal-dev-beta1-linux64.zip "Initiates file download")) and update synthesis experiments ([zip](http://download.tapaal.net/fileadmin/download/tapaal-3.5/experiments.zip "Initiates file download"))
*   [partial-order-experiments.zip](http://download.tapaal.net/fileadmin/download/resources/partial-order-experiments.zip "Initiates file download") - models with timed partial order reduction (blood transfusion, BAwPC, alternating bit protocol, fire alarm, Fischer, Lynch Shavit, MPEG-2, patient monitoring).
*   Approximation of Time Intervals - Beta Release 3.0.99 ([Win](http://download.tapaal.net/fileadmin/download/tapaal-3.0/tapaal-3.0.99-win.zip "Initiates file download"), [Linux](http://download.tapaal.net/fileadmin/download/tapaal-3.0/tapaal-3.0.99-linux.zip "Initiates file download"), [Linux64](http://download.tapaal.net/fileadmin/download/tapaal-3.0/tapaal-3.0.99-linux64.zip "Initiates file download"), [Mac](http://download.tapaal.net/fileadmin/download/tapaal-3.0/tapaal-3.0.99-mac.dmg "Initiates file download"), [Mac64](http://download.tapaal.net/fileadmin/download/tapaal-3.0/tapaal-3.0.99-mac64.dmg "Initiates file download"), [case studies](http://download.tapaal.net/fileadmin/download/tapaal-3.0/models.zip "Initiates file download"))
*   Timed workflow nets - Beta Release 2.4.99 ([Win](http://download.tapaal.net/fileadmin/download/tapaal-2.4/tapaal-2.4.99-win.zip "Initiates file download"), [Linux](http://download.tapaal.net/fileadmin/download/tapaal-2.4/tapaal-2.4.99-linux.zip "Initiates file download"), [Linux64](http://download.tapaal.net/fileadmin/download/tapaal-2.4/tapaal-2.4.99-linux64.zip "Initiates file download"), [Mac](http://download.tapaal.net/fileadmin/download/tapaal-2.4/tapaal-2.4.99-mac.dmg "Initiates file download"), [Mac64](http://download.tapaal.net/fileadmin/download/tapaal-2.4/tapaal-2.4.99-mac64.dmg "Initiates file download"), [workflow case studies](http://download.tapaal.net/fileadmin/download/tapaal-2.4/workflows.zip "Initiates file download"))
*   [NFM'14 case studies](http://download.tapaal.net/fileadmin/download/resources/nfm14-experiments.zip "Initiates file download")
*   [FHIES'12 Blood Transfusion Case Study](http://download.tapaal.net/fileadmin/download/resources/FHIES12-blood-transfusion.zip "Initiates file download") and [MEMICS'12 experiments](http://download.tapaal.net/fileadmin/download/resources/MEMICS-experiments.zip "Initiates file download")
*   [Patient Monitoring System (PMS) and BAwPC Protocol](http://download.tapaal.net/fileadmin/download/resources/PMS-BAwPC.zip "Initiates file download") (TAPAAL nets)
*   [Experiments in TAPAAL and UPPAAL](http://download.tapaal.net/fileadmin/download/resources/experiments-journal.zip) (Alternating bit protocol, engine workshop, Fischer's protocol, Lynch-Shavit protocol, medical workflow, MPEG2 encoder)
*   [Lynch-Shavit Protocol and MPEG-2 Encoding Algorithm](http://download.tapaal.net/fileadmin/download/resources/lynch-shavit-and-mpeg2-models.zip) (TAPAAL and UPPAAL models)
*   [UPPAAL version](http://download.tapaal.net/fileadmin/download/tapaal-1.1/abp.xml "Initiates file download") of Alternating Bit Protocold with [query](http://download.tapaal.net/fileadmin/download/tapaal-1.1/abp.q "Initiates file download") (not to be opened in TAPAAL)

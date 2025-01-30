---
title: "Download"
date: 2019-05-28T14:45:55+02:00
draft: false
menu: "main"
weight: 4
---


# Prior to Download

TAPAAL provides a standalone editor, simulator and verifier (called verifytapn) of timed-arc Petri nets. 

***UPPAAL Integration***. 
Optionally, for running an automated translation to timed automata, the user should install UPPAAL. You will need to procure a vesion of UPPAAL from [www.uppaal.org](https://www.uppaal.org). Get the latest version from [download section](https://uppaal.org/downloads/), and follow the instalation instructions. You will need to locate the file ***verifyta*** that comes with the UPPAAL distribution and point TAPAAL to its location in the engine selection dialog from the Tools menu.

# Download

***Before running TAPAAL make sure that Java 11 or higher is installed on your system. You can use [Adoptium](https://adoptium.net) to obtain Java for your system. Additionally, on Mac OS X remember to allow applications downloaded from anywhere (in System Preferences and Security & Privacy tab or right-click on the application and choose "open"). On windows, it is important that during the installation you select "JavaSoft (Oracle) registry keys", otherwise TAPAAL may not find your Java and fail with "This application requires a Java Runtime Environment 11.0-21.0" even if Java is already installed.***

Binarier for Windows/Linux/Mac OS X:

  * [TAPAAL 3.9.5 for Windows Download (64 bit)](https://download.tapaal.net/tapaal/tapaal-3.9/tapaal-3.9.5-win64.zip)
  * [TAPAAL 3.9.5 for Linux Download (64 bit)](https://download.tapaal.net/tapaal/tapaal-3.9/tapaal-3.9.5-linux64.zip)
  * [TAPAAL 3.9.5 for Mac Download (64 bit)](https://download.tapaal.net/tapaal/tapaal-3.9/tapaal-3.9.5-mac64.dmg)
  
[**Older Releases**](older-releases/)

-----------------------

Source download:

  * Download TAPAAL GUI from [Github](https://github.com/TAPAAL/tapaal-gui)
  * [Download Continuous-Time TAPAAL Engine from Github](https://github.com/tapaal/verifytapn)
  * [Download Discrete-Time TAPAAL Engine Source from Github](https://github.com/tapaal/verifydtapn)
  * [Download Untimed P/T TAPAAL Engine from Github](https://github.com/tapaal/verifypn)

Please report any bugs that you might discover to our general [bug tracker](https://github.com/TAPAAL/TAPAAL/issues) or on the bug tracker for the individual project.

# Changelog

See the [tapaal changelog](changelog).

# Installation Guide
To install TAPAAL unpack the files for your platform and follow instructions in README.txt.

# License 
TAPAAL is licensed under tree licenses: 

  * The GUI tool is licensed under the [Open Source Licence 3.0](https://www.opensource.org/licenses/osl-3.0.php)
  * The reduction lib, used for automatic translation of TAPN models into UPPAAL Timed Automata and the discrete verification engine verifydtapn are licensed under the [BSD License](https://www.opensource.org/licenses/bsd-license.php). 
  * The continuous-time verification engine verifytapn is licensed under GPL v2 license: https://www.gnu.org/licenses/gpl-2.0.txt
  		
# Other Downloads

 * beta release of TAPAAL SMC for [windows](https://download.tapaal.net/tapaal/tapaal-4.0-beta/tapaal-4.0.0-win64.zip), [linux](https://download.tapaal.net/tapaal/tapaal-4.0-beta/tapaal-4.0.0-linux64.zip), [intel mac](https://download.tapaal.net/tapaal/tapaal-4.0-beta/tapaal-4.0.0-mac-intel64.dmg), [arm mac](https://download.tapaal.net/tapaal/tapaal-4.0-beta/tapaal-4.0.0-mac-arm64.dmg) and [SMC case studies](https://download.tapaal.net/tapaal/tapaal-4.0-beta/SMC-models.zip).
* beta release of TACPN GUI and unfolding engine ([Win64](https://download.tapaal.net/tapaal/tapaal-3.5/tapaal-dev-beta1-win64.zip "Initiates file download"), [Linux64](https://download.tapaal.net/tapaal/tapaal-3.5/tapaal-dev-beta1-linux64.zip "Initiates file download")) and update synthesis experiments ([zip](https://download.tapaal.net/tapaal/tapaal-3.5/experiments.zip "Initiates file download"))
*   [partial-order-experiments.zip](https://download.tapaal.net/tapaal/resources/partial-order-experiments.zip "Initiates file download") - models with timed partial order reduction (blood transfusion, BAwPC, alternating bit protocol, fire alarm, Fischer, Lynch Shavit, MPEG-2, patient monitoring).
*   Approximation of Time Intervals - Beta Release 3.0.99 ([Win](https://download.tapaal.net/tapaal/tapaal-3.0/tapaal-3.0.99-win.zip "Initiates file download"), [Linux](https://download.tapaal.net/tapaal/tapaal-3.0/tapaal-3.0.99-linux.zip "Initiates file download"), [Linux64](https://download.tapaal.net/tapaal/tapaal-3.0/tapaal-3.0.99-linux64.zip "Initiates file download"), [Mac](https://download.tapaal.net/tapaal/tapaal-3.0/tapaal-3.0.99-mac.dmg "Initiates file download"), [Mac64](https://download.tapaal.net/tapaal/tapaal-3.0/tapaal-3.0.99-mac64.dmg "Initiates file download"), [case studies](https://download.tapaal.net/tapaal/tapaal-3.0/models.zip "Initiates file download"))
*   Timed workflow nets - Beta Release 2.4.99 ([Win](https://download.tapaal.net/tapaal/tapaal-2.4/tapaal-2.4.99-win.zip "Initiates file download"), [Linux](https://download.tapaal.net/tapaal/tapaal-2.4/tapaal-2.4.99-linux.zip "Initiates file download"), [Linux64](https://download.tapaal.net/tapaal/tapaal-2.4/tapaal-2.4.99-linux64.zip "Initiates file download"), [Mac](https://download.tapaal.net/tapaal/tapaal-2.4/tapaal-2.4.99-mac.dmg "Initiates file download"), [Mac64](https://download.tapaal.net/tapaal/tapaal-2.4/tapaal-2.4.99-mac64.dmg "Initiates file download"), [workflow case studies](https://download.tapaal.net/tapaal/tapaal-2.4/workflows.zip "Initiates file download"))
*   [NFM'14 case studies](https://download.tapaal.net/tapaal/resources/nfm14-experiments.zip "Initiates file download")
*   [FHIES'12 Blood Transfusion Case Study](https://download.tapaal.net/tapaal/resources/FHIES12-blood-transfusion.zip "Initiates file download") and [MEMICS'12 experiments](https://download.tapaal.net/tapaal/resources/MEMICS-experiments.zip "Initiates file download")
*   [Patient Monitoring System (PMS) and BAwPC Protocol](https://download.tapaal.net/tapaal/resources/PMS-BAwPC.zip "Initiates file download") (TAPAAL nets)
*   [Experiments in TAPAAL and UPPAAL](https://download.tapaal.net/tapaal/resources/experiments-journal.zip) (Alternating bit protocol, engine workshop, Fischer's protocol, Lynch-Shavit protocol, medical workflow, MPEG2 encoder)
*   [Lynch-Shavit Protocol and MPEG-2 Encoding Algorithm](https://download.tapaal.net/tapaal/resources/lynch-shavit-and-mpeg2-models.zip) (TAPAAL and UPPAAL models)
*   [UPPAAL version](https://download.tapaal.net/tapaal/tapaal-1.1/abp.xml "Initiates file download") of Alternating Bit Protocold with [query](https://download.tapaal.net/tapaal/tapaal-1.1/abp.q "Initiates file download") (not to be opened in TAPAAL)

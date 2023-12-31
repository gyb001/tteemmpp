Intel(R) Network Connections Software Version 28.2 Release Notes
=======================================================================
June 23, 2023

This release includes software and drivers for Intel(R) Ethernet adapters and 
integrated network connections.


Contents
========

- What's New in This Release
- Supported Operating Systems
- User Guides
- Intel Fiber Optic Connections
- Customer Support


What's New in This Release
==========================

Hardware Support
----------------
- Support for the Intel(R) Ethernet Connection (20) I219-LM
- Support for the Intel(R) Ethernet Connection (24) I219-LM
- Support for the Intel(R) Ethernet Connection (25) I219-LM
- Support for the Intel(R) Ethernet Connection (26) I219-LM
- Support for the Intel(R) Ethernet Connection (27) I219-LM
- Support for the Intel(R) Ethernet Connection (20) I219-V
- Support for the Intel(R) Ethernet Connection (24) I219-V
- Support for the Intel(R) Ethernet Connection (25) I219-V
- Support for the Intel(R) Ethernet Connection (26) I219-V
- Support for the Intel(R) Ethernet Connection (27) I219-V
- Support for the Intel(R) Ethernet Network Adapter I226-T1

Software Features
-----------------
- Support for Microsoft* Windows* 10 on Intel Intel(R) Ethernet 800 Series 
10Gbps devices
- Support for Microsoft Windows 10 on Intel Intel(R) Ethernet 800 Series 25Gbps 
devices
- Support for SUSE* Linux Enterprise Server (SLES) 15 SP5
- The following Microsoft* PowerShell* cmdlets now support Intel(R) Ethernet 
700 Series devices
  * Get-IntelEthernetLogConfig
  * Set-IntelEthernetLogConfig
  * Start-IntelEthernetLog
  * Stop-IntelEthernetLog
  * Reset-IntelEthernetLogConfig
  * Disable-IntelEthernetLogConfig
- The following Microsoft PowerShell cmdlets now support "Driver" as a valid 
value for the "Module" parameter. The new parameter "SubModule" was added to 
the following cmdlets:
  * Get-IntelEthernetLogConfig
  * Set-IntelEthernetLogConfig

Removed Features
----------------
End of support for RSS on Microsoft Windows operating systems for the following 
devices:
- Intel(R) Ethernet Connection I217-LM
- Intel(R) Ethernet Connection I218-LM
- Intel(R) Ethernet Connection (2) I218-LM
- Intel(R) Ethernet Connection (3) I218-LM
- Intel(R) Ethernet Connection I218-LM
- Intel(R) Ethernet Connection I218-V
- Intel(R) Ethernet Connection (2) I218-V
- Intel(R) Ethernet Connection (3) I218-V
- Intel(R) Ethernet Connection I218-V
- Intel(R) Ethernet Connection I217-V
- Intel(R) Ethernet Network Adapter I226-T1
- Intel(R) Ethernet Network Adapter I226-T1
- Intel(R) Ethernet Network Adapter I225-T1
- Intel(R) Ethernet Network Adapter I225-T1
- Intel(R) Ethernet Controller (2) I225-IT
- Intel(R) Killer(TM) E3100X 2.5 Gigabit Ethernet Controller
- Intel(R) Ethernet Controller (2) I225-LM
- Intel(R) Ethernet Controller (2) I225-LMvP
- Intel(R) Ethernet Controller (2) I225-V
- Intel(R) Ethernet Controller (3) I225-IT
- Intel(R) Killer(TM) E3100X 2.5 Gigabit Ethernet Controller
- Intel(R) Ethernet Controller (3) I225-LM
- Intel(R) Ethernet Controller (3) I225-LMvP
- Intel(R) Ethernet Controller (3) I225-V
- Intel(R) Ethernet Controller I226-IT
- Intel(R) Killer(TM) E3100X 2.5 Gigabit Ethernet Controller (3)
- Intel(R) Ethernet Controller I226-LM
- Intel(R) Ethernet Controller I226-LMvP
- Intel(R) Ethernet Controller I226-V
- Intel(R) Ethernet Controller I225-LM
- Intel(R) Ethernet Controller I225-V
- Intel(R) Ethernet Connection (2) I219-LM
- Intel(R) Ethernet Connection (2) I219-V
- Intel(R) Ethernet Connection (3) I219-LM
- Intel(R) Ethernet Connection (4) I219-LM
- Intel(R) Ethernet Connection (4) I219-V
- Intel(R) Ethernet Connection (5) I219-LM
- Intel(R) Ethernet Connection (5) I219-V
- Intel(R) Ethernet Connection I219-LM
- Intel(R) Ethernet Connection (10) I219-LM
- Intel(R) Ethernet Connection (11) I219-LM
- Intel(R) Ethernet Connection (12) I219-LM
- Intel(R) Ethernet Connection (13) I219-LM
- Intel(R) Ethernet Connection (14) I219-LM
- Intel(R) Ethernet Connection (15) I219-LM
- Intel(R) Ethernet Connection (16) I219-LM
- Intel(R) Ethernet Connection (17) I219-LM
- Intel(R) Ethernet Connection (18) I219-LM
- Intel(R) Ethernet Connection (19) I219-LM
- Intel(R) Ethernet Connection (20) I219-LM
- Intel(R) Ethernet Connection (22) I219-LM
- Intel(R) Ethernet Connection (23) I219-LM
- Intel(R) Ethernet Connection (24) I219-LM
- Intel(R) Ethernet Connection (25) I219-LM
- Intel(R) Ethernet Connection (26) I219-LM
- Intel(R) Ethernet Connection (27) I219-LM
- Intel(R) Ethernet Connection (6) I219-LM
- Intel(R) Ethernet Connection (7) I219-LM
- Intel(R) Ethernet Connection (8) I219-LM
- Intel(R) Ethernet Connection (9) I219-LM
- Intel(R) Ethernet Connection I219-V
- Intel(R) Ethernet Connection (10) I219-V
- Intel(R) Ethernet Connection (11) I219-V
- Intel(R) Ethernet Connection (12) I219-V
- Intel(R) Ethernet Connection (13) I219-V
- Intel(R) Ethernet Connection (14) I219-V
- Intel(R) Ethernet Connection (16) I219-V
- Intel(R) Ethernet Connection (17) I219-V
- Intel(R) Ethernet Connection (18) I219-V
- Intel(R) Ethernet Connection (19) I219-V
- Intel(R) Ethernet Connection (20) I219-V
- Intel(R) Ethernet Connection (22) I219-V
- Intel(R) Ethernet Connection (23) I219-V
- Intel(R) Ethernet Connection (24) I219-V
- Intel(R) Ethernet Connection (25) I219-V
- Intel(R) Ethernet Connection (26) I219-V
- Intel(R) Ethernet Connection (27) I219-V
- Intel(R) Ethernet Connection (6) I219-V
- Intel(R) Ethernet Connection (7) I219-V
- Intel(R) Ethernet Connection (8) I219-V
- Intel(R) Ethernet Connection (9) I219-V
- Intel(R) Ethernet Connection (3) I218-LM
- Intel(R) Ethernet Connection (3) I218-V


Supported Operating Systems
===========================
The drivers in this release have been tested with the following operating 
systems (OSs). Additional OSs may function with our drivers but are not tested. 

NOTE: Not all devices support all operating systems listed. Refer to the 
release notes for detailed OS support information for your device. 

Microsoft* Windows Server*, Azure Stack HCI, and Windows*
----------------------------------------------------------
Microsoft Windows Server 2022 
Microsoft Windows Server 2019, Version 1903
Microsoft Windows Server 2016
Microsoft Windows Server 2012 R2
Microsoft Windows Server 2012
Microsoft Azure Stack HCI
Microsoft Windows 11 22H2 
Microsoft Windows 11 21H2 
Microsoft Windows 10 21H2 
Microsoft Windows 10, Version 1809

VMware* ESXi*
-------------
VMWare ESXi 8.0 
VMware ESXi 7.0 
Please refer to VMWare's download site for the latest ESXi drivers for Intel® 
Ethernet® devices.

Linux*
------
Linux Real Time Kernel 5.x and 4.x (only on Intel Ethernet E810 Series) 
Linux, v2.4 kernel or higher
Red Hat* Enterprise Linux* (RHEL) 9.2
Red Hat Enterprise Linux 8.8 
SUSE* Linux Enterprise Server (SLES) 15 SP5
SUSE Linux Enterprise Server 12 SP5
Canonical* Ubuntu* 22.04 LTS 
Canonical Ubuntu 20.04 LTS
Debian* 11

FreeBSD*
--------
FreeBSD 13.1 
FreeBSD 12.4 


User Guides
===========

Several user guides for Intel Network Connections are available for this 
product. You may access them in the following ways:
- Double-click "index.htm" located in the root of the Intel download.
- On Windows-based systems, start the autorun program on the download,
  then click "View User Guides."
- Go to http://support.intel.com.


Intel Fiber Optic Connections
=============================

Caution: The fiber optic ports may utilize Class 1 or Class 1M laser devices. 
Do not stare into the end of a fiber optic connector connected to a "live" 
system. Do not use optical instruments to view the laser output. Using optical 
instruments increases eye hazard. Laser radiation is hazardous and may cause 
eye injury. To inspect a connector, receptacle or adapter end, be sure that the 
fiber optic device or system is turned off, or the fiber cable is disconnected 
from the "live" system.

The Intel Gigabit and 10GbE network adapters with fiber optic connections 
operate only at their native speed and only at full-duplex. Therefore you do 
not need to make any adjustments. Use of controls or adjustments or performance 
of procedures other than those specified herein may result in hazardous 
radiation exposure. The laser module contains no serviceable parts.


Customer Support
================

- Main Intel support website: http://support.intel.com
- Network products information:
http://support.intel.com/support/go/network/adapter/home.htm


Legal / Disclaimers
===================

Copyright (C)2002 - 2023, Intel Corporation. All rights reserved.
Parts of Intel(R) PROSet for Windows Device Manager are based on the pugixml 
library (http://pugixml.org). pugixml is Copyright (C) 2006-2015 Arseny 
Kapoulkine.

This software and the related documents are Intel copyrighted materials, and 
your use of them is governed by the express license under which they were 
provided to you ("License"). Unless the License provides otherwise, you may not 
use, modify, copy, publish, distribute, disclose or transmit this software or 
the related documents without Intel's prior written permission.

This software and the related documents are provided as is, with no express or 
implied warranties, other than those that are expressly stated in the License.

Intel technologies may require enabled hardware, software or service activation.

No product or component can be absolutely secure.

 Intel, the Intel logo, and other Intel marks are trademarks of Intel 
Corporation or its subsidiaries. 
*Other names and brands may be claimed as the property of others.



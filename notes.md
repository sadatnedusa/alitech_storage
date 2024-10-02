# Reference
---
SCSI Enclosure Service (SES) - **https://www.snia.org/sites/default/orig/sdc_archives/2008_presentations/monday/RajendraDivecha_SCSI_SES.pdf**


---
# **Dell MD1400**

https://www.broadcom.com/support/knowledgebase/1211161502750/getting-ses-information-from-an-expander-via-megaraid

The sg_ses utility https://sg.danny.cz/sg/sg_ses.html
https://sg.danny.cz/sg/sg_ses.html

https://matrix207.github.io/2013/06/20/use-sg_ses/


**use sg_ses**
##1.Introduction

The sg_ses utility enables a user “to manage and sense the state of the power
supplies, cooling devices, displays, indicators, individual drives, and other
non-SCSI elements installed in an enclosure”.
The SCSI Enclosure Services standards (most recent is SES-2 ANSI INCITS 448-2008
) and the latest draft (ses3r03.pdf at www.t10.org) describe the format that the
sg_ses utility expects to find in a SES device (“logical unit” or “process”)

##2.Command Tools

sg_map - displays mapping between linux sg and other SCSI devices

sg_ses - send controls and fetch status from a SCSI EnclosureServices (SES) device

sg = SCSI Generic
ses = SCSI Enclosure Service

##3.Use command
query mapping of expander and device name

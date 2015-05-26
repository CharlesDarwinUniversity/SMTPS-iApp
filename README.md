# SMTPS-iApp
iApp for setting up SMTPS and/or straight SMTP. This is just an extended version of the SMTP iApp with added SSL support and improved monitoring. Contains contributions by members of the Devcentral community.

## Noteworthy Features
* Support for several combinations of SMTP, STARTTLS as well as a dedicated SSL virtual server (port 465)
* Scripted monitor sends a mail to confirm the service is functional

The scripted monitor overcomes "4.3.1 Insufficient system resources" error which Exchange sometimes sends when it's in need of additional resources.

Tested on BIG-IP LTM 11.3 - 11.6

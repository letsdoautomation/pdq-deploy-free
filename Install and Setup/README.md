# PDQ DEPLOY FREE: Install and setup
### Documentation and download
Download link:
* [PDQ Deploy](https://sales.pdq.com/products)

Documentation link:

* [Getting Started](https://documentation.pdq.com/PDQDeploy/16.1.0.0/Getting%20Started.pdf)
* [Firewall Ports and External Exceptions](https://help.pdq.com/hc/en-us/articles/220533627-Firewall-Ports-and-External-Exceptions)

<b>Objectives:</b>

* Create pdq_deploy domain user
* Setup Group Policy
    * Computer Configuration > Preferences > Local Users and Groups
        *   Add pdq_deploy to local administrators group
    * Computer Configuration  > Policies > Administrative Templates > Network > Network Connections > Windows Defender Firewall > Domain Profile
        * Windows Defender Firewall: Allow inbound file and printer sharing exception
        * Windows Defender Firewall: Allow ICMP exceptions
            * Allow inbound echo request

### My enviroment setup
My windows server setup: <br />
[Windows Server 2022: Install File Server role and prepare a share for software deployment with GPO](https://youtu.be/jEWSdC2qwyA) <br />
[Windows Server 2022: Install DHCP server](https://youtu.be/8n0MD9stQis) <br />
[Windows Server 2022: Install Active Directory Domain Services (AD DS)](https://youtu.be/1cYewbW3Tl0) <br />
# PDQ DEPLOY: Install and setup
### Documentation and download
Download link:
* [PDQ Deploy](https://sales.pdq.com/products)

<b>Objectives:</b>

* Create pdq_deploy domain user
* Setup Group Policy
    * Computer Configuration > Preferences > Local Users and Groups
        *   Add pdq_deploy to local administrators group
    * Computer Configuration  > Policies > Administrative Templates > Network > Network Connections > Windows Defender Firewall > Domain Profile
        * Windows Defender Firewall: Allow inbound file and printer sharing exception
        * Windows Defender Firewall: Allow ICMP exceptions
            * Allow inbound echo request
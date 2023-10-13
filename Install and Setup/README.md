# PDQ DEPLOY: Install and setup

* Create pdq_deploy user
    * Add pdq_deploy to local administrators group
* Setup Group Policy 
    * Computer Configuration > Administrative Templates > Network > Network Connections > Windows Defender Firewall > Domain Profile
        * Windows Defender Firewall: Allow inbound file and printer sharing exception
        * Windows Defender Firewall: Allow ICMP exceptions
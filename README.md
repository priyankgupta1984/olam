
# Automating Leapp Upgrades Using Oracle Linux Automation Manager

With the help of the following playbooks let's understand how the process of Leapp Upgrade from Oracle Linux 7 to Oracle Linux 8 as documented in https://docs.oracle.com/en/operating-systems/oracle-linux/8/leapp/leapp-AboutLeapp.html#about-leapp can be automated:

* leapp_prepare.yml: Enables leapp repositories, install the leapp related pacakges, performs a yum update and prepares the system for the leapp updgrade.
* leapp_preupgrade.yml: Run the leapp Preupgrade phase, displays the inhibitors and the answer file.
* Leapp_upgrade.yml: Performs the upgrade and reboots the machine.
* post_upgrade.yml: Checks the system and removes any residual Oracle Linux 7 packages.



  


Greetings !!!

Update your Host entries with the right IP address before running the playbook.

I believe the security groups are open between the servers. Firewall for required ports are open in the server
The Mysql Installation is by default. Im not copying any my.cnf
Mysql Variables like username and password are encrypted with ansible-vault. vault password is sent in email.
Localsettings.php is not enabled as the db for wikimedia is not getting created. But the setup page comes once the installation is complete.
Sticky sessions are enabled for HAProxy

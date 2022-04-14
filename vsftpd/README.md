# Debian 10
<h1>VSFTPD config for virtual users</h1>

The most important thing here is thar users are virtuals, they don't have a real account on the system.

This was done with this documentation https://nasauber.de/blog/2020/howto-virtual-users-for-vsftpd/, plus some config that I had in my environment
Also the script "userdbadm" is in https://nasauber.de/opensource/userdbadm/


vsftpd.conf located in /etc/vsftpd.conf, config file of vsftpd
vsftpd.virtual located in /etc/pam.d/vsftpd.virtual, for PAM authentication
userdbadm downloaded in /usr/local/bin/, and with chmod +x permissions

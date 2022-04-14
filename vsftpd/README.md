# Debian 10
<h1>VSFTPD config for virtual users</h1>

<p>The most important thing is that we are working here with virtual users, they don't have a real account on the system.</p>

<p>This was done with this documentation https://nasauber.de/blog/2020/howto-virtual-users-for-vsftpd/, plus some config that I have in my environment</p>
<p>Also the script "userdbadm" is in https://nasauber.de/opensource/userdbadm/</p>


<p>
<code>vsftpd.conf</code> located in <code>/etc/vsftpd.conf</code>, config file of vsftpd<br />
<code>vsftpd.virtual located in <code>/etc/pam.d/vsftpd.virtual</code>, for PAM authentication<br />
<code>userdbadm</code> downloaded in <code>/usr/local/bin/</code>, and with <code>chmod +x</code> permissions<br />
</p>

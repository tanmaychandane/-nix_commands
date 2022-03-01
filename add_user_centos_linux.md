<p>Add user in CentOS/ Red Hat linux. Requited: sudo privilege or login as root.</p><br>
<h6>Add a user named Silver</h6>
<code>sudo adduser silver</code>
<h6>Set password for user silver</h6>
<code>sudo passwd silver</code>
<br>
<h6>If you want newly created user to have administrative rights, Add user silver to sudoers group.</h6>
<code>sudo usermod -aG wheel silver</code>

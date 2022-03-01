<h1>A quick guide for managing users in Red Hat based distros.</h1>
<p>For performing these commands user needs to have sudo privilege or needs to be logged into system as root.</p>
<h6>Add a user named Silver</h6>
<code>sudo adduser silver</code>
<h6>Set password for user silver</h6>
<code>sudo passwd silver</code>
<br>
<h6>If you want newly created user to have administrative rights, Add user silver to sudoers group.</h6>
<code>sudo usermod -aG wheel silver</code>
<br><br>
<h6>Delete user named Silver</h6>
<code>sudo userdel silver</code>
<h6>Use <code>-r</code> flag for deleting users home directory alongside user</h6>
<code>sudo userdel -r silver</code>

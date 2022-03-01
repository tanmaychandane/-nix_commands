<h1>A quick guide to configure cockpit in CentOS 7</h1>
<p>Cockpit package is already included in centos repositories. Hence, can be directly installed.</p>
<h6>Install Cockpit application:</h6>
<code>sudo yum install cockpit -y</code>
<h6>Enable cockpit service:</h6>
<code>sudo systemctl enable --now cockpit.socket</code>
<h6>Firewall settings for cockpit:</h6>
<code>sudo firewall-cmd --permanent --zone=public --add-service=cockpit</code>
<h6>Reload Firewall:</h6>
<code>sudo firewall-cmd --reload</code>
<br><br>
<p>Once Cockpit is installed, we can access it by opening browser and typing url as IP address of server followed by :9090. E.g. If IP address of server is 192.168.11.50, Cockpit can be accessed by typing URL in browser as 192.168.11.50:9090.</p>

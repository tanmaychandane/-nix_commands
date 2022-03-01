<h1>Linux Filesystem in a nutshell</h1>
<p>No BS explanitaion for linux FS</p>
<br>

![image](https://user-images.githubusercontent.com/33379183/156220683-4950989f-84d4-43a8-9479-ce2ccb178c57.jpg)


<br>
<p>In Linux, everything is a file, and it follows a case sensitive approach. Which means: "Github" is different from "github" and "GITHUB"</p>
<p><code>/bin</code> This folder contains binaries ~ programs/ applications e.g. <code>ls</code>, <code>cat</code>, etc. are stored here.</p>
<p><code>/sbin</code> System binaries for system administrators.Standard users does not have access without permission. both folders contain files needed to run in a single user  mode</p>
<p><code>/boot</code> - contains everything OS needs to boot.  BOOTLOADER</p>
<p><code>/dev</code> - here devices live, almost every driver is  here. webcam, keyboard, hdd</p>
<p><code>/etc</code> - here are all configurations are stored(systemwide).</p>
<p><code>/lib</code>, <code>/bib32</code>, <code>lib64</code> - here liberiaries are stored. - All files applications can use to perform specific functions. - required by binaries in bin, sbin</p>
<p><code>/media</code>, <code>/mnt</code>- here are other mounted drives. e.g. USB, Flopy, external HDD, N/W drive, 2nddary HDD. (1st it was just MNT, now media is added in most distro), if mounting manually, use /mnt. leave/media for OS to manage</p>
<p><code>/opt</code> - optional folder. here manually instaled  software from vendor resides. some soft installed  from repo are also here. e.g. virtualbox  edition, brother driver.</p>
<p><code>/proc</code> - sudo files (contain info about system file & resources) - kernal translating other information  as files. e.g. cat/proc/cpuinfo</p>
<p><code>/root</code> - root users home holder. unlike other users it does not reside in home directory.</p>
<p><code>/run</code> - new - it is tempFS filesystem. i.e. it runs in   ram. everything is gone when system is shutdown</p>
<p><code>/snap</code> - here snap packages are stored. /srv - service directory/ service data directory, if any file/ print/ ftp folder is hosted, it stores files  here.</p>
<p><code>/sys</code> - system - way to interract with kernal. - run directorey - not physically writte to disk - created</p>

<h4>WIP</h4>

# mac-camo
# MOVED TO ![https://gitlab.com/keeganjk/](https://gitlab.com/keeganjk/mac-camo) !
[![Donate](https://img.shields.io/badge/donate-%24-green.svg)](https://keeganjk.github.io/donate/) <br />
![BASh](https://img.shields.io/badge/bash--5A5A5A.svg) ![Stable v1.0](https://img.shields.io/badge/stable-v1.0-orange.svg) <br />
![ANSI Art](https://github.com/keeganjk/mac-camo/blob/master/images/ansi-art.jpg "ANSI Art")
  
### Supported platforms<sup>0</sup>:
> <h5>Linux</h5>
> <h5>MacOS</h5>
> <sup>0</sup>Not all devices and routers will work with this script. Some devices won't let you change [part of] your MAC Address, some routers give Internet access by MAC, etc.
### Dependencies:
> <h5>superuser (<code>sudo</code>/<code>su</code>)</h5>
 
## What is it?
> <code>mac-camo</code> allows users to search for a MAC manufacturer and spoof their MAC Address as one of that manufacturer.
## Why?
> <code>mac-camo</code> is intended for anonymity<sup>1</sup> (or the exact opposite!<sup>2</sup>). <br />
> > <sup>1</sup>For example, I might be in a café where everyone is using Dell computers and I'm using a Mac. I could run the script, search for <code>Dell</code>, and spoof my MAC as a Dell computer so that anyone scanning the network would see my IP Address from Dell and not Apple. <br /> <br />
> > <sup>2</sup>However, if I wanted to be the opposite of anonymous, I could do something like this:
> > > I'm at a business where every device is Apple. I use this script and make it something really unexpected, like <code>GoPro</code> or even <code>Raspberry Pi Foundation</code> to startle, scare, or surprise scanners and security researchers. 

<hr>

> ## Download and Install
> ### 1. Download
> Firstly, on any OS, you would navigate to https://github.com/keeganjk/mac-camo. Once on this page, click the button that says "Clone or Download" and then "Download as ZIP".
> <br />
> ![Clone or Download](https://github.com/keeganjk/mac-camo/blob/master/images/clone-or-download.gif?raw=true "")
> <br />
> Alternatively, you can type <code>git clone https://github.com/keeganjk/mac-camo</code> into the terminal to 
> clone this repository and then <code>mv</code> into the directory. <br />
> If <code>git</code> isn't installed, you can always use cURL like so: 
> <code>curl -LO https://github.com/keeganjk/mac-camo/archive/master.zip</code>
> ### 2. Extract files
> Nextly, extract the ZIP file and then move into the <code>mac-camo</code> folder.
> ### 3. Run <code>mac-camo</code>
> Nextly, run <code>mac-camo</code>.
<pre>
chmod +x mac-camo
sudo ./mac-camo
</pre>
-- or --
<pre>
chmod +x mac-camo-simple
sudo ./mac-camo-simple
</pre>
<b>Notice: If you are using macOS, you will need to hold <i>⌘ + R</i> while booting. From there, click <i>Utilities > Terminal</i> from the top menu. Next, type the following:
<pre>
csrutil disable
reboot
</pre>
</b><br/>
> ### 4. Install
> After running <code>mac-camo</code>, type <code>1</code> and then press enter to install.
> After a few seconds, it should be installed.
 
<hr>
 
> ## How to use it
> ### 1. Run
> After installation, run <code>sudo mac-camo</code>.
> ### 2. Menu
> Once started, a menu will appear, from which you can install or spoof by typing the number by your desired option and pressing enter.
> ### 3a. Spoofing
> To spoof your MAC Adress, type <code>2</code> from the first menu.
> ### 3b. Finding a manufacturer
> After selecting <code>2</code>, type <code>0</code> to search for a manufacturer, type <code>1</code> to browse through a long list <b>(WARNING! THIS LIST IS ~16,870 LINES LONG!!)</b>, or type `2` and a random MAC will be generated. If you selected to search, then search for a manufacturer. Once you found the manufacturer you want to use, select "Use one of these" and then enter the number that is next to the manufacturer's name.
> ### 3c. Selecting an interface
> Next, an interface list will appear. Select one and your spoofed MAC will be generated and used.

[![asciicast](https://asciinema.org/a/c6cxac6qln0ibc6s0rohylnx3.png)](https://asciinema.org/a/c6cxac6qln0ibc6s0rohylnx3)

## Credits:
<b>[IEEE OUI List](http://standards-oui.ieee.org/oui.txt "IEEE OUI LIST")</b> Provides list of MAC manufacturers and addresses. <br/>

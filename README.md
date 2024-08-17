# Install-Software-in-Linux-Distribution
We will be installing and uninstalling an application in a Linux Bash Shell. First we will confirm that APT is installed on your Linux Bash shell. To confirm, the command is "apt"

<p>
<img src="https://i.imgur.com/WksENGl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/gRdCQOm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Second is we will install Suricata, a a network analysis tool used for intrusion detection.
It will then ask if you want to process Y/N. Type "Y"
it should now be installed.
</p>
<br />

<p>
<img src="https://i.imgur.com/pvs5SN6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
Third, we will now use APT package manager to uninstall Suricata
The command is Sudo apt remove suricata. You will then type "Y" to proceed
</p>
<br />

<p>
Fourth, we will now install TCPDump application. TCPDump is a command line that can be used to capture network traffic in a Linux Bash shell.
The command is "sudo apt install tcpdump"
</p>
<br />

<p>
<img src="https://i.imgur.com/c2C3pz2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/YPmpjH8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<img src="https://i.imgur.com/iN4bB2t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
Now lets reinstall Suricata. Type command "Sudo apt install Suricata".
Lastly, check if both tcpdump and suricata has been installed by typing "apt list --installed" and you should see this. You're all done!
</p>
<br />

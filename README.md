# WindowsDefenderFirewallICMPBlock
Blocking ICMP pings on Windows Defender Firewall &amp; any TCP/UDP port.

Control Panel > System & Security > Windows Defender & Firewall (Settings could be used by another software ex: Antivirus), but you can create a new rule either program or port TCP/UDP to allow or block in this case let's create a ICMP block.

![Screenshot](https://github.com/jasnnh/WindowsDefenderFirewallICMPBlock/blob/main/image8.png)

Protocol set is as ICMP, but if you want a specific TCP or UDP port you can set it as that then enter the port # to block.

![Screenshot](https://github.com/jasnnh/WindowsDefenderFirewallICMPBlock/blob/main/image16.png)

After configuring and saving the settings your host pc should now block any connection to this host pc on that port. You can also view the firewall logs if enabled and saving located at "C:\Windows\System32\LogFiles\Firewall\pfirewall.log"

![Screenshot](https://github.com/jasnnh/WindowsDefenderFirewallICMPBlock/blob/main/log.PNG)


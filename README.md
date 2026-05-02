# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
```
Microsoft Windows [Version 10.0.26200.8246]
(c) Microsoft Corporation. All rights reserved.

C:\Users\acer>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2409:40f4:19:550e:92b5:7384:5c6c:8f93
   Temporary IPv6 Address. . . . . . : 2409:40f4:19:550e:6d93:2582:bf53:1ac9
   Link-local IPv6 Address . . . . . : fe80::bc1:7991:3205:e67a%16
   IPv4 Address. . . . . . . . . . . : 10.47.117.248
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::c440:72ff:fe1f:9334%16
                                       10.47.117.39

C:\Users\acer>ipconfig /all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : TMP215-75-G2
   Primary Dns Suffix  . . . . . . . :
   Node Type . . . . . . . . . . . . : Mixed
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Realtek PCIe GbE Family Controller
   Physical Address. . . . . . . . . : 74-D4-DD-CF-7C-8C
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter
   Physical Address. . . . . . . . . : FC-6D-77-8A-7F-10
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Intel(R) Wi-Fi 6E AX211 160MHz
   Physical Address. . . . . . . . . : FC-6D-77-8A-7F-0F
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   IPv6 Address. . . . . . . . . . . : 2409:40f4:19:550e:92b5:7384:5c6c:8f93(Preferred)
   Temporary IPv6 Address. . . . . . : 2409:40f4:19:550e:6d93:2582:bf53:1ac9(Preferred)
   Link-local IPv6 Address . . . . . : fe80::bc1:7991:3205:e67a%16(Preferred)
   IPv4 Address. . . . . . . . . . . : 10.47.117.248(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 02 May 2026 13:26:16
   Lease Expires . . . . . . . . . . : 02 May 2026 14:26:14
   Default Gateway . . . . . . . . . : fe80::c440:72ff:fe1f:9334%16
                                       10.47.117.39
   DHCP Server . . . . . . . . . . . : 10.47.117.39
   DHCPv6 IAID . . . . . . . . . . . : 301755767
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-30-49-A7-63-74-D4-DD-CF-7C-8C
   DNS Servers . . . . . . . . . . . : 10.47.117.39
                                       2409:40f4:19:550e::c8
   NetBIOS over Tcpip. . . . . . . . : Enabled

C:\Users\acer>ipconfig /release

Windows IP Configuration

No operation can be performed on Ethernet while it has its media disconnected.
No operation can be performed on Local Area Connection* 1 while it has its media disconnected.

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2409:40f4:19:550e:92b5:7384:5c6c:8f93
   Temporary IPv6 Address. . . . . . : 2409:40f4:19:550e:6d93:2582:bf53:1ac9
   Link-local IPv6 Address . . . . . : fe80::bc1:7991:3205:e67a%16
   Default Gateway . . . . . . . . . : fe80::c440:72ff:fe1f:9334%16

C:\Users\acer>ipconfig /renew

Windows IP Configuration

No operation can be performed on Ethernet while it has its media disconnected.
No operation can be performed on Local Area Connection* 1 while it has its media disconnected.

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2409:40f4:19:550e:92b5:7384:5c6c:8f93
   Temporary IPv6 Address. . . . . . : 2409:40f4:19:550e:6d93:2582:bf53:1ac9
   Link-local IPv6 Address . . . . . : fe80::bc1:7991:3205:e67a%16
   IPv4 Address. . . . . . . . . . . : 10.47.117.248
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::c440:72ff:fe1f:9334%16
                                       10.47.117.39

C:\Users\acer>ping google.com

Pinging google.com [2404:6800:4007:80e::200e] with 32 bytes of data:
Reply from 2404:6800:4007:80e::200e: time=59ms
Reply from 2404:6800:4007:80e::200e: time=65ms
Reply from 2404:6800:4007:80e::200e: time=54ms
Reply from 2404:6800:4007:80e::200e: time=60ms

Ping statistics for 2404:6800:4007:80e::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 54ms, Maximum = 65ms, Average = 59ms

C:\Users\acer>tracert google.com

Tracing route to google.com [2404:6800:4007:80e::200e]
over a maximum of 30 hops:

  1    12 ms     3 ms     3 ms  2409:40f4:19:550e::c8
  2     *        *        *     Request timed out.
  3    57 ms    30 ms    48 ms  2405:200:5218:21:3925::1
  4    56 ms    27 ms    38 ms  2405:200:88c:1513:62::4
  5     *        *        *     Request timed out.
  6    32 ms    26 ms    38 ms  2405:200:801:900::1624
  7     *        *        *     Request timed out.
  8    76 ms    32 ms    39 ms  2404:6800:8202:200::1
  9    57 ms    30 ms    39 ms  2404:6800:8202:200::1
 10    59 ms    38 ms    49 ms  2404:6800:8202:200::1
 11    47 ms    37 ms    37 ms  2001:4860:0:1::13de
 12    59 ms    37 ms    38 ms  2001:4860:0:1::1109
 13    55 ms    36 ms    37 ms  maa05s04-in-x0e.1e100.net [2404:6800:4007:80e::200e]

Trace complete.

C:\Users\acer>nslookup google.com
Server:  UnKnown
Address:  10.47.117.39

Non-authoritative answer:
Name:    google.com
Addresses:  2404:6800:4007:80e::200e
          142.250.206.78


C:\Users\acer>netstat -a

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    0.0.0.0:80             TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:135            TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:445            TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:1309           TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:4343           TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:4449           TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:5040           TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:5141           TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:46760          TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:49664          TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:49665          TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:49666          TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:49667          TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:49668          TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:49672          TMP215-75-G2:0         LISTENING
  TCP    0.0.0.0:58995          TMP215-75-G2:0         LISTENING
  TCP    10.47.117.248:139      TMP215-75-G2:0         LISTENING
  TCP    10.47.117.248:54545    10.47.117.39:domain    TIME_WAIT
  TCP    127.0.0.1:4709         TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:5141         TMP215-75-G2:49735     ESTABLISHED
  TCP    127.0.0.1:9993         TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:15152        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:19443        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:46753        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:46934        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:46935        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:46935        TMP215-75-G2:49724     ESTABLISHED
  TCP    127.0.0.1:46936        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:46936        TMP215-75-G2:49686     ESTABLISHED
  TCP    127.0.0.1:46937        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:46937        TMP215-75-G2:49688     ESTABLISHED
  TCP    127.0.0.1:49669        TMP215-75-G2:49670     ESTABLISHED
  TCP    127.0.0.1:49670        TMP215-75-G2:49669     ESTABLISHED
  TCP    127.0.0.1:49675        TMP215-75-G2:49676     ESTABLISHED
  TCP    127.0.0.1:49676        TMP215-75-G2:49675     ESTABLISHED
  TCP    127.0.0.1:49679        TMP215-75-G2:49680     ESTABLISHED
  TCP    127.0.0.1:49680        TMP215-75-G2:49679     ESTABLISHED
  TCP    127.0.0.1:49681        TMP215-75-G2:49682     ESTABLISHED
  TCP    127.0.0.1:49682        TMP215-75-G2:49681     ESTABLISHED
  TCP    127.0.0.1:49683        TMP215-75-G2:49684     ESTABLISHED
  TCP    127.0.0.1:49684        TMP215-75-G2:49683     ESTABLISHED
  TCP    127.0.0.1:49685        TMP215-75-G2:49687     ESTABLISHED
  TCP    127.0.0.1:49686        TMP215-75-G2:46936     ESTABLISHED
  TCP    127.0.0.1:49687        TMP215-75-G2:49685     ESTABLISHED
  TCP    127.0.0.1:49688        TMP215-75-G2:46937     ESTABLISHED
  TCP    127.0.0.1:49700        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:49705        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:49707        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:49718        TMP215-75-G2:49719     ESTABLISHED
  TCP    127.0.0.1:49719        TMP215-75-G2:49718     ESTABLISHED
  TCP    127.0.0.1:49720        TMP215-75-G2:49721     ESTABLISHED
  TCP    127.0.0.1:49721        TMP215-75-G2:49720     ESTABLISHED
  TCP    127.0.0.1:49722        TMP215-75-G2:49723     ESTABLISHED
  TCP    127.0.0.1:49723        TMP215-75-G2:49722     ESTABLISHED
  TCP    127.0.0.1:49724        TMP215-75-G2:46935     ESTABLISHED
  TCP    127.0.0.1:49735        TMP215-75-G2:5141      ESTABLISHED
  TCP    127.0.0.1:51779        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:51780        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:51781        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:51782        TMP215-75-G2:0         LISTENING
  TCP    127.0.0.1:58995        TMP215-75-G2:49700     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:49705     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:49707     ESTABLISHED
  TCP    [::]:80                TMP215-75-G2:0         LISTENING
  TCP    [::]:135               TMP215-75-G2:0         LISTENING
  TCP    [::]:445               TMP215-75-G2:0         LISTENING
  TCP    [::]:4343              TMP215-75-G2:0         LISTENING
  TCP    [::]:4449              TMP215-75-G2:0         LISTENING
  TCP    [::]:5141              TMP215-75-G2:0         LISTENING
  TCP    [::]:46760             TMP215-75-G2:0         LISTENING
  TCP    [::]:49664             TMP215-75-G2:0         LISTENING
  TCP    [::]:49665             TMP215-75-G2:0         LISTENING
  TCP    [::]:49666             TMP215-75-G2:0         LISTENING
  TCP    [::]:49667             TMP215-75-G2:0         LISTENING
  TCP    [::]:49668             TMP215-75-G2:0         LISTENING
  TCP    [::]:49672             TMP215-75-G2:0         LISTENING
  TCP    [::]:58995             TMP215-75-G2:0         LISTENING
  TCP    [::1]:15161            TMP215-75-G2:0         LISTENING
  TCP    [::1]:15161            TMP215-75-G2:49706     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:49708     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:53424     TIME_WAIT
  TCP    [::1]:24642            TMP215-75-G2:0         LISTENING
  TCP    [::1]:42050            TMP215-75-G2:0         LISTENING
  TCP    [::1]:49706            TMP215-75-G2:15161     ESTABLISHED
  TCP    [::1]:49708            TMP215-75-G2:15161     ESTABLISHED
  TCP    [::1]:53423            TMP215-75-G2:15161     TIME_WAIT
  TCP    [::1]:53424            TMP215-75-G2:15161     TIME_WAIT
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:49409  [2603:1040:a06:6::1]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:49411  [2603:1040:a06:6::1]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:49671  [2620:1ec:33:1::11]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:49673  lb-140-82-114-22-iad:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:50700  [2001:4860:4802:38::223]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:53420  [64:ff9b::284f:c522]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:53524  sc-in-f188:5228        ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:53525  [64:ff9b::68d0:105f]:https  TIME_WAIT
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:54546  [2603:1063:27:1::14]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:54547  [64:ff9b::68d0:105f]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:59428  [2603:1040:a06:6::2]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:61342  [64:ff9b::284f:c522]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:63237  whatsapp-cdn6-shv-02-maa5:https  TIME_WAIT
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:63854  lb-140-82-114-22-iad:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:64164  [2620:1ec:33::11]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:65249  [64:ff9b::acbc:9b19]:https  ESTABLISHED
  TCP    [2409:40f4:19:550e:6d93:2582:bf53:1ac9]:65297  whatsapp-cdn6-shv-02-maa5:https  ESTABLISHED
  UDP    0.0.0.0:5050           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5355           *:*
  UDP    0.0.0.0:50656          *:*
  UDP    0.0.0.0:52654          *:*
  UDP    0.0.0.0:54089          *:*
  UDP    0.0.0.0:65507          *:*
  UDP    10.47.117.248:137      *:*
  UDP    10.47.117.248:138      *:*
  UDP    10.47.117.248:1900     *:*
  UDP    10.47.117.248:61642    *:*
  UDP    127.0.0.1:1900         *:*
  UDP    127.0.0.1:49664        127.0.0.1:49664
  UDP    127.0.0.1:50655        *:*
  UDP    127.0.0.1:61643        *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5355              *:*
  UDP    [::]:52654             *:*
  UDP    [::]:54089             [2001:4860:4826:7700::]:443
  UDP    [::]:65507             *:*
  UDP    [::1]:1900             *:*
  UDP    [::1]:61641            *:*
  UDP    [fe80::bc1:7991:3205:e67a%16]:1900  *:*
  UDP    [fe80::bc1:7991:3205:e67a%16]:61640  *:*

C:\Users\acer>netstat -r
===========================================================================
Interface List
  9...74 d4 dd cf 7c 8c ......Realtek PCIe GbE Family Controller
 12...fc 6d 77 8a 7f 10 ......Microsoft Wi-Fi Direct Virtual Adapter
 16...fc 6d 77 8a 7f 0f ......Intel(R) Wi-Fi 6E AX211 160MHz
  1...........................Software Loopback Interface 1
===========================================================================

IPv4 Route Table
===========================================================================
Active Routes:
Network Destination        Netmask          Gateway       Interface  Metric
          0.0.0.0          0.0.0.0     10.47.117.39    10.47.117.248     30
      10.47.117.0    255.255.255.0         On-link     10.47.117.248    286
    10.47.117.248  255.255.255.255         On-link     10.47.117.248    286
    10.47.117.255  255.255.255.255         On-link     10.47.117.248    286
        127.0.0.0        255.0.0.0         On-link         127.0.0.1    331
        127.0.0.1  255.255.255.255         On-link         127.0.0.1    331
  127.255.255.255  255.255.255.255         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link     10.47.117.248    286
  255.255.255.255  255.255.255.255         On-link         127.0.0.1    331
  255.255.255.255  255.255.255.255         On-link     10.47.117.248    286
===========================================================================
Persistent Routes:
  None

IPv6 Route Table
===========================================================================
Active Routes:
 If Metric Network Destination      Gateway
 16     46 ::/0                     fe80::c440:72ff:fe1f:9334
  1    331 ::1/128                  On-link
 16     46 2409:40f4:19:550e::/64   On-link
 16    286 2409:40f4:19:550e:6d93:2582:bf53:1ac9/128
                                    On-link
 16    286 2409:40f4:19:550e:92b5:7384:5c6c:8f93/128
                                    On-link
 16    286 fe80::/64                On-link
 16    286 fe80::bc1:7991:3205:e67a/128
                                    On-link
  1    331 ff00::/8                 On-link
 16    286 ff00::/8                 On-link
===========================================================================
Persistent Routes:
  None

C:\Users\acer>arp -a

Interface: 10.47.117.248 --- 0x10
  Internet Address      Physical Address      Type
  10.47.117.39          c6-40-72-1f-93-34     dynamic
  10.47.117.255         ff-ff-ff-ff-ff-ff     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static

C:\Users\acer>
```

## Result
Thus Execution of Network commands Performed 

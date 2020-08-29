# Ehtools Framework Documentation

# Attacking frameworks

```
Most new Wi-Fi hacking tools rely on many of the same underlying 
attacks, and scripts that automate using other more familiartools like 
Aireplay-ng are often referred to as frameworks. These frameworks try 
to organize tools in smart or useful ways to take them a step beyond 
the functionality or usability of the original program.

An excellent example of this are programs that integrate scanning tools like 
Airodump-ng, attacks like WPS Pixie-Dust, andcracking tools like Aircrack-ng to 
create an easy-to-follow attack chain for beginners. Doing this makes the process 
of using these tools easier to remember and can be seen as sort of a guided tour. 
While each of these attacks is possible without the hand-holding, the result 
can be faster or more convenient than trying to do so yourself.

An example of this we've covered is the Airgeddonframework, a wireless attack 
framework that does useful things like automatingthe target selection process and 
eliminating the time a user spends copying and pasting information between programs. 
This savesvaluable time for even experienced pentesters but has the disadvantage of 
preventing beginners from understanding what's happening "under the hood" of the attack. 
While this is true, most of these frameworks are fast, efficient, and dead simple to 
use, enabling even beginners to take on and disable an entire network.
```

***

# UX/UI impruvements for beginners

```
The Ehtools Framework starts by merely typing the letter ehtools into a terminal window, 
then it asks for the name of your network interfaces after the first run. It uses the names 
you supply to connect to the tools needed to execute any attacks you select. Aside from that 
initial input, the majority of the possible attacks can be performed merely by choosing the 
option number from the menu. This means you can grab a network handshake or download a 
new hacking tool like Pupy by just selecting from one of the menu options.
```

***

# Basic networking tools

> (ehtools)> if

```
Runs ifconfig and gives the names and 
information about all network devices.
```

> (ehtools)> 1

```
Enable wlan0. 
(d1 disables it)
```

> (ehtools)> 2

```
Enable wlan0mon. 
(d2 disables it)
```

> (ehtools)> 3    

```
Randomize or set the MAC 
address to a specific value.
```

> (ehtools)> 7     

```
View the public IP address your 
computer is leaving on sites you visit.
```

> (ehtools)> 19    

```
Look up the physical address of a given IP 
address to determine it's relative location.
```

> (ehtools)> scan   

```
Start an ARP scan on the network 
to discover nearby devices.
```

> (ehtools)> start  

```
Start monitor mode on the 
wireless network adapter.
```

> (ehtools)> stop

```
Stop wireless monitor mode 
on the network adapter.
```

***

# Installing new tools

```
Part of the fun of Ehtools Framework is how easy it is to add new tools to our arsenal. 
We can select option 9 to access the list of tools in Ehtools Framework. From the next 
menu, the tools are broken down into major categories, with options for managing the 
installation of scripts. The options presented are:
```

**1.** Wi-Fi tools (tools for attacking wireless networks).

```
Wi-Fi options this is tools for attacking 
wireless networks and network databases.
```

**2.** Remote access (tools for getting remote access to other devices and remotely managing them).

```
Remote access means tools for getting access 
to other devices and remotely managing them.
```

**3.** Information gathering (collecting intelligence on people or website).

```
Information gathering tools, tools for 
collecting intelligence on peaple or website.
```

**4.** Website tools (tools for exploiting or attacking sites).

```
Website tools, tools for exploiting or 
attacking sites and network databases.
```

**5.** Other (a miscellaneous collection of other hacking tools)

```
Other tools this is collection 
of miscellaneous hacking tools.
```

 * You can also manage your installed tools by accessing option 6.

***

# Ehtools Framework application 

```
Ehtools application is an Ehtools Framework shortcut 
that allows users to run Ehtools Framework just selecting 
ehtools in the applications and clicking on it! I mean ehtools 
application allows users to run ehtools via the application!
```

 * There are two ways how to setup ehtools application.

## Using the installer

```
The ehtools install.sh allows 
you to create ehtools application.
```

## Using the ehtapp

```
There is an ehtools utility named ehtapp 
(read more in Ehtools Utilities) that allows 
users to configure ehtools application.
```

> ehtapp -c

***

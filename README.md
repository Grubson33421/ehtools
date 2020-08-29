# Entynet Hacker Tools (Ehtools Framework)

<h3 align="center"><img src="https://user-images.githubusercontent.com/54115104/67109604-8ac6ea80-f1d9-11e9-89c5-ee89ee2fbaa1.png" alt="logo" height="250px"></h3>
                
<p align="center">
  <a href="http://entynetproject.simplesite.com/">
    <img src="https://img.shields.io/badge/entynetproject-Ivan%20Nikolsky-blue.svg">
  </a> 
  <a href="https://github.com/entynetproject/ehtools/releases">
    <img src="https://img.shields.io/github/release/entynetproject/ehtools.svg">
  </a>
  <a href="https://wikipedia.org/wiki/Shell_script">
    <img src="https://img.shields.io/badge/language-shell-green.svg">
 </a>
  <a href="https://github.com/entynetproject/ehtools/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues/entynetproject/ehtools.svg">
  </a>
  <a href="https://github.com/entynetproject/ehtools/wiki">
      <img src="https://img.shields.io/badge/wiki%20-ehtools-lightgrey.svg">
 </a>
  <a href="https://twitter.com/entynetproject">
    <img src="https://img.shields.io/badge/twitter-entynetproject-blue.svg">
 </a>
</p>

![ehtools-red](https://user-images.githubusercontent.com/54115104/86511955-54340d00-be06-11ea-816b-e241d4e27b42.png)

***

# About Ehtools Framework

```
Wi-Fi tools keep getting more and more accessible to beginners, and the Ehtools Framework 
is a framework of serious penetration tools that can be explored easily from within it. This 
powerful and simple tool can be used for everything from installing new add-ons to grabbing 
a WPA handshake in a matter of seconds. Plus, it's easy to install, set up, and utilize.
```

***

# Getting started

## Ehtools installation

> cd ehtools

> chmod +x install.sh

> ./install.sh 

## Ehtools uninstallation

**1.** Start Ehtools Framework.

**2.** Open Ehtools Framework settings.

**3.** Select `Uninstall Ehtools Framework`.

***

# System requirements 

* Ehtools Framework only supports two OS.

```
Ehtools Framework only supports two 
operating systems - Kali Linux and Parrot OS!
```

* Full root access and access to /root folder.

```
All ehtools files and folders will be copied to /root,
/bin and /etc system folders, to copy ehtools data to
your system Ehtools Framework needs full root access!
```

***

# Selecting framework version

```
After executing install.sh it will be ask you 
to select version of Ehtools Framework - PRO os LITE. 
Select LITE if you did not buy Ehtools Framework PRO. 
If you bought Ehtools Framework PRO, select PRO.
```

> ./install.sh
    
***
    
# Ehtools Framework PRO activation

```
This key you can buy on the ehtools site! This key is used to activate 
ehtools PRO enter it in the input field of the activation key in the file 
install.sh and then you can install ehtools and use it only for educational 
purposes! The key works only one week then it changes! You 
should to have time to enter it before it is updated!
```

> ./install.sh

```
Also, we do not recommend to change the source code of ehtools because 
it is very complex and you can mess up something and disrupt the framework!
```

***

# Ehtools Framework execution

```
To run Ehtools Framework you should 
execute the following command.
```

> ehtools

***

# Why Ehtools Framework

* More than 58 tools for pentesting installed by default.

```
More than 58 options installed by default 
you can find in ehtools, this is tools such 
as MetaSploit, Pupy and other tools!
```

* Password protection and config encryption.

```
In version 2.1.6 we added pasword protection, we added 
it for users who think that his/her friend or parents will 
turn into ehtools and will remove or destroy it. Only for this 
people we created Ehtools Framework password protection.
```

* UX/UI impruvements for beginners.

```
It uses the names you supply to connect to the tools needed to 
execute any attacks you select! Aside from that initial input, the majority 
of the possible attacks can be performed merely by choosing the option number 
from the menu. This means you can grab a network handshake or download a new 
hacking tool like Pupy by just selecting from one of the menu options!
```

![ehtools-yellow](https://user-images.githubusercontent.com/54115104/86511984-92c9c780-be06-11ea-9888-9179447529b8.png)

***

# Ehtools Framework utilities

## ehtmod | <img src="https://img.shields.io/badge/utility-ehtmod-blue.svg">

* ehtmod (ehtools modules) is an utility that adds permissions or the ability to control the Ehtools Framework modules.
 
> ehtmod -h

```
Usage: ehtmod [option] <arguments>

  -i, --install         Install ehtools modules.
  -t, --take    <name>  Take a new ehtools modules snapshot.
  -r, --restore <name>  Restore saved ehtools modules snapshot.
  -d, --delete  <name>  Delete saved ehtools modules snapshot.
  -u, --uninstall       Uninstall ehtools modules.
  -h, --help            Give this help list.
```
         
* To install ehtools modules you need to execute the following command.

```
The ehtools install.sh will ask you to "install" or "not 
install" ehtools modules and if you answered "not install" and 
want to install them, run the following command!
```

> ehtmod -i

### Ehtools Modules Snapshot (EMS) 

```
EMS is a saved ehtools modules data, you can 
take it using the ehtmod utility and restore it.
```

* To take ehtools modules snapshot you need to execute the following command. You need to enter the name of the ehtools modules snapshot you want to take (example: snapshot1).

> ehtmod -t snapshot1

### Ehtools Modules Restoration (EMR) 

```
EMR is an operation that removing modules and restoring it from 
the saved ehtools modules snapshot, you can restore it using the 
ehtmod utility but ESR will remove all your old ehtools modules data!
```

* To restore ehtools modules snapshot you need to execute the following command. You need to enter the name of the saved ehtools modules snapshot (example: snapshot1).

> ehtmod -r snapshot1
    
## ehtkey | <img src="https://img.shields.io/badge/utility-ehtkey-brown.svg">

* ehtkey (ehtools key) is an utility that allows you to change your ehtools config key (ehtools config/boot key) and rewrite /etc/ehtools/.config.

> ehtkey

```
Usage: ehtkey [option] <arguments>

  -c, --change <old_key> <new_key>  Change ehtools config key.
  -h, --help                        Give this help list.
```

* To change ehtools config key you need to execute the following command. You need to enter your old ehtools config key (example: 1001) and after this enter your new ehtools config key (example: 2002).

> ehtkey -c 1001 2002

## ehtapp | <img src="https://img.shields.io/badge/utility-ehtapp-red.svg">

* ehtapp (ehtools application) is an utility that allows you to configure ehtools application, for example creating ehtools desktop application.
 
> ehtapp -h
 
```
Usage: ehtapp [option] <arguments>

  -c, --create               Create ehtools application.
  -d, --desktop <operation>  Create/remove ehtools desktop application.
  -r, --remove               Remove ehtools application.
  -h, --help                 Give this help list.
```

* To create ehtools application you need to execute the following command.

```
The ehtools install.sh will ask you to "create" or 
"not create" ehtools application and if you answered "not 
create" and want to create it, run the following command!
```

> ehtapp -c

* To create ehtools desktop application you need to execute the following command.

> ehtapp -d create

## epasswd | <img src="https://img.shields.io/badge/utility-epasswd-green.svg">

* epasswd (ehtools password changer) is an utility that allows you to change your ehtools login and password or ehtools root password.

### Changing ehtools login and password

> epasswd

* To change ehtools login and password enter your old ehtools login (example: ehtools) and your old ehtools password (example: sloothe).

> (login)> ehtools

> (password)> sloothe

* After this enter your new ehtools login (example: admin) and your new ehtools password (example: 1234).

> ((new)login)> admin

> ((new)password)> 1234

* Congratulations, you have successfully changed ehtools login and password!

```
In no case do not forget this password, it will not 
be restored and you will need to reinstall ehtools!
```

### Changing ehtools root password

* To cange root password, login to epasswd as ehtools root.

> epasswd

> (login)> root

* After this enter your old ehtools root password (default: toor).
 
> (password)> toor

* After this enter your new ehtools root password (example: 1234).

> ((new)password)> 1234

* Congratulations, you have successfully changed ehtools root password!

```
In no case do not forget this password, it will not 
be restored and you will have to reinstall ehtools!
``` 
***
    
# Ehtools Framework protection

![ehtools-login](https://user-images.githubusercontent.com/54115104/86511975-7f1e6100-be06-11ea-8476-a01324898eb2.png)

* Do this using install.sh.

```
Create login and password using install.sh 
(example: login: ehtools, password: sloothe)
```

* Do this when you are going to exit from ehtools.

```
When you are going to exit framework,
exit with shortcuts - 0 or exit. 
```

* Do not do this when you are going to exit from ehtools.

``` 
Do not just close ehtools window and 
do not exit from the Ehtools Framework 
using Ctrl-C or other exit signals!
```

***

# Ehtools Framework disclaimer

```
Usage of the Ehtools Framework for attacking targets without prior mutual consent is illegal.
It is the end user's responsibility to obey all applicable local, state, federal, and international laws.
Developers assume no liability and are not responsible for any misuse or damage caused by this program.
```

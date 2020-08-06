## GNU/Linux Beginner Guide

## Table of Contents
- [Why GNU/Linux?](#why-gnulinux)
- [Distributions](#distributions)
  - [User-Friendly distros](#user-friendly-distros)
  - [Advanced distros](#advanced-distros)
 - [The terminal](#the-terminal)
  - [Basic commands](#basic-commands)
  
---

## Why GNU/Linux?
First of all, it must be said that GNU/Linux isn't a *"free alternative to Windows"* like many people tend to believe, but rather, a solution for a free (as in freedom) computing; because your machine is only yours and nobody but the user has the right to have control over it.  
Proprietary operating systems don't give this freedom to the user, in fact, any computer running Windows or macOS are Microsoft or Apple property, and being them the owner they can don whatever they want with your machine.</br>
The problem doesn't stop there, because we live in the [mass surveillance](https://en.wikipedia.org/wiki/Mass_surveillance) age all our activities are monitored and reported back to the corporations and probably government agencies too.</br>
This obviously isn't morally right and it is against the article 12 of *The Universal Declaration of Human Rights*:
> No one shall be subjected to arbitrary interference with his privacy, family, home or correspondence, nor to attacks upon his honour and reputation. Everyone has the right to the protection of the law against such interference or attacks.
  
GNU/Linux is the solution to all of this, to a free computing experience where the user is the only and real owner of the system, a system that *leaves you alone.*
Many people believe that Linux as a whole and is the future of technology, even nowdays Linux is everywhere from the very servers that are keeping up your favorite Social Media websites and the most popular search engine to your Android smartphone!<br/>

But what makes GNU/Linux **free**? It's simple: the license<br/>  
The OS and all its components are *free as in freedom* which means the source code is available to the public so everybody can study, modify and re-distribute the software by using the [GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License) or [GPL-compatible](http://gplv3.fsf.org/wiki/index.php/Compatible_licenses) license.</br>

## Distributions
So you decided to join the land of freedom but don't know where to start, but don't worry, this guide got you covered!<br/>
GNU/Linux gets distributed by many "versions" of the OS which are generally called *distro(s)* or *flavor(s)* and there are many of them, but if you're a beginner is recommended to stick with easy to use distros, otherwise there is also a list of more complex distros, it's all about choice!

### User-Friendly distros
- [Ubuntu](https://ubuntu.com/): simply the most used distribution, if you don't know what distro install Ubuntu got you covered.
- [Pop!OS](https://pop.system76.com/): Ubuntu-based distro with more up-to-date packages and a vanilla GNOME workflow.
- [Linux Mint](https://linuxmint.com): another Ubuntu-based distro with the focus on simplicity and UI familiarity.
- [Debian](https://debian.org): the mother of 90% of all distros, definetely recommended if you want a pure and stable distro.
- [Fedora](https://getfedora.org): mantained by the community, focused on innovation with the latest technologies for Linux.
- [Manjaro](https://manjaro.org/): based on Arch Linux, this distro has the most bleeding edge software even though it's not that stable.
- [Solus](https://getsol.us/home/): an indipendent distro focused on simplicity and OOTB experience with a pretty interface.

### Advanced distros
- [Arch Linux](https://archlinux.org): the loved DIY distribution with bleeding edge packages, also great for memes.
- [Gentoo](https://gentoo.org): source-based distro focused on speed and customization. Make sure to have a fast processor.
- [Void Linux](https://voidlinux.org): one of the most interesting distros out there, it has that BSD touch that doesn't hurt.
- [GNU Guix](https://guix.gnu.org/): FSF-approved GNU/Linux distro with one of the most powerful package managers out there.
- [NixOS](https://nixos.org): a distro centralized around the Nix Package Manager.
- [Artix Linux](https://artixlinux.org/): the loved DIY distribution once again but free from systemd.

## The terminal
While most of the basic stuff can be done throught a GUI, more advanced tasks must be done with a terminal. This thing has been said many times but the terminal isn't something to be afraid of, even on Windows and macOS sometimes we must rely on the terminal if something goes wrong, it's just the nature of computers.<br/>
But unlike on other operating systems isn't just something to use when something breaks, it's the heartbeat of the whole system and makes even basic tasks faster and more efficient.

### Basic commands
A command has the following structure and it is applied for all of them:<br/>
```command <option(s)> <argument(s)>```<br/><br/>

### Navigation
```ls``` - shows the current files in the working directory.<br/><br/>
**Example:**<br/>
```
{kojy@linux ~]# ls
Documenti  Immagini  Modelli  Musica  Pubblici  Scaricati  Scrivania  Video
```

You can even use ```ls -a``` to show hidden folders:</br>
```

.              .cache     Immagini  Musica         .ssh        .wget-hsts
..             .config    .java     .npm-packages  .steam
.bash_history  Documenti  .john     .pki           .steampath
.bash_logout   .dosbox    .local    Pubblici       .steampid
.bash_profile  .esd_auth  Modelli   Scaricati      .var
.bashrc        .gnupg     .mozilla  Scrivania      Video
```
Alternatively you can use ```ls -l``` to get details about folders:<br/>
```
[kojy@linux ~]# ls -l
totale32
drwxr-xr-x. 7 kojy kojy 4096  5 ago 17.56 Documenti
drwxr-xr-x. 3 kojy kojy 4096  6 ago 15.03 Immagini
drwxr-xr-x. 2 kojy kojy 4096 31 lug 00.29 Modelli
drwxr-xr-x. 2 kojy kojy 4096 31 lug 19.49 Musica
drwxr-xr-x. 3 kojy kojy 4096  2 ago 18.09 Pubblici
drwxr-xr-x. 2 kojy kojy 4096  6 ago 02.22 Scaricati
drwxr-xr-x. 2 kojy kojy 4096  5 ago 15.09 Scrivania
drwxr-xr-x. 3 kojy kojy 4096  2 ago 20.50 Video
```
Or ```ls -lh``` for human readable format:
```
[root@ryzen-chan kojy]# ls -lh
totale 32K
drwxr-xr-x. 7 kojy kojy 4,0K  5 ago 17.56 Documenti
drwxr-xr-x. 3 kojy kojy 4,0K  6 ago 15.03 Immagini
drwxr-xr-x. 2 kojy kojy 4,0K 31 lug 00.29 Modelli
drwxr-xr-x. 2 kojy kojy 4,0K 31 lug 19.49 Musica
drwxr-xr-x. 3 kojy kojy 4,0K  2 ago 18.09 Pubblici
drwxr-xr-x. 2 kojy kojy 4,0K  6 ago 02.22 Scaricati
drwxr-xr-x. 2 kojy kojy 4,0K  5 ago 15.09 Scrivania
drwxr-xr-x. 3 kojy kojy 4,0K  2 ago 20.50 Video
```
You can use ```ls -lS``` to sort the output by size:
```
[root@ryzen-chan kojy]# ls -lS
totale 32
drwxr-xr-x. 7 kojy kojy 4096  5 ago 17.56 Documenti
drwxr-xr-x. 3 kojy kojy 4096  6 ago 15.03 Immagini
drwxr-xr-x. 2 kojy kojy 4096 31 lug 00.29 Modelli
drwxr-xr-x. 2 kojy kojy 4096 31 lug 19.49 Musica
drwxr-xr-x. 3 kojy kojy 4096  2 ago 18.09 Pubblici
drwxr-xr-x. 2 kojy kojy 4096  6 ago 02.22 Scaricati
drwxr-xr-x. 2 kojy kojy 4096  5 ago 15.09 Scrivania
drwxr-xr-x. 3 kojy kojy 4096  2 ago 20.50 Video
```
<br/><br/>
```cd /path/to/directory/``` - goes to the chosen directory.<br/><br/>
**Example:**
```
[kojy@linux ~]# cd Documenti/
[kojy@linux ~/Documenti]#
```
As you can see the shell has changed directory going from the user home folder (```~```) to the Documents folder (```~/Documenti```).<br/><br/>

It's possible to go back by one directory by just simply adding `..` instead of a directory:<br/>
```
[kojy@linux ~/test/test2] cd ..
[kojy@linux ~/test/]
```
As you can see the shell has changed directory going from *test2* folder (```~/test/test2```) to *test* folder (```~/test```).<br/><br/>

### Files manipulation
```mv /path/to/directory/``` - moves file(s) to a specific folder or directory.<br/><br/>
**Example:**
```
[kojy@linux ~/test]# mv here/moveme/ there/
```
As you can see we moved the file ```moveme``` cointained in the ```here``` folder to ```there``` folder.

```mkdir /path/to/<directory name>``` - to create a new folder or directory.<br/><br/>
**Example:**
```
[kojy@linux ~/test] mkdir folder
[kojy@linux ~/test] ls
folder
```
As you can see we succesfully managed to create the folder ```folder``` (```~/test/folder```) inside of ```~/test```.<br/>
We can also create multiple stack of files, doing so we can create whole new directory by just using ```mkdir -p```:
```
[kojy@linux ~/test] mkdir -p test2/folder2
[kojy@linux ~/test] ls test2
folder2
```
<br/>

```rm -f /path/to/file``` - to remove a file.<br/><br/>
**Example:**
```
[kojy@linux ~/test] rm -f file
```
Alternatively we can use ```rm -r``` to delete folders: **DO NOT USE IT WITH THE ROOT (/) FOLDER!**
```
[kojy@linux ~/test] rm -r folder
```
<br/>

```touch <file>``` - creates an empty file where you can then write text in it.<br/><br/>
**Example:**
```
[kojy@linux ~/test] touch catme.txt
[kojy@linux ~/test] echo "Hello, what's up?" > catme.txt
```
Using ```touch``` we succesfully made a text file called ```catme.txt``` and by using the ```echo``` command I added some text inside of the file.<br/><br/>


### Utilities
```lsblk``` - to show some informations about the partitions such as the size, free space, etc.<br/><br
**Example:**
```
[kojy@linux ~]# lsblk
NAME                            MAJ:MIN RM   SIZE RO TYPE MOUNTPOINT
sda                               8:0    0   1,8T  0 disk 
└─sda1                            8:2    0   1,8T  0 part /run/media/kojy/HDD
nvme0n1                         259:0    0 232,9G  0 disk 
├─nvme0n1p1                     259:1    0   600M  0 part /boot/efi
├─nvme0n1p2                     259:2    0     1G  0 part /boot
└─nvme0n1p3                     259:3    0 231,3G  0 part 
  ├─fedora_localhost--live-root 253:0    0    70G  0 lvm  /
  ├─fedora_localhost--live-swap 253:1    0   7,9G  0 lvm  [SWAP]
  └─fedora_localhost--live-home 253:2    0 153,4G  0 lvm  /home
```
The output shows the ```NAME``` of the drive, the ```SIZE``` and the ```MOUNTPOINT```, it means where the drive is mounted.<br/><br/>


```cat <file>``` - shows the content of a file.<br/><br/>
**Example:**
```
[kojy@linux ~/test]# cat catme.txt 
Hello, what's up?
```
As you can see the shell gave us as output the content of ```catme.txt```, it's possible to do that with any file so not just text files.

### Help
```man <command>``` - to call a manual page in case you don't know what a command does or how it works.<br/>
```<command> --help``` - shows a fair list of possible options for specific command.<br/>

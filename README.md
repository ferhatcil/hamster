<p align="center">
<img title="Hamster" src="https://img.shields.io/badge/Hamster-%20-SCRIPT?colorA=red&colorB=black&colorC=white&style=for-the-badge"></a>
</p>

<p align="center">
<a href="https://github.com/ferhatcil/hamster"><img title="Hamster" src="https://img.shields.io/badge/Tool-Hamster-red.svg"></a>
<a href="https://github.com/ferhatcil/hamster"><img title="Version" src="https://img.shields.io/badge/Version-1.0-red.svg?style=flat-square"></a>
</p>

<p align="center">  
<a href="https://github.com/ferhatcil/hamster"><img title="Hamster" width="300" height="300" src="https://i.hizliresim.com/8V4Hnm.jpg"></img></a>
</p>

<p align="center">
<a href="https://github.com/ferhatcil"><img title="Github" src="https://img.shields.io/badge/Ferhat%20%C3%87il-%20-red?style=for-the-badge&logo=github"></a>
<a href="https://www.youtube.com/channel/UCNFlGKonTAN9dfXgg_VrGoA"><img title="YouTube" src="https://img.shields.io/badge/Ferhat%20%C3%87il-%20-red?style=for-the-badge&logo=Youtube"></a>
</p>

<p align="center">
<a href="https://github.com/ferhatcil"><img title="Language" src="https://img.shields.io/badge/Made%20with-Python-yellowgreen"></a>
<a href="https://github.com/ferhatcil"><img title="Followers" src="https://img.shields.io/github/followers/ferhatcil?color=yellowgreen&style=flat-square"></a>
<a href="https://github.com/ferhatcil"><img title="Stars" src="https://img.shields.io/github/stars/ferhatcil/hamster?color=yellowgreen&style=flat-square"></a>
<a href="https://github.com/ferhatcil"><img title="Forks" src="https://img.shields.io/github/forks/ferhatcil/hamster?color=yellowgreen&style=flat-square"></a>
<a href="https://github.com/ferhatcil"><img title="Watching" src="https://img.shields.io/github/watchers/ferhatcil/hamster?label=Watchers&color=yellowgreen&style=flat-square"></a>
<a href="https://github.com/ferhatcil"><img title="Licence" src="https://img.shields.io/badge/License-MIT-yellowgreen.svg"></a>
</p>

### About the tool :

Hamster is a python-based script to test the password strength of the Http Basic Authentication page with a bruteforce attack. This tool works wherever there is python.

### Tested on :

* Ubuntu 20.04
* Ubuntu 18.04
* Kali Linux 2020.4

### Installation [Linux](https://wikipedia.org/wiki/Linux) [![alt tag](http://icons.iconarchive.com/icons/dakirby309/simply-styled/32/OS-Linux-icon.png)](https://fr.wikipedia.org/wiki/Linux)
```bash
git clone https://github.com/ferhatcil/hamster.git
cd hamster
python3 hamster.py -u admin --passwords rockyou.txt -v
```

### Optional arguments
<table>
<thead>
<tr>
<th>Short form</th>
<th>Long form</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>-h</td>
<td>--help</td>
<td>show this help message and exit</td>
</tr>
<tr>
<td>-v</td>
<td>-v</td>
<td>also shows failed session requests</td>
</tr>
<tr>
<td>-u</td>
<td>--user</td>
<td>you can specify only one username</td>
</tr>
<tr>
<td>-U</td>
<td>--users</td>
<td>you can upload a txt file filled with usernames</td>
</tr>
<tr>
<td>-p</td>
<td>--password</td>
<td>you can specify only one password</td>
</tr>
<tr>
<td>-P</td>
<td>--passwords</td>
<td>you can upload a txt file filled with passwords</td>
</tr>
<tr>
<td>-d</td>
<td>--domain</td>
<td>you can specify only one domain</td>
</tr>
<tr>
<td>-D</td>
<td>--domains</td>
<td>you can upload a txt file filled with domains</td>
</tr>
</tbody></table>

### Example
<code> python3 hamster.py -u admin -p admin -d http://localhost/login.php </code> </br>
<code> python3 hamster.py -u admin --passwords rockyou.txt -d http://localhost/login.php </code> </br>
<code> python3 hamster.py --users users.txt --passwords passwords.txt --domains host-list.txt -v </code> </br>

### Overview

<br>
<p align="center">
<img src="https://i.hizliresim.com/siFUbh.png"/>
</p>

### Video
[Youtube](https://www.youtube.com/watch?v=_QrL6uhYZ7s)

### Version
#### Current version is 1.0
* pilot

### Connect :

<p align="center">
<a href="https://github.com/ferhatcil"><img title="Github" src="https://img.shields.io/badge/Ferhat%20%C3%87il-%20-red?style=for-the-badge&logo=github"></a>
<a href="https://www.youtube.com/channel/UCNFlGKonTAN9dfXgg_VrGoA"><img title="YouTube" src="https://img.shields.io/badge/Ferhat%20%C3%87il-%20-red?style=for-the-badge&logo=Youtube"></a>
<a href="https://www.linkedin.com/in/ferhatcil/"><img title="Linkedin" src="https://img.shields.io/badge/Ferhat%20%C3%87il-%20-red?style=for-the-badge&logo=Linkedin"></a>
<a href="https://packetstormsecurity.com/user/ferhatcil/"><img title="Packet storm" src="https://img.shields.io/badge/Packet%20storm-Ferhat%20%C3%87il-red?style=for-the-badge"></a>
</p>

# smart

A Repository to store tinc public keys and templates



### Simple Usage Guide

* Windows: Install tap-win64


* Copy and paste from templates dir
* Modify hostname in ```tinc.conf```


* Windows: Modify Interface in ```tinc.conf```, setup IP in Network Manager
* Linux: Modify IP in ```tinc-up```


* tinc < 1.1: ```tincd -n smart -K 4096```
* tinc >= 1.1: ```tinc -n smart generate-keys 4096```
* Public node: Insert ```Address = <IPHERE>``` into host file
* (Recommend) Add ```Subnet = 10.0.135.<DIGIT>/32``` into host file


* Windows: ```tincd -n smart```
* Linux: ```systemctl start tinc@smart```




### Resource for Windows

Git: https://git-scm.com/download/win

Tinc: https://www.tinc-vpn.org/download/ (recommend 1.1-pre branch)

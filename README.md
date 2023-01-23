# mycrt
Get public cetificates info from crt.sh

* Uses jq and curl
* apt install jq curl 

```bash 
yum instal jq curl
```
# Help
```bash
#########################################################################
# Author: alf149                                                        #
# Scriptname: mycrt version 1.1.001                                     #
# You'll find last version at https://github.com/alf149/myfiles         #
#                                                                       #
# Uses jq as json handler                                               #
# uses curl to get json form crt.sh                                     #
#                                                                       #
#########################################################################

Syntax: scriptTemplate [-g|h|v|V]
options:
-h     Print this Help.
-d     Domain - Get active domain certificates info from crt.sh
       -d <DOMAIN> 
-l     List - like -d but for at list of domains in crt/domain_list
```

# example
```bash
./mycrt -d domain.com 

or 

./mycrt -l # this needs a prebuild crt/domain_list to work (one line pr domain.)

```
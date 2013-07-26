dlink-backup
============

backup dlink switch:

    $ ./dlink.exp switch_addr user pass config_name tftp_host

mass backup:

1. edit 1.list (see example default.list)
2. install expect
3. edit backup.sh (tftp host,tftp directory, backup directory and others)
4. ```$ ./backup.sh```
5. check backup dir for configs


Supported hardware
------------------


### D-Link


* dlink DES-3052
* dlink DES-3200-10
* dlink DES-3200-26
* dlink DES-3200-28
* dlink DES-3526
* dlink DES-3552
* dlink DGS-3312SR

### SNR

* SNR-S2950-24G

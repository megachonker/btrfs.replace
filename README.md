# btrfs.replace
replace corrupted file by original on local drive

## remplace
allow  you to batch replace all corrupted file from a list looking for the same name in local and replace it

## last corrupt 
use **journalctl** and **btrfs inspect-internal inode-resolve** for *lookup* the **realpath of a broken inode**!

`watch -n 60 "lastcorrupt 1m|tee -a test"`
record all error from now to ctrl+c

## error log
is  the command to create the  log file  for feeding  remplace

## remove
if you  whant to  destroy file  from a  list

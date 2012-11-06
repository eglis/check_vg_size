check_vg_size
=============

Check volume groups usage and return nagios plugin style output

Usage: 
-w <min size warning level in GB> 
-c <min size critical level in GB> 
[-v <volumegroupname>]
[-a] - all volumegroups defined by -v will be ommited and all groups which are found on system will be checked
[-p] - Use percentage for w and c instead of GB


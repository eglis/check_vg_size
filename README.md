check_vg_size
=============

Check volume groups usage and return nagios plugin style output

Usage: 
-w warnlevel 
-c criticallevel 
[-v  volumeGroup] 
[-a] - when -a used, all volumegroups defined by -v will be ommited and all groups which are found on system will be checked 
[-p] - Use percentage for w and c instead of GB

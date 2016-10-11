check_vg_size
=============

Check volume groups free space and return nagios plugin style output

Usage:

    check_vg_size -w warn_level -c critical_level [ -v volume_group ] [-p] ( -a | volume_group )

    -w Integer threshold for freespace to trigger WARNING status, in GB.

    -c Integer threshold for freespace to trigger CRITICAL status, in GB.

    -v Ignore target volume group.

    -a  check all volume groups except the ignored

    -p  Use percentage for w and c instead of GB. Still integer, ie 5 for 5%, 10 for 10%.

nagios-nrpe-check_glusterfs
===========================

Fork of Mark Ruys' check_glusterfs from http://exchange.nagios.org/directory/Plugins/System-Metrics/File-System/GlusterFS-checks/details

Hint: If you receive the error message that utils.sh is missing, you should check if the script is existing on your system and in the same folder as the check.

On Debian 7, the command
ln -s /usr/lib/nagios/plugins/utils.sh utils.sh
will help. 

An alternative would be to edit the check and adapt the line ". $PROGPATH/utils.sh" according to your needs.

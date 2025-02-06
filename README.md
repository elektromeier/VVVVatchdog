a watchdog for vvvv based installations

can restart v4 patches or exported .exes based on different conditions. by creating a client node in the patch you want to watch, it transmits a serialised object which contains different information about itself.
this way the watchdog can restart the patch if a certain conditions occurs.

for example:
-The patch doesnt send back this record on the watchdogs alive ping 
-the framerate drops below a certain threshold
more conditions could be easily added

compared to other watchdogs it should manage crashes where the patch is not responding but the process is still running

usage:
coming soon...


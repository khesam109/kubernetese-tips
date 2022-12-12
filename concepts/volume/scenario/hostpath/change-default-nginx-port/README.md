Problem Description: nginx running on ```80``` by default. you can change it be editing default.conf exsit on ```/etc/nginx/conf.d```
We solved it by mounting a new default.conf on this location.

**NOTE** that the new file should be place in the exact host in which nginx will be run.

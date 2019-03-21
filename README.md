# iplog
python script for logging and checking IP

+ pulls from [ifconfig.me](https://ifconfig.me)

+ getting the file in `/var/logs` is tricky because it wants to add a `\n` if you edit it

+ flags `>> BAD IP` if it matches one already logged

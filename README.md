
local.rules:

alert icmp any any -> any any (msg:"Testing ICMP alert "; sid:100001;)

alert tcp any any -> any any (msg:"Testing TCP alert "; sid:100002;)

alert udp any any -> any any (msg:"Testing UDP alert "; sid:100003;)


snort command:

snort -V

snort -W

snort -i 4 -c C:\snort\etc\snort.conf -T

snirt -i 4 -c C:\snort\etc\snort.conf -A console

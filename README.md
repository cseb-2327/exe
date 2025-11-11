
local.rules:

alert icmp any any -> any any (msg:"Testing ICMP alert "; sid:100001;)

alert tcp any any -> any any (msg:"Testing TCP alert "; sid:100002;)

alert udp any any -> any any (msg:"Testing UDP alert "; sid:100003;)

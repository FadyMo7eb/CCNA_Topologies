Project: 'Telnet_vs_SSH' 
Author: Fady Moheb <fmoheb6@gmail.com>
Task: telnet and ssh from router 1 to router 3 only from ssh once and telnet once 
---------------------------------------------------------------------------------------Telnet_SSH----------------------------------------------------------------------------------------
NOTE: you can change the ip address , mac address , caples and make your own toplogy it's only for education Fell free when use it 

NOTE: R(1) :
           => username fady password 123
           => enable password 1234
      R(2) :
           => username fady secret 456
           => enable secret 4567
      R(3) :
           => username fady privilage 15 secret 789
           => enable secret 78910

NOTE: that the md5 encrypted only on the private network not from the traffic test it with wireshark
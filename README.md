# dinamic_dns
A program to automatically change dns records for dynamic IP addresses Programmed by Marcel Bandić, contact: marcelb96@yahoo.com Applicable in bind9 DNS servers. Support A records. 

You can only run the program on the bind9 DNS server. It runs with  "sudo ./dinamic_dns". Before the flow, you must enter the domain in  the doamin.conf file and capture the path to the file zone in the  hosts.conf file since the override in the bind9 configuration.

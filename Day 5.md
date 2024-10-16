Day 5

Personal Notes


AWS -->> Shared responsibility 

SECURITY GROUP (SG)
Security group works at the instance level. Only allowed specified ports in your applications.

SG is divided into inbound and outbound traffic. 
Inbound traffic is from user 2 app
Outbound traffic is from app 2 user (internet)

AWS create default security group and it allows outbound traffics only but denies all inbound traffic. 

Port 25 outbound traffic is blocked by default by AWS.


NETWORK ACCESS CONTROL LIST (NACL)

This is applied at the subnet level. This denies some sets of network. It has an advantage over security group because once the list is created all network or traffic not in the list is denied access to the EC2 instances.
Rules in NACL uses priority of numbers and the last priority considered is the *.

NACL is the first layer of defense followed by the security groups. 

Security group is used for only allowing. 
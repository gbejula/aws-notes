AWS Zero-to-Hero

Day 4


AWS Virtual Private Cloud (VPC)

The size of VPC is decided by IP address range.
-- Elastic Load balancer has a target groups and host the private networks. It uses route table to direct target request.
-- Route table defines the path and helps the request from the internet to be directed to the right place.

HOW IT WORKS
Internet -->> VPC (Internet Gateway) -->> Public subnet -->> Load Balancer (LB) -->> Route table -->> Security groups (SG) -->> Application


NAT Gateway
This is the masking of IP address in order to access the internet from a VPC and also to download from the internet.



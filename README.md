# Vyatta Configuration Generator Page

This static site accepts a generic VPN configuration from Amazon VPC and generates a configuration file for a Vyatta appliance


### Additional Notes:

One additional step to run from the Vyatta appliance:

set protocols bgp 65000 network {VYATTA PRIVATE IP CIDR}

commit

save

### Credits:

Credits to kikumoto and Dave Rose excellent blog post

http://drcs.ca/blog/connecting-to-the-amazon-vpc-using-vyatta-community-edition/

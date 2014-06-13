# Vyatta Configuration Generator Page

This static site accepts a generic VPN configuration from Amazon VPC and generates a configuration file for a Vyatta appliance

## Installation

Checkout or clone the project and open it in a web browser using:

file://{path where saved}/public_html/en/index.html

## Additional Notes:

One additional step to run from the Vyatta appliance:

set protocols bgp 65000 network {VYATTA PRIVATE IP CIDR}

commit

save

## Credits:

Credits to kikumoto and Dave Rose excellent blog post

http://drcs.ca/blog/connecting-to-the-amazon-vpc-using-vyatta-community-edition/

## LICENSE

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

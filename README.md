# depaula_eip
 DePaula Ethernet IP prototype to connect with UR20-FBC-EIP
 

## Usage

Just drop a `depaula_eip in` node to read and watch addresses of the UR20-FBC-EIP, or a `depaula_eip out` node to write values to the UR20-FBC-EIP. Both of them need a `depaula_eip endpoint`, where you can configure the address  (IP Address, port, and routing), the cycle time and timeout values, and the list of addresses available on the FBC-Coupler.


### Addressing

The addresses follow the same syntax of what would be used on RSLogix, so for example `B3:0/0` addresses the bit 0 of byte 0 in the file B3, and `F8:1` points to the float 1 at the file F8.


### About routing
In case to use with PLC follow down information.  ( ( not implemented yet !!! ) ) 
The configuration of routing follows a very special syntax for now


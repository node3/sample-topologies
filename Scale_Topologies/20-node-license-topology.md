# Topology description

## 42 nodes
- 4 IOS XRv routers
- 14 IOSvL2 switches
- 24 9 iPerf LXCs

This simulation includes the use of OSPF along with the use of VLANs between LXC instances, switches and routers.

Each of the LXC nodes can be accessed using the 'ssh' connection method. Telnet will NOT work.

Log in the node as username 'cisco', password 'cisco'.

## Requirements
- This simulation requires the use of VIRL 1.0.x or later.
- The simulation will require ~26Gb to run.
- This scale topology will run within the 20 node license for VIRL. 

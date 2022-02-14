# Task7
1. Set up two focal VMs and assign IPs from the same network range eg.172.16.0.0 /24 and check if ping works. 
2. 2. Add another focal VM to the setup and assign connectivity in the following order where VM2 acts like a router. VM1 &lt;->VM2&lt;->VM3. VM1 should be from 172.16.0.0 /24 and VM3 should be from 192.168.0.0 /24. Should be done using static routing. 
3. Assign IPs to loopback (lo interface) and recreate #1 and #2 via BGP using FRR. VM1 lo: 10.1.1.1/32, VM2 lo: 10.1.1.2/32, VM3 lo: 10.1.1.3/32. Ping should work between the loopback addresses. The network range for BGP IPs is 172.16.0.0/24 for both the scenarios. 

# tcptools
## Using "ping" 
### What were the min/avg/max/stddev statistics for each?
### 1st
#### Amazon: Minimum = 16ms, Maximum = 25ms, Average = 18ms, stddev = 4.59
#### Google: Minimum = 15ms, Maximum = 19ms, Average = 16ms, stddev = 1.537
#### Microsoft: Minimum = 15ms, Maximum = 18ms, Average = 16ms, stddev = 1.2
### 2nd
#### Amazon: Minimum = 13ms, Maximum = 19ms, Average = 16ms, stddev = 1.77
#### Google: Minimum = 16ms, Maximum = 934ms, Average = 200ms, stddev = 744.96
#### Microsoft: Minimum = 14ms, Maximum = 28ms, Average = 17ms, stddev = 5.33
### 3rd
#### Amazon: Minimum = 14ms, Maximum = 20ms, Average = 15ms, stddev = 2.52
#### Google: Minimum = 15ms, Maximum = 141ms, Average = 61ms, stddev = 62.22
#### Microsoft: Minimum = 14ms, Maximum = 33ms, Average = 19ms, stddev = 7.02

### Was there any packet loss on any of the pings?
No, there was no packet loss on any of the pings. 
### Did the IP address change for a given website between pings?
No, the IP address does not change

## Using "tracert"
### What was the target server's IP address?
Amazon: 18.172.169.208, google:142.250.217.68, Microsoft:23.45.229.117
### How many hops were needed to reach the target?
Amazon:16, google:10, microsoft:9
### Can you identify your ISP from the intermediate server DNS names?
Comcast
### Identify the "class" of IP address for each major step in the trip
Amazon: class A,  Google: class A but the last hop is class B,  Microsoft: class A

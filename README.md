# Traceroute
 
A traceroute is a computer networking diagnostic tool that allows a user to trace the route from a host to any other host in the world. This is accomplished by sending ICMP echo messages to the specified destination while incrementing the time-to-live field with each message sent until the destination is reached. This will show each router that is used to reach the destination.

I programmed this tool for an Intro to Computer Networks course. I was provided with a skeleton code, and wrote or updated the definitions for the following functions:

__validateIcmpReplyPacketWithOriginalPingData(self, icmpReplyPacket) <br>
__sendIcmpEchoRequest(self, host) <br>
__sendIcmpTraceRoute(self, host) <br>
printResultToConsole(self, ttl, timeReceived, addr, type)

Here is an example of what the traceroute looks like when routing to Google's DNS 8.8.8.8
<img src=https://i.imgur.com/cs6Udon.png>
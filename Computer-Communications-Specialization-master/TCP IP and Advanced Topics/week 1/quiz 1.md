# TCP/IP and Advanced Topics
# LATEST SUBMISSION GRADE
# 80%
- 1.Question 1
Which of following is the range of IPv4 addresses spanned by Class C?


[ ] - 1.0.0.0 to 127.255.255.255


[ ] - 128.0.0.0 to 191.255.255.255


[x] - 192.0.0.0 to 223.255.255.255


[ ] - None of the above

Incorrect
Incorrect. Refer to IP Version 4 Protocol, Subnet reading

0 / 1 point

- 2.Question 2
If a subnet needs to accommodate up to 500 hosts. How many bits for HostID would be sufficient?


[ ] - 5


[ ] - 8


[ ] - 7


[x] - 9

Correct
Correct. 2^9 = 512, enough to accommodate 500 hosts in a subnet

1 / 1 point

- 3.Question 3
Consider a Class B network, where the subnet ID takes 9 bits. What will be the subnet mask?


[ ] - 11111111 11111111 11111110 00000000


[x] - 11111111 11111111 11111111 10000000


[ ] - 11111111 11111111 00000000 00000000


[ ] - None of the above

Correct
Correct. # of Host ID bits = 16 – 9 = 7. So 7 hostID bits in 0 for the mask

1 / 1 point

- 4.Question 4
Given a subnet mask 255.255.255.240, how many hosts the subnet can support?


[x] - 14


[ ] - 30


[ ] - 62


[ ] - None of the above

Correct
Correct. The subnet in binary string is 11111111 11111111 11111111 11110000. So the mask has 4 bits for hostID. 2^4 = 16. But two special bit strings (all 0s and all 1s have special purpose). So there are 16 -2 = 14 legitimate hosts.

1 / 1 point

- 5.Question 5
A host in an organization has an IP address 150.32.64.34 and a subnet mask 255.255.240.0. What is the address of this subnet?


[ ] - 150.32.64.24


[ ] - 150.32.64.32


[x] - 150.32.64.0


[ ] - 150.32.64.16

Correct
Correct. Address: 10010110 00100000 01000000 00100010

Mask: 11111111 11111111 11110000 00000000

Subnet: 10010110 00100000 01000000 00000000

1 / 1 point

- 6.Question 6
What is the maximum number of IP addresses that can be assigned to hosts on a local subnet that uses the 255.255.255.224 subnet mask


[ ] - 14


[ ] - 15


[x] - 30


[ ] - 62

Correct
Correct. Refer to Subnetting lecture

1 / 1 point

- 7.Question 7
When calculating usable hosts per subnet, the following formula is used 2^bits - 2. For what reason is two subtracted? (choose two)


[x] - Broadcast

Correct
Correct. Refer to Subnetting lecture


[ ] - Unicast


[x] - Network

Correct
Correct. Refer to Subnetting lecture


[ ] - Multicast

1 / 1 point

 - 8.Question 8
How many hosts can be addressed on 10.0.0.0/16?


[ ] - 16


[ ] - 254


[ ] - 65536


[x] - 65534

Correct
Correct. Refer to IP Version 4 Protocol, Subnet reading

1 / 1 point

- 9.Question 9
Which of the following is a valid IP host address given the network ID of 191.254.0.0 while using 11 bits for subnetting?


[ ] - 191.254.1.29


[1] - 191.254.0.96


[ ] - 191.54.1.64


[ ] - 191.254.0.32

Incorrect
Incorrect. Refer to Subnetting lecture

0 / 1 point

 - 10.Question 10
DISCO Corporation has been assigned the Class B network address 165.87.0.0. DISCO needs to divide the network into eight subnets. What subnet mask should be applied to the network to provide the most hosts per subnet?


[ ] - 255.255.192.0


[ ] - 255.255.224.0


[x] - 255.255.240.0


[ ] - 255.255.248.0

Correct
Correct. 2^3-2 = 6 subnets; 2^4-2 = 14 subnets; (2^16 - 2^4) -2 = 2^12 - 2 = 4094 hosts possible per subnet. Because 3 bits of subnetting will only yield 6 usable subnets (7 if ip subnet-zero is enabled), you will need to borrow another bit. To meet your minimum requirement of 8 subnets, and the maximum number of hosts per subnet, this Subnet mask will be correct: 255.255.240.0

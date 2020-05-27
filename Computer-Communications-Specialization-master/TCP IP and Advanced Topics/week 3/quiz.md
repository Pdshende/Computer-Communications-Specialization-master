# Graded Assessment - Transmission Control Protocol

# LATEST SUBMISSION GRADE

# 80%

- 1.Question 1
When a TCP client initiates a three-way handshake with a sequence number x, what will be the acknowledgement number when the TCP server replies?


[ ] - x


[x] - x + 1


[ ] - x + y (where y is the sequence number proposed by TCP server)


[ ] - None of the above

Correct
Correct. Refer to TCP Three-way Handshake lecture

The TCP server receives the packet, records the Sequence Number of x from the TCP client, and replies with an acknowledgment and synchronization (SYN-ACK). The Acknowledgment Number is a 32-bit field in TCP segment header. It contains the next sequence number that the TCP server is expecting to receive (x + 1).

1 / 1 point

 - 2.Question 2
TCP header has a field called window size. What value is the value window size set to?


[x] - None of the above


[ ] - Advertised window size for flow control


[ ] - Round-trip delay


[ ] - Advertised window size for congestion control

Correct
Correct. It is the minimum of flow control window size and congestion control window size.

1 / 1 point

 - 3.Question 3
In general, there are three phases of congestion behavior, i.e., light traffic, knee, congestion collapse. Which phase does TCP congestion avoidance maps to?


[ ] - Light traffic


[ ] - Knee


[1] - Congestion collapse


[ ] - None of the above

Incorrect
Incorrect. Refer to TCP Congestion Control lecture

0 / 1 point

- 4.Question 4
When three duplicate acknowledgements arrive before timeout expires, what will TCP congestion control algorithm reset congestion threshold to for fast re-transmission and fast recovery?


[ ] - Reset congestion threshold to 1


[ ] - Reset congestion threshold to half of the current congestion window size


[1] - Reset congestion threshold to the current congestion window size


[ ] - None of the above

Incorrect
Incorrect. Refer to TCP Congestion Control lecture

0 / 1 point

- 5.Question 5
Assume a TCP source writes a 1200-byte message in one write. Which of following is possible for the destination to receive the message?




[ ] - It receives three reads of 400 bytes each




[ ] - It receives a 1200-byte message in one read




[x] - All of the above




[ ] - It receives two reads of 600 bytes each

Correct
Correct. TCP may split or combine the application information and pack it into segments for efficiency and flow control.

1 / 1 point

 - 6.Question 6
The process of combining multiple outgoing protocol streams at the Transport and Network layers in TCP/IP is called Multiplexing




[x] - True




[ ] - False

Correct
Correct. Refer to UDP and TCP lecture

1 / 1 point

- 7.Question 7
TIMELY provides a framework for rate control that depends on transport layer protocol for reliability




[ ] - True




[x] - False

Correct
Correct. Refer to TIMELY: RTT-based Congestion Control for the Datacenter reading

1 / 1 point

- 8.Question 8
The operation of TCP congestion control can be divided into three phases, which phase requires that the congestion window size be increased by one segment upon receiving an ACK from receiver




[ ] - Congestion avoidance




[x] - Slow start




[ ] - Congestion




[ ] - None of the above

Correct
Correct. Slow start adds another window to the sender's TCP such that each time an ACK is received, the congestion window is increased by one segment.

1 / 1 point

- 9.Question 9
In a router, the control of the transmission rate at the sender's side such that the router's buffer will not be over-filled is called _________ if sender is transmitting too fast




[ ] - Network under-utilization




[ ] - Host flooding




[x] - Network congestion




[ ] - None of the above

Correct
Correct. Refer to TCP Flow Control and Data Transfer

1 / 1 point

- 10.Question 10
Congestion control is associated with the window size field




[ ] - True




[x] - False

Correct
Correct. Flow control is associated with window size field not congestion control

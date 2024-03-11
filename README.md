All the instructions on running the project, along with comprehensive details on the underlying logic, are available through the provided [link](https://pergamos.lib.uoa.gr/uoa/dl/object/2898147/file.pdf). 
This information is integral to a master's thesis titled 'Emulation of HTTP Adaptive Video Streaming over SDN.' 
Please note that uploading the code is prohibited as per the regulations of the DIT department.

**ABSTRACT**
Video streaming is growing into a well-known technology for media transmission over
the Internet. Dynamic Adaptive Streaming over HTTP (DASH) permits transmitting data
streams to a user with the largest feasible bit rate in different bandwidth situations which
is especially important for wireless networks. The purpose of this thesis is to analyze
DASH technology as far as live video streaming is concerned, as well as to examine the
Quality of Experience (QoE) on SDN networks, namely to understand the user’s
perspective. Thus, in this thesis, a virtual SDN network was developed in the Mininet
environment to simulate DASH technology. In each experiment, one server transmitted
a video live to a client while the throughput was changing by adding extra traffic to the
network. At the same time, the Wireshark application was monitoring the transmitted
packets from the server to the client, storing various parameters related to the network,
based on which the user’s QoE was calculated. Specifically, the impact of the added
traffic on the quality of the broadcast video was examined, and as a result the impact in
terms of QoE was measured. We concluded that the transmitted data is entirely
connected with the existing traffic in the network and in particular the higher the traffic,
the poorer the selected resolution. However, we observed that the resolution of the
broadcast video would not always change immediately, as a result of the existence of
the buffer at the video client.
The structure of this thesis is the following: Chapter 1 provides a detailed overview of
the mobile networks’ evolution from the first generation to the fifth one. Chapter 2
describes in detail the HTTP Adaptive Streaming (HAS) technology in terms of its
architecture, its advantages and disadvantages. It also describes the architecture of
DASH technology, its implementation and the additional advantages it offers. Chapter 3
is about QoE, the way in which it is calculated through specific models, and its influence
on HTTP video streaming technology. All the necessary programs in order to conduct
the experiments presented in this thesis, as well as any necessary settings, can be
found in Chapter 4. Chapter 5 provides an in-depth analysis of the design of the
experiments, during which a decrease in the quality of the user’s experience was
observed. It also presents the obtained results. Finally, Chapter 6 summarizes the
conclusions of this thesis and discusses future work topics.

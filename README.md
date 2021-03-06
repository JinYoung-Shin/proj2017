Multi-Connectivity in Edge Computing Using RNN Algorithm

Abstract

 As number of devices which need network increase. Necessity of new technology for managing massive connectivity came to light.
This research adopts Recurrent Neural Network(RNN) algorithm to manage multi connectivity. Research develops the most ideal algorithm by strict analysis.
And the developed method is going to be applied on network managing hub combined with LPWAN(Low-Power Wide Area Network) based connectivity managing technology.
Selection and application of best fit method by dealing with kinds of RNN algorithm, we expect gaining outstanding performance on network management.
And the performance would lead popularization of edge computing.

Introduction

 It is unable to overemphasize importance of IoT these days.
Frequently used word ‘Connected World’ explains well about era of IoT. Recent predictions say that there will be around 30 ~ 50billion IoT nodes at 2020.
On growth of IoT, researches to deal with large scale future network are prevalent.
For example, breaking down the nodes into smaller pieces. Let’s suppose a switch(power) of the entire room’s light was a connected node, movement spreading the nodes to whole light(lamps) is on.

 Wireless technology has been facing necessity of change as Connected World coming to reality. 
Current connectivity managing algorithm is MADM(Multiple Attribute Decision Making). 
MADM algorithm can be devided into algorithm like SAW(Simple Additive Weighting), MEW(Multiplicative Exponential Weighting), TOPSIS(Technique for Order Proference by Similarity to an Ideal Solution), VIKOR. 
But, MADM algorithm seems not to fit right in massive connected IoT environment. 
The reason is MADM sets priorities by weighting on specific elements. 
And core factor is that it is unable to get dynamic location of nodes with MADM. 
In other words, MADM cannot consider variety of factors which should be handled in IoT network environment. 
That is why another algorithm for IoT usage become necessary. 
This paper contains proposal of IoT environment fit algorithm(RNN) and application of RNN to multi-connectivity.

TOPSIS : The Technique for Order of Preference by Similarity to Ideal Solution is a multi-criteria decision analysis method. TOPSIS is based on the concept that the chosen alternative should have the shortest geometric distance from the positive ideal solution. and the longest geometric distance from the negative ideal solution.

AHP : Analytic Hierarchy Process calculate weight from the top of the elements moving toward low class elements and consider relative preference of alternatives. Rather than giving a correct solution, AHP gives one that best suits for goals.

SAW : Simple Additive Weighting is kind of a classic and simple method. It gives weight to each element regarding importance. And selecting the biggest sum of weight multipled elements. This method is used a lot in the field of network.

MEW : MEW(weighted multiplicative method) is similar to SAW algorithm. This method multiples to summate weight multipled values.

 'Edge Computing' was a big issue in IT fields of 2016. The concept of edge computing is locating data center near users so that faster speed service could be offered. Before edge computing central data center covered whole users. Now edge data centers cover separate area. This new concept of service could lower latency of service time and users could experience more real-time like service with high quality.

![image1](https://user-images.githubusercontent.com/8980813/27447872-a25a0640-57bd-11e7-97ef-9ef804d8f2c4.JPG)

RNN Algorithm

2.1 About RNN

 RNN(Recurrent Neural Networks) is a kind of artificial neural network.
By using RNN, we will be able to realize memorizing function similar to human brain.
Because it enables memorization of dynamic data so that it could solve non-linear featured problems around us. 
That is why RNN is considered as one of the most powerful one among other kinds of neural networks.
Unlike FFNET(Feed-Forward neural network) which could be considered as general neural network, RNN can process dynamic sequence of inputs. 


2.2 Kind(Structure) of RNN Algorithm
- Fully Recurrent Network
- Hopfield Network
- Elman Network
- Echo State Network(ESN)
- Long Short-Term Memory Network(LSTM)
- Bi-directional RNN
- Continuous-time RNN(CTRNN)
- Hierarchical RNN
- Second Order RNN

 These lists above are typical example of RNN. Though there are a lot to deal with, we will focus on Long Short-Term Memory Network(LSTM) in this paper. LSTM is the most frequent used method among other methods. 
Major problem on usage of RNN is that as process goes deep, it is hard for the network to have old data. 
With emergence of this kind of matter, LSTM, which could be cosidered evloved version of RNN appeared. 
Unlike other RNN methods, LSTM networks are not affected by time.

Principle of LSTM is classifying of memory to two class. 
One can be held for long duration of time and the other does not. Which means LSTM does not have data vanishing phenomenon. 

2.3 Fields which RNN is used

One of the most remarkable feature of RNN is handling with dynamic data. 
This feature allow RNN to be used in the fields dealing with changable and unsegemented kind of data.

* RNN used fields
-Natural Language Processing
	-Handwriting Recognition
	-Creation of Text(Message)
	-Speech Recognition
	-Machine(Automatic) Translation
-Image Recognition
-Video Recognition

2.4  Objective

 This research cover applying RNN to multi-connectivity. Proper application of the algorithm would bring effective scheduling of network on dealing with massive connectivity. 
RNN on multi-connectivity can be a solution for absence of optimized IoT management algorithm. Applied technology can be efficiently used at hub which schedules IoT network. 


3. 1 
Title : Multi Connectivity in edge computing using RNN Algorithm

Schedule Planning :

![chart1](https://user-images.githubusercontent.com/8980813/27691106-090fe958-5d1e-11e7-8a50-fa08b7f2e32a.jpg)

Proposal(Planning) of Research
: Research of expectancy effects of the research. Research of preceding technology in related area. Preparation of a paper proposal.

Research of multi-connectivity
: By taking research about limitation of current technology, focus on necessity and efficiency of new technology.

Research of RNN algorithm
: Study about kinds of RNN algorithm and summarize them by focusing on main feature.

Simulate RNN Algorithm
: Incorporate powerful RNN algorithm for multi-connectivity in edge computing. Try to enhance performance of algorithm.

Apllication of RNN on multi-connectivity environment
: Apply the developed RNN to multi-connectivity environment. Test real performance and compare with the expected result. 


4. Expectancy Effect

	By applying RNN algorithm on multi-connectivity, we can expect to gain more performance on connection speed. With the gained performance, it could be adopted on edge computing node. Nodes are about to be more split when we are on edge computing, so characteristic of RNN would help building smooth communicating networks.

	This research would cause improve performance of LPWAN especially in sorting and scheduling of requests. The enhanced performance in network managing technology would contribute to maintain stable network in edge computing.

	Edge computing is now a inevitable technology for enterprise or service agent to offer more rapid, available, scalable service. This research would help establishing fine connectivity management in Edge computing world.
	
===================================================================================
Korean VER.

===================================================================================
Interim Report

■ 관련연구 (4페이지 이내)
졸업작품/논문과 관련된 related work를 작성합니다. 국문논문 영문논문 무방합니다만, 적어도 국문 3개 이상 영문 3개 이상을 포함합니다. 각 관련된 문장에 관련된 연구 참조문헌 번호 기록바랍니다. [2]

2.1 Edge Computing
 Mobile Computing is term used to describe which enables people access network services anytime, anywhere. 


Figure 2. Mobile Computing


 As mobile computing developed, a number of forms of network & connectivity technology have enable and also the Internet of Things(IoT) have rised. Term ‘(Mobile) Edge Computing’ came out as IoT brought necessities of numberous nodes. Mobile computing There is no a single type of connectivity solution that connects nodes. To develop billions of devices, we need new Wide Area Network(WAN) technology. Solutions of wireless solutions these days are for example RFID, NFC, Bluetooth, Wi-Fi, Zigbee etc.

 Edge Computing is a kind of cloud computing which serve data applying distribute computing technology to base station. Edge Computing consists of cloud(core) and server with Radio Area Network(RAN). When user device requests the server sends cached data to user device and cloud. Then the cloud sends proper data to the server and the server sends it to user. The core feature of this idea is using server near to user so that user gets rapid service and distributing load of core server to edge servers.

2.2 RNN Algorithm

 RNN(Recurrent Neural Networks) is a kind of artificial neural network. By using RNN, we will be able to realize memorizing function similar to human brain. Because it enables memorization of dynamic data so that it could solve non-linear featured problems around us. That is why RNN is considered as one of the most powerful one among other kinds of neural networks. Unlike FFNET(Feed-Forward neural network) which could be considered as general neural network, RNN can process dynamic sequence of inputs. 

 RNN algorithm works like the figure above, it runs recurrently returning output. The previous state of iteration done(input, ouput) is memorized and it determines next step. 

2.3 Multi-Connectivity
 Multi-Connectivity on IoT is driven by a few different protocols(Wireless Protocols). Representitive samples are Wi-Fi, Bluetooth, ZigBee etc. Each protocols have difference in performance in energy consuption, service range, mobility etc. This paper recommends MQTT protocol based on TCP/IP to achieve communication between edge nodes. MQTT is light messaging protocol which enable connection of maximum 10K devices. It could cover the number of nodes in purpose of edge computing.

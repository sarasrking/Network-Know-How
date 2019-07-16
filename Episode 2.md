---
title: "Networks"
teaching: 30
exercises: 3
questions:
- What are common networks and how do they differ?
objectives:
- Differentiate between different types of networks
- Understand what the National Research Network is
- Calculate file transfer times using an online tool
- Conduct a ping test and understand the result
keypoints:
- Different networks behave differently. 
- Knowing about network speeds means good data movement decisions.
---

# NETWORKS
 
 Here is a list of different networks in Australia and their client base.
 
- **ADSL** – domestic, small business
- **NBN** – domestic (being rolled out), CBD, schools
- **NREN** – universities, CSIRO, some schools and hospitals
 
Each of these networks has different properties. 

## ADSL

Digital subscriber line (DSL) service provides a connection to the Internet through the telephone network. Asymmetric digital subscriber line (ADSL) is a type of DSL technology. In ADSL, bandwidth and bit rate are said to be asymmetric, meaning greater *toward* the customer premises (downstream) than the reverse (upstream). ADSL2+ extends the capability of basic ADSL by doubling the number of downstream channels. The data rates can be as high as 24 Mbit/s downstream and up to 1.4 Mbit/s upstream. 

ADSL2+ service is most commonly offered in highly-populated metropolitan areas and subscribers must be in close geographical locations to the provider in order to receive ADSL2+. The further the subscriber is from the telephone exchange the slower the connection.

ADSL2+ has a maximum potential download speed of 24Mbps. Most ADSL2+ connections are much slower: the average Australian ADSL speed is just 8Mbps.

## NBN

The National Broadband Network (NBN) is an Australian national wholesale open-access data network project. It is a government initiative to upgrade Australia’s broadband infrastructure to provide consumers with faster broadband connections.

Using a variety of broadband network technologies including running fibre all the way to the consumer’s premises (‘fibre to the premises’ or FTTP), running fibre to a nearby box or apartment block and then using the existing copper telephone wire (‘fibre to the node’ FTTN, and ‘fibre to the basement’ FTTP) the aim is to bring data closer to the end user on optical fibers. The differences between the methods have mostly to do with just how close to the end user the delivery on fiber comes.

The main difference for the consumer between the NBN and ADSL is speed. There are various options for speed, depending on requirements.

This video helps explain: https://www.youtube.com/watch?time_continue=31&v=L3QJLEbUj94 


### NBN evening speeds

Maximum speeds are not always available due to high traffic. This table shows 'evening speeds', which is what is expected at peak usage times between 7pm and midnight. 

Tier | Maximum speed | Evening speed
---- | ------------- | -------------
Basic (NBN 12) | 12Mbps | 7Mbps
Standard (NBN 25) | 25Mbps | 15Mbps
Standard Plus (NBN 50) | 50Mbps | 30Mbps
Premium (NBN 100) | 100Mbps | 60Mbps
---

## NREN
 
The Australian National Research Network (NREN) provides advanced research network infrastructure. It is fast, with connections from 10 Gbps to 40 and 100 Gbps. It is high capacity, catering to 1 million + users and is tailored for research, teaching and learning. It has low latency (lag) providing consistent connectivity and response times because it is designed to have ‘headroom’ or allow for bursts (elephants) of large data moving through the network. 
 
Australia is a large continent, and the networks AARNet provides enable data capture and research to be conducted in major cities and in regional areas, where universities and research facilities and infrastructure are located, e.g. the National Computational Infrastructure (NCI) in Canberra and the Square Kilometre Array (SKA) in Murchison (WA).
 
Australia lies at a distance from research conducted in other parts of the world, like the northern hemisphere, and the networks AARNet provides, aid in removing distance as a barrier, to research collaboration.
 
Click here to learn more: [https://www.aarnet.edu.au/network-and-services/advanced-network-services](https://www.aarnet.edu.au/network-and-services/advanced-network-services)
 
## FILE TRANSFER TIME CALCULATION

### Activity 1
 
Test the speed of your connection: [http://www.speedtest.net/](http://www.speedtest.net/)

Pay attention to upload vs download speeds. Check wi-fi, mobile phone and cable differences, either in the class or compare when you change your access type. 
 
Now let's ake a look at some samples of data transfer times according to which network you are on and how you are connected:

**100MB TRANSFER (OR MAX EMAIL ATTACHMENT)**

Network type | Connection speed | Transfer time
------------ | ---------------- | -------------
At home on poor ADSL | 3.38 Mbps | 7 minutes
At a conference, using wifi | 54 Mbps | 17 seconds
On the NBN | 100 Mbps | 8 seconds
On the NREN | 10 Gbps | milliseconds
--

Time can be saved if the network speeds are tested ahead of trying to transfer data, network traffic levels are known, and file sizes have been calculated. How would you (or would you recommend a researcher) undertake a data transfer process? What do you need to consider when thinking about the network they are using? Did you know that the time of day at both the point of departure AND the point of arrival can have an influence on network speeds?
 
### Activity 2
 
You have 20TB data to transfer on a 40Gbps link. How long will it take to transfer that data? Use: https://techinternets.com/copy_calc


**CABLE OR WI-FI?**
 
Networks have physical properties. 

Think of a standard network connection like rope where you unwind it and hand out each strand (as users log in). The more users, the less and less rope there is to hand out. Many laptops link to an access point on the network (the wifi) and that access point divides up the traffic to each laptop user. Even the placement of the cables can make a difference, as interference can come from different places, such as lifts and fans!

Many factors can influence the capacity of a wi-fi connection too. Can you think of any times when your wi-fi has become unstable?

 
 ### Activity 3

We are now going to do a 'ping' test. A ping is a message sent from one IP address to another to ensure connection. It is a signal sent to a host that requests a response. It serves two primary purposes: 1) to check if the host is available and 2) to measure how long the response takes.

Instructions here: https://www.wikihow.com/Ping-an-IP-Address 

Pay attention to the network address, speed in milliseconds, packet loss, and min/avg/max speeds. Try a few different websites to see if there are differences.

A ping test is an important step in troubleshooting speed and connection problems with specific servers or even your own router. It can help identify problems along a network path.

## Resources:

Types of networks:

https://en.wikipedia.org/wiki/Internet_access

https://en.wikipedia.org/wiki/Internet_in_Australia

https://en.wikipedia.org/wiki/Asymmetric_digital_subscriber_line

https://en.wikipedia.org/wiki/G.992.5 

More about the NBN:

https://www.nbnco.com.au/content/dam/nbnco2/documents/nbn-business-fact-sheets/nbn-business-fact-sheet-tc4.pdf

https://www.accc.gov.au/consumers/internet-landline-services/broadband-speeds

https://www.whistleout.com.au/Broadband/Guides/what-nbn-speed-do-you-need

https://www.nbnco.com.au/residential/learn/speed

https://en.wikipedia.org/wiki/National_Broadband_Network

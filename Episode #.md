---
title: "Testing a connection"
teaching: 15
exercises: 2
questions:
- How can you test your connection?
objectives:
- Perform a ping test and understand the results
- Perform a traceroute and understand the results
keypoints:
- There are a couple of easy ways to test your connection with another website is working, or where there might be a problem. This is helpful to alleviate frustration when attempting to move data. 
---

# Testing a connection

There are a couple of different ways you can check if your connection is working. 

## Ping test

A ping is a message sent from one IP (Internet Protocol) address to another to ensure connection. It is a signal sent to a host that requests a response. 

 ### Activity 1

We are now going to do a 'ping' test. 

It serves two primary purposes: 

  1) Checks if the host is available 
  2) Measures how long the response takes

See instructions here: https://www.wikihow.com/Ping-an-IP-Address 

Or follow the steps below, depending on the operating system you are using:

  * Windows: Type “cmd” in the search box in your task bar at the bottom of the screen, then open up the Command Prompt. Type **ping aarnet.edu.au**

  * Linux: Open a terminal window, type **ping aarnet.edu.au** the press **CTRL+C** C to stop the command

  * Mac: Open up Network Utilities (using Spotlight) and select *ping menu* and type in **aarnet.edu.au**

Pay attention to the network address, speed in milliseconds, packet loss, and min/avg/max speeds. Try a few different websites to see if there are differences.

A ping test is an important step in troubleshooting speed and connection problems with specific servers or even your own router. It can help identify problems along a network path.

## Traceroute

When you're on the Internet, a number of computers networked together help you receive and transmit information. Information or requests sent from your computer don't reach the destination computer in a single jump (or hop!). Data requests and replies take unique routes. The 'traceroute' command will show you how many hops there are between you and your destination address, and how long it took to move the data from one computer to the next.

See instructions here: https://iihelp.iinet.net.au/How_to_run_a_traceroute

Or follow the steps below, depending on the operating system you are using:

  * Windows: Type “cmd” in the search box in your task bar at the bottom of the screen, then open up the Command Prompt. Type **tracert aarnet.edu.au**

  * Linux: Open a terminal window, type **traceroute aarnet.edu.au** the press **CTRL+C** C to stop the command

  * Mac: Open up Network Utilities (using Spotlight) and select *traceroute menu* and type in **aarnet.edu.au**

Pay attention to the addresses, speed in ms, and hops. Try a few different websites to see if there are differences.

The traceroute identifies each computer/server on that list and the amount of time it took. If there is a problem or interruption in the transfer of data, the traceroute will show where it occurred. If someone is having difficulty accessing a particular website or computer, performing a traceroute can help find out where the problem is occurring along the network.

Resource: https://whatismyipaddress.com/traceroute

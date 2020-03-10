Name: Maryn Kunthara

EID: mhk724

Team Number: Team 15

Questions
1. What is the purpose of an IP address?

    For machines to learn identities of the machines in other LANs , we need a naming mechanism and accompanying discovery methods. This naming mechanism gives each machine a “unique” identity called, its IP (Internet Protocol) address.

2. What is a DNS? What are the benefits of using domain names instead of IP addresses?

    The ARP protocol’s target is to get every machine to learn the hardware address and the corresponding IP address of every other machine in a LAN. The 32-bit IP-address that is unique to each machine poses the problem of being hard to remember. A lookup service called Domain Name Service (DNS), maps a symbolic name (like www.utexas.edu) to its corresponding IP address.

3. What is the difference between a static IP and a dynamic IP?

    A static IP address is simply an address that doesn't change. Once your device is assigned a static IP address, that number typically stays the same until the device is decommissioned or your network architecture changes. Static IP addresses generally are used by servers or other important equipment. As the name suggests, dynamic IP addresses are subject to change, sometimes at a moment's notice. Dynamic addresses are assigned, as needed, by Dynamic Host Configuration Protocol (DHCP) servers. We use dynamic addresses because IPv4 doesn't provide enough static IP addresses to go around. (taken from: https://www.avast.com/c-static-vs-dynamic-ip-addresses)

4. What is the tradeoff between UDP and TCP protocols?

    TCP is connection-based and reliable meaning no loss. UDP is connectionless, unreliable, but fast.

5. Why can't we use the delay function with Blynk?

    When we use a blocking delay function nothing else can run while it is running, effectively wasting time we could spend elsewhere. Thankfully, the ESP32 has hardware built in that allows us to automatically output PWM signals on every pin! This means we can just write a duty cycle to a register, set it and forget it, no delaying necessary.

6. What does it mean for a function to be "Blocking"?

    When a function is "blocking", nothing else can run while it is running, effectively wasting time we could spend elsewhere.

7. Why are interrupts useful for writing Non-Blocking code?

    The program doesn't always have to be checking for something to be set in the time that it could be running other code. Functions can be called and run through only when certain condiitons are met while other code is running.

8. What is the difference between interface and implementation? Why is it important?

    An interface defines how a function is called, and is usually in a header file. The implementation describes what the function actually does.

9. Screenshot of your Blynk App:

    ![your image here->](img/blynk_screenshot.PNG)

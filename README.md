# Netpractice-42

## What's an IP adresse?
> An IP address, or Internet Protocol address, is a series of numbers that identifies any device on a network. Computers use IP addresses to communicate with each other both over the internet as well as on other networks.

## What's a Network?
> A network consists of two or more computers that are linked in order to share resources (such as printers and CDs), exchange files, or allow electronic communications. The computers on a network may be linked through cables, telephone lines, radio waves, satellites, or infrared light beams.

<tr>
<img src="https://ewgqz2vh7kv.exactdn.com/wp-content/uploads/2021/12/IP-Address-Explained-1024x512.jpeg?strip=all&lossy=1&ssl=1"></img>
</tr>


## What's a TCP/IP?
> TCP/IP stands for Transmission Control Protocol/Internet Protocol and is a suite of communication protocols used to interconnect network devices on a network.
## What's a subnet mask?
>  The subnet mask is used by the TCP/IP protocol to determine whether a host is on the local subnet or on a remote network.

## Why using routers?

> If a TCP/IP computer needs to communicate with a host on another network, it will usually communicate through a device called a router. In TCP/IP terms, a router that is specified on a host, which links the host's subnet to other networks, is called a default gateway. This section explains how TCP/IP determines whether or not to send packets to its default gateway to reach another computer or device on the network.

# Levels: 
<details open>
<summary>Level 1</summary>
<br>
<img src="img/Screen Shot 2022-07-23 at 5.33.30 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>In this level, we should put the hosts on the same network by providing the same Net-ID while respecting the IP adress range.</li>
</ul>

</details>
<details open>
<summary>Level 2</summary>
<br>
<img src="img/Screen Shot 2022-07-24 at 2.57.33 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>In this level, we should know the private IP adress : A private IP address is a range of non-internet facing IP addresses used in an internal network.</li>
<p>Address ranges to be use by private networks are:</p>

<li>Class A: 10.0.0.0 to 10.255.255.255</li>
<li>Class B: 172.16.0.0 to 172.31.255.255</li>
<li>Class C: 192.168.0.0 to 192.168.255.255</li>
<br>
<p>The IP address 127.0.0.1 is a special-purpose IPv4 address and is called the localhost or loopback address. All computers use this address as their own, but it doesn't let computers communicate with other devices as a real IP address does.</p>
</ul>

</details>

<details open>
<summary>Level 3</summary>
<br>
<img src="img/Screen Shot 2022-07-24 at 3.04.24 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>A network switch forwards data packets between devices. Switches send packets directly to devices, rather than sending them to networks like a router does.</li>
</ul>

</details>
<details open>
<summary>Level 4</summary>
<br>
<img src="img/Screen Shot 2022-07-24 at 3.08.31 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>A router is a device that connects two or more packet-switched networks or subnetworks. It serves two primary functions: managing traffic between these networks by forwarding data packets to their intended IP addresses, and allowing multiple devices to use the same Internet connection.</li>
</ul>

</details>
<details open>
<summary>Level 5</summary>
<br>
<img src="img/Screen Shot 2022-07-24 at 3.24.22 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>The main function of a switch is to connect the end devices such as computers, printers, etc., whereas the main function of a router is to connect two different networks.</li>
</ul>

</details>

<details open>
<summary>Level 6</summary>
<br>
<img src="img/Screen Shot 2022-07-24 at 4.53.27 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>In this level, we should put the hosts on the same network by providing the same Net-ID while respecting the IP adress range.</li>
  <p>0.0.0.0 has the specific meaning "unspecified". This roughly translates to "there is none" in the context of a gateway. Of course, this assumes that the network is locally connected, as there is no intermediate hop. The machine will send the packet out that interface as though to a machine connected to that segment, which in Ethernet means the MAC address of the destination host will be used instead of the MAC address of the next hop gateway.

As a destination, 0.0.0.0/0 is special: if there are no network bits, there can't be anything in the network number either. So, it's naturally unspecified. For prefix matching it masks off all bits, so all addresses are within 0.0.0.0/0; for this reason it's used to mean "default gateway" in routing tables. It is also the least-specific possible route, so selections that prioritize specificity will choose anything else available and match 0.0.0.0/0 as a last resort.</p>
</ul>

</details>
<details open>
<summary>Level 7</summary>
<br>
<img src="img/Screen Shot 2022-07-24 at 5.28.21 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>In this level, we handle the overlaping issue, with the 255.255.255.0 mask, there is only one network, but we have 3 , that is why we use a new mask , respecting the ranges. </li>
</ul>

</details>
<details open>
<summary>Level 8</summary>
<br>
<img src="img/Screen Shot 2022-07-23 at 5.33.30 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>In this level, we should put the hosts on the same network by providing the same Net-ID while respecting the IP adress range.</li>
</ul>

</details>
<details open>
<summary>Level 9</summary>
<br>
<img src="img/Screen Shot 2022-07-23 at 5.33.30 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>In this level, we should put the hosts on the same network by providing the same Net-ID while respecting the IP adress range.</li>
</ul>

</details>

<details open>
<summary>Level 10</summary>
<br>
<img src="img/Screen Shot 2022-07-23 at 5.33.30 PM.png" alt="Markdown Monster icon"></img>
<br>
<ul>
<li>In this level, we should put the hosts on the same network by providing the same Net-ID while respecting the IP adress range.</li>
</ul>


<h1>Wireshark Tcp/Http log analysis</h1>

<h2>Description</h2>
In a fictional scenario where I serve as a Security Analyst for a prominent travel agency, I encountered a critical incident that required immediate attention and mitigation. The company's web server, crucial for advertising sales and promotions, faced a disruptive attack, resulting in a service outage. In this project, I conducted a comprehensive network analysis using Wireshark and tcpdump to gain insights into communication patterns, identify anomalies, and troubleshoot potential issues. The project highlights my proficiency in network protocol analysis and troubleshooting skill
<br />

<h2>Environments Used </h2>

- <b>Wireshark</b>

<h2>Key aspects</h2>

- <b>Packet Capture:</b>
Utilized Wireshark and tcpdump to capture network traffic during specific scenarios or incidents.
Focused on capturing packets related to specific protocols, services, or devices to narrow down the analysis.
- <b>Protocol Analysis:</b>
Analyzed individual packets to understand the communication protocols and data flow within the network.
Identified patterns, irregularities, or unexpected behaviors in the network traffic.



<h2>Documentation:</h2>

<p align="center">
Launch the utility: <br/>

<img src="https://i.imgur.com/5luDGgP.png" height="80%" width="80%" alt="Sample Image"/>
<img src="https://imgur.com/V6YTJTv.png" height="80%" width="80%" alt="Sample Image"/>
<img src="https://imgur.com/dRgmaTV.png" height="80%" width="80%" alt="Sample Image"/>
<img src="https://imgur.com/9cwqHTK.png" height="80%" width="80%" alt="Sample Image"/>
<img src="https://imgur.com/sP6hh3B.png" height="80%" width="80%" alt="Sample Image"/>
<img src="https://imgur.com/UkeuenZ.png" height="80%" width="80%" alt="Sample Image"/>

One potential explanation for the website’s connection timeout error message is
a DoS attack. The logs show that the web server stops responding after it is
overloaded with SYN packet requests. This event could be a type of DoS attack
called SYN flooding.
The logs indicate that the web server has become overwhelmed and is unable
to process the visitors’ SYN requests. The server is unable to open a new
connection to new visitors who receive a connection timeout message.
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

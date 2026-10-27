# Packet Tracer: The Client Interaction

## Project Overview
This lab explores how a client computer requests a web page from a server using DNS and HTTP. Cisco Packet Tracer Simulation Mode is used to observe the exchange of network messages and inspect Protocol Data Units (PDUs).

## Objectives
- Observe client-server communication.
- Understand DNS name resolution.
- Examine HTTP requests and responses.
- Observe the sequence of events involved in loading a web page.
- Inspect PDU information using the OSI Model and Simulation Mode.

## Tools and Technologies
- Cisco Packet Tracer
- DNS (Domain Name System)
- HTTP (Hypertext Transfer Protocol)
- TCP (Transmission Control Protocol)
- Client-server architecture
- OSI model and PDU analysis

## Network Scenario
A PC is connected directly to a simulated server configured to provide DNS resolution and host a web page through HTTP.

The client requests the website `www.example.com` using the simulated web browser.

## Tasks Performed
1. Switched Packet Tracer to Simulation Mode.
2. Configured Event List Filters to display DNS and HTTP events.
3. Requested `www.example.com` from the simulated PC browser.
4. Ran the simulation to observe the client-server exchange.
5. Inspected event details in the PDU Information window.
6. Examined inbound and outbound protocol layers and their descriptions.

## Communication Process

### 1. DNS Query
The PC sends a DNS query asking the server to resolve `www.example.com` to an IP address.

### 2. DNS Response
The DNS server returns the IP address associated with the requested hostname.

### 3. HTTP Request
The PC uses the resolved address to request the web page from the server.

### 4. HTTP Response
The server returns the requested web content. The transfer may involve multiple TCP segments.

### 5. Acknowledgment
TCP acknowledgments help confirm receipt of transmitted data and support reliable delivery.

## Key Findings
- DNS translates hostnames into IP addresses.
- HTTP enables clients to request web resources from servers.
- TCP provides reliable, ordered data delivery for HTTP over TCP.
- Simulation Mode helps visualize the sequence of network events.
- PDU inspection reveals how protocols operate at different OSI layers.

## Skills Demonstrated
- DNS resolution analysis
- HTTP client-server communication
- TCP fundamentals
- Packet and PDU inspection
- OSI model analysis
- Cisco Packet Tracer Simulation Mode

## Conclusion
This lab demonstrates the basic process of accessing a web page over a network. It shows how DNS resolution precedes the HTTP request and how TCP supports reliable delivery of web content.

## Disclaimer
This is a simulated networking exercise completed in Cisco Packet Tracer for educational and portfolio purposes.

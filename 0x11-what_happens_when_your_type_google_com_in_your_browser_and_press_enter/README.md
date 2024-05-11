# What Happens When You Type https://www.google.com in Your Browser?

This document explains the step-by-step process that occurs behind the scenes when you type `https://www.google.com` in your web browser and press Enter.

## 1. DNS Request

When you type `https://www.google.com`, your browser initiates a DNS (Domain Name System) lookup to resolve the domain name `www.google.com` to its corresponding IP address (`172.217.3.100`).

## 2. TCP/IP

Once the IP address is resolved, your browser establishes a TCP (Transmission Control Protocol) connection with the server at the IP address. This connection ensures reliable and ordered delivery of data packets.

## 3. Firewall

The request may pass through a firewall, a network security system that monitors and controls incoming and outgoing network traffic based on predefined security rules.

## 4. HTTPS/SSL

If using `https://`, your browser and the server negotiate an encrypted SSL/TLS (Secure Sockets Layer/Transport Layer Security) connection, ensuring secure communication between your browser and Google's servers.

## 5. Load-Balancer

Incoming traffic is distributed across multiple servers using load balancers, optimizing server resources and improving responsiveness and availability of websites.

## 6. Web Server

The request is received by Google's web server (e.g., Apache or Nginx), which processes the HTTP request, retrieves the requested webpage (e.g., Google's homepage), and serves any associated assets (images, stylesheets, scripts).

## 7. Application Server

In more complex web applications like Google Search, backend application servers process requests, execute algorithms (e.g., search algorithms), and interact with databases.

## 8. Database

Web applications often interact with databases to serve dynamic content. For example, Google's search query might involve fetching results from massive databases that index and retrieve relevant web pages.

Understanding this process is fundamental for anyone working with web technologies, including developers, network engineers, and system administrators.

---

# 01. How the Internet Works

## 1. What Is the Internet?

The Internet is a worldwide network that connects millions of computers, servers, mobile phones, and other devices.

It allows these devices to communicate and exchange information.

**In simple words:**

The Internet connects devices around the world so they can share information.

### Real-World Example

Imagine you are sitting in India and your friend is sitting in the United States.

You send your friend a message through WhatsApp.

- Your phone sends the message.
- The message travels through the internet.
- WhatsApp's servers help deliver the message.
- Your friend's phone receives it.

Both devices communicate even though they are in different countries.

That is one example of how the internet works.

---

## 2. What Is a Network?

A network is a group of connected devices that can communicate and share information.

These devices can include:

- Computers
- Mobile phones
- Servers
- Printers
- Routers

### Example

Imagine you have three computers connected to the same Wi-Fi network.

They can communicate with each other and share resources.

This is called a network.

### Types of Networks

**1. LAN (Local Area Network)**

A network that connects devices within a small geographical area.

Examples:
- Home Wi-Fi
- College computer laboratory
- Office network

**2. WAN (Wide Area Network)**

A network that connects devices or smaller networks across large geographical areas.

Examples:
- Networks connecting offices in different countries.
- The Internet is the largest example of an interconnected global network.

---

## 3. How Are Devices Connected to the Internet?

To access the internet, devices need a connection through an Internet Service Provider (ISP).

An ISP is a company that provides internet access.

Examples:
- Jio
- Airtel
- ACT Fibernet
- BSNL

### How It Works

1. You connect your mobile phone or laptop to Wi-Fi.
2. Your Wi-Fi router connects to your ISP.
3. Your ISP provides access to the internet.
4. Your device can now communicate with other internet-connected devices.

### Basic Architecture

```text
       YOUR LAPTOP
            |
            |
         WI-FI
            |
            |
       WI-FI ROUTER
            |
            |
           ISP
            |
            |
         INTERNET
            |
            |
      GOOGLE SERVER
```

This is a simplified representation of an internet connection.

---

## 4. What Is an IP Address?

IP stands for Internet Protocol.

An IP address is a numerical address used to identify a device or network interface on an IP network.

Think of it like a postal address.

A postal address helps deliver a letter to the correct location.

Similarly, an IP address helps network traffic reach the intended destination.

### Example

An IPv4 address looks like this:

```text
192.168.1.10
```

Another example:

```text
8.8.8.8
```

The address `8.8.8.8` is Google's public DNS resolver.

### Types of IP Addresses

**1. IPv4**

Uses 32-bit addresses.

Example:

```text
192.168.1.10
```

**2. IPv6**

Uses 128-bit addresses.

Example:

```text
2001:4860:4860::8888
```

IPv6 provides a much larger address space than IPv4.

---

## 5. What Is a Server?

A server is a computer or software application that provides services or resources to other computers and applications.

Servers can:

- Store website files.
- Process user requests.
- Store application data.
- Handle login operations.
- Provide APIs.
- Process business logic.

### Example

Imagine you open an online shopping website.

1. Your browser requests the homepage.
2. The server receives the request.
3. The server processes it.
4. The server sends the required information.
5. Your browser displays the homepage.

A server is not necessarily a special type of computer. Ordinary computers can also run server software.

---

## 6. What Is a Client?

A client is an application or device that requests services or information from a server.

Examples:

- Google Chrome
- Firefox
- Mobile applications
- Desktop applications

### Example

When you open YouTube:

- Your browser acts as a client.
- YouTube's servers provide the requested content.

The client requests information, and the server responds.

---

## 7. How Does the Internet Work?

Let's understand what happens when you visit a website.

Imagine you type:

```text
https://www.google.com
```

The following is a simplified explanation of what happens:

**Step 1: You enter a website address.**

You type `www.google.com` into your browser.

**Step 2: Your browser needs the server's IP address.**

It uses DNS to find the IP address associated with the domain name.

**Step 3: Your device establishes a connection.**

Your device communicates with the destination server using network protocols.

For HTTPS, a secure connection is established using TLS.

**Step 4: Your browser sends an HTTP request.**

The browser requests the webpage from the server.

**Step 5: The server processes the request.**

The server handles the request and prepares the appropriate response.

**Step 6: The server sends a response.**

The server sends information back to your browser.

**Step 7: Your browser displays the webpage.**

The browser processes the received HTML, CSS, JavaScript, and other resources to display the website.

### Simplified Architecture

```text
       USER
        |
        v
     BROWSER
        |
        v
    DNS LOOKUP
        |
        v
  SERVER IP ADDRESS
        |
        v
 CONNECTION TO SERVER
        |
        v
   HTTP REQUEST
        |
        v
      SERVER
        |
        v
   HTTP RESPONSE
        |
        v
     BROWSER
        |
        v
   WEBSITE DISPLAYED
```

We will study DNS, HTTP, HTTPS, TCP, and the request-response cycle in separate lessons.

---

## 8. Important Terms

| Term | Meaning |
|---|---|
| Internet | Worldwide network connecting devices |
| Network | Group of connected devices |
| LAN | Local Area Network |
| WAN | Wide Area Network |
| ISP | Company providing internet access |
| IP Address | Address used to identify a network interface |
| Server | Provides services and resources |
| Client | Requests services and resources |
| Router | Forwards network traffic between networks |
| DNS | Translates domain names into IP addresses |
| HTTP | Protocol used for web communication |
| HTTPS | HTTP communication protected using TLS |

---

## 9. Key Takeaways

1. The internet is a worldwide network of connected devices.
2. Networks allow devices to communicate.
3. ISPs provide internet access.
4. IP addresses help identify network interfaces.
5. Servers provide services and resources.
6. Clients request information from servers.
7. DNS helps find the IP address associated with a domain name.
8. HTTP and HTTPS are used for web communication.
9. Browsers send requests and receive responses from servers.

---

## 10. Practice Questions

Try answering these questions without looking at the notes.

1. What is the Internet?
2. What is a computer network?
3. What is the difference between LAN and WAN?
4. What is an ISP? Give two examples.
5. What is an IP address?
6. What is the difference between IPv4 and IPv6?
7. What is a server?
8. What is a client?
9. What happens when you enter `www.google.com` in your browser?
10. How does your laptop connect to the internet?

### Practical Thinking Exercise

Imagine you open YouTube on your laptop.

Explain the following:

1. How does your laptop connect to the internet?
2. What role does your ISP play?
3. Why does your browser need the server's IP address?
4. What does the YouTube server do?
5. How does the video information reach your laptop?


# Networking Basics — Module 2

## Hosts
All computers connected to a network that participate
directly in network communication are classified as hosts.

---

## Servers
Hosts that have software installed to provide information
to other hosts on the network.

- Examples of services: email, web pages, file sharing
- Each service requires its own separate server software
- Every website you visit is hosted on a server connected
  to the global internet

| Server Type | What it provides |
|---|---|
| Web Server | Web pages |
| Email Server | Email services |
| File Server | File storage and sharing |
| DNS Server | Domain name resolution |

---

## Clients
Computer hosts that have software installed to request
and display information obtained from servers.

Examples of client software:
- Google Chrome
- Mozilla Firefox
- Safari
- Internet Explorer

---

## Peer to Peer Networks (P2P)
A network where devices communicate directly with each
other without a dedicated server.

- Simplest form: two directly connected computers
- Connection can be wired or wireless
- Each device acts as both client and server simultaneously

### Advantages
- Easy to set up
- Less expensive
- Simple for small networks

### Disadvantages
- Less secure than client-server networks
- Hard to manage at large scale
- No centralized control

---

## Network Infrastructure
The path a message takes from source to destination can be
as simple as a single cable or as complex as a global network.
The network infrastructure is the platform that supports
all communication providing a stable and reliable channel.

### Three Categories of Hardware Components

| Category | Description |
|---|---|
| End Devices | Interface between users and the network |
| Intermediate Devices | Connect and manage network traffic |
| Network Media | Physical path data travels through |

---

## End Devices (Hosts)
The most familiar network devices — they form the interface
between users and the communication network.

Examples of end devices:
- Computers (workstations, laptops, file servers, web servers)
- Network printers
- Telephones and teleconferencing equipment
- Security cameras
- Mobile devices (smartphones, tablets, PDAs, barcode scanners)

> 💡 Each end device has a unique address so the network
> knows exactly where to send and receive messages

---

## ISP (Internet Service Provider)
Provides the link between your home network and the internet.

Types of ISPs:
- Local cable provider
- Landline telephone service provider
- Cellular network provider
- Independent provider leasing bandwidth from another company

---

## Cable and DSL Connections

### Cable
- Offered by cable television providers
- Internet data travels on the same coaxial cable as TV
- High bandwidth, always on connection
- Uses a special cable modem to separate internet signal
  from TV signal
- Provides Ethernet connection to host or LAN

### DSL (Digital Subscriber Line)
- High bandwidth, always on connection
- Runs over existing telephone line
- Line is split into three channels:
  - Channel 1: Voice telephone calls
  - Channel 2: Download data
  - Channel 3: Upload data
- Requires special high-speed modem

| | Cable | DSL |
|---|---|---|
| **Medium** | Coaxial cable | Telephone line |
| **Speed** | Generally faster | Slightly slower |
| **Availability** | Urban areas | Wider coverage |
| **Always on** | ✅ Yes | ✅ Yes |

---

## Other Connectivity Options

### Cellular
- Uses mobile network towers
- Available anywhere with cell coverage
- Speed depends on network generation (4G, 5G)

### Satellite
- Uses satellites orbiting earth
- Available in remote areas
- Higher latency than cable or DSL

### Dial-Up
- Uses standard telephone line
- Very slow — mostly obsolete today
- Still used in some very remote areas

---

## Key Difference: Server vs Client

| | Server | Client |
|---|---|---|
| **Role** | Provides information | Requests information |
| **Software** | Server software | Browser or app |
| **Example** | Web server | Chrome browser |

---

## My Questions
- What happens if a server goes down?
- How do attackers target web servers specifically?
- Can a computer be both a server and a client?
- How do ISPs protect against attacks on their infrastructure?
- Why is satellite connection more vulnerable than wired?# Networking Basics — Module 2

## Hosts
All computers connected to a network that participate
directly in network communication are classified as hosts.

---

## Servers
Hosts that have software installed to provide information
to other hosts on the network.

- Examples of services: email, web pages, file sharing
- Each service requires its own separate server software
- Every website you visit is hosted on a server connected
  to the global internet

| Server Type | What it provides |
|---|---|
| Web Server | Web pages |
| Email Server | Email services |
| File Server | File storage and sharing |
| DNS Server | Domain name resolution |

> 💡 Cybersecurity relevance: Servers are the most common
> targets for attackers because they store and provide
> valuable data to many users simultaneously

---

## Clients
Computer hosts that have software installed to request
and display information obtained from servers.

Examples of client software:
- Google Chrome
- Mozilla Firefox
- Safari
- Internet Explorer

> 💡 Cybersecurity relevance: Client software like browsers
> are common attack vectors through malicious websites,
> phishing links, and drive-by downloads

---

## Peer to Peer Networks (P2P)
A network where devices communicate directly with each
other without a dedicated server.

- Simplest form: two directly connected computers
- Connection can be wired or wireless
- Each device acts as both client and server simultaneously

### Advantages
- Easy to set up
- Less expensive
- Simple for small networks

### Disadvantages
- Less secure than client-server networks
- Hard to manage at large scale
- No centralized control

> 💡 Cybersecurity relevance: P2P networks are harder to
> monitor and secure, making them common targets for
> malware distribution and unauthorized file sharing

---

## Network Infrastructure
The path a message takes from source to destination can be
as simple as a single cable or as complex as a global network.
The network infrastructure is the platform that supports
all communication providing a stable and reliable channel.

### Three Categories of Hardware Components

| Category | Description |
|---|---|
| End Devices | Interface between users and the network |
| Intermediate Devices | Connect and manage network traffic |
| Network Media | Physical path data travels through |

---

## End Devices (Hosts)
The most familiar network devices — they form the interface
between users and the communication network.

Examples of end devices:
- Computers (workstations, laptops, file servers, web servers)
- Network printers
- Telephones and teleconferencing equipment
- Security cameras
- Mobile devices (smartphones, tablets, PDAs, barcode scanners)

> 💡 Each end device has a unique address so the network
> knows exactly where to send and receive messages

> 💡 Cybersecurity relevance: Every end device is a
> potential entry point for attackers — this is why
> endpoint security is a critical field in cybersecurity

---

## ISP (Internet Service Provider)
Provides the link between your home network and the internet.

Types of ISPs:
- Local cable provider
- Landline telephone service provider
- Cellular network provider
- Independent provider leasing bandwidth from another company

> 💡 Cybersecurity relevance: ISPs can monitor traffic
> passing through their infrastructure — understanding
> this is important for privacy and security

---

## Cable and DSL Connections

### Cable
- Offered by cable television providers
- Internet data travels on the same coaxial cable as TV
- High bandwidth, always on connection
- Uses a special cable modem to separate internet signal
  from TV signal
- Provides Ethernet connection to host or LAN

### DSL (Digital Subscriber Line)
- High bandwidth, always on connection
- Runs over existing telephone line
- Line is split into three channels:
  - Channel 1: Voice telephone calls
  - Channel 2: Download data
  - Channel 3: Upload data
- Requires special high-speed modem

| | Cable | DSL |
|---|---|---|
| **Medium** | Coaxial cable | Telephone line |
| **Speed** | Generally faster | Slightly slower |
| **Availability** | Urban areas | Wider coverage |
| **Always on** | ✅ Yes | ✅ Yes |

---

## Other Connectivity Options

### Cellular
- Uses mobile network towers
- Available anywhere with cell coverage
- Speed depends on network generation (4G, 5G)

### Satellite
- Uses satellites orbiting earth
- Available in remote areas
- Higher latency than cable or DSL

### Dial-Up
- Uses standard telephone line
- Very slow — mostly obsolete today
- Still used in some very remote areas

> 💡 Cybersecurity relevance: Connection type affects
> security — public cellular and satellite connections
> are more vulnerable to interception than wired connections

---

## Key Difference: Server vs Client

| | Server | Client |
|---|---|---|
| **Role** | Provides information | Requests information |
| **Software** | Server software | Browser or app |
| **Example** | Web server | Chrome browser |
| **Target for attacks?** | High value target | Common entry point |

---

## My Questions
- What happens if a server goes down?
- How do attackers target web servers specifically?
- Can a computer be both a server and a client?
- How do ISPs protect against attacks on their infrastructure?
- Why is satellite connection more vulnerable than wired?

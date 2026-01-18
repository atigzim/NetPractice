# NetPractice
*This project has been created as part of the 42 curriculum by atigzim.*

## Description

This project is a networking training interface created as part of the 42 curriculum.  
Its goal is to help students understand fundamental networking concepts such as IP addressing, subnetting, routing, and OSI layers through progressive levels.

NetPractice provides an interactive learning environment where students solve real-world networking problems by configuring IP addresses, subnet masks, and routing tables.

Each of the 10 levels increases in complexity, challenging students to apply their knowledge of network segmentation, address allocation, and packet routing to build functional network topologies.

Through hands-on practice, students gain practical experience in designing networks that are efficient, scalable, and properly segmented.  
The project emphasizes understanding how devices communicate across networks, how routers forward packets between different network segments, and how proper IP addressing schemes enable network organization and security.

## Instructions

### Running the Training Interface

1. Open the `index.html` file in a modern web browser  
   (Chrome, Firefox, Safari, or Edge recommended).
2. The interface will load with **Level 1** by default.
3. Navigate between levels using the level selector.
4. Configure the network by filling in:
   - IP addresses
   - Subnet masks
   - Routing information
5. Click the **Check** button to verify your configuration.
6. If successful, proceed to the next level.

### Exporting Configurations

1. Complete each level by correctly configuring all network parameters.
2. Once a level is validated, click the **Export** button.
3. The configuration will be saved as a JSON file  
   (example: `level1.json`).
4. Save each exported file with its corresponding level number.

### Submission Requirements

- All **10 exported configuration files** (`level1.json` through `level10.json`)
  must be placed at the **root of the Git repository**.
- This `README.md` file must be included.
- The complete NetPractice training interface files must be included.

⚠️ **Important**  
Do not modify the exported configuration files manually.  
They must be generated directly from the training interface to ensure validity.

## Resources

### Learning Materials

- **Wikipedia – Computer network**  
  https://en.wikipedia.org/wiki/Computer_network
- **GeeksforGeeks – Introduction to Subnetting**  
  https://www.geeksforgeeks.org/computer-networks/introduction-to-subnetting/ :contentReference[oaicite:0]{index=0}
- **YouTube – NetPractice / Networking Concepts Playlist**  
  https://www.youtube.com/watch?v=uG4v5ws5ioY&list=PL8s4OGp06498kNuy0Sduw93gqNg-XD1_H&index=8

### Key Networking Concepts Studied

#### IP Addressing and Subnetting
- IPv4 address structure and classes (A, B, C)
- Network ID and Host ID
- Subnet masks and network segmentation
- CIDR (Classless Inter-Domain Routing)
- Usable host range calculation
- Public vs private IP address ranges

#### TCP/IP Protocol Suite
- TCP (Transmission Control Protocol)
- UDP (User Datagram Protocol)
- IP (Internet Protocol)

#### Subnet Masks
- Binary representation of subnet masks
- Network vs host portion separation
- Default subnet masks
- Network address, broadcast address, valid hosts

#### Default Gateway
- Gateway role in inter-network communication
- Routing traffic outside the local subnet
- Correct gateway configuration

#### Routers and Switches
- Routers (Layer 3 – Network Layer)
- Switches (Layer 2 – Data Link Layer)
- Broadcast domains and collision domains
- Network segmentation for performance and security

#### OSI Model Layers
- Layer 1: Physical
- Layer 2: Data Link
- Layer 3: Network
- Layer 4: Transport
- Layer 5: Session
- Layer 6: Presentation
- Layer 7: Application

#### Routing Concepts
- Routing table structure
- Static vs dynamic routing
- Longest prefix match
- Multi-router communication
- Network topology optimization

#### Advanced Networking Concepts
- VLSM (Variable Length Subnet Masking)
- NAT (Network Address Translation)
- Supernetting and aggregation
- Network troubleshooting
- Packet flow analysis

## Use of AI in This Project

AI assistance (Claude) was used for:
- Generating this comprehensive `README.md`
- Explaining complex networking concepts
- Organizing documentation and resources
- Improving clarity and structure

AI was **NOT** used for:
- Solving NetPractice levels
- Generating exported configuration files
- Calculating IP addresses or subnet masks
- Completing routing configurations

All practical work was completed manually to ensure a solid understanding of networking fundamentals.

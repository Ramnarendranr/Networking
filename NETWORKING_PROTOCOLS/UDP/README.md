# UDP

- User Datagram Protocol (UDP).
- Ideal for time-sensitive transmissions (e.g., video playback, DNS lookups).
- Speeds up communication by not establishing a formal connection before data transfer.
- Allows very quick data transmission.
- Can result in lost packets during transit.
- May create opportunities for exploitation, such as DDoS attacks.

# How does UDP protocol works?

- Standardized method for transferring data between two computers in a network.
- Sends packets (units of data transmission) directly to the target computer.
- Does not establish a connection before sending packets.
- Does not indicate the order of packets.
- Does not check whether packets arrived as intended.
- UDP packets are referred to as 'datagrams'.

## What is UDP used for?

- **Time-sensitive communications:**
    - **Voice and video traffic: VoIP (Voice over IP)** and video streaming are time-sensitive and designed to handle some  packet loss, making UDP ideal.
        *Example: Internet-based telephone services use UDP to prioritize timely delivery over perfect accuracy, resulting in minor static rather than significant delays.*
- **Online gaming:** Games require fast, real-time communication, where occasional packet loss is less critical than latency.
    
- **DNS servers:** DNS queries and responses are fast and efficient with UDP, allowing quick resolution of domain names.

## How is UDP used in DDoS attacks?

**Exploitation for malicious purposes:**
    - No handshake requirement: UDP does not require a handshake, enabling attackers to flood a server with traffic without permission.

**UDP flood attacks:**
    - Attackers send a large number of UDP datagrams to random ports on the target computer.
    - The target must respond with ICMP packets indicating those ports are unreachable.
    - This response effort can exhaust the target's computing resources, resulting in a denial-of-service to legitimate traffic.

**Defense against UDP flood attacks:**
    - Limit ICMP response rate: Reduces the impact of fraudulent requests but may also filter out legitimate traffic.
    - Intermediary network: Use a distributed network of data centers to receive and respond to UDP traffic, preventing any single server from being overwhelmed.
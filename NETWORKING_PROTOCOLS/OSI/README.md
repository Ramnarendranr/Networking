# OSI model

- The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network.
- Adopted by all major computer and telecommunication companies in the early 1980s.
- The modern Internet uses the simpler TCP/IP model.
- OSI model is still widely used to visualize and communicate how networks operate.
- Helps in isolating and troubleshooting networking problems.

## 7 Layers:

1. Application Layer
2. Presentation Layer
3. Session Layer
4. Transport Layer
5. Network Layer
6. Data Link Layer
7. Physical layer


## OSI Layers (Top-Down Description)

1. **Application Layer (Layer 7)**

- Used by end-user software such as web browsers and email clients.
- Provides protocols for sending and receiving information.
- Examples: HTTP, FTP, POP, SMTP, DNS.

2. **Presentation Layer (Layer 6)**

- Prepares data for the application layer.
- Defines encoding, encryption, and compression of data.
- Prepares data for transmission over the session layer.

3. **Session Layer (Layer 5)**

- Creates communication channels (sessions) between devices.
- Manages opening, maintaining, and closing of sessions.
- Can set checkpoints to resume data transfer if interrupted.

4. **Transport Layer (Layer 4)**

- Breaks data into segments on the transmitting end.
- Reassembles segments on the receiving end.
- Manages flow control and error control.

5. **Network Layer (Layer 3)**

- Breaks up segments into network packets.
- Routes packets by discovering the best path across a network.
- Uses network addresses (e.g., IP addresses) for routing.

6. **Data Link Layer (Layer 2)**

- Establishes and terminates connections between physically connected nodes.
- Breaks up packets into frames and sends them from source to destination.
- Composed of LLC (Logical Link Control) and MAC (Media Access Control).

7. **Physical Layer (Layer 1)**

- Responsible for the physical connection between network nodes.
- Defines connectors, electrical cables, or wireless technology.
- Manages transmission of raw data as a series of 0s and 1s.

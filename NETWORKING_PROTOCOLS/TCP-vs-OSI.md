# Comparing TCP and OSI

## TCP/IP vs. OSI Model

**TCP/IP Model**

   **Origins:**
   
        Created by the US Department of Defense (DoD).
        Older than the OSI model.
   
   **Layer Structure:**
        
        Application Layer: Combines OSI layers 5 (Session), 6 (Presentation), and 7 (Application).
        Network Access Layer: Combines OSI layers 1 (Physical) and 2 (Data Link). Note that TCP/IP leaves sequencing and acknowledgement functions to the transport layer.
        Other Layers:
            Internet Layer (corresponds to OSI Network Layer 3).
            Transport Layer (corresponds to OSI Transport Layer 4).


**OSI Model**

   **Origins:**
        
        Introduced by representatives of major computer and telecom companies in 1983.
        Adopted by ISO as an international standard in 1984.
   
   **Layer Structure:**
        
        7 Layers: Physical (1), Data Link (2), Network (3), Transport (4), Session (5), Presentation (6), and Application (7).


## Key Differences

**Purpose:**

    TCP/IP: Functional model designed to solve specific communication problems based on standard protocols.
  
    OSI: Generic, protocol-independent model intended to describe all forms of network communication.

**Complexity:**
  
    TCP/IP: Simpler, collapsing several OSI layers into single layers.
  
    OSI: More complex, with distinct layers for different functions.

**Layer Utilization:**
  
    TCP/IP: Most applications use all layers.
  
    OSI: Simple applications may not use all seven layers; only layers 1, 2, and 3 are mandatory for any data communication.

**Responsibility for Functions:**
  
    TCP/IP: Does not take responsibility for sequencing and acknowledgement functions, leaving these to the underlying transport layer.
  
    OSI: Each layer has specific responsibilities, including sequencing and acknowledgement in the appropriate layers.


## Summary

### TCP/IP:

   - Older, simpler, and functional.
   - Combines several OSI layers into one.
   - Designed to solve specific communication problems.
   - Uses standard protocols.
   - Most applications use all layers.

### OSI:

   - Introduced later as a standard model.
   - More complex with seven distinct layers.
   - Protocol-independent and generic.
   - Designed to describe all network communication forms.
   - Simple applications may not use all layers; layers 1, 2, and 3 are essential for communication.

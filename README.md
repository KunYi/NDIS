Windows Kernel Driver - Create a driver device in intermediate layer of Windows kernel based on NDIS, 
which communicates with and connect upper layer (user mode applications) and lower layer (miniport driver/network card).
Create self-defined protocols for transmitting data and control communications by simulating very simple HTTP, TCP and ARP protocols. 
Try best to implement connection establishing mechanism and retry sending mechanism following TCP’s specification in order to achieve stable data transmission.
So it can walk around system TCP protocol layer and firewall to capture and send custom data packets.
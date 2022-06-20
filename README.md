# Network-Monitoring-Capture-The-Generated-Network-Traffic-Using-TCPDUMP

Download a web image with a maximum size of 3MB over HTTP (not HTTPS) using wget. Capture the generated network traffic using tcpdump; after capturing, run the packet trace through a filter to create a new file that contains only the TCP connection corresponding to the HTTP interaction; submit the new file with the coursework for this task. If you are not able to use an HTTP site, you may use a your pcap trace from step 1 and apply a tcpdump filter, then submit the resulting packet trace.

For the resulting packet trace, perform the analysis tasks below:
•	Describe the procedure to collect the packet trace, filter the TCP connection in the trace, and verify that the TCP connection is complete
•	Describe the timeline of events within the connection (TCP initiation, HTTP GET request, TCP closing) using clear references to timestamps 
•	Calculate RTT (provide three samples using SEQ/ACK matching from the TCP connection establishment, GET request, and TCP connection closing
•	Estimate bottleneck bandwidth (provide at least one sample using interarrival times) 


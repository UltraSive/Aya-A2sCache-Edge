# Aya-A2sCache-Edge
A user space program will update the common BPF map with the newest A2s query results to deliver as responses on the edge. The eBPF program will use the map to compare destination IP:Port and if a query is valid otherwise to drop, if it passes scrubbing checks it will be responses with the value in the map.

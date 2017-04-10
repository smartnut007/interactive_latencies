# Memory Hierarchy Latencies
* L1 (1 ns) < Memory < SSD < Disk (1 ms). 
* Each level in the hierarchy is ~100x slower than previous 

# CPU cost
* Mutex Lock ~10ns
* Branch Mispredict ~3ns

# Sequential Data
* Sequential 1MB read from memory ~ 6us
* Compress 1MB with zippy ~2 ms
* Sequential 1MB read from disk   ~ 1ms

# Network Latencies
* Same datacenter latency < 1 ms
* US to India Roundtrip latency = 300 ms

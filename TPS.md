### TPS Competition Questionnaire

*Please replace the square brackets and the text in it with your answers*

**Number of CPUs**

64

**Memory (GB)**

369 G

**Storage (GB)**

200 G

**Network**

[Comment on the network connecting clusters. For example, 1 Gbps LAN]

**Machine Type (Optional)**

[If you are using public cloud service, note down the name of the provider and the machine type. For example, AWS EC2 m5.2xlarge.]

**Command Lines for Running Cluster**
```
[Copy the command line here]
```

**Peak TPS**

[Note down the highest TPS observed.]

**Video URL**

[URL for the video showing how you produced the above TPS.]

**Output From `stats` Tool**
```
----------------------------------------------------------------------------------------------------
                                      QuarkChain Cluster Stats
----------------------------------------------------------------------------------------------------
CPU:                64
Memory:             369 GB
IP:                 localhost
Shards:             512
Servers:            64
Shard Interval:     10
Root Interval:      60
Syncing:            False
Mining:             True
Peers:              172.31.39.89:38291, 172.31.43.126:38291
----------------------------------------------------------------------------------------------------
Timestamp                     TPS   Pending tx  Confirmed tx       BPS      SBPS      ROOT       CPU
----------------------------------------------------------------------------------------------------
2018-10-23 23:41:40          0.00            0             0     50.85      0.00         1     65.90
2018-10-23 23:41:50          0.00            0             0     50.85      0.00         1     64.85
2018-10-23 23:42:00          0.00            0             0     50.85      0.00         1     66.07
2018-10-23 23:42:11       2215.20       200760        132912     47.15      0.00         1     58.09
2018-10-23 23:42:21       4241.07       427192        254464     42.20      0.00         2     66.40
2018-10-23 23:42:31       4932.32       504477        295939     39.82      0.00         2     65.62
2018-10-23 23:42:41       5908.13       548280        354488     36.73      0.00         2     66.05
2018-10-23 23:42:51       7433.77       637942        446026     31.82      0.00         2     66.71
2018-10-23 23:43:01       4847.15       476003        288557     27.15      0.00         1     65.06
2018-10-23 23:43:11       3464.93       318312        207896     25.35      0.00         1     65.85
2018-10-23 23:43:21        577.47        46872         34648     20.67      0.00         1     68.71
2018-10-23 23:43:31          0.00         1200             0     19.62      0.00         1     64.99
```

**Additional Comment**

[If you have special setup, e.g., running a single cluster over multiple machines, the above questionnaire might not fit. Note down
whatever you want us to know here to help evaluate the result.]

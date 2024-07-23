# Network-Activity-Anomaly-Detection
Build a model to predict whether a network a network is experiencing "normal" activity or "neptune" activity

The dataset contains detailed records of network activities, capturing various attributes associated with network connections. Each record is labeled to indicate whether the activity is normal or a "Neptune" attack, providing a foundation for binomial classification.

A Neptune attack, also known as a SYN flood attack, is a type of denial-of-service (DoS) attack where an attacker overwhelms a target system with a high number of SYN requests, causing the system to become unresponsive to legitimate traffic. It exploits the TCP handshake process to consume resources on the target machine.

The training set contains 86,845 rows, including whether the activity (column - Attack) is normal or not. Use this to train a Machine Learning model, then predict whether the 21,712 entries in the test set have a normal activity or not (Neptune).

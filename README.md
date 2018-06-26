# Simple_IDS_using_RYU_SDN_controller_and_Machine_Learning
Implemented a network intrusion detection system for a software defined network using Random Forest method for classification of port and flow statistics.

Project Execution:


1. Create a mininet topology.
2. ssh to the mininet virtual machine.
3. Run the collectStats.py file on the ryu controller.
(Data from collectStat.py file is used for training the algorithm.)
4. Now, run IDS_RyuApp.py to check whether current traffic is clean or malacious using machine learning algorithm.

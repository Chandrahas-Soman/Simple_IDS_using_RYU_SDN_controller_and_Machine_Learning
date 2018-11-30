# Simple_IDS_using_RYU_SDN_controller_and_Machine_Learning
Implemented a network intrusion detection system for a software defined network using Random Forest method for classification of port and flow statistics.

Project Execution:

1. Run collectstats.py on the controller.
2. Then create a mininet custom topology.
3. (While collecting normal traffic label the data 0.)
4. Run some simple commands. So that you will be able to generate the clean data.
5. Stop the controller.
6. Change the collectstats.py file. Label the data as 1.
7. Start the controller and run collectstats.py file.
8. Create topology.
9. Run hping flood command to capture malicious data.
10. Now stop the controller.
11. Run ryuapplication.py on the controller.
12. Create a topology.
13. Test the model on the new traffic.

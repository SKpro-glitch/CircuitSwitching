# CircuitSwitching

**PROJECT DETAILS**
</br>**Authors**        :   Soham Kapur, Koushiki Sinha
</br>**Year**           :   2023
</br>**Title**          :   Circuit Switching using Dynamic Programming
</br>**Purpose**        :   Undergraduate Graded Project
</br>**Course**         :   Computer Networks
</br></br>
**Problem Statement:** </br>Simulation of Circuit Switching in Java to find optimal set of paths for multiple data transfers using Dynamic Programming.
</br></br>
**Description:** </br>
- The program begins with a graph represented by an adjacency matrix with edge weights.
- Pairs of Source-Destination nodes are taken as input.
- It iterates all possible paths between the required source and destination nodes.
- The combinations of paths between each source-destination pair are compared to find the one with least maximum time.
</br></br>
Steps to improve efficiency: </br>
- The  incoming edges of source nodes and outgoing edges of destination nodes are omitted.
- If a direct edge to a destination node is found, all other paths to that node are ignored.

# Drug-Similarity-Network

This is for the paper: Sun, Yahui, et al. "A physarum-inspired prize-collecting steiner tree approach to identify subnetworks for drug repositioning." BMC systems biology 10.5 (2016): 128.

This repository contains 18 Drug Similarity Networks.

In each DSN, there are some vertices and edges. Part of the vertices are terminals. Each vertex is associated with a weight, and each edge is associated with a cost.

Note that, the initial vertex prizes and edge costs calculated using the equations in "A Physarum-inspired Prize-Collecting Steiner Tree approach to identify subnetworks for drug repositioning" have a range of [0,1]. For the computational convenience, the vertex prizes and edge costs in these DSNs are multiplied by 100. Thus they have a new range of [0,100].

# Algorithms

The codes for the GW algorithm are at  https://github.com/YahuiSun/GW-to-identify-subnetworks

The codes for PSIA are at https://github.com/YahuiSun/PSIA-to-identify-subnetworks 

For any question, please contact Yahui Sun yahui.sun@anu.edu.au I'll be very happy to help.

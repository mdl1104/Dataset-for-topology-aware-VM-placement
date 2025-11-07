# Dataset for Topology-Aware VM Placement

This repository provides the dataset used for research on **topology-aware virtual machine (VM) placement** in cloud data centers.  
It supports reproducible experiments for evaluating algorithms that consider the NUMA structure and topology-related constraints, including collocation, anti-collocation and fault-domain constraints.

---

## 📘 Dataset Description

The dataset contains three main components:

1. **Datacenter Topology**
   - Hierarchical structure including racks and servers.

2. **Server Resource Information**
   - Available CPU cores and memory capacity for each server.
   - Every sever is set as double-NUMA type.

3. **Five VM Request Sequences Information**
   - Each record includes:
     - Resource requirements (CPU, memory)
     - NUMA configuration
     - Type label (e.g., nan, collocation, anti-collocation or fault-domain)

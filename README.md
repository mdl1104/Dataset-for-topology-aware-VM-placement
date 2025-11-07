# Dataset for Topology-Aware VM Placement

This repository provides the dataset used for research on **topology-aware virtual machine (VM) placement** in cloud data centers. Note that the dataset is obtained based on the practice production information from Huawei Cloud. It supports reproducible experiments for evaluating algorithms that consider the NUMA structure and topology-related constraints, including collocation, anti-collocation and fault-domain constraints.

---

## 📘 Dataset Description

The dataset contains three main components:

1. **Datacenter Topology**
   - topology_provider.xls
   - Hierarchical structure including racks and servers.

2. **Server Resource Information**
   - PM_res.xlsx
   - Available CPU cores and memory capacity for each server.
   - Every sever is set as double-NUMA type.

5. **Five VM Request Sequences Information**
   - VM_data_C1, VM_data_C2, VM_data_C3, VM_data_C4, VM_data_C5
   - Each record includes:
     - Resource requirements (CPU, memory)
     - NUMA configuration
     - Type label (e.g., nan, collocation, anti-collocation or fault-domain)
    
## 📝 Citation Requirement
**Please provide proper citation when using or referencing this dataset in your work.**

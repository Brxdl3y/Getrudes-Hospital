**Getrude's Hospital Network Lab**

A Cisco Packet Tracer lab project simulating a hospital network designed with **scalability, redundancy**, and **security**in mind.  
This lab demonstrates **enterprise-grade network design** and **OSPF routing configuration** across multiple departments.  


 **Project Overview**

This project models **Getrude's Hospital's** internal network infrastructure, connecting multiple departments (Reception, Laboratory, ICU, Pharmacy, and a Data Center) over a robust Layer 3 network. The design ensures:  
- **High availability** via redundant router links  
- **Optimized routing** with OSPF (Open Shortest Path First)  
- **Departmental segmentation** using subnetting  
- **External ISP connectivity** for internet access 

 **Objectives**

- Build a hospital-wide network for inter-departmental communication  
- Implement **OSPF Single-Area** routing across all routers  
- Configure **redundant paths** between routers for failover  
- **Segment networks** for different hospital departments (Reception, Lab, ICU, Pharmacy and Data Center)  
- Connect the hospital to an external **ISP** (simulated)  
- Test and verify end-to-end connectivity 

  **IP Addressing & Subnetting**

| Department      | Subnet          | Example Host IP |
|-----------------|----------------|-----------------|
| Reception       | 10.0.2.0/24    | 10.0.2.10       |
| Laboratory      | 10.0.1.0/24    | 10.0.1.10       |
| Pharmacy        | 10.1.2.0/24    | 10.1.2.10       |
| Data Center     | 10.1.3.0/24    | 10.1.3.2        |
| WAN Links       | /30 Subnets    | 10.x.x.x        |

**Skills Demonstrated**

Enterprise LAN/WAN Design

OSPF Single-Area Configuration & Troubleshooting

Subnetting & IP Address Planning

Cisco Router & Switch Configuration

Network Redundancy & High Availability

Documentation & Diagramming


Why This Project Stands Out

This lab shows hands-on skills that directly align with CCNA, networking roles, and IT support jobs:

Designed with real-world hospital use cases in mind

Demonstrates understanding of routing protocols and redundancy

Professional documentation & clear topology


How to Use

Download and open **getrudes-hospital.pkt** in Cisco Packet Tracer 8.x.
Refer to **commands.txt** for full CLI configurations.

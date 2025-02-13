# 📌 Multi-AS BGP Network Simulation

### *Advanced Networking - ENCS5321*
🚀 **BGP Scenario: Multi-AS Topology with Policy-Based Traffic Engineering**

---

## 📚 **Project Overview**
This project focuses on designing and implementing a **multi-autonomous system (multi-AS) BGP network** to explore advanced **BGP features** such as **route filtering, traffic engineering, and redundancy testing**. The network is built using **GNS3** and configured with **iBGP and eBGP sessions** across multiple ASes.

The objective includes:

✔️ **Configuring Interior Gateway Protocols (OSPF, RIP, Static Routing) within ASes.**  
✔️ **Establishing eBGP connectivity between ASes and iBGP within each AS.**  
✔️ **Implementing traffic engineering using BGP attributes (Local Preference, AS_PATH, MED).**  
✔️ **Testing redundancy by simulating link failures and automatic rerouting.**  
✔️ **Monitoring and troubleshooting BGP sessions using debugging commands.**  

📌 **See the report for multiple scenarios and a detailed explanation of everything done.**

---

## 📂 **Repository Structure**
```
📂 Multi_AS_BGP_Project
│── 📝 README.md (This file)
│── 📝 Report.pdf (Detailed analysis and discussion)
│── 📝 BGP_Project_Description.docx (Assignment instructions and requirements)
│── 📁 Configurations (Router and topology configurations)
│    │── 🖼️ GNS3+import+ios+image.png
│── 📁 GNS3_Project (GNS3 simulation files)
│    │── 📝 BgpProject.gns3project (Topology file)
```

---

## 🌐 **Network Topology**
Below is the **BGP network topology** used in this project:

![image](https://github.com/user-attachments/assets/7a76cf38-29d4-417d-8d2b-2ff1debc1d0c)

The topology consists of **four autonomous systems (ASes)**:
- **AS100:** Enterprise network (internal clients).
- **AS200:** Internet Exchange (IX) provider.
- **AS300:** Transit Provider (ISP).
- **AS400:** Enterprise network (connected externally).

Each AS runs **its own internal routing protocol**, and **BGP** is used for inter-AS communication.

---

## 🛠️ **Tools Used**
✅ **GNS3** (Network Simulation)  
✅ **Cisco 3725 Router IOS** (For real-world routing scenarios)   

📌 **Download GNS3:** [GNS3 Official Download](https://www.gns3.com/software/download)  
📌 **Cisco 3725 IOS Image:** [Download Router IOS](https://drive.google.com/file/d/1nkmoPEpnq-h-yPTBXmQKfPQUEqGA6ZHz/view)  
📌 **Tutorial: How to import IOS into GNS3:** [YouTube Guide](https://www.youtube.com/watch?v=nBw4lsxE0-s)  

---

## 📝 **How to Run the Project**
1️⃣ **Clone the repository:**
```bash
git clone https://github.com/ManarShawahni/BGP_Network_Project.git
```

2️⃣ **Open the topology in GNS3.**  
- Load `BgpProject.gns3project` in **GNS3**.
- Start all routers and verify neighbor relationships.

3️⃣ **Verify network connectivity.**  
```bash
ping 10.86.3.1
traceroute 192.168.5.2
```

4️⃣ **Modify configurations and test scenarios as needed.**




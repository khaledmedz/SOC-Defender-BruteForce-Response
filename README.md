# Defender Brute-Force Response Project

**Microsoft Defender for Servers P2 + Microsoft Sentinel**  
**April 2026**

### 🎯 Project Goal
I simulated a real SSH brute-force attack against an Azure Linux VM and handled the complete incident response using Microsoft Defender for Servers and Sentinel, with a strong focus on incident management in Sentinel.

### 🛠️ What I Did
- Enabled **Defender for Servers Plan 2** in my Azure subscription  
- Deployed a Linux VM (`SOC-VM1`)  
- Executed a controlled brute-force attack using Hydra from my TryHackMe Kali Linux machine  
- Detected the attack in real time  
- Fully managed the incident inside **Microsoft Sentinel** (triage, investigation, containment, and closure)  
- Blocked the attacker IP using a Network Security Group rule  

### 📸 Project Walkthrough

**1. Environment & Defender Setup**
![Defender for Cloud Setup](screenshots/01-defender-cloud-setup.png)
![VM Creation](screenshots/02-vm-creation.png)
![Defender Plan 2 Enabled](screenshots/03-defender-plan2-enabled.png)

**2. Attack Execution**
![Hydra Brute-Force Attack](screenshots/04-hydra-attack.png)

**3. Incident Detection & Management in Sentinel**
![Sentinel Alert](screenshots/05-sentinel-alert.png)

**4. Incident Investigation – Attack Story Graph**
![Attack Story Graph](screenshots/06-attack-story-graph.png)

**5. Containment & Evidence Collection**
![Auth Log Analysis](screenshots/07-auth-log.png)
![NSG Block Rule](screenshots/08-nsg-block.png)

**6. Incident Closure in Sentinel**
![Incident Resolved](screenshots/09-incident-closed.png)


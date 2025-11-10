 # Investigating a Cybersecurity Incident Using Digital Forensics

### **Overview**
This project simulates a **real-world cybersecurity incident investigation** involving a security breach at a fictional company, **Oceanix Living**.  
Acting as a **Digital Forensics Investigator**, I conducted a structured analysis to identify, contain, and understand the breach using formal **Incident Response (IR)** and **Digital Forensics** methodologies.

Through this investigation, I applied industry frameworks, created forensic images, and analyzed digital evidence to reconstruct the incident timeline and determine the scope and impact of the compromise.

---

### **Objectives**
- Apply the **Incident Response Framework (IRF)** to assess and manage a cybersecurity incident.  
- Perform **forensic imaging** and maintain the **chain of custody** for digital evidence.  
- Conduct **data recovery and analysis** to uncover deleted, hidden, or malicious files.  
- Draw evidence-based conclusions about **threat actor activity, intent, and data exfiltration.**

---

### **Tools & Technologies**
| Category | Tools Used |
|-----------|-------------|
| **Forensic Imaging** | FTK Imager, Autopsy |
| **Data Recovery & Analysis** | Autopsy, Sleuth Kit, Hex Editor |
| **Verification & Integrity** | MD5/SHA256 Hash Verification |
| **Documentation & Frameworks** | NIST 800-61, Incident Response Framework (IRF), Chain of Custody Form |

---

### **Key Tasks & Process**

#### **Task 1: Apply the Incident Response Framework**
- Reviewed the Oceanix Living breach report and supporting evidence.
- Mapped the investigation using the **six IRF phases**:
  1. **Preparation**
  2. **Identification**
  3. **Containment**
  4. **Eradication**
  5. **Recovery**
  6. **Lessons Learned**
- Identified gaps in the organization’s initial response and proposed process improvements.

---

####  **Task 2: Create a USB Flash Drive Image**
- Collected a USB device linked to a potential suspect.
- Performed a **bit-by-bit forensic image acquisition** using **FTK Imager**.  
- Verified image integrity using **MD5 and SHA256 hashes**.  
- Documented the process following **chain of custody** best practices.

---

####  **Task 3: Analyze Digital Forensics Evidence**
- Examined the USB image with **Autopsy** and **Sleuth Kit**.  
- Recovered deleted and hidden files, identifying:
  - Confidential data exfiltrated from the company network.  
  - Suspicious scripts indicating lateral movement and privilege escalation.  
- Correlated findings with the **MITRE ATT&CK** framework to infer attacker techniques and tactics.

---

### **Findings & Results**
- Confirmed unauthorized data exfiltration via removable media.  
- Traced evidence of malicious scripting for credential harvesting.  
- Provided remediation recommendations to strengthen **incident detection, response, and data handling policies**.

---

### **Outcome**
By completing this project, I:
- Applied a **formal incident response process** in a real-world-style scenario.  
- Executed **forensic imaging and evidence preservation** using professional tools.  
- Analyzed and interpreted **digital evidence** to build an investigative report.  
- Strengthened practical skills in **incident handling, digital forensics, and threat analysis** — essential competencies for **SOC and DFIR roles**.

---

### **Repository Structure**

 

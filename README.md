### **Cybersecurity SOC Analyst Lab**

#### **Project Overview**  
This lab is designed to simulate a Security Operations Center (SOC) environment where aspiring cybersecurity analysts can develop skills in threat detection, incident response, and adversary emulation. The lab utilizes a combination of defensive and offensive security tools to create realistic attack scenarios and analyze security events.  

#### **Objectives**  
- Configure and monitor security logs using **Sysmon** and **LimaCharlie**.  
- Conduct adversary emulation using **Sliver C2** to simulate real-world cyber threats.  
- Utilize **Ubuntu Server** and **Windows 10** to create a hybrid infrastructure for testing security measures.  
- Detect and analyze malicious activity through endpoint logging and response mechanisms.  

#### **Lab Setup**  

##### **1. Infrastructure**  
- **Ubuntu Server**: Acts as the central log aggregation and SIEM platform, hosting security tools for monitoring activities.  
- **Windows 10**: Functions as a target endpoint for threat detection and logging analysis.  

##### **2. Security & Attack Tools**  
- **Sysmon**: Installed on Windows 10 for detailed event logging, providing insights into processes, registry changes, network connections, and file activities.  
- **LimaCharlie**: A cloud-native security operations platform used for endpoint detection and response (EDR), threat hunting, and automated remediation.  
- **Sliver C2**: A powerful command-and-control framework for red teaming exercises, allowing adversary emulation to assess detection capabilities.  

#### **Implementation Steps**  
1. **Deploy Ubuntu Server and Windows 10** with necessary configurations.  
2. **Install Sysmon** on Windows 10 and configure logging rules to monitor suspicious activities.  
3. **Set up LimaCharlie** for endpoint monitoring and create custom detections for malicious behavior.  
4. **Deploy Sliver C2** to simulate cyber threats, including persistence, privilege escalation, and lateral movement techniques.  
5. **Analyze logs** from Sysmon and LimaCharlie to investigate adversary activities and generate incident reports.  
6. **Tune detection rules** based on findings to improve threat visibility and response actions.  

#### **Expected Outcomes**  
- Develop hands-on experience with cybersecurity monitoring tools.  
- Gain practical knowledge in detecting and mitigating cyber threats.  
- Enhance skills in log analysis, incident response, and threat hunting.  
- Improve understanding of adversary techniques used in real-world cyber attacks.


## *Walkthrough | Screenshots*

**Installing Ubuntu Server 24.04.1**

<img src="project/image1.png"> <img src="project/image2.png"> <img src="project/image3.png"> <img src="project/image4.png"> <img src="project/image5.png"> <img src="project/image6.png"> <img src="project/image7.png">

**Sliver C2 Installation**

<img src="project/image8.png">

**Windows 10 Installation**

<img src="project/image9.png"> <img src="project/image10.png"> <img src="project/image11.png"> <img src="project/image12.png"> <img src="project/image13.png">

**Disabling Windows Security**

<img src="project/image14.png"> <img src="project/image15.png"> <img src="project/image16.png"> <img src="project/image17.png"> <img src="project/image18.png"> <img src="project/image19.png"> <img src="project/image20.png"> <img src="project/image21.png"> <img src="project/image22.png"> <img src="project/image23.png"> <img src="project/image24.png"> <img src="project/image25.png">

**Sysmon Installation**

<img src="project/image26.png"> <img src="project/image27.png">

**Installing LimaCharlie Sensor in Windows 10**

<img src="project/image28.png"> <img src="project/image29.png"> <img src="project/image30.png"> <img src="project/image31.png"> <img src="project/image32.png"> <img src="project/image33.png"> <img src="project/image34.png"> <img src="project/image35.png"> <img src="project/image36.png"> <img src="project/image37.png"> <img src="project/image38.png">

**Creating New Artifact Rule In LimaCharlie**

<img src="project/image39.png"> <img src="project/image40.png"> <img src="project/image41.png"> <img src="project/image42.png">

**Generating Sliver C2 payload and Running in Windows 10**

<img src="project/image43.png"> <img src="project/image44.png"> <img src="project/image45.png"> <img src="project/image46.png"> <img src="project/image47.png"> <img src="project/image48.png"> <img src="project/image49.png"> <img src="project/image50.png"> <img src="project/image51.png"> <img src="project/image52.png">


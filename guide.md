# **CI/CD Setup: Jenkins and Nexus Installation**  

This guide provides steps to install **Jenkins** and **Nexus Repository Manager** and configure an example Java web application for a CI/CD pipeline.

[install video](https://drive.google.com/file/d/1C2e-ffgayDutHCernc2NDTyYu690xiQX/view?usp=sharing)


[pipeline video](https://drive.google.com/file/d/1cIB3pxUqHKxiRW9GVZGKWgJx32GzD1VR/view?usp=sharing)

[updated](https://drive.google.com/file/d/18PKN0uDRrRO1_vU08UCLDg1lY8yDAIqU/view?usp=sharing)

[up2](https://drive.google.com/file/d/1QO4cR5MKnyMrMAXAhVOizT0SCeEqNtfg/view?usp=sharing)

---

## **1. Install Jenkins and Nexus**  

### **a. Install Jenkins**  
Follow the official Jenkins installation guide for your operating system:  
[https://www.jenkins.io/doc/book/installing/](https://www.jenkins.io/doc/book/installing/)  
add insecure repository to docker at jenkins server:
[link](https://stackoverflow.com/questions/61116766/add-insecure-registry-to-docker-in-ubuntu)
   ```bash
   sudo usermod -a -G docker jenkins
   ```
### **b. Install Nexus**  
Refer to the official Sonatype Nexus installation guide:  
[nexus](https://hub.docker.com/r/sonatype/nexus3/)  

---

## **2. Example Application**  

An example Java web application is available to demonstrate the CI/CD pipeline setup:  

- **Repository URL:** [cicd-pipeline-java-webapp](https://github.com/nguyentrungduc134/fakeweb/)

---

### **Steps to Use the Application**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/nguyentrungduc134/fakeweb/
   ```  
2. Configure Jenkins to build the application and integrate Nexus for artifact storage.  
3. Define pipeline stages (build, test, and deploy) in Jenkins.  

---

**You are now ready to set up your CI/CD pipeline using Jenkins and Nexus!**

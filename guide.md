# **CI/CD Setup: Jenkins and Nexus Installation**  

This guide provides steps to install **Jenkins** and **Nexus Repository Manager** and configure an example Java web application for a CI/CD pipeline.

---

## **1. Install Jenkins and Nexus**  

### **a. Install Jenkins**  
Follow the official Jenkins installation guide for your operating system:  
[https://www.jenkins.io/doc/book/installing/](https://www.jenkins.io/doc/book/installing/)  

### **b. Install Nexus**  
Refer to the official Sonatype Nexus installation guide:  
[https://help.sonatype.com/repomanager3/installation-and-upgrades](https://hub.docker.com/r/sonatype/nexus3/)  

---

## **2. Example Application**  

An example Java web application is available to demonstrate the CI/CD pipeline setup:  

- **Repository URL:** [cicd-pipeline-java-webapp](https://github.com/nguyentrungduc134/cicd-pipeline-java-webapp)  

---

### **Steps to Use the Application**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/nguyentrungduc134/cicd-pipeline-java-webapp.git
   ```  
2. Configure Jenkins to build the application and integrate Nexus for artifact storage.  
3. Define pipeline stages (build, test, and deploy) in Jenkins.  

---

**You are now ready to set up your CI/CD pipeline using Jenkins and Nexus!**

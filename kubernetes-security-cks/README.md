# CKS General Tips

Welcome to the CKS (Certified Kubernetes Security Specialist) exam! This document provides general tips and guidance for preparing for the exam. Below, you'll find the main topics covered in the CKS exam along with 15 sample questions to help you in your preparation.

## Main Topics Covered:
1. [**Cluster Setup**](#question1)
2. [**Cluster Hardening**](#question2)
3. [**System Hardening**](#question3)
4. [**Minimise Microservice Vulnerabilities**](#question4)
5. [**Supply Chain Security**](#question5)
6. [**Monitoring, Logging, and Runtime Security**](#question6)
7. [**Identity and Access Management**](#question7)
8. [**Network Policies**](#question8)
9. [**Security Contexts**](#question9)
10. [**Service Mesh Security**](#question10)
11. [**Pod Security Policies/Security Policy**](#question11)
12. [**Incident Response**](#question12)

## General Tips:
- **Understand Kubernetes Architecture**: Familiarise yourself with Kubernetes components and their interactions.
- **Hands-on Experience**: Practice with real-world scenarios and Kubernetes clusters.
- **Documentation**: Refer to official Kubernetes documentation for in-depth understanding of concepts.
- **Stay Updated**: Keep yourself updated with the latest developments in Kubernetes security best practices.
- **Mock Exams**: Take practice exams to gauge your preparedness and identify areas for improvement.


## Sample Questions:
1. <a name="question1"></a>**Cluster Setup:**  
   Scenario:  
   You've been tasked with setting up a Kubernetes cluster for your organisation. Your first task is to ensure that the cluster is configured securely from the outset. Use RBAC (Role-Based Access Control) to create a user with limited permissions, such as only being able to view pods in a specific namespace.

2. <a name="question2"></a>**Cluster Hardening:**  
   Scenario:  
   Building upon the previous scenario, now that your cluster is set up, your next task is to further harden it to prevent unauthorised access and attacks. Utilise Network Policies to restrict inbound traffic to only allow connections from specific IP addresses or subnets.

3. <a name="question3"></a>**System Hardening:**  
   Scenario:  
   With the cluster hardened, your next task is to harden the underlying system to mitigate potential security risks. Implement Pod Security Policies to ensure that all pods in the cluster run with restricted privileges and cannot escalate their permissions.

4. <a name="question4"></a>**Minimise Microservice Vulnerabilities:**  
   Scenario:  
   Given that your system and cluster are hardened, your team is now focusing on addressing vulnerabilities specific to microservices running within the Kubernetes environment. Identify a vulnerable container image used by one of your microservices and replace it with a more secure version.

5. <a name="question5"></a>**Supply Chain Security:**  
   Scenario:  
   Your team is now tasked with ensuring the security of the supply chain, including the deployment of trusted container images. Set up image scanning in your CI/CD pipeline to automatically detect and block the deployment of container images with known vulnerabilities.

6. <a name="question6"></a>**Monitoring, Logging, and Runtime Security:**  
   Scenario:  
   As part of your ongoing efforts to enhance security, you need to implement monitoring and logging mechanisms within your cluster to detect and respond to security incidents in real-time. Configure Prometheus and Grafana to collect metrics from your cluster and set up alerts for any suspicious activity.

7. <a name="question7"></a>**Identity and Access Management:**  
   Scenario:  
   Building upon the previous scenario, your next task is to enhance identity and access management to ensure only authorised entities can interact with your Kubernetes resources. Integrate your Kubernetes cluster with an LDAP or Active Directory server for centralised user authentication and authorisation.

8. <a name="question8"></a>**Network Policies:**  
   Scenario:  
   With access controls in place, your team is now focusing on enforcing network policies to restrict communication between different parts of your Kubernetes cluster. Write a Network Policy that denies egress traffic from a specific pod to prevent data exfiltration.

9. <a name="question9"></a>**Security Contexts:**  
   Scenario:  
   Given the network policies implemented, your next task is to utilise security contexts to further isolate and secure individual pods and containers within the cluster. Identify a pod running with elevated privileges and update its security context to run with a non-root user.

10. <a name="question10"></a>**Service Mesh Security:**  
    Scenario:  
    Your team is now considering implementing a service mesh to enhance security between services in your Kubernetes environment. Install and configure Istio as a service mesh and enforce mutual TLS authentication between services.

11. <a name="question11"></a>**Pod Security Policies/Security Policy:**  
    Scenario:  
    Building upon the previous scenario, your next task is to enforce pod security policies or security policies to ensure that all pods adhere to predefined security standards. Write a Pod Security Policy that requires all pods to run with read-only root filesystems.

12. <a name="question12"></a>**Incident Response:**  
    Scenario:  
    Finally, with all security measures in place, your team needs to establish an incident response plan to effectively mitigate and respond to security breaches within your Kubernetes environment. Simulate a security incident, such as a pod compromise, and follow your incident response plan to contain and remediate the issue.



Feel free to use these questions to test your knowledge and prepare effectively for the CKS exam!

                         INGRESS HANDS-ON
To enhance the security of our application's exposure, we will implement the NGINX Ingress Controller in place of a traditional load balancer, utilizing HTTPS for secure communication. The Ingress Controller efficiently routes incoming traffic to the appropriate backend services, ensuring a robust and secure architecture.
To accomplish this, the following steps and guidelines have been outlined below. Additionally, the corresponding commands and file structures are provided for reference


OVERVIEW OF THE  7 PHASES
•	PHASE 1: Purchasing of Domain name from any hosting platform
•	PHASE 2: Configuring Nameservers with AWS Route53 and GoDaddy
•	PHASE 3:  Create your EKS cluster                                
•	PHASE 4: AWS certificate manager setup
•	PHASE 5: Deploy Nginx ingress controller
•	PHASE 6: AWS loadbalancer setup
•	PHASE 7: Deploying the Ingress Yaml File


	Note : To have all the files and folders to carry out this hands-on, clone this repo url below
```bash
git clone https://github.com/kingsleyzikora/ingress-project.git
```

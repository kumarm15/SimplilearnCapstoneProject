# SimplilearnCapstoneProject
Infra Optimization.
DESCRIPTION
Create a DevOps infrastructure for an e-commerce application to run on high-availability mode.

Background of the problem statement:
A popular payment application, EasyPay where users add money to their wallet accounts, faces an issue in its payment success rate. The timeout that occurs with the connectivity of the database has been the reason for the issue. While troubleshooting, it is found that the database server has several downtime instances at irregular intervals. This situation compels the company to create their own infrastructure that runs in high-availability mode.Given that online shopping experiences continue to evolve as per customer expectations, the developers are driven to make their app more reliable, fast, and secure for improving the performance of the current system.

Implementation requirements:
1.	Create the cluster (EC2 instances with load balancer and elastic IP in case of AWS)
2.	Automate the provisioning of an EC2 instance using Ansible or Chef Puppet
3.	Install Docker and Kubernetes on the cluster
4.	Implement the network policies at the database pod to allow ingress traffic from the front-end application pod
5.	Create a new user with permissions to create, list, get, update, and delete pods
6.	Configure application on the pod
7.	Take snapshot of ETCD database
8.	Set criteria such that if the memory of CPU goes beyond 50%, environments automatically get scaled up and configured


The following tools must be used:
1.	EC2 ,2.Kubernetes , 3.Docker 4. Ansible or Chef or Puppet
The following things to be kept in check:
1.	You need to document the steps and write the algorithms in them.
2.	The submission of your GitHub repository link is mandatory. In order to track your tasks, you need to share the link of the repository.
3.	Document the step-by-step process starting from creating test cases, then executing them, and recording the results.
4.	You need to submit the final specification document, which includes:
•	Project and tester details
•	Concepts used in the project
•	Links to the GitHub repository to verify the project completion
•	Your conclusion on enhancing the application and defining the USPs (Unique Selling Points)


<img width="527" alt="Screen Shot 2021-11-21 at 4 39 25 AM" src="https://user-images.githubusercontent.com/56155128/142743421-8670832f-2169-4c22-b172-67de4efe33a8.png">

Below includes the Server details in which the setup has been deployed and Tested.

VM Name	      Pub IP	     IP-Local		
Master-VM-1	54.88.204.113	172.31..42.93		
Worker-VM-1	54.235.91.60	172.31.39.24		
Worker-VM-2	34.234.222.97	172.31.41.162		
		


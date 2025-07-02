Basic interview Questions

**1. Introduce yourself**\
**2. Statefile management**\
**3. What is the state file and where can it be stored?**\
**4. When will the state file be created?**\
**5. What is state locking? Locking mechanism in Terraform?**\
**6. Move block in Terraform --- define and give example.**\
**7. Difference between implicit and explicit dependencies (share
syntax).**\
**8. Difference between variable.tf and terraform.tfvars files.**\
**9. Variable.tf vs variables.tf vs terraform.tfvars.**\
**10. Type constraints in Terraform.**\
**11. What is a module in Terraform?**\
**12. What is a pattern module? Difference between root and child
modules.**\
**13. What are lifecycle rules in Terraform? (mention 2--3 arguments,
e.g. in storage account)**\
**14. Data block in Terraform --- is it part of the state file?**\
**15. What are data types in Terraform?**\
**16. Difference between count vs for_each. Is count only integer? Why
deletion with count is difficult?**\
**17. What are logging levels supported by Terraform?**\
**18. What is provisioner in Terraform? File provisioners? Null
resource?**\
**19. If you have a VM template + PowerShell script for domain join,
which provisioner do you use?**\
**20. What is the difference between provider and provisioner?**\
**21. What is TFLint (linting) in Terraform?**\
**22. What is a service connection in Azure DevOps? What is required to
create one?**\
**23. Deployment group vs task group in Azure DevOps**\
**24. What are security best practices in pipelines/ADO?**\
**25. What is a gate in Azure DevOps?**\
**26. What are pools and agent pools? Is macOS supported as agent?**\
**27. What is a sprint in Azure Boards? What is a work item? Difference
between them.**\
**28. What is a stakeholder in Azure DevOps?**\
**29. Process for PR (pull request)**\
**30. Git: what is the difference between commit and push? Also git
fetch vs git pull.**\
**31. Tools used for pipeline---e.g., YAML, GitHub Actions**\
**32. E2E pipeline flow---explain full YAML example**\
**33. How do you manage multiple Azure subscriptions?**\
**34. VM vs VMSS --- what's the difference?**\
**35. If requirement is 2 VMs + 2 databases, would you choose VM or
VMSS?**\
**36. If you have 1500 subscriptions, how to manage from ADO?**\
**37. As an architect, how do you plan and propose infra solutions to
customers?**\
**38. Recently upgraded Terraform templates---give an example**\
**39. What are Terraform backends? Which are you familiar with?**\
**40. How do you encrypt the state file?**\
**41. When you declare a variable with default value in Terraform---what
argument?**\
**42. If a VM installed Office after creation, then terraform apply
again---what happens?**\
**43. In TF, if you update a VM custom image and re-run apply---what
happens?**\
**44. Lifecycle block usage in storage scenario (duplicate of #13?)**\
**45. What is workspace in Terraform and why use it?**\
**46. What is terraform show?**\
**47. What is terraform fmt?**\
**48. What is terraform provisioners?**\
**49. How to handle sensitive variables --- if marked sensitive, how to
view in state?**\
**50. If variable values are hard-coded in VM definition, will they show
in plan?**\
**51. What is terraform download module and providers stage?**\
**52. What is Saltener? (Possibly \"splinter\"? Clarify)**\
**53. What is pipeline or which pipelines you\'ve worked on---explain
E2E flow**\
**54. Kubernetes: stateless vs stateful**\
**55. If a pod is pending --- how to troubleshoot?**\
**56. Docker: basics, script, volume, where images are stored**\
**57. Bash and PowerShell scripting experience**\
**58. Managing PVs in Kubernetes with a specific service account**\
**59. Cluster role binding in Kubernetes**\
**60. Terraform functions --- name and examples**\
**61. How to maintain/upgrade Kubernetes cluster**\
**62. What is peering?**\
**63. Availability set vs availability zone**

Persistent\
\
Interviewer: Vinita Gupta

1.  Write Terraform code for 1 VNet with 10 subnets (without using
    for_each).

2.  How to assign 1000 IPs to one subnet and 500 IPs to another? Kaunsa
    CIDR range use karoge?

3.  Networking types in Kubernetes?

4.  Write a sample Ingress YAML file.

5.  Write a sample Deployment YAML file.

6.  What are Liveness and Readiness probes? Unmein kya difference hai?

7.  Kaise banayoge pod ko scalable? What is HPA (Horizontal Pod
    Autoscaler)?

8.  What is CNI and how do you use it in Kubernetes?

9.  Difference between Load Balancer and Application Gateway?

10. Explain nodeSelector, Taints, and Tolerations in Kubernetes.

11. Difference between a reusable workflow and a composite action in
    GitHub Actions?

12. GitHub Action kya hota hai? Kaise likhte hain?

13. For checkout, kaunsa action aur version use karte ho?

14. Difference between jobs, steps, and actions in GitHub Actions
    workflow?

15. Build metrics in GitHub Actions--- aapne use kiye hain?

16. Azure resource groups kya hain? Infrastructure management mein kaise
    use hote hain?

17. Azure Monitor pe kaam kiya hai? Describe your experience.

18. Azure mein RBAC ka role-based control kaise configure karte hain?

19. AKS mein autoscaling Azure-native tools se kaise enable karoge?

20. AKS autoscaling kaise kaam karta hai (internally)?

21. Terraform state ko team mein kaise manage karte ho?

22. Terraform se AKS cluster kaise provision karte ho, aur ACR se kaise
    connect karte ho?

23. terraform init kya karta hai?

24. terraform plan aur terraform apply mein kya farq hai?

25. Agar state file local thi aur accidentally delete ho gayi, toh
    recover kaise karoge?

26. Kubernetes mein deployed services ke secrets ya credentials kaise
    retrieve karoge?

27. Kubernetes service discovery cluster ke andar kaise handle hota hai?

28. Kubernetes mein "stateful" ka kya matlab hota hai?

29. Terraform provisioners kya hote hain? Kaise kaam karte hain?

30. Terraform provider kya hota hai?

31. null_resource kya hai Terraform mein?

32. Terraform meta-arguments kya hote hain (e.g., count, depends_on)?
    Examples do.

33. Mandatory Terraform commands kya hain aur Azure DevOps mein kaise
    use karte ho?

34. Agar cloud mein resource hai lekin state file mein nahi hai, to
    terraform plan/apply kya karega?

35. Terraform drift kya hota hai? Usko kaise detect aur fix karte ho?

36. Existing resource ko Terraform state mein kaise import karte ho?

37. Aap Docker ko apne current project mein kaise use karte ho?

38. Ek Dockerfile explain karo with example.

39. Multi-stage Dockerfile kya hota hai? Uska use kya hai?

40. Dockerfile mein CMD vs ENTRYPOINT kya difference hai? Practical
    example do.

41. Git: fetch aur pull mein kya farq hai?

42. Kubernetes: Deployment, StatefulSet, ReplicaSet mein kya difference
    hai?

43. service.yaml kaise likhte ho aur kya use hota hai?

44. Kubernetes mein different service types kaunse hain?

45. Kubernetes YAMLs mein general metadata (e.g., labels, annotations)
    kyon aur kahan use hoti hai?

46. Cloud & CI/CD pipeline mein credentials kaise securely manage karte
    ho?

47. Aise code pushes prevent kaise karoge jo insecure code contain karte
    hain? (Pipeline mein security scanning)

48. Highly available infrastructure ko deploy aur ensure kaise karte ho?

49. Agar GitHub Action ke Azure CLI step se timeout ho raha hai,
    troubleshoot kaise karoge?

50. Dev, Stage, Prod environments ke liye Terraform code ko kaise design
    & secure karoge?

51. Azure Functions aur AWS Lambda ka kya use hai?

52. Kubernetes mein monitoring kaise enable karte ho?

53. Agar pods mein "cross loopback" error aaye, troubleshoot approach
    kya hogi?

54. Terraform state file kya hota hai? Usko secure kaise karte ho?

55. Azure & AWS mein secrets ko kaise secure karte ho?

56. CI/CD pipelines aap kaise deploy karte ho? Organization mein kya
    process follow karte ho?

57. Terraform mein HA aur security ke liye kaunse components use karte
    ho?

58. PowerShell script likho jo memory check kare aur notify kare agar
    usage 85% se zyada ho.

59. Terraform code: 1 VNet + 3 subnets + NSG attach to VM dynamically.

60. Terraform code to create multiple VMs.

61. Terraform backend config & state file ka code.

62. Agar VM pehle portal se create kia aur fir Terraform code likha,
    plan/apply se kya hota hai?

63. CI/CD pipeline process end-to-end kya hai?

64. Pipeline trigger ka YAML code likho.

65. Git: undo command after git add.

66. Git: Squash kya hota hai?

67. git clone vs git merge batao.

68. Git staging area kya hoti hai?

69. Hotfix branch scenario--- kya steps honge?

70. Terraform code: VNet + 2 subnets using module and map.

71. Kubernetes pod create karne ke liye YAML likho.

72. Terraform: Map vs List object kya hai? Kab kaun use karte ho?

73. Bash script likho jo 5 VMs ki memory export kare.

74. ISO 27001 kya hai? DevOps mein relevance kya hai?

75. Terraform code likhne ke baad kya steps follow karte ho (testing,
    deployment)?

76. Aap kaun kaunse Azure services pe kaam kar chuke ho?

77. Azure Key Vault kya hai?

78. Code mein aur cloud mein secrets kaise manage karte ho?

79. Kubernetes mein ek namespace ke sare pods kaise list karoge?

80. Kubernetes pods troubleshoot karne ke steps kya hain?

81. Agar Terraform resource manual change ho gaya ho, handle kaise
    karoge?

82. Manual changes ignore karna ho Terraform mein--- kaise? (Lifecycle
    settings)

83. Terraform-managed VM mein manually extra OS disk add hua ho---
    handle kaise karoge?

84. Databases ka backup kaise lete ho (Azure/AWS)?

85. Application Load Balancer kya hota hai?

86. Network rule vs Application rule in Azure Firewall--- kya farq hai?

87. Classic vs Application Load Balancer in AWS--- difference kya hai?

88. SRE (Site Reliability Engineering) practices kya hote hain?

89. Apne recent SRE project ka walkthrough do.

90. CI/CD pipelines mein additional security kaise add karte ho?

91. Terraform se infrastructure optimize karne ka kya scenario hai?

92. Azure cloud mein kisi problem ko troubleshoot karne ka example do.

93. Grafana aur Prometheus use kiye hain monitoring ke liye?

94. Agar customer Terraform version upgrade maange, impact assessment
    kaise karoge?

Capgemini

1.  What is Git squash and Git rebase? What is the difference between
    them?

2.  If you are creating a VM via Terraform code and it fails, how do you
    roll back the changes?

3.  Is it possible to manually modify Terraform state files after
    deployment?

4.  What are the different variable types in Terraform? How do you
    define them?

5.  How are you passing values into variables in Terraform?

6.  You have two Azure subscriptions: one with an image, another with VM
    --- how do you manage this via Terraform?

7.  How do you manage secrets using Azure Key Vault, and how do you
    reference them via Service Principal in Terraform?

8.  What is Python or PowerShell? How do you use it in automation? Write
    a loop to print numbers from 1 to 10.

```{=html}
<!-- -->
```
9.  Can we convert a Federation Service connection into a secret as per
    client request?

10. If I define a default value in variables.tf, why should I use
    terraform.tfvars? How is it helpful in automation?

11. If there are three folders: prod, stage, and qa, how will you use
    .tfvars for each?

12. How can we create multiple resource groups across multiple
    subscriptions using Terraform?

```{=html}
<!-- -->
```
13. How many ways can we deploy or host an application on Azure?

14. What are the strategies you use to deploy an application using CI/CD
    pipelines?

15. How do you validate your CI/CD pipeline end-to-end? If you face any
    conflicts, how do you resolve them?

16. What is Azure Data Factory? How do you use and implement it in a
    pipeline?

17. If a developer has created a database manually, how will you convert
    it into a managed SQL database through CI/CD?

18. Have you used Azure Runbooks? If yes, where and how?

```{=html}
<!-- -->
```
20. How do you manage infrastructure (IaC)?

21. What is your approach to designing a CI/CD pipeline?

22. Which tools are you using for your CI/CD pipelines?

23. How do you handle deployments in Kubernetes?

24. What is the difference between Availability Zones and Regions?

25. What is GitOps?

26. How do you ensure security in your CI/CD or infrastructure process?

27. How do you handle system failures or outages?

```{=html}
<!-- -->
```
28. Is it possible to get a public DNS and public IP using an internal
    load balancer?

29. From on-premises, how do you connect to Azure Cloud? Which tools do
    you use for failover?

30. What is Azure Site Recovery (ASR), and why do we use it?

31. What is Azure Blob Storage and where do you use it?

32. What is the use of containers in cloud deployment?

33. Difference between Windows Active Directory and Azure Active
    Directory?

34. What is Geo-targeting in AWS CloudFront?

```{=html}
<!-- -->
```
35. What is the difference between Continuous Delivery and Continuous
    Deployment?

36. Write a YAML file for a release pipeline.

37. How do you create a custom Docker image? Write a sample Dockerfile.

38. What is a Kubernetes cluster?

39. If a build fails, how do you revert the last commit?

40. Explain your Git branching strategy.

41. What is git rebase and when do you use it?

42. How do you monitor Kubernetes clusters?

43. You need to configure a Canary deployment --- how will you do it?

**Interviewers: Naren Reddy / Priyanka Jena**

44. Give your self-introduction.

45. Tell me about your current project and day-to-day activities.

46. Write Terraform code for a VNet and Subnet (basic, in Notepad).

47. Write a basic Kubernetes Pod YAML file.

48. What command do you use to build an application using NPM?

49. What is a Service Endpoint in Azure?

50. How do you refer to Key Vault secrets in GitHub Actions?

51. What are all the DevOps tools you\'ve worked with?

Mirafra Software Technologies Pvt. Ltd

1.  Introduce yourself and explain your current project along with your
    day-to-day work.

2.  Have you worked on Jenkins and if yes, open notepad and write a
    CI/CD pipeline code.

3.  Have you worked on GitHub Actions and if yes, open notepad and write
    a CI/CD pipeline code.

4.  What is the difference between git pull and git fetch?

5.  How do you view the commit history in Git for the last 5 commits
    only?

6.  What is a merge conflict in Git and how do you resolve it?

7.  What is the difference between git reset and git revert?

8.  What is the purpose of the git stash command?

9.  What is the difference between git merge and git rebase?

10. What type of branch strategy do you follow in your team?

11. Write a Terraform code to create a virtual machine. What logic would
    you use if you need to add 10 VMs?

12. What is Terraform lint?

13. How would you deploy Terraform infrastructure through a pipeline?

14. Do you have experience with shell scripting or Python?

15. What are the commonly used commands or operations you perform using
    shell scripting?

TechRBM:

1.  I have a developed project locally with Node API, Kafka services,
    Zookeeper, and PostgreSQL. How do I deploy this project on Azure
    using a secure gateway?

2.  How do I incorporate AKS (Azure Kubernetes Service) and a Load
    Balancer into this deployment?

3.  What are App Services in Azure Cloud?

4.  How would you use Azure App Services to deploy an application?

5.  Explain the differences between microservices in the context of your
    project.

6.  What are some best practices to secure microservices communication
    on Azure?

7.  How would you manage data persistence for PostgreSQL in a Kubernetes
    environment on Azure?

8.  How to set up Kafka and Zookeeper on AKS with secure access?

9.  How do you configure the Azure Load Balancer for your AKS cluster?

10. What is an Azure Secure Gateway, and how does it integrate with AKS?

\"Altimetrik\"

1\. How do you Enable monitoring in AKS?

2\. How do you implement zero-downtime deployments in Kubernetes?

3\. How you Monitor the infra logs ?

4\. Your app is not reachable via Ingress. How will you debug it?

5\. how you manage the secrets using Azure services?

6\. Why we using terraform?

7\. How you will manage if somebody run terraform destroy command ?

8\. How you manage Hardcode secrets?

9\. What are Docker volumes and how are they different from bind mounts?

10\. In which language you have scripting knowledge ?

Tech Mahindra - Tech Lead

1.  Introduce yourself.

2.  **Do you have experience in Azure infrastructure at the
    administrative level, particularly in troubleshooting?**

3.  **Do you have experience in Docker, Kubernetes, and YAML?**

4.  **Scenario-based: How would you suggest to the customer whether to
    deploy their application on a VM or in a container?**

5.  **What are the components of a Kubernetes cluster?**

6.  **How would you deploy an application to Kubernetes?**

7.  **If your Terraform state file got deleted, how would you recover
    it?**

8.  **Explain the git import command.**

9.  **How do you create multiple resource groups at multiple locations
    using Terraform?**

10. **How do you create a Grafana dashboard? Have you created any?**

11. **How do you configure alert messages for a VM in any monitoring
    tool?**

12. **Do you know about environment variables in Azure?**

13. **What are the types of agents in Azure DevOps?**

14. **What do you understand by a trigger in a pipeline?**

15. How much will you rate yourself in Python out of 5? (I've rated 3/5)

16. What is OOPS?

17. What are the 4 pillars of OOPS?

18. Tell me what is polymorphism?

19. Where have you used Python?

20. Tell me which version of Kubernetes are you using?

21. Have you deployed an AKS cluster?

22. What are the default namespaces created after AKS deployment?

23. Which tools are you strong in? (I've told them Terraform, Docker,
    and Pipeline)

24. Write a script or code to deploy 100 VMs.

25. Tell me about your current project.

26. Explain the strategy and architecture overview of your project.

27. Have you designed LLD and HLD? Which approach do you prefer?

28. Have you done any certification?

29. Suppose we have to migrate on-premise infrastructure to any cloud,
    how would you migrate? Explain the workflow and process.

30. Have you worked on security solutions?

31. How will Key Vault integrate with the pipeline?

32. Write a Terraform code for creating 10 Linux VMs.

33. What is the lifecycle of Terraform?

34. We have multiple environments; how do you pass the variables? Please
    write the command.

35. Please explain the complete workflow for Terraform automation.

36. What is a module and where do we store the state file? Why do we use
    Blob storage in Terraform and not file share?

37. Have you worked on Azure Functions? What is the use case?

38. What are the options to backup data? Do you have an idea about S3
    bucket and Storage Account?

39. How can we transfer data securely from on-prem to Azure?

40. How do you rate yourself in Terraform?

41. What is the use of provisioners in Terraform?

42. What is a page blob and how can we access a storage account?

43. Have you deployed any cloud-native NVA?

44. How proficient are you in PowerShell?

45. Have you worked on moving resources?

DXC Technology

1.  What is the CI/CD flow?

2.  Do you work with infrastructure pipeline or application pipeline?

3.  What kind of pipeline do you use? Classic or YAML?

4.  What kind of strategy do you use in Git?

5.  Tell the difference between classic and YAML pipelines.

6.  What Azure services have you used?

7.  Tell the difference between Load Balancer, Application Gateway, and
    Traffic Manager.

8.  How do you manage different environments?

9.  Do you know about Kubernetes?

10. What is blue-green deployment? What happens if it fails? Is there
    any downtime?

11. What is an artifact?

12. What do you use to store artifacts?

13. Can you work with application pipelines?

14. What language or framework do we use in frontend and backend?

15. Can you build software with developer code and integrate it with
    CI/CD?

16. Git questions: Explain pull, fetch, PR, and Git conflict with
    scenario-based examples.

Infosys

1.  Tell me about yourself?

2.  Tell me Azure DevOps features?

3.  How do you handle secrets in CI/CD?

4.  What is the difference between Azure Repos and Azure Boards?

5.  How do you push code to Azure Repos?

6.  What kind of applications or plugins can you use in Azure DevOps?

7.  How do you provision infrastructure?

8.  Tell me key features of Terraform?

9.  Tell me the difference between terraform init, plan, and apply?

10. Why do we use Terraform and what are its benefits?

11. Have you worked with Azure Web App Services?

12. Tell me about your daily routine?

13. Do you also work with PaaS services?

14. Tell me how you would provision a SQL database?

15. Why do we use SQL PaaS service instead of SQL on VM?

16. If a database is deleted, how can we recover it in PaaS?

17. How can we connect SQL database with application? Why do we do that?

18. Do you know about replica sets?

19. If a new engineer comes to your team, how will you give permissions
    on Azure DevOps?

20. What level of permission will you give?

21. One developer or user is not able to connect to your production
    server VM, what steps will you take to troubleshoot?

22. Tell me about Log Analytics or Application Insights?

23. Have you worked on disaster recovery?

Propel Noblq

1.  Tell me brief about yourself.

2.  What is virtual network?

3.  What is subnet?

4.  What is NSG (Network Security Group)?

5.  What is a load balancer?

6.  What is application gateway, and how is it different from a load
    balancer?

7.  What is VMSS (Virtual Machine Scale Set)?

8.  How would you block an IP in firewall for outbound traffic?

9.  What are endpoints? What is the difference between service endpoints
    and private endpoints?

10. Do you have experience in PostgreSQL?

11. How would you take backup of PostgreSQL database?

12. What is VNet peering?

13. What is a virtual network gateway?

14. How would you connect on-premises network to cloud?

15. How would you temporarily elevate permission for a user in Azure?

16. Difference between build and release pipeline?

17. How do you publish artifacts?

18. What are artifacts?

19. What are agents in pipeline?

20. What is private link in Azure?

21. How do you keep secrets in pipeline?

```{=html}
<!-- -->
```
22. Could you explain the key components of the Kubernetes control plane
    and their respective roles?

23. How would you differentiate between a Pod, a ReplicaSet, and a
    Deployment in Kubernetes?

24. What is the standard approach to performing a rolling update in
    Kubernetes while minimizing service disruption?

25. In what scenarios would you choose a StatefulSet over a Deployment,
    and why?

26. What is the purpose of kube-proxy in a Kubernetes cluster, and how
    does it function?

27. Can you describe the role of Ingress in Kubernetes and how it
    differs from a standard Service?

28. How would you systematically troubleshoot a pod that is stuck in a
    CrashLoopBackOff state?

29. What deployment strategies do you recommend to ensure zero downtime
    during application releases?

30. How do you typically structure a CI/CD pipeline to support multiple
    environments such as development, QA, staging, and production?

31. If a pipeline\'s unit tests fail immediately after a commit, what
    steps would you take to identify and resolve the issue efficiently?

32. What methods do you use to pass artifacts or variables between
    stages in a CI/CD pipeline?

Accenture

1.  What is peering?

2.  What happens with the route table when you peer the virtual network?

3.  What do you understand with CAF?

4.  What is landing zone?

5.  What do you understand with azure application gateway?

6.  What is listener in application gateway?

7.  What is flow of application gateway in traffic is coming from end
    user?

8.  How much are you comfortable with terraform?

9.  Can you create azure application gateway with its all component via
    terraform?

10. Can you create 3 virtual machine and their disk via terraform how
    will you approach this scenario?

11. What do you know about devops?

12. If I have some code and it is infra code how do you push using git
    what will be the commands?

13. How do you create pipeline in azure devops?

14. Do you know ansible/puppet?

15. Do you have knowledge about any scripting language?

16. Can you create end to end landing zone using terraform, there are
    two landing zone platform and application. What are the steps for
    platform landing zone via terraform?

17. What are other devops tool you use?

18. scenario based questions regarding private dns resolver, private dns
    zone and endpoint

19. do you know python?

20. how to patch linux and windows vms

21. how to create linux lvm volume and some other as well.

United Layer (Unity Cloud)

1\. Tell me about yourself, day to day activities and skills you have

2\. What are the cloud you\'ve worked with ?

3\. Any other cloud than Azure ?

4\. What are the resources you\'ve provisioned on azure ?

5\. How do you write configuration in Terraform, tell me the
architecture

6\. What are different commands you use in Terraform?

7\. Explain me about different components of Terraform

8\. Tell me about workspaces in Terraform

9\. How do you manage different environments ?

10\. How do you keep secrets in Terraform?

11\. Can we keep secrets in local and access them ? Are they secure ?

12\. What is state file? Tell me about state locking and how they are
related

13\. What is backend in Terraform?

14\. Let me give you a requirement, I want to create a VM and then
install few applications like docker ,etc. automatically .I want to use
a load balancer and cluster IPs. How will you provision this ?

15\. Do you have any experience with Ansible?

16\. Is the data you fetch using data block from keyvalult encrypted?

17\. How did you do Containerization? What applications were you using?

18\. How did you deployed the containers ? Were you using kubernetes?

9\. What are the different cloud providers supported by Terraform, give
me 5-6 names

20\. What are private cloud providers supported by Terraform ?

21\. What is private module in Terraform?

Hexaware

Panel - anup singh

1.  Introduce yourself.

2.  Your day-to-day activities.

3.  Explain your transition to DevOps.

4.  What are Agile ceremonies?

5.  How long is your sprint and how does it start?

```{=html}
<!-- -->
```
6.  How many IPs are available in 192.168.1.0/32?

7.  What is Azure Bastion and what does it do?

8.  What is a Virtual Network (VPC) and how do you use a child module
    for it?

9.  What is VNet peering?

10. What is Azure Key Vault? What default permissions are given to a
    user?

11. What is a Service Principal and service connection?

12. What is Azure Repos and service connection?

```{=html}
<!-- -->
```
13. What is a null resource?

14. What is a data source?

15. What is a module?

16. You have modules for 3 environments. How do you execute the dev
    environment?

17. If a storage account was created with Terraform, teams used it and
    now you want to modify it, what will happen?

18. What is Terraform lifecycle?

19. Difference between count and foreach in Terraform.

20. Write Terraform code to create a resource group.

21. Write Terraform code to provision Azure Key Vault secrets and how to
    access them in Terraform.

22. How do you provision the whole infrastructure using Terraform?

23. How do you execute your Terraform pipeline in Azure DevOps? (Write
    YAML steps)

24. How to call a specific .tfvars file like prod.tfvars from multiple
    tfvars files?

25. Where do you store Terraform state file and why prefer blob storage
    over file share?

```{=html}
<!-- -->
```
26. Write a YAML pipeline (application pipeline).

27. What is a variable in YAML pipeline?

28. How do you handle secrets in CI/CD pipelines?

29. What are artifacts? How do you publish them?

30. What are agents in pipelines?

31. How do you deploy Node.js using Azure DevOps pipeline?

32. How do you integrate AKS/ACS in infrastructure using Terraform?

33. How do you deploy containers to AKS using Azure DevOps?

34. How do you add storage to pods in Kubernetes?

35. How do you manage different environments in CI/CD pipelines?

36. How do you rollback in GitHub Actions?

37. What kind of pipelines do you use---classic or YAML?

38. What kind of branching strategy do you use?

```{=html}
<!-- -->
```
39. What is Docker and why do you need it if you already have VMs?

40. Write a Dockerfile to create a custom image.

41. What is the difference between Docker image and Docker container?

42. Write YAML files for Kubernetes Service, Ingress, Pod, and
    Namespace.

43. What is Kubernetes and explain different services in Kubernetes.

44. What is a pod?

45. What is ReplicaSet?

46. How do you manage external access to services in Kubernetes?

47. How do you reduce downtime during Kubernetes deployment?

48. What are considerations for designing a Kubernetes cluster?

49. What is autoscaling strategy in Kubernetes?

50. Write some common kubectl commands.

```{=html}
<!-- -->
```
51. Do you have experience with scripting languages like PowerShell or
    Bash?

52. Write a Bash script to find and remove old files from a VM.

53. Write a Python script that swaps 'a' with 'c' and 'c' with 'a' in a
    given string.

```{=html}
<!-- -->
```
54. Application suddenly stops --- how do you check?

55. One developer cannot connect to production VM --- what steps do you
    take?

56. Scenario-based questions on database processing.

57. How do you troubleshoot pods stuck in CrashLoopBackOff?

58. Provide an example of resolving a conflict in a cross-functional
    DevOps project.

59. How do you explain deployment to non-technical stakeholders?

```{=html}
<!-- -->
```
60. What is SLA in Azure?

61. What is Harness?

62. What is a remote backend in Terraform?

63. What is continuous integration vs continuous deployment vs
    continuous delivery?

64. What is Canary deployment and Blue-Green deployment?

65. What is the role of cloud in DevOps?

66. How do you migrate on-premise applications to cloud?

67. How do you keep secrets in a pipeline?

68. What is the difference between build and release pipeline?

Cognizant

1.  Please introduce yourself and explain your day-to-day activities as
    a DevOps Engineer.

2.  What is your current organization and what is your role there?

3.  Have you worked on Kubernetes? If yes, what tasks did you handle?

4.  What is the Terraform taint command and what is its use case?

5.  What is the typical Terraform directory structure you follow?

6.  How do you write Terraform code for reusability?

7.  How do you handle zero-downtime infrastructure upgrades using
    Terraform?

8.  Do you have any idea about the lifecycle argument in Terraform?

9.  What is a null resource in Terraform and when do you use it?

10. Please explain the CI/CD pipeline process in Azure DevOps.

11. How do you integrate GitHub with an Azure DevOps pipeline?

12. How do you create a service connection between GitHub and Azure
    DevOps?

13. What Azure DevOps resources have you worked with?

```{=html}
<!-- -->
```
14. Have you connected two VNets in Azure? What are the different
    methods to connect VNets and their differences?

15. Explain your AKS load balancer experience.

16. How to configure network policy in Kubernetes?

17. What are the different types of cluster storage? How do you
    configure cluster storage?

18. What is the best practice for managing identity control in cluster
    policies?

19. What is the difference between Azure CNI and Kubernetes CNI?

20. Explain about logs in Kubernetes or Azure DevOps context.

21. From a DevOps perspective, how does Azure DevOps interact with other
    services?

22. What is deployment approval and gate approvals in Azure DevOps?

23. How to design a CI/CD pipeline using Azure DevOps methodology?

24. Explain the key concerns of microservices architecture.

25. What is scaling in Kubernetes or infrastructure context?

26. What is a high availability setup?

27. What are different Disaster Recovery (DR) options available?

28. What is ED to PC?

29. What are multiple tenants in Azure or cloud context?

30. What are ESC Tools?

31. What is AKS patch management?

32. How do you use regular expressions for redirection tools?

33. What are common troubleshooting steps you follow?

34. What is the difference between CNI and cluster networking?

35. How do you configure policies of a Kubernetes cluster?

36. What is an EKS Cluster?

37. How do you create a Kubernetes cluster?

38. What is VNet peering?

39. Have you worked with Azure Front Door (AFD) and Application
    Performance Management (APM)?

```{=html}
<!-- -->
```
40. Have you worked on any databases?

41. How did you connect a database to your local machine for testing or
    development?

42. What types of queries have you used in the database? Can you give
    some examples?

EY

1.  Write a code for virtual machine to import resource group name which
    already exists in your cloud with the help of data block.

2.  Suppose your colleague created a resource in cloud; how do you match
    your Terraform code and tfstate file?

3.  How do you manage different workspaces in your Terraform?

4.  What are the best practices you follow to make resources highly
    available and redundant in Terraform code and block to avoid
    accidental removal?

5.  Have you worked on GitHub Actions?

6.  What is the lifecycle of Terraform?

7.  What is a Docker image?

8.  Have you worked on Ansible?

9.  How do you reduce the size of a Dockerfile while deploying pipeline?

10. How do you check layers of a Dockerfile and troubleshoot?

11. How do you troubleshoot Docker containers?

12. Have you worked on Kubernetes?

13. Apart from Azure side, what DevOps areas have you worked on?

14. Have you worked on pipelines or do you have only an overview?

15. Are you proficient with IaC tools like Bicep or Terraform?

16. Have you worked on GitLab pipelines or Azure DevOps pipelines?

17. Please explain your day-to-day activities for GitHub Actions
    pipeline.

18. How are you deploying the environment---manually or automated?

19. What kinds of migration have you done: refactoring or lift and
    shift?

20. For refactoring, are you using Terraform?

21. What checks do you perform before starting a migration to assess
    client environments?

22. Please define the end-to-end cycle of migration.

23. After accessing customer environments, do you directly start
    replication or start planning? Explain the planning phase.

24. Suppose you have 2000 servers to migrate. How do you plan to
    migrate---migrate all at once or use another strategy?

25. How do you perform dependency analysis for servers and applications?

26. If you forgot a batch of servers during dependency analysis, would
    you start wave migration or something else? Which migration would
    you do first?

27. Suppose a client is using on-premise environment and wants to
    migrate to cloud but is confused. How do you convince them to
    migrate? What things do you explain to move forward?

28. What is hub and spoke, and what is the significance of hub and spoke
    architecture?

29. What is transit gateway and remote gateway?

30. Suppose you have 3 VNets: VNetA, VNetB, and VNetC. VNetA is peered
    with VNetB, and VNetB is peered with VNetC. Only VNetA is peered
    with the hub network (a separate VNet). Will VNetC be able to access
    hub resources?

31. How do you design a three-tier web application on Azure? Include
    network and security architecture, and what Azure services you would
    deploy.

32. When users try to hit the server from outside Azure, which server do
    they hit, and what security checks do you put in place?

33. How do you distribute traffic if users are across the globe and need
    scale sets?

34. Suppose your infrastructure has 3 tiers (frontend, application, and
    database). The frontend server is scaled up. How do you manage
    traffic on the backend and what network services can you use?

35. What is the difference between Private Endpoint and Service
    Endpoint?

36. What is the difference between CDN and Traffic Manager?

37. What is Point of Presence (POP)?

38. What is the significance of the Terraform statefile?

39. What is the ideal way to store the Terraform statefile?

40. Where do you configure the storage of the Terraform statefile?

41. How do you handle secrets in Terraform?

42. How do you access resources with Key Vault in Terraform?

43. How do you link services to the service principal? For example, if
    the service principal has Key Vault access and you need to fetch a
    key from the storage account to decrypt data disks?

44. How do you define modules in Terraform code? What is the
    significance of modules?

45. Write the code for Azure Container Registry (ACR) and how to call it
    using a module in Terraform.

46. What is the significance of workspace in Terraform? Why do you use
    workspace?

47. What is the use of outputs in Terraform?

48. Suppose you design pipelines and want to trigger changes on push to
    the main branch. What do you write in the pipeline code?

49. What is the difference between self-hosted and Microsoft-hosted
    agents?

50. What are the main advantages of using self-hosted agents?

51. Do you know about templates in pipelines? How do you use them in
    YAML pipelines?

52. Have you worked on Kubernetes services? Please explain the
    Kubernetes architecture.

53. Why are we using Kubernetes? What is the function of Kubernetes?

54. What do you understand by orchestration in Kubernetes?

55. What is a Kubernetes cluster?

xceedance

1.  Suppose a new joiner joins the organization. What access do you give
    them in Azure DevOps?

2.  We have three different infrastructures and the code is ready in the
    artifacts repository. How do you approach deployment?

3.  Suppose there are two projects in Azure DevOps for the same VM and
    same app, and you want a single service connection. How would you
    achieve that?

4.  Suppose we have two VMs and you have to deploy a service on both at
    the same time. What approach would you take in a single pipeline to
    deploy the app simultaneously?

5.  How do you deploy a pipeline for Terraform code? What are the steps
    you follow?

6.  You have to add a column in a debug sheet. How will you do it in
    Azure DevOps?

7.  What is the code quality percentage allowed to proceed with the
    release pipeline?

8.  What is the difference between ADD and COPY commands in a
    Dockerfile?

9.  What option do you select to add an approver in Azure DevOps
    pipeline?

10. Do we need a destroy pipeline for infrastructure? What is the
    purpose of it?

11. What is the command to check logs of a Pod?

12. What tool do you use for code quality check in pipelines?

13. SonarQube uses different environments. What access do you give in
    Azure DevOps for your pipeline to check code?

14. Suppose in your organization there are 10 projects, but a new
    developer joined. You want to give access only to 3 projects. How do
    you do that?

15. How many types of user-level access are there in Azure DevOps?

16. What is the difference between Basic level and Stakeholder level
    access in Azure DevOps?

17. If you want to add more Basic users in Azure DevOps, do you need to
    pay Microsoft? How much?

18. How many agents are available in Azure DevOps to run pipelines?

19. What is the difference between Microsoft-hosted agents and
    self-hosted agents?

20. If Microsoft provides only one agent and you want to run 10
    pipelines, how much money do you have to pay for additional agents?

21. How do you add a new field in the Bug template in Azure DevOps?

22. When a user enters the correct username and password but gets an
    invalid credential error, what could be the issue?

23. Suppose you want to deploy an application to 2 VMs at the same time.
    How would you do that using Azure DevOps pipeline?

24. What is a service connection in Azure DevOps and how do you use it
    for VM deployments?

25. Is it possible to share the same service connection across multiple
    projects in the same organization? How?

26. How do you handle different environment deployments (DEV, QA, PROD)
    in pipelines with different credentials?

27. Can you use Dockerfile instead of YAML for CI/CD? Explain.

28. Suppose you have 2 containers and the second container should run
    only after the first one has started. How do you achieve that in
    Docker Compose?

29. If all secrets (like DB name, username, passwords) are stored in
    Azure Key Vault, how do you fetch those in the pipeline while
    building a Docker image?

30. What is the difference between COPY and ADD commands in Dockerfile?

HCL

1.  What is dependency \> implicit and explicit? Share the syntax and
    chart.

2.  What is the move block in Terraform?

3.  What is a state file and where can we store it?

4.  When is the state file created?

5.  What is a lock file and why is it created?

6.  What is the difference between variable.tf and variables.tf?

7.  What is terraform.tfvars?

8.  What is a service connection?

9.  What are the things required while creating a service connection?

10. What is Basic in Azure DevOps (ADO)?

11. What is Stakeholder in ADO?

12. What are the security best practices in ADO?

13. What is dependency \> implicit and explicit?

14. How do you manage multiple subscriptions?

15. What is the difference between VM and VMSS?

16. If there is a requirement to create two VMs and two databases, which
    approach will you follow: VM or VMSS?

17. Suppose you have 1500 subscriptions; how will you manage them from
    Azure DevOps level?

18. As an architect, if you want to set up infrastructure, what will be
    your approach to provide a solution to the customer?

19. What is a linter in Terraform?

20. What is a task group?

21. What is a deployment group?

22. What is Azure DevOps?

23. What is a sprint and work item?

24. How can you secure Azure DevOps?

25. What is variable.tf and terraform.tfvars?

26. What is the output block and how do you pass this into a pipeline?

27. If you have a Terraform code till VM and you applied terraform plan
    and apply but want VM result in JSON format, what is the command?
    (Tell me the command only)

28. What tools are used for pipelines?

29. What are provisioners in Terraform?

30. If you mark a variable as sensitive in Terraform, how do you see
    this variable in the state file?

31. If you pass the value hardcoded in VM, will it show in terraform
    plan or not?

32. What is a move block?

33. Will move block impact our current infrastructure or not?

34. Give an example of a recent template upgrade in Terraform.

35. What data types are you familiar with in Terraform?

36. After which command is the state file created?

37. What is the stage where Terraform downloads modules and providers?

38. What backends are you familiar with?

39. How do you encrypt the state file?

40. You are creating a variable in Terraform and need to provide its
    default value. What argument will you declare?

41. You have a VM created through Terraform and installed Microsoft
    Office after VM creation. If you run terraform apply again, what
    will happen to Microsoft Office?

42. What are lifecycle rules in Terraform, and where are they declared?

43. What are dependencies in Terraform?

44. What are gates in Azure DevOps?

45. Is macOS supported as an agent pool?

46. In Azure, what is an availability set?

47. How many types of variables are declared and stored?

48. What is the provisioners block? How many types and when do you use
    it? Give examples.

49. What is Ansible and why do we use it?

50. Tell use cases combining Terraform and Ansible.

51. A new feature is not present in Terraform. How would you provision
    it in Azure portal through Terraform?

52. You manually created 10 VMs in different resource groups, and now
    want to automate it using Terraform. How do you update the state
    file for existing resources?

53. Terraform backend and state file management?

54. To validate Terraform code, do you need to execute terraform init?

55. Share your experience in CI/CD pipelines and tools used.

56. Have you used GitHub Actions in CI/CD?

57. Have you worked on GitHub Actions?

58. Do you have experience in Terraform?

59. Rate yourself on CI/CD pipelines out of 5.

60. Have you worked on Docker?

61. Have you worked on Kubernetes?

62. When do you suggest Docker and when Kubernetes for deployment?

63. Rate yourself in Docker out of 5.

64. Rate yourself in Kubernetes out of 5.

65. Rate yourself in Terraform out of 5.

66. Are you using Helm charts?

67. Rate yourself in Helm charts out of 5.

68. Among AWS, GCP, and Azure, which are you most comfortable with?

69. Have you deployed Docker and Kubernetes related deployments in
    Azure?

70. What Azure services have you used?

71. Rate yourself in Azure out of 5.

72. You have Python automated scripts to automate testing during
    deployment. How do you write test scripts that run on Docker
    containers and push the build to remote repo once tests pass?

73. Have you used any monitoring tools?

74. How have you used Prometheus and Grafana and for what activities?

75. Rate yourself in Monitoring and Observability out of 5.

76. Have you heard about vulnerability scanning?

77. How do you integrate vulnerability scanning for automated security
    checks?

78. Have you implemented any security measures or tools?

79. Rate yourself in Security & Compliance out of 5.

80. In Azure, have you deployed microservices with High Availability and
    Disaster Recovery strategies?

81. You have 20 microservices in Docker. How do you check the health
    status of each service?

82. Rate yourself in Disaster Recovery and High Availability out of 5.

83. Have you worked on version control tools like Git? What are your
    daily activities?

84. Rate yourself in Version Control out of 5.

85. Have you worked on Dockerfiles?

86. What scripting languages have you worked with and which are you most
    proficient in?

87. Can you share your screen and open a compiler or interpreter?

88. Rate yourself in scripting out of 5.

Neosoft ltd pune

1.  **What are the types of load balancers?**

2.  **What is the difference between ASG and NSG?**

3.  **What is Azure Firewall?**

4.  **What is the lifecycle of Terraform?**

5.  **How do you maintain different workspaces in Terraform?**

6.  **Can we implement NSG on VNet, Subnet, or at Virtual Machine
    level?**

7.  **How do you reduce the size of a Dockerfile?**

8.  **What is the use of CMD in Docker?**

9.  **What does the output block in Terraform do?**

10. **How do you manage manually created resources in your Terraform
    pipeline?**

11. **Application load balancer uses which protocol?**

Infy architect

1.  **What is your role and job in your current project?**

2.  **How did you create a pipeline for a Java application?**

3.  **Where do you store the code artifacts, and how do you deploy those
    artifacts on Azure Cloud?**

4.  **How are you setting up Azure Kubernetes Service (AKS) in your
    application pipeline?**

5.  **How do you manage sensitive information in your pipeline?**

6.  **How do you fetch sensitive information from Azure Key Vault to
    your pipeline?**

7.  **Can you explain the stages, tasks, and steps you defined in your
    application code pipeline?**

8.  **How do you connect your Terraform code with the Azure portal
    without using VS Code terminal?**

9.  **What is a Terraform module?**

10. **Which Azure services have you worked with?**

11. **How do you create a Virtual Machine in Terraform?**

12. **What do you do after you have created the code for a Terraform
    module?**

13. **What is Azure Front Door?**

14. **Do you know PowerShell and Bash scripting?**

15. **What is the correct answer for the workflow of Terraform?**

Mphasis

1.  **What is null resource in Terraform?**

2.  **What is the difference between providers and provisioners?**

3.  **What is the use of user_data in Terraform, and what is
    userdata.tpl? (Hint: provisioning one server from another)**

4.  **How are state files managed in your organization?**

5.  **If 20 servers are created (with specific memory, CPU & software)
    via Terraform and later you want to upgrade the software on all of
    them at once, how would you do it (using Terraform or not)?**

6.  **Why is the terraform taint command used?**

7.  **What are best practices to use Dockerfile and minimize image
    size?**

8.  **What is the difference between CMD and ENTRYPOINT in Docker?**

9.  **If both CMD and ENTRYPOINT are mentioned in a Dockerfile, which
    one takes precedence?**

10. **What monitoring tools do you use? (e.g., Prometheus/Grafana)**

11. **How does Prometheus work and how does it collect data?**

12. **Have you worked on any configuration tools like Ansible or
    Puppet?**

13. **What kind of servers are you managing? (e.g., IIS, NGINX)**

14. **What is the hierarchy of deployment in a CI/CD pipeline?**

15. **Do you have any scripting knowledge? What is your process if
    you\'re given a file to work on?**

16. **Introduction**

17. **What is the workflow of Terraform?**

18. **What is a Tenant ID in Azure?**

19. **What is Blob Storage in Azure?**

20. **Which tools are you using in your project?**

21. **What types of issues are you facing on a daily basis?**

22. **How do you add or remove a VM in Terraform?**

23. **What is a Terraform module?**

24. **Do you know Docker and Kubernetes?**

25. **Do you have experience working on multi-cloud environments?**

26. **What are three major issues you have faced in DevOps, and how did
    you resolve them?**

27. **How do you securely access an API in your DevOps workflow?**

28. **If a resource becomes deprecated, what lifecycle management
    strategy or rule do you apply?**

29. **How do you prevent a specific subnet from accessing an App
    Service?**

30. **How do you use route tables in combination with a firewall to
    control traffic flow?**

31. **How do you securely access secrets from a Key Vault?**

32. **How do you access a Terraform state file locally?**

33. **If a Kubernetes pod is OOMKilled, how do you troubleshoot and
    resolve it?**

MYgroup

1.  **What is Azure Functions?**

2.  **What is NAT and what is an Application Gateway in Azure?**

3.  **What is a sidecar container?**

4.  **Can we deploy more than one container in a single pod?**

5.  **What is a taint in Kubernetes and why is it used?**

6.  **What are headless services in Kubernetes?**

7.  **What is a deployment set in Kubernetes?**

8.  **What is Docker Swarm?**

9.  **What is ARG in Docker and how is it used?**

10. **How do you manage Terraform state files, especially when working
    with multiple state files?**

11. **Why do you use MySQL over other databases? What are its
    benefits?**

12. **If you are using a CIDR range like /16 and have thousands of IP
    addresses, what is your approach to manage them efficiently?**

13. **If 150 people are using the same backend, how would you handle or
    recognize them individually?**

14. **What is the difference between a root module and a child module in
    Terraform?**

15. **If you don't want to hardcode the IP address in the main.tf file,
    how would you manage it?**

16. **What is the use of the top command in Linux?**

17. **What is a StatefulSet in Kubernetes?**

ParentPay

1\. What is count and for each.

2\. How you do lookup in Terraform.

3\. What are different type agents in pipeline.

4\. What are different Azure services.

5\. In Kubernetes what is ingress.

6\. Introduction about yourself.

7\. If you have a deprecated resource and cannot delete it . How can you
migrate to a new resource which has new features.

8\. How can you change a single resource without impacting
infrastructure.

9\. What is Application scaling.

10\. What are Branching policies.

LTI Mindtree

1.  **Can you tell me about your projects that you have worked on?**

2.  **What services have you used in Azure?**

3.  **How do you connect your VM with a private IP?**

4.  **What is VNet peering?**

5.  **What is the difference between a route table and a Network
    Security Group (NSG)?**

6.  **What is an Application Gateway?**

7.  **How is Application Gateway different from a Load Balancer?**

8.  **How do you patch your VM?**

9.  **If a vendor pushes a patch while a developer is working on a VM,
    how will you handle this delta patching?**

10. **What is swap space in a Linux VM?**

11. **Where can you find Microsoft's updates about upcoming Azure
    services? Which page/website?**

12. **How have you configured backups for your environment?**

13. **Where are your VMs located? Which region?**

14. **Where are your Disaster Recovery (DR) servers located?**

15. **How have you configured your Disaster Recovery setup?**

16. **How have you set up monitoring for VMs?**

17. **If your VM goes above 80% CPU utilization, how will you get
    notified?**

18. **How do you configure alerts using Azure Monitor?**

19. **What is the difference between Automation Account and Function App
    in Azure?**

20. **How do you horizontally scale your App Services in Azure?**

21. **How do you access a Storage Account in Azure? How is it securely
    configured?**

22. **How do you manage your Terraform state file?**

23. **How do you access the Terraform state file from your local CLI?**

24. **Give a case scenario: if a client gives a requirement to deploy a
    landing zone, what would your approach be?**

25. **If an architect provides a High-Level Design (HLD) for Azure
    Virtual Desktop, how would you deploy it as the sole responsible
    person?**

26. **After environment deployment, if access is not provided or a
    firewall port is closed, how would you troubleshoot connectivity
    issues?**

27. **What challenges have you faced in the past, and how did you
    resolve them?**

28. **In your previous organization, what were the major problems you
    encountered and how did you overcome them?**

29. **You are given 10--15 days to deploy 4000 VMs using Terraform ---
    how will you approach this?**

30. **How do you troubleshoot a VM in Azure?**

31. **What are the key services available in the Azure DevOps portal?**

32. **How do you set up monitoring in Azure?**

33. **How do you set up Splunk for monitoring in Azure?**

34. **What is KQL (Kusto Query Language)? Can you write or explain any
    query used in Log Analytics?**

35. **If you\'re unable to SSH into a VM, what steps will you take to
    troubleshoot and resolve the issue?**

36. **How do you configure alerting in Azure DevOps?**

37. **How do you collect performance or log data from a VM?**

38. **If you have two subscriptions in Azure DevOps, how will you give
    access to new resources across them?**

39. **How is KQL used in Log Analytics?**

**DB Schenker**

1.  How are you doing today

2.  Tell me about yourself

3.  What all resources you have worked on Azure, how you deploying all
    these

4.  Terraform state

5.  Difference between Terraform init, plan and apply

6.  What is disaster recovery? How you handle the disaster recovery in
    Azure?

7.  Have you performed any disaster recovery?

8.  Multiple engineer working on same state file, will they get any
    error?

9.  Suppose server is hosted in availability zone 1, if breach happens
    what preventive steps should users take to avoid this in Azure?

10. How to increase the data disk in Azure

11. I have 100 GB disk, I want to add 50 GB more --- how?

12. Suppose you are working in a feature branch and you are merging it
    to main branch --- how do you resolve conflict?

13. Suppose teammate accidentally deletes unmerged commit and main
    branch --- how you recover it?

14. Suppose teammate accidentally deletes unmerged commit and feature
    branch --- how you recover it?

15. How you recover the lost work?

16. What is Jenkins file

17. What all the tools you used in Azure DevOps

18. Have you performed in-place OS upgrade? What are prerequisites and
    how you done?

19. Suppose you restart a server, server got hung and from the serial
    console it stuck on dracut emergency shell --- how you resolve the
    error?

20. How do you resolve the kernel panic error?

21. What steps you take if getting error access denied while creating
    IAM role?

22. Suppose user is not able to do SSH in Azure VM --- what steps you
    will take to resolve the issue?

23. How you automate the patching in Azure?

24. What is Satellite server, how you do?

25. What is the role of Azure Update Management?

26. Difference between Azure Load Balancer and Application Gateway?

27. Suppose you have a URL, and user is trying this URL but getting 503
    error --- how you resolve?

28. Have you worked on Azure App Services? What is it? Why is it used?

29. What is variable group?

30. How do you handle the deployment roll back in Azure DevOps?

31. How do you handle the multiple environment in Azure DevOps?

32. Do you know what is blue-green deployment in Azure?

### 

### 

### 

### **Celebal Technology**

1.  Tell me about yourself

2.  What all tools you have used in DevOps?

3.  What are the components/services Azure DevOps provide?

4.  What is the difference between CI and CD?

5.  What is VNet?

6.  Difference between Git and TFVC?

7.  What is artifacts?

8.  Difference between Azure DevOps and Jenkins?

9.  What are the benefits of Azure DevOps over Jenkins?

10. What is branch policy?

11. What is service hooks?

12. What are the security features available in Azure DevOps?

13. What is build definitions?

14. How to manage dependency?

15. What is the purpose of pipeline artifact?

16. What are the different types of trigger?

17. How do you implement rollback in Azure DevOps?

18. What is IAC?

19. What is blue-green deployment?

20. What types of projects have you done? What types of domains?

21. What is the lifecycle of DevOps engineer?

22. What is peer programming?

23. Architecture of DevOps

24. What is sudo concept?

25. Do you know postmortem in DevOps?

26. Can you explain the \"left to reduce failure\" concept in DevOps?

27. How can you ensure a script runs every time the repository gets a
    new commit through git push?

### 

### 

### 

### 

### 

### 

### 

### 

### **Locktown**

1.  Tell me about yourself

2.  Can you explain a little about application pipelines, what tools you
    worked with, and describe every stage?

3.  How do you handle secrets?

4.  How do you handle the approvers and check?

5.  Have you worked on Terraform? How do you manage the state file?

6.  Apart from blob storage, where else can the state file be found?

7.  Suppose some resources were deleted from the Azure portal, what is
    drift?

8.  Terraform deployment failed midway --- how do you recover it?

9.  Terraform apply command failed --- how do you resolve it?

10. On Azure side, what all services have you worked on?

11. How do you handle core rules in blob storage settings? What is the
    purpose of that?

12. Have you worked on virtual machines? What types of applications have
    you deployed?

13. How do you build React frontend application in your pipelines?

14. Let\'s say you did a deployment on Friday and on Monday suddenly the
    application stops working --- what are the troubleshooting steps?

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### **Metacube**

1.  Tell me about yourself

2.  List down the services of Azure you have worked on

3.  Difference between point-to-site and site-to-site VPN

4.  Have you heard about NSG? Suppose I create one NSG and apply it to
    NIC of VM in virtual network ---

5.  I created another NSG at subnet level for the same VM --- which NSG
    gets priority?

6.  One NSG port 22 allow, another NSG port 22 block --- can I SSH from
    my system?

7.  What is defined in NSG? In inbound rules, what do we define?

8.  What is Azure Bastion?

9.  What are the types of storage accounts in Azure?

10. Storage account tier --- what is that? Difference between hot and
    cool?

11. Accidentally deleted the state file and some resources exist in
    Azure --- how do you manage the resources?

12. I deleted the state file and want to attach tags to resources in
    portal --- how would you do that?

13. In null resource block, what will you mention? Write the code of
    null resource.

Citius Technology

1.  **What is this job for, and why do you think you are the right fit
    for it?**

2.  **What is your work style? How do you typically approach your
    tasks?**

3.  **Can you describe your current role, especially in operations and
    automation?**

4.  **What are the main roles and responsibilities in CloudOps
    (operations)?**

5.  **How do you perform patching?**

6.  **What is the process you follow to deploy patches in a production
    environment?**

7.  **Do you have experience with Bash scripting? Please explain.**

8.  **What are some common troubleshooting commands you use? (Give only
    the exact commands.)**

9.  **Do you have experience with Azure monitoring? How do you set it
    up?**

10. **What is a host in computing or cloud terminology?**

11. **Where are you using YAML files? Why are YAML files used?**

12. **What resources have you created in Azure?**

13. **How do you collaborate with your team? How do you handle or lead a
    team?**

14. **Can you give examples of Standard Operating Procedures (SOPs)
    you've created or followed? Explain.**

15. **When do you usually handle releases, and what challenges have you
    faced during release cycles?**

16. **Can you troubleshoot a DNS issue? For example, if vikram.com is
    not showing in Google, how would you approach this?**

17. **Which users are allowed to use a subscription? How do you manage
    and assign access to users in Azure?**

18. **Where do you see yourself in the next 5 years?**

19. **What skills have you added or improved in the past few years?**

20. **Why are you looking for a change in your current role? What
    repetitive tasks are you currently doing that you want to move
    beyond?**

Evalueserve

1\) introduction

2\) what is module

3\) where you save statefile

4\) can we save statefile on other place except backend storage

5\) how we send code 1 terraform to other terraform

6\) what is the diff in validate and fmt

7\) write script memory \> 90 and copy from one server to another server

8\) what is the flow of terraform

9\) what is ci cd

10\) which agent are u use in azure devops

11\) what is pod in docker

12\) write a terraform code of vm

Avigna.ai

1\. Tell me about yourself.

2\. Roles and responsibilities, team size.

3\. What azure services have you worked on.

4\. How will you do deployments in AKS. What is imagepull secret.

5\. How will you do deployment in Azure Webapps..both microservices and
monolithic deployment.

6\. 5 linux commands.

7\. How will you troubleshoot if in app insigh your rest api is throwing
\"connection refused\" while connection to sql instance

8\. What is private endpoint.

9\. Why you want to switch?

All Infinite

1\. How to take backup of a SQL Server database using SQL query.

2\. customer table and customer transation how will fetch particular
customer (65)transcation deatile.

3\. some production data rollback database.

4\. How to check security and vulnerabilities

5\. if any vulnerabilities is there how to fix it in database.

6\. Have u used application pipline

7\. which os you using linux, window.Any script language you are using.

8\. Mutual Authentication Between Load Balancer and Backend?

9\. How Many Domains Can Azure Front Door Handle?

10\. Have you used tsql query?

Glorious Insight

1\) what is azure function

2\) what is keyvault

3\) what is AKS and ICS

4\) what is loadbalancer

5\) what are the type of loadbalancer

6\) introduction

7\) what is Types of availability zone support

Publicis Sapient

1.  **What is agent-based and agent-less monitoring?**

2.  **What is a landing zone in cloud architecture?**

3.  **What is hub and spoke architecture in Azure?**

4.  **What is Azure Arc and how is it used?**

5.  **What are the types of storage available in Azure?**

6.  **What is the difference between Blob Storage and File Storage in
    Azure?**

7.  **What are the types of disks in Azure?**

8.  **Tell me about your recent project.**

9.  **What is a Virtual Network (VNet) in Azure?**

10. **How are you balancing traffic in the cloud?**

11. **How many types of load balancers are there in Azure?**

12. **What is priority in a Network Security Group (NSG) rule?**

13. **What is the difference between a Service Endpoint and a Private
    Endpoint?**

14. **How do you securely access your cloud resources?**

15. **What is Azure Bastion and why is it used?**

16. **What are NSG (Network Security Group) rules in Azure?**

17. **How do you restrict access to any service on a specific
    resource?**

18. **What network topology have you worked with?**

19. **How do you connect an on-premise application to the cloud?**

20. **Where do you store your Terraform state file?**

21. **What is the lifecycle block in Terraform?**

22. **If you run a pipeline and it fails after apply, and you're stuck
    in a Terraform lock state, how will you resolve the issue?**

23. **If you are calling a variable from Key Vault but do not want to
    mention it in the pipeline or Terraform code, how would you handle
    it?**

24. **We have Dev, Prod, and Staging branches. We want to trigger a
    pipeline only when the Dev pipeline passes 90%. Write a condition in
    YAML for this.**

25. **Write a shell script that sends an alert email if a VM disk
    reaches 80% full.**

CitiusTech

1\. Introduce your self

2\. How do you manage banckend state management

3\. describe a real time scnario where you used terraform configuration
to minimize the complexity of your code

4\. What issues you faced while migrating your infrastructure to
Kubernetes cluster

5\. 1 question realted to Pulumi , I cannot recall exactly

6\. How do you manage running parallal jobs in Azure Devops

7\. How do you manage alerting using Prometheus and Grafana

8\. wHat is lifecycle in terraform

9\. What are the basic troubleshooting you have done in terraform

10\. How to manage reuasbility and maintenability of configuration in
terraform

11 .There was one coding question related to AWS in terraform
incorporating DR and IAM . I cannot recall the exact question

Parentpay

1\. introduce yourself

2\. Can you ping one vm in one vnet with anther vm in another vnet.

3\. How can you create the connectivity between them.

4\. If the vms are in different subscriptions how will you achieve the
same.

5\. Difference between owner , reader and contributor rights.

6\. What is service connection and service principle

7\. If there are 1000 blob containers in 1 storage account, how will you
migrate them to another storage account.

8\. What is backend state management

9.if you have an sql block in terrafrom which has deprecated and you
want to change it but there is already some data in the current sql
database , how will you achieve it

10\. I I want to read the details of keyvault , what role should be
assigned to me

11\. how to import secrets in keyvault in your pipeline.

12\. Any other way you can achieve it other than variable groups.

13\. What is deployment group in azure pipeline

14.Tell me the entire workflow in azure piepline.

15\. What is multi stage pipelines

16\. Have you worked on kubernetes

17.what can you use as a backend pool in a load balancer

18 Do you have any experince with alert monitoring tools

19.extensions in azure pipeline

Ntt Data

1 .intro

2\. Difference between git revert and reset

3\. Difference between git fetch and git pull

4\. Difference between COPY and ADD

5.If you are having any issue in a container how can you check and
troubleshoot it

6\. Suppose I am working on a feature branch and you are working on a
different feature branch, now I want to merge these 2 feature branches
together , how will I achieve it

7\. Can you tell me the command to create a container from an image

8\. Write a dockerfile and explain it

9\. We are working on a banking project so, we do not have direct access
to internet, how will you execute npm install

10\. Explain workflow of pipeline

11\. How can we enter inside a particular container.

12\. What does tflint do

13\. What is the linux command to compress a file

14.git rebase

Dover

1.  **Tell me about your education, work experience, and day-to-day
    activities.**

2.  **Have you heard about Dover before?**

3.  **Which cloud platforms do you have experience with? Have you worked
    with any others beyond your primary one?**

4.  **Do you have experience in Terraform? How would you rate yourself
    out of 10?**

5.  **What resources have you provisioned using Terraform?**

6.  **Tell me about the Terraform state file --- what it is and how it
    works.**

7.  **If you were to create an AKS cluster using Terraform, what would
    be your high-level approach?**

8.  **Have you worked on Kubernetes?**

9.  **What is a Network Security Group (NSG) in Azure?**

10. **In Kubernetes, what are masters, nodes, and pods? Can you briefly
    explain the AKS cluster design?**

11. **What are node pools in AKS?**

12. **How do you monitor logs for an AKS cluster?**

13. **Have you worked on any monitoring tools? Which ones?**

14. **Suppose there's an application deployed on Azure App Services and
    it goes down (as informed by a customer) --- how would you
    troubleshoot it?**

15. **Can you share a recent incident from your current project where
    something broke in production? How did you resolve it, and what
    preventive measures did you take?**

16. **How many environments (e.g., dev, test, staging, prod) have you
    managed?**

17. **Are you available to work in shifts and be on-call?**

18. **What is your notice period? Since your colleagues were released in
    30--45 days, are you also expecting the same?**

19. **Have you worked on cost optimization in cloud projects?**

Altud

1.  Have you recently worked with Kubernetes and Azure PaaS?

2.  How do you maintain container security in Kubernetes deployment?

3.  How do you ensure the images used in your containers are secure and
    not vulnerable?

4.  What tools can you use to scan for code vulnerabilities or follow
    best practices in infrastructure as code?

5.  Can you provide examples of linting tools used in Terraform?

6.  What does TFLint do in Terraform?

7.  How do you handle blueprint deployments in Kubernetes?

8.  Is there a master step configuration in Kubernetes?

9.  What do you understand by rolling deployments in Kubernetes?

10. How do you achieve rolling deployments?

11. After deployment, if a pod goes down, how do you ensure the website
    is not affected? How do you handle rollbacks and troubleshooting?

12. Can you list common errors due to which Kubernetes pods don\'t come
    up post deployment?

13. What are common causes for Kubernetes pods getting stuck in loopback
    or crashloop errors?

14. How do you resolve Kubernetes deployment issues using pod logs?

15. What challenges do you face when deploying AKS using Terraform?

16. If your AKS cluster is private and subnet IPs are exhausted, how do
    you handle that situation?

17. Can you increase the IP range of an existing subnet in Azure?

18. What is a pod distribution budget in AKS?

19. What is the difference between a deployment and a stateful set in
    Kubernetes?

20. What does a Pod kind component do in Kubernetes?

21. What is a Persistent Volume Claim (PVC) in Kubernetes?

22. If a container is facing performance issues, how do you check its
    CPU and memory usage?

23. What command can be used inside a container to monitor performance?

24. Have you ever upgraded an AKS cluster using Terraform?

25. What types of application migrations have you handled recently?

26. How do you migrate a function app to AKS?

27. What tools have you used to migrate on-prem infrastructure to Azure?

28. How do you call a shared Terraform module from multiple repositories
    in Azure DevOps pipelines?

29. If the shared repository is private, how do you authenticate and
    pull code in a CI/CD pipeline?

30. What is the difference between self-hosted and Microsoft-hosted
    agents in Azure DevOps?

31. If a VM or web app is private, can you use a Microsoft-hosted agent
    for deployment? Why or why not?

32. How do you ensure a specific pipeline runs only on a Windows agent
    when using a shared agent pool?

33. What approach do you take to set up CI/CD for 20+ .NET backend
    microservices?

34. What would you do differently if you had 100+ microservices instead
    of 20?

35. Have you worked with reusable templates in Azure DevOps?

36. How do you securely access secrets from Azure Key Vault during
    CI/CD?

37. If migrating CI/CD from Azure DevOps to Jenkins or GitHub Actions,
    how do you handle the lack of built-in templates?

38. What is a deployment group in Azure DevOps?

39. What is an environment in Azure DevOps?

40. What is an approval gate in Azure DevOps?

41. What happens if your Terraform state file gets corrupted?

42. How can you recover a corrupted Terraform state file without using
    Azure Storage Account?

43. What is the .terraform.tfstate.backup file, and how can it be used?

44. What is the Terraform import command used for?

45. Have you worked with Helm charts?

46. What types of applications have you deployed previously?

47. Where (VMs, PaaS, AKS) were the applications deployed?

48. How do you distribute load across applications deployed in VMs?

49. What is the difference between a Load Balancer and an Application
    Gateway in Azure?

50. What does a Web Application Firewall (WAF) do?

51. How will you use a Web Application Firewall (WAF) if your
    organization is using a third-party firewall like Palo Alto or
    Zscaler, and you don't want to use Azure Firewall?

52. Is the only difference between Azure Application Gateway and Load
    Balancer the fact that one operates at Layer 7 and supports WAF?

53. Can Application Gateway distribute traffic based on content, and is
    that feature available in Load Balancer?

54. Suppose you have a private storage account and a private VM deployed
    in the same subnet. When you try to access the storage account from
    the VM, you get a 403 Forbidden network error. How would you
    troubleshoot this issue?

55. What could be the possible causes for the VM not being able to
    access the storage account, even though they are in the same subnet
    and NSG rules are correct?

56. Are you familiar with Private DNS zones in Azure?

57. Could a missing or incorrect Private DNS record cause the issue
    where the VM cannot resolve the storage account endpoint?

58. Have you worked with Azure App Services?

59. What are deployment slots in Azure App Service?

60. Have you worked with Azure SQL Database?

61. What is the difference between Azure SQL Database and SQL Elastic
    Pool?

62. Have you worked on upgrading services (e.g., AKS upgrades)?

63. Which services are you most experienced with in terms of monitoring
    and configuration?

64. Which tools are you primarily using (e.g., Terraform, Azure DevOps,
    Git)?

Opstree

1.  Introduce yourself

2.  What is your day-to-day activity?

3.  What kind of defects do you get?

4.  Explain the latest defect. How did you resolve it? How do you ensure
    it doesn\'t happen again in the future?

5.  What kind of infrastructure have you provisioned into Azure Cloud?

6.  What is the difference between Application Gateway and Azure Front
    Door?

7.  What is Terraform Workspaces?

8.  How do you provision any infrastructure using Terraform?

9.  What is the data block in Terraform?

10. How do you handle secrets in Terraform?

11. Rate yourself in Terraform.

12. What is the difference between App Services and a Service Principal?

13. What is App Services?

14. How much experience do you have in Linux?

15. How do you check memory and CPU usage in Linux?

16. Rate yourself in Linux.

17. Explain a Kubernetes cluster.

18. What resources have you deployed using Kubernetes (K8s)?

19. What is the difference between Deployment and \_\_\_? *(Note:
    Question seems incomplete)*

20. What are Services in Kubernetes?

21. How do Services work in Kubernetes?

22. What is RBAC (Role-Based Access Control)?

UST Global

1\. git project size is very huge 20 gb how reduce size how to better
way maintain and lot of conflict happening in how to avoid this type
issue, what is your suggestion(repo model).

2\. How to maintain distributed repo model.

3\. what is better branching strategy and avoid the conflict (tool or
plugin)and don\'t want to solve manual conflict issue.

4\. In our CI pipeline take to much time for run. how Speed Up CI
Pipelines .

5\. junior by mistake changed in testing environment but that is for dev
environment how to correct.

6\. Is it possible to create jenkins job and run it.

**Accolite Digital**

1.Introduce yourself and brief your project and day to day
responsibilities

2\. Terraform lifecycle

3\. ⁠diff between terraform taint and destroy command.

4\. Write Yaml file for VM creation using ado pipeline

5\. what is SonarQube.

6\. Monolithic vs Microservices

7\. Docker all commands with their use case.

8\. K8s architecture and create a yaml for policy control. PV and PVC.

9\. Diff between different load balancer you used in azure.

10\. Components of different load balancers.

11\. vnet peering vs express route

12\. write code for log analytic and diagnostic using terraform.

13\. dierrent types of quer editor in azure monitoring

14\. what role you assigned in K8.

15\. docker swarm vs K8

16\. Explain all 3 git merge, git rebase, and git stash.

17\. What is the difference between head, head\^, head\~1, head\~2, and
head@{1}

18\. You accidentally committed sensitive data (like a password). How do
you remove it completely from Git history

19\. What is the .git folder structure and what are key files inside it

20\. You did a rebase and now your history is messed up. How do you
recover

21\. How does Kubernetes integrate with cloud-native services like Azure

22\. What is a NetworkPolicy and how does Kubernetes enforce it.

**Vlink**

1.  Your task is to design a generic pipeline which can be used for Java
    Spring Boot microservices application --- how would you approach
    dockerizing the application and deploying it to AKS?

2.  Which build tool is used for Java applications, and how do you push
    the Docker image to Azure Container Registry (ACR)?

3.  How do you design a CI/CD pipeline for a .NET application?

4.  Write a Dockerfile from scratch and explain each step.

5.  How do you deploy an application to AKS (Azure Kubernetes Service)?

6.  Secrets are stored in Azure Key Vault --- how do you retrieve them
    in your CI/CD pipelines?

7.  If your source code is in one Azure repository and your pipeline
    YAML is in another, how do you reference the source code repo in
    your pipeline?

8.  What is the Terraform state file?

9.  If the Terraform state file is accidentally deleted, how do you
    troubleshoot or recover it?

10. You have multiple providers in Terraform like Azure and AWS --- how
    do you manage these providers in your Terraform code?

11. During which step is the provider plugin downloaded in Terraform?

12. How do you check running processes in Linux?

13. How do you kill a process in Linux?

14. How do you check if a port is open in Linux?

**Xebia**

1\. Introduce yourself with your education background, work experience

2\. Tell me about your project

3\. How have you deployed your projects? Dockerfile and CICD pipeline?
Or how?

4\. Have you done setup for monitoring, creating dashboard and all ?

5\. If I have to create 2 VM ,one in azure another in AWS, can we do it
using a single code and applying terraform command at once?

6\. What is self hosted agent ?

**intelliswift**

1.  Introduce yourself.

2.  What is a Storage Account lifecycle in Azure?

3.  What is Azure HLD (High-Level Design)?

4.  How do you manage Terraform for multiple environments (e.g., dev,
    staging, prod)?

5.  How do you provide input to create hundreds of VMs using Terraform?

6.  If a pod is in **Pending** state, how do you troubleshoot and fix
    it?

7.  If a pod shows **CrashLoopBackOff** or **ImagePullBackOff**, how do
    you troubleshoot and fix it?

8.  Share your screen and open Notepad. Write a basic pod.yaml file.

9.  How do you break or unlock a Terraform state file if it is locked
    due to a failed operation?

10. How do you manage communication between two storage accounts without
    using VPN or Load Balancer?

11. What is UDR (User Defined Route) and how is it used in Azure
    networking?

12. How do you provide security to a Virtual Machine in Azure?

13. What is the command to check logs of a Kubernetes pod?

14. Can you explain how to manage a branching system in Git?

15. If both you and I raise a Pull Request (PR) and mine gets merged
    first, how do you handle your PR to avoid conflicts and proceed?

16. What security tools can be implemented in a CI/CD pipeline to ensure
    code quality and vulnerability scanning?

17. If a CI/CD pipeline fails, how do you troubleshoot and fix it?

18. What is the difference between NSG (Network Security Group) and UDR
    (User Defined Route)?

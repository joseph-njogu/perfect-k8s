# perfect-k8s

+ Perfecting kubernetes and using ansible to deploy it to production servers
+ In this repo, we focus on k8s for orchestrating docker images on production.
+ We will use Ansible as the deployment tool instead of helm or other tools.
+ Both Ansible and K8s use YAML as the main language.

## Master
+ We will have one cluster which will serve as the master controlling the workers.
 ## Workers
 + For scalability purposes we will have two workers.

 Mater and workers will be three individual vm instances on cloud.

 + For our use case here we will manage our own kubernetes clusters rather than using  managed service in cloud, GKE or EKS for the reasons known to us.
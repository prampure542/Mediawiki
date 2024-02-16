# Mediawiki

AWS_VPC.yaml deploys VPC, subnet and route tables in AWS account, and AWS_EKS deploys EKS Cluster and nodegroup.

Steps followed :
1. Deploy AWS VPC resources
2. Deploy/create EKS cluster and nodegroups along with namespace.
3. Deploy media-wiki application and service.
4 Set up Media wiki by connecting to db.


List of additional things that are required: 
1. Addition of certs.
2. Cluster-autoscaler
3. Ingress with DNS resolution.
4. CI/CD to automate deployment.

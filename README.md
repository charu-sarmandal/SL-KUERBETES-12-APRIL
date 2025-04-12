## Kubectl Commands

kubectl api-resources

## Kubectl Command to Connect to AWS EKS Cluster

aws eks --region ap-south-1 describe-cluster --name hiteshCluster --query cluster.status

aws eks --region ap-south-1 update-kubeconfig --name hiteshCluster


## Kubectl Commands

kubectl api-resources

## Kubectl Command to Connect to AWS EKS Cluster

aws eks --region ap-south-1 describe-cluster --name hiteshCluster --query cluster.status

aws eks --region ap-south-1 update-kubeconfig --name hiteshCluster

## AWS CLI Downlaod and Install

https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html#getting-started-install-instructions

## Kubectl Context Commands

kubectl config current-context

kubectl config get-contexts

kubectl config use-context docker-desktop

## Undo Deployment

kubectl rollout undo deployment nginx-deployment-recreate

## HPA Demo

https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale-walkthrough/

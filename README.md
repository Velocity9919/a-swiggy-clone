Deploying the Swiggy clone app with Terraform, Kubernetes, and Jenkins CICD.

Cleanup

1--Delete EKS Cluster

$ eksctl delete cluster virtualtechbox-cluster --region ap-south-1     OR    eksctl delete cluster --region=ap-south-1 --name=virtualtechbox-cluster

2--Delete EC2 Instance with below Terraform Command

terraform destroy







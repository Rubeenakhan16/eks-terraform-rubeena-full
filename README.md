# eks-terraform-rubeena-full


I have created this in the singapore region that is us-southeast-1 so when you configure the user you must use the singapore region itself because ami will be different for the different region 


https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html  -- this is for the installation of kubectl in the kubectl server 

commands after the kubectl is installed ..

aws eks --region ap-southeast-1 describe-cluster --name pc-eks --query cluster.status
aws eks --region ap-southeast-1 update-kubeconfig --name pc-eks

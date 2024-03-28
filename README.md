# eks-terraform-rubeena-full



step 1 
once you clone this repo you need to configure with aws configure <access key and secret key>
step2 
once the master and nodes created ssh to the master and do aws configure again 
command for EKS cluster setup in kubectl server: 
aws eks --region ap-southeast-1 describe-cluster --name pc-eks --query cluster.status
aws eks --region ap-southeast-1 update-kubeconfig --name pc-eks

step3
you need to run this following commands to add the cluster 


step4 
install the kubectl by following up this document https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html












I have created this in the singapore region that is us-southeast-1 so when you configure the user you must use the singapore region itself because ami will be different for the different region 


https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html  -- this is for the installation of kubectl in the kubectl server 

commands after the kubectl is installed ..

aws eks --region ap-southeast-1 describe-cluster --name pc-eks --query cluster.status
aws eks --region ap-southeast-1 update-kubeconfig --name pc-eks

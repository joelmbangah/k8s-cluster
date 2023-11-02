## https://docs.aws.amazon.com/eks/latest/userguide/add-user-role.html 

## https://antonputra.com/kubernetes/add-iam-user-and-iam-role-to-eks/#add-iam-user-to-eks-cluster

k get configmap -n kube-system 

kubectl edit -n kube-system configmap/aws-auth

cd ~/.kube/  # Access the kube config file

Run notepad ~/.kube/config  # Creates a kube config file

# fiap-self-service-k8s
Infraestrutura terraform - AWS EKS

# Variaveis de ambiente
export AWS_ACCESS_KEY_ID=
export AWS_SECRET_ACCESS_KEY=

# Comandos úteis
terraform init
terraform fmt
terraform validate
terraform apply
terraform destroy

# Conectar kubectl

aws eks update-kubeconfig --region us-east-1 --name fiap-self-service-k8s
kubectl get svc 


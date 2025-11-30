EKS Automation: Production-like Cluster (EKS | Terraform | Docker | CI/CD)
Built a lightweight production-style Kubernetes stack on AWS using Terraform to provision EKS,
VPC, and node groups. Deployed a Dockerized microservice via Kubernetes manifests with
readiness/liveness probes, rolling updates, and CPU-driven autoscaling (HPA). Integrated
CloudWatch Container Insights for cluster observability and set up GitHub Actions CICD to
automate image builds, ECR pushes, and rollout updates to the cluster.

🌐 Ingress Controller Setup

🔐 OIDC Provider
✅ Trust and authentication provider setup

REGION_CODE=us-east-1
CLUSTER_NAME=roboshop-dev
ACC_ID=315069654700

🔁 Associate IAM OIDC provider with EKS:

eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve

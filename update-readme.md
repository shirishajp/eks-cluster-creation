CleanUP
Delete node-group:

eksctl delete nodegroup --cluster=eksdemo \
                   --region=us-east-1 \
	          			   --name=eksdemo-ng-public
Delete Cluster:

eksctl delete nodegroup --cluster=eksdemo-dev --region=us-east-1 --name=eksdemo-ng-public Delete Cluster:

eksctl delete cluster --name=eksdemo                       --region=us-east-1	
eksctl delete cluster --name=eksdemo \
                  --region=us-east-1	
EKS-Fargate-Setup
EKS Fargate Cluster Setup
eksctl create cluster --name eksdemo --region us-east-1 --fargate

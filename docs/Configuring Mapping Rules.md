
oc create secret generic aws-auth-secret \
  --from-literal=AWS_ACCESS_KEY_ID=SUA_KEY \
  --from-literal=AWS_SECRET_ACCESS_KEY=SUA_SECRET \
  --from-literal=AWS_REGION=us-east-2 \
  --from-literal=AWS_BUCKET=threescale-storage-cluster \
  -n 3scale-lab
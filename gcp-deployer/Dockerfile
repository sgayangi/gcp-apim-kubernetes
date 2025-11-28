ARG MARKETPLACE_TOOLS_TAG=latest
FROM gcr.io/cloud-marketplace-tools/k8s/deployer_helm:0.12.10

# Copy the Helm chart
COPY chart/ /data/chart/

# Copy the Marketplace deployer schema
COPY schema.yaml /data/schema.yaml

# Copy application metadata
COPY apptest/deployer/schema.yaml /data/apptest/schema.yaml

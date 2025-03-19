## Deploy

The following will deploy Kasm in a single zone configuration.

## Prerequisite
StorageClass for Persistent Volume Claims (PVC): A StorageClass must be configured in the cluster to create Persistent Volume Claims (PVC) for the postgres-db. For detailed instructions, refer to the [Rancher Docs](https://ranchermanager.docs.rancher.com/how-to-guides/new-user-guides/manage-clusters/create-kubernetes-persistent-storage).

## Deploy Helm Chart
Please refer to values.yaml for available Helm values and their defaults.

values.yaml
1. set the hostname
2. add ssl cert
3. add ingress class

additional steps:
1. add the ingress address to your dns zone
2. install agent
Please refer to [values.yaml]() for available Helm values and their defaults.
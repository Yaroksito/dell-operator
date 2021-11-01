# dell-operator
This repo consists of the necessary Kubernete resources to deploy the Dell CSI Operator
with ArgoCD.
If you wish to deploy it with OLM just add the following reasorces: Subscription, CatalogSource
These generate the ClusterServiceVersioning, the OperatorGroup and the InstallPlan.

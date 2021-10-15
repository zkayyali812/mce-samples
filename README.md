# mce-samples

Sample Multicluster Engine apps deployed via OpenShift Pipelines

## Prereqs

- OCP 4.8+ 
- OpenShift Pipelines

## Quickstart

Before running the pipeline, ensure that the resources defined in prereqs are created on your cluster. These resources may require manual input. 
Notably aws-creds and ocp-pull-secret must be defined.

After the secrets are created, create and run the pipeline by creating the resources in the `pipelines` directory by running on your cluster- 

```bash
oc apply -f pipelines
```

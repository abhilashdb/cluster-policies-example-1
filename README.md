# cluster-policies-example

An example directory structure to store cluster policies

**Cluster policies**

https://docs.databricks.com/administration-guide/clusters/policies.html

**Cluster policies best practices**

https://docs.databricks.com/administration-guide/clusters/policies-best-practices.html

**Cluster policies API**

The Cluster Policies API allows you to create, list, and edit cluster policies. Creation and editing is available to admins only. Listing can be performed by any user and is limited to policies accessible by that user

https://docs.databricks.com/dev-tools/api/latest/policies.html#cluster-policies-api-20

**Cluster policy permissions API**

The Cluster Policy Permissions API enables you to set permissions on a cluster policy. When you grant CAN_USE permission on a policy to a user, the user will be able to create new clusters based on it. A user does not need the cluster_create permission to create new clusters.

Only admin users can set permissions on cluster policies

https://docs.databricks.com/dev-tools/api/latest/policies.html#cluster-policy-permissions-api

**Managing cluster policies through Terraform**

https://registry.terraform.io/providers/databricks/databricks/latest/docs/resources/cluster_policy



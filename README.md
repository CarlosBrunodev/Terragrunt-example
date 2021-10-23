# Terragrunt-example
## Pratical example using terragrunt and AWS 


![Logo terragrunt](https://miro.medium.com/max/1313/1*ixqIFlcBJCItbUWFae-F3Q.jpeg)


## What is terraform?
Terraform is an infrastructure as code (IaC) tool that allows you to build, change, and version infrastructure safely and efficiently. This includes low-level components such as compute instances, storage, and networking, as well as high-level components such as DNS entries, SaaS features, etc. Terraform can manage both existing service providers and custom in-house solutions.

## What Is Immutable Infrastructure?
In a traditional mutable server infrastructure, servers are continually updated and modified in place. Engineers and administrators working with this kind of infrastructure can SSH into their servers, upgrade or downgrade packages manually, tweak configuration files on a server-by-server basis, and deploy new code directly onto existing servers. In other words, these servers are mutable; they can be changed after they’re created. Infrastructure comprised of mutable servers can itself be called mutable, traditional, or (disparagingly) artisanal.

An immutable infrastructure is another infrastructure paradigm in which servers are never modified after they’re deployed. If something needs to be updated, fixed, or modified in any way, new servers built from a common image with the appropriate changes are provisioned to replace the old ones. After they’re validated, they’re put into use and the old ones are decommissioned.

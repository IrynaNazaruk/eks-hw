# eks-hw
With these files we are able deploy an EKS cluster using Terraform.

vpc.tf                  - provisions a VPC, subnets and availability zones using the AWS VPC Module.

security-groups.tf      - provisions the security groups used by the EKS cluster.

eks-cluster.tf          - provisions all the resources required to set up an EKS cluster using the AWS EKS Module.

outputs.tf              - defines the output configuration.

versions.tf             - sets the Terraform version to at least 0.14. It also sets versions for the providers used.

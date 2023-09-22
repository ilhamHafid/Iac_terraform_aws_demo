<!-- @format -->

# TERRAFORM

Terraform is an infrastructure tool as code. It’s open source and written in Go by Hashicorp. Concretely, it allows us to declare, via our code, what we want for our infrastructure. In structured configuration files we will be able to automatically manage our infrastructure without manual action. Whether it is the initial supply, the update or the destruction of the infrastructure, it is the code that drives.

## How Terraform Works?

Terraform can be thought of as consisting of two main parts: Terraform Core and Plugins. Core is responsible for life cycle management of infrastructure.

- Terraform Core: takes into consideration the current state and evaluates it against our desired configuration. It then proposes a plan to add or remove infrastructure components as needed. Next, it takes care of provisioning or decommissioning any resources if we choose to apply the plan.

- Terraform Plugins: provide a mechanism for Terraform Core to communicate with our infrastructure host or SaaS providers.

Terraform Core communicates with the plugins via Remote Procedure Call (RPC).

## Main commands:

- init Prepare our working directory for other commands
- validate Check whether the configuration is valid
- plan Show changes required by the current configuration
- apply Create or update infrastructure
- destroy Destroy previously-created infrastructure

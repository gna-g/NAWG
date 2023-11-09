# Orchestration and Automation at GÉANT

The approach to Orchestration and Automation at GÉANT is documented on the following website: 
<https://docs.gap.geant.org/>. All source code is hosted at the 
[GÉANT GitLab instance](https://gitlab.software.geant.org/goat/gap).

## Workflow Orchestrator Domain Models

The GÉANT Workflow Orchestrator Domain Models are available 
[here](https://gitlab.software.geant.org/goat/gap/geant-service-orchestrator/-/tree/develop/gso/products) as part of the
GÉANT Service Orchestrator (GSO).

## Collection of Ansible playbooks

For communication between the Workflow Orchestrator and devices, an Ansible collection is used that is published
[here](https://galaxy.ansible.com/ui/repo/published/geant/gap_ansible/). Source code for this can be found in 
[this repository](https://gitlab.software.geant.org/goat/gap/geant-gap-ansible).

The execution of Ansible playbooks is the responsibility of a tool that is available to GSO as an external service: the
[Lightweight Service Orchestrator](https://gitlab.software.geant.org/goat/gap/lso).

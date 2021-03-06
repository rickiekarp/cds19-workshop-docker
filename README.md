# Blogging Series: Secure Pipelines

## Prerequisites

### Things you should already have (hopefully):
- A computer

![computer](images/bad_computer.jpg)
- A keyboard

![keyboard](images/bad_keyboard.jpg)

- [Git](https://git-scm.com/)

### Things to start downloading:
- [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

### Things we need to do
- Get everyone access to [Handouts](https://gethandouts.com)

## Code Objectives

- (DONE) [Setup demo repo](docs/demo_project.md)
- (DONE) [Signing Commits](docs/signing_commits.md)
- (DONE) [Verified Commit](docs/verified_commit.md)

## Container Objectives
- (DONE) [Tests](docs/tests.md)
- (DONE) [SAST](docs/sast.md): container security scanning
- [Claire](docs/clair.md): Vulnerability Statis Analysis for Containers
- Code Quality
- Secrets Detection
- DAST: container security scanning

## Registry Objectives
- (DONE) [Private Registry](docs/private_registry.md)
- (DONE) [Docker Builds](docs/docker_build.md)
- (DONE) [Robot Users](docs/robot_users.md)
- (DONE) [Pushing to Private Registry](docs/delivery.md)
- Notary: Signed Images
- A/V: container scanning - via trust
- Image promotions

# Delivery Objectives

- (DONE) [Create Kubernetes Environment](docs/create_k8s.md)
- (DONE) [Configure Kubernetes to pull from private registry](docs/private_reg_k8s_config.md)
- (DONE) [Deploy Application](docs/deploy_application.md)
- [Configure Admission Controls](docs/admission_controls.md)

## Host Objectives:

- Kubernetes node restrictions
- Taints/Tolerances
- Runtime Security (falco)

## Additional Objectives:

- Patch Management: container build process
- Artifact Security (trust model)
- keybase GPG keys
- code quality

We'll be modifying the details page

### Nodes
in a managed solution, access to the Node isn't always permitted, as such you rely on the vendor to keep your nodes up to date. In a non-managed solution it is important to understand how to safetly pull a node out of the cluster, upgrade it and put it back in the cluster.

## Regisry Objectives

### Signed Images

[Docker content trust](https://docs.docker.com/engine/security/trust/content_trust/)

## Aditional Objectives

- [Static Application Security Testing](docs/sast.md)
- [Patch Management](docs/patch_management.md)
- [Using Keybase](docs/keybase.md)

# Awesome-Cloud-Infrastructure-Local-Cloud-Mocking

## Top Cloud Infrastructure & Local Cloud Mocking Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Local Cloud Mocking (AWS/GCP/Azure/Cloudflare), Ephemeral Infrastructure Testing, Containerized Test Environments & Virtual Kubernetes Clusters*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Cloud Infrastructure & Local Cloud Mocking**. These tools mock, emulate, provision, and test cloud provider APIs, storage/queue services, Kubernetes clusters, and isolated ephemeral environments locally and in CI/CD pipelines without incurring live cloud costs or network latency.



**Examples** include LocalStack Cloud, Serverless Framework, Minikube Cloud, Testcontainers Cloud, DevZero, Gitpod (Ona), Okteto, Daytona, Codeanywhere, vCluster, and floci-io/floci (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for local AWS/Azure/GCP/Cloudflare cloud mocking (`LocalStack`, `floci-io/floci`, `Moto`, `Azurite`, `Miniflare`, `MinIO`), programmatic test infrastructure (`Testcontainers`), local Kubernetes (`Minikube`, `kind`, `k3d`, `vCluster`), and self-hosted dev infrastructure (`Daytona`, `DevPod`, `Coder`) — ideal for cloud architects, DevOps/platform engineers, backend developers, and QA automation teams.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[LocalStack Cloud / Pro](https://localstack.cloud)**  

  Commercial cloud testing and team collaboration platform extending open-source LocalStack with Cloud Pods state snapshots, CI analytics, IAM policy enforcement, and extended AWS service coverage.



- **[Testcontainers Cloud (Docker)](https://testcontainers.com)**  

  Serverless on-demand container runtime offloading heavy Testcontainers integration tests and local cloud emulators from developer laptops and CI runners to the cloud.



- **[Serverless Framework (Serverless Inc. Cloud)](https://serverless.com)**  

  Managed cloud deployment, monitoring, and multi-stage orchestration platform for AWS Lambda, API Gateway, and event-driven cloud infrastructure.



- **[DevZero](https://devzero.io)**  

  Managed cloud infrastructure platform delivering production-like Kubernetes and VM environments with instant hot-reloading and database branching.



- **[Gitpod (Ona)](https://gitpod.io)**  

  Cloud Development Environment (CDE) platform automating ephemeral, standardized cloud infrastructure workspaces for developers and AI agents directly from Git.



- **[Okteto Cloud](https://okteto.com)**  

  Cloud-native development platform enabling teams to deploy, test, and preview microservices inside realistic remote Kubernetes namespaces.



- **[Codeanywhere](https://codeanywhere.com)**  

  Browser-based cloud IDE and container workspace service providing instant SSH, Git, and DevContainer infrastructure from any device.



- **[vCluster Cloud / Loft Labs](https://vcluster.com)**  

  Enterprise control plane for provisioning multi-tenant virtual Kubernetes clusters, sleep-mode cost optimization, and self-service developer namespaces.



- **[Minikube Cloud / Managed K8s Sandboxes (KillerCoda / Instruqt)](https://killercoda.com)**  

  Browser-hosted interactive Kubernetes and cloud-native lab environments for running isolated infrastructure sandboxes with zero local setup.





## Open-Source GitHub Projects



- **[floci-io/floci](https://github.com)**  

  Open-source local cloud mocking and infrastructure simulation toolkit engineered for fast, lightweight offline cloud API emulation and reproducible testing workflows.



- **[LocalStack (`localstack/localstack`)](https://github.com)**  

  Flagship open-source cloud service emulator running inside a single Docker container to mock core AWS infrastructure (S3, Lambda, DynamoDB, SQS, SNS, IAM, CloudFormation) locally.



- **[Testcontainers (`testcontainers/testcontainers-java` / `-python` / `-node` / `-go`)](https://github.com)**  

  Industry-standard open-source library providing programmatic, throwaway Docker instances of databases, message brokers, and LocalStack directly inside unit and integration tests.



- **[Moto (`getmoto/moto`)](https://github.com)**  

  Widely adopted open-source Python library mocking over 100 AWS services via decorators or a standalone HTTP server mode for fast offline unit testing.



- **[vCluster (`loft-sh/vcluster`)](https://github.com)**  

  Popular open-source virtual Kubernetes cluster engine that spins up isolated, certified K8s control planes inside regular namespaces of a shared host cluster.



- **[Daytona (`daytonaio/daytona`)](https://github.com)**  

  Open-source Development Environment Manager and secure elastic runtime for provisioning standardized local, remote, or AI-agent infrastructure sandboxes with a single command.



- **[Minikube (`kubernetes/minikube`)](https://github.com)**  

  Official open-source tool for running local single-node and multi-node Kubernetes clusters across macOS, Linux, and Windows via Docker, QEMU, or KVM.



- **[kind — Kubernetes in Docker (`kubernetes-sigs/kind`)](https://github.com)**  

  Fast open-source tool for running local Kubernetes clusters using Docker container "nodes," purpose-built for testing K8s controllers and CI/CD pipelines.



- **[MinIO (`minio/minio`)](https://github.com)**  

  High-performance open-source, S3-compatible object storage server widely used to mock AWS S3 buckets, presigned URLs, and event notifications locally.



- **[Azurite (`Azure/Azurite`)](https://github.com)**  

  Official open-source cross-platform emulator for Microsoft Azure Storage (Blob, Queue, and Table) enabling local offline cloud development and automated testing.



- **[Miniflare (`cloudflare/workers-sdk`)](https://github.com)**  

  Full-featured open-source local simulator for Cloudflare Workers, KV, R2, D1, Durable Objects, and Queues powered by `workerd`.



### Additional Strong Open-Source Options



- **[DevPod (`loft-sh/devpod`)](https://github.com)** and **[Coder (`coder/coder`)](https://github.com)** for open-source DevContainer and Terraform-provisioned self-hosted development environments.

- **[k3d (`k3d-io/k3d`)](https://github.com)** for spinning up ultra-fast, lightweight Rancher k3s Kubernetes clusters inside Docker containers in seconds.

- **[fake-gcs-server (`fsouza/fake-gcs-server`)](https://github.com)** and **[Firebase Local Emulator Suite (`firebase/firebase-tools`)](https://github.com)** for local Google Cloud Storage, Firestore, Auth, and Pub/Sub emulation.

- **[Serverless Offline (`dherault/serverless-offline`)](https://github.com)** and **[AWS SAM CLI (`aws/aws-sam-cli`)](https://github.com)** for running and debugging AWS Lambda and API Gateway functions locally in Docker.

- **[OpenTofu (`opentofu/opentofu`)](https://github.com)** and **[Pulumi (`pulumi/pulumi`)](https://github.com)** for open-source Infrastructure-as-Code (IaC) provisioning directly against LocalStack, `floci-io/floci`, and local Kubernetes clusters.



**Frameworks for building custom systems**: Combine **LocalStack** or **floci-io/floci** with **OpenTofu** for offline Infrastructure-as-Code validation, **Testcontainers** for automated integration test suites, and **vCluster** or **kind** for ephemeral Kubernetes environments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Local cloud mocking tools approximate cloud provider APIs, IAM evaluation, and eventual consistency; always run final security, quota, and integration validation against real staging cloud environments before production releases.

- Self-hosted developer infrastructure (`Coder`, `Daytona`, `Testcontainers`) requiring access to the host Docker socket (`/var/run/docker.sock`) must enforce strict network isolation and RBAC policies.



---



**Made for cloud architects, DevOps/platform engineers, backend developers, and open-source contributors.**  

Let's make cloud infrastructure testing and local cloud mocking more open, fast, and cost-free.

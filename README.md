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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global cloud infrastructure testing and emulation market is valued at approximately **$13B–$15B** (projected to reach **$30B–$45B** by the early 2030s at an ~11–13% CAGR), driven by multi-cloud complexity, microservices shift-left testing, and AI container workloads. The sector remains **highly fragmented** across specialized cloud mockers, local virtual Kubernetes runtimes, and remote container test runners, with hyper-scalers and developer-platform leaders (e.g., Docker, OpenAI) selectively acquiring key category innovators rather than a single winner-take-all monopoly.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Pricing (Starting Tier) | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Testcontainers Cloud (Docker)](https://testcontainers.com)** | ~$2.1B Valuation / ~$165M ARR (Docker acquired AtomicJar) | $9/user/month (Docker Pro billed annually; includes 100 cloud runtime mins) | Free Tier (Personal): 50 lifetime one-time worker minutes & 1 concurrent CI session; libraries free locally | Serverless on-demand container runtime offloading heavy Testcontainers integration tests and local cloud emulators from developer laptops and CI runners to the cloud. |
| **[Gitpod (Ona)](https://gitpod.io)** | ~$41M Funding / ~$5M ARR (Acquired by OpenAI in 2026) | $9/user/month (Pay-As-You-Go tier with baseline 1,000 credits) | 500 credits/month (up to 50 workspace hours/month) for public repositories and individuals | Cloud Development Environment (CDE) platform automating ephemeral, standardized cloud infrastructure workspaces for developers and AI agents directly from Git. |
| **[LocalStack Cloud / Pro](https://localstack.cloud)** | ~$100M–$250M Valuation (est.) / $28.2M Total Raised / ~$5M+ ARR | $39/license/month (Base Team tier billed annually) | Permanent Community/Hobby plan: Core AWS emulation free for non-commercial usage; 14-day free trial on Pro | Commercial cloud testing and team collaboration platform extending open-source LocalStack with Cloud Pods state snapshots, CI analytics, IAM policy enforcement, and extended AWS service coverage. |
| **[vCluster Cloud / Loft Labs](https://vcluster.com)** | ~$75M–$100M Valuation (est.) / $28.6M Total Raised / 4.6x YoY ARR | Custom enterprise quotes (pricing tied to vCPU/GPU compute consumption rather than seat licenses) | Permanent Free Platform Tier: Unlimited tenant clusters up to 64 vCPUs or 32 GPUs & 1 HA virtual control plane | Enterprise control plane for provisioning multi-tenant virtual Kubernetes clusters, sleep-mode cost optimization, and self-service developer namespaces. |
| **[DevZero](https://devzero.io)** | ~$50M–$80M Valuation (est.) / $26M Total Raised | $5/CPU/month (Pro tier tracked at minute-level granularity across fleet) | Permanent Free Tier: Unlimited K8s clusters, resource/cost monitoring, multi-cloud governance, and 30-day data retention | Managed cloud infrastructure platform delivering production-like Kubernetes and VM environments with instant hot-reloading and database branching. |
| **[Okteto Cloud](https://okteto.com)** | ~$60M Valuation / $18.1M Total Raised / ~$5M ARR | Custom quote per user seat (Scale tier for teams; contact sales for pricing) | Permanent Free Starter Plan: Up to 5 users and 500 environments/month on self-hosted Kubernetes | Cloud-native development platform enabling teams to deploy, test, and preview microservices inside realistic remote Kubernetes namespaces. |
| **[Serverless Framework (Serverless Inc. Cloud)](https://serverless.com)** | ~$30M–$50M Valuation (est.) / $13M Total Raised / ~$1.5M ARR | $4/credit (Starter credit bundles begin at ~$114–$142/month for commercial users) | Permanent Free Tier: 100% free for all developers and organizations with under $2M annual revenue | Managed cloud deployment, monitoring, and multi-stage orchestration platform for AWS Lambda, API Gateway, and event-driven cloud infrastructure. |
| **[Minikube Cloud / Managed K8s Sandboxes (KillerCoda / Instruqt)](https://killercoda.com)** | ~$5M–$15M Market footprint (KillerCoda bootstrapped / Instruqt raised $18M+) | KillerCoda PLUS at $9.99/month; Instruqt custom annual packages starting ~$15,000/year (~1,000 lab hrs) | KillerCoda Free Tier: 1 concurrent scenario, max 1 hour per session on community playgrounds; Instruqt: vendor-guided PoC trial only | Browser-hosted interactive Kubernetes and cloud-native lab environments for running isolated infrastructure sandboxes with zero local setup. |
| **[Codeanywhere](https://codeanywhere.com)** | ~$2M–$5M Historical Valuation / ~$1M Total Raised / Wound Down (2026) | Historical: $12/month (Basic tier); platform ceased operations July 1, 2026 | Historical: 7-day free trial (up to 1 container); service currently wound down / redirected to Daytona | Browser-based cloud IDE and container workspace service providing instant SSH, Git, and DevContainer infrastructure from any device. |





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

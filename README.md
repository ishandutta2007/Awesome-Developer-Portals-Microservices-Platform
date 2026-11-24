# Awesome Developer Portals & Microservices Platforms

[![Awesome](https://awesome.re/badge.svg)](https://github.com/ishandutta2007/Awesome-Developer-Portals-Microservices-Platform)
[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Developer-Portals-Microservices-Platform?style=flat-square)](https://github.com/ishandutta2007/Awesome-Developer-Portals-Microservices-Platform/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ishandutta2007/Awesome-Developer-Portals-Microservices-Platform?style=flat-square)](https://github.com/ishandutta2007/Awesome-Developer-Portals-Microservices-Platform/network)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A curated list of top **Internal Developer Portals (IDPs)**, **Microservices Platforms**, **Software Service Catalogs**, **Golden Path Scaffolding Tools**, **Production Readiness Scorecards**, and **Platform Engineering Orchestrators**.

---

## What is an Internal Developer Portal (IDP)?

An **Internal Developer Portal (IDP)** serves as the single pane of glass for engineering teams navigating modern cloud-native and microservice architectures. Key capabilities include:

- 📋 **Software Service Catalog:** Centralize microservice ownership, API specifications (OpenAPI/AsyncAPI/gRPC), technical documentation (Docs-like-Code/TechDocs), and runtime dependencies.
- 🚀 **Golden Paths & Self-Service Scaffolding:** Empower developers to scaffold production-ready services and cloud resources adhering to organizational security and architecture standards.
- 📊 **Maturity & Readiness Scorecards:** Track production readiness, security compliance (SOC2/ISO), SLOs/DORA metrics, code quality, and operational health.
- ⚙️ **Platform Orchestration & Cloud Automation:** Coordinate underlying infrastructure-as-code, GitOps pipelines (Argo CD, Flux), and cloud environments seamlessly.

---

## Table of Contents

- [SaaS & Hosted Developer Portals](#saas--hosted-developer-portals)
- [Open-Source Developer Portals & Frameworks](#open-source-developer-portals--frameworks)
- [Platform Orchestration & Infrastructure-as-a-Service](#platform-orchestration--infrastructure-as-a-service)
- [Microservice Runtimes & GitOps Delivery](#microservice-runtimes--gitops-delivery)
- [Architecture Blueprint & Recommended Stack](#architecture-blueprint--recommended-stack)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

---

## SaaS & Hosted Developer Portals

Curated managed IDPs and SaaS developer experience platforms.

| Platform | Description | Pricing Model | Free Tier & Limits |
| :--- | :--- | :--- | :--- |
| **[Port](https://getport.io)** | No-code/low-code customizable Internal Developer Portal with software catalog, self-service developer actions, scorecards, and live GitOps integrations. | Freemium / Paid per active user | **Free tier available**: up to 15 users, 1 data source, core catalog & scorecards. |
| **[Cortex.io](https://cortex.io)** | Enterprise IDP focused on microservice catalogs, automated production-readiness scorecards, incident tracking, and engineering maturity initiatives. | Paid / Enterprise subscription | **Free trial available** on request; custom quote per developer/service. |
| **[Atlassian Compass](https://atlassian.com/software/compass)** | Distributed architecture management platform unifying component catalogs, health scorecards, DevOps metrics, and Jira/Bitbucket workflows. | Freemium / Paid per full user | **Free tier available**: up to 30,000 components, basic scorecards, unlimited basic users. |
| **[OpsLevel](https://opslevel.com)** | Microservice catalog and developer portal designed to automate service maturity checks, assign code ownership, and provide self-service templates. | Paid / Tiered per service/user | **Free trial available** (14-day full feature trial); paid plans scale per developer. |
| **[Roadie Backstage](https://roadie.io)** | Fully managed, zero-maintenance SaaS hosting for Spotify Backstage offering enterprise RBAC, SOC2 compliance, and pre-configured plugins. | Paid / Per seat subscription | **Free trial available** (14 days); custom growth & enterprise plans. |
| **[Harness IDP](https://harness.io/products/internal-developer-portal)** | Backstage-powered cloud developer portal deeply integrated with Harness CI/CD pipelines, feature flags, cloud cost management, and golden paths. | Paid / Tiered per developer seat | **Free trial available** with Harness platform credits. |
| **[Rely.io](https://rely.io)** | AI-native Internal Developer Portal and software catalog automating service discovery, DORA metrics, reliability scorecards, and developer workflows. | Freemium / Paid per seat | **Free tier available**: up to 10 users with core catalog, integrations, and basic scorecards. |
| **[DX Platform](https://getdx.com)** | Developer experience and engineering intelligence platform combining qualitative developer surveys with system telemetry and catalog insights. | Paid / Enterprise subscription | **Demo / Trial upon request**; custom enterprise pricing per seat. |
| **[Configure8](https://configure8.io)** | Universal Internal Developer Portal aggregating cloud resources, Kubernetes clusters, CI/CD pipelines, and microservice dependencies into unified scorecards. | Freemium / Paid | **Free tier available**: up to 20 users and standard cloud integrations. |
| **[Spotify Portal for Backstage](https://spotify.com)** | Commercial enterprise SaaS offering from the creators of Backstage providing turnkey cloud hosting, enterprise support, and exclusive Spotify plugins. | Enterprise subscription | **Enterprise quote only**; custom demo available upon request. |

---

## Open-Source Developer Portals & Frameworks

Open-source frameworks to build, customize, and self-host developer portals.

- **[Backstage by Spotify (`backstage/backstage`)](https://github.com/backstage/backstage)**  
  Flagship CNCF incubating open-source framework for building customizable Internal Developer Portals. Features an extensible Software Catalog, Software Templates (Scaffolder), TechDocs (Markdown docs-like-code), and an extensive ecosystem of community plugins.
- **[Red Hat Developer Hub / Janus IDP (`janus-idp/backstage-showcase`)](https://github.com/janus-idp/backstage-showcase)**  
  Enterprise-ready open-source Backstage distribution maintained by Red Hat and the Janus community. Offers dynamic runtime plugin loading, pre-integrated Keycloak RBAC, and Kubernetes/OpenShift/Argo CD modules.
- **[kdlbs/kandev (`kdlbs/kandev`)](https://github.com/kdlbs/kandev)**  
  Open-source developer portal and microservices platform toolkit engineered to streamline service organization, developer self-service, and modern platform workflows.
- **[Port Ocean (`port-labs/ocean`)](https://github.com/port-labs/ocean)**  
  Open-source extensible integration framework built in Python for ingesting real-time metadata from Kubernetes, GitHub, GitLab, PagerDuty, Jira, and cloud providers into developer portals.

---

## Platform Orchestration & Infrastructure-as-a-Service

Engines enabling platform teams to compose golden paths and expose self-service cloud APIs.

- **[Crossplane (`crossplane/crossplane`)](https://github.com/crossplane/crossplane)**  
  CNCF open-source control-plane framework turning Kubernetes into a universal cloud API. Enables platform teams to model composite cloud infrastructure abstractions for developer self-service.
- **[KubeVela (`kubevela/kubevela`)](https://github.com/kubevela/kubevela)**  
  CNCF open-source application delivery and platform orchestration engine built on the Open Application Model (OAM) for deploying multi-cloud microservice workloads.
- **[Kratix (`syntasso/kratix`)](https://github.com/syntasso/kratix)**  
  Open-source platform engineering framework enabling teams to compose, curate, and deliver as-a-Service APIs ("Promises") across multi-cluster Kubernetes environments.
- **[Score (`score-spec/spec`)](https://github.com/score-spec/spec)**  
  Open-source developer-centric workload specification (`score.yaml`) allowing developers to define service requirements once and run them identically on local Docker Compose or remote Kubernetes clusters.
- **[Radius (`radius-project/radius`)](https://github.com/radius-project/radius)**  
  Open-source cloud-native application platform from Microsoft enabling developers and platform teams to collaborate on microservice definitions, connections, and environment recipes.
- **[Porter (`porter-dev/porter`)](https://github.com/porter-dev/porter)** & **[Qovery Engine (`Qovery/engine`)](https://github.com/Qovery/engine)**  
  Open-source PaaS layers that transform your AWS, GCP, or Azure Kubernetes infrastructure into a self-service Heroku-like platform experience.
- **[OpenTofu (`opentofu/opentofu`)](https://github.com/opentofu/opentofu)** & **[Terragrunt](https://github.com/gruntwork-io/terragrunt)**  
  Open-source Infrastructure-as-Code engines powering golden-path infrastructure provisioning behind developer portal templates.

---

## Microservice Runtimes & GitOps Delivery

Core runtimes, service mesh backbones, and continuous delivery pipelines.

- **[Argo CD (`argoproj/argo-cd`)](https://github.com/argoproj/argo-cd)**  
  Declarative, GitOps continuous delivery engine for Kubernetes widely embedded inside Internal Developer Portals for live microservice synchronization and self-service rollouts.
- **[Dapr (`dapr/dapr`)](https://github.com/dapr/dapr)**  
  Distributed Application Runtime providing portable, event-driven microservice building blocks—service-to-service invocation, pub/sub, state store, and distributed locking—via sidecar APIs.
- **[Istio (`istio/istio`)](https://github.com/istio/istio)** & **[Linkerd (`linkerd/linkerd2`)](https://github.com/linkerd/linkerd2)**  
  Industry-standard open-source service meshes providing zero-trust mTLS, dynamic traffic management, and telemetry graphs across microservices architectures.
- **[KubeSphere (`kubesphere/kubesphere`)](https://github.com/kubesphere/kubesphere)**  
  Distributed open-source container management platform featuring a multi-tenant developer console, automated CI/CD pipelines, and integrated service mesh observability.
- **[Copier (`copier-org/copier`)](https://github.com/copier-org/copier)**  
  Library and CLI for rendering microservice project templates with support for lifecycle updates alongside Backstage Scaffolder.

---

## Architecture Blueprint & Recommended Stack

```
               ┌─────────────────────────────────────────────────────────────┐
               │              Internal Developer Portal (IDP)                │
               │  (Backstage / Port / Atlassian Compass / Cortex / Janus)    │
               │  • Software Catalog   • Scorecards   • TechDocs   • Actions  │
               └──────────────────────────────┬──────────────────────────────┘
                                              │ Golden Path Triggers
                                              ▼
               ┌─────────────────────────────────────────────────────────────┐
               │             Platform Engineering Orchestration              │
               │          (Crossplane / Kratix / KubeVela / Score)           │
               └──────────────┬──────────────────────────────┬───────────────┘
                              │ Infrastructure API           │ Manifests
                              ▼                              ▼
               ┌──────────────────────────────┐ ┌────────────────────────────┐
               │    Cloud / IaC Resources     │ │  GitOps Delivery (Argo CD) │
               │ (AWS, GCP, Azure, OpenTofu)  │ │   & Microservice Runtime   │
               │                              │ │       (Dapr, Istio)        │
               └──────────────────────────────┘ └────────────────────────────┘
```

---

## How to Contribute

Contributions from platform engineers, SREs, and open-source maintainers are welcome!

1. **Fork** this repository.
2. Add your project or platform to the appropriate section in `README.md`:
   - Follow the established formatting (include links, GitHub repo name if open-source, and concise description).
   - If adding a SaaS product, include its pricing model and free tier limits in the SaaS table.
3. Verify formatting and links.
4. **Submit a Pull Request** with a descriptive summary of your changes.

---

## Support & Share

If you find this curated collection useful for your team or organization:

- ⭐ **Star this repository** on GitHub.
- 🍴 **Fork & share** with platform engineering and DevOps communities on LinkedIn, X/Twitter, and Reddit.
- ☕ **Sponsor**: Support open-source curation on [GitHub Sponsors](https://github.com/sponsors/ishandutta2007).

---

## Disclaimer

- This list is community-curated for informational purposes and does not constitute formal endorsement.
- Developer portals and platform orchestrators interface directly with cloud credentials and production deployment pipelines; always enforce robust RBAC, OIDC/SSO authentication, least-privilege IAM policies, and audit logging.

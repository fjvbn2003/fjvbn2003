<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=3B82F6&center=true&vCenter=true&width=500&lines=Youngju+Kim;AI+DevOps+Engineer;CNCF+Kubestronaut+%F0%9F%9A%80" alt="Typing SVG" />
</h1>

<p align="center">
  <strong>AI 모델을 프로덕션에 안정적으로 서빙하는 DevOps 엔지니어</strong>
</p>

<p align="center">
  <a href="https://www.credly.com/badges/81902074-cc4f-4046-b614-2dbcf9783c53/public_url"><img src="https://img.shields.io/badge/CNCF-Kubestronaut-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/></a>
  <a href="https://techblog.lycorp.co.jp/ko/develop-hitbasehandler-to-manage-apache-hbase-cluster"><img src="https://img.shields.io/badge/LINE-Tech%20Blog-00C300?style=flat-square&logo=line&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/%EC%98%81%EC%A3%BC-%EA%B9%80-2303b8214/"><img src="https://img.shields.io/badge/LinkedIn-Youngju%20Kim-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:fjvbn2003@gmail.com"><img src="https://img.shields.io/badge/Email-fjvbn2003-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

---

### 👋 About Me

DevOps engineer specializing in deploying AI models (LLM, OCR, Embedding) to on-premise and Kubernetes environments. Delivered AI solutions to **10+ projects** across finance, manufacturing, education, and public sectors.

- 🏢 **Upstage** — AI DevOps Engineer *(2024.11 ~)*
- 🟢 **LINE** — Software Engineer / DBA *(2021.11 ~ 2024.11)*
### 🛠 Tech Stack

<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white"/>
  <img src="https://img.shields.io/badge/vLLM-FF6F00?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/NVIDIA_MIG-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/HBase-C72E49?style=flat-square&logo=apache&logoColor=white"/>
</p>

### 🏅 Certifications

| Certification | Issuer | Date |
|:---|:---|:---|
| **Kubestronaut** (CKA + CKAD + CKS + KCNA + KCSA) | CNCF | 2025 |
| CKA (Certified Kubernetes Administrator) | CNCF | 2023.12 |
| CKAD (Certified Kubernetes Application Developer) | CNCF | 2024.11 |
| KCSA (Kubernetes and Cloud Native Security Associate) | CNCF | 2025.07 |
| 정보처리기사 | 한국산업인력공단 | 2021.06 |
| 빅데이터분석기사 | 한국데이터산업진흥원 | 2023.08 |

### 💼 What I Do

**@ Upstage** — On-premise & K8s delivery of AI products (LLM, OCR, EWS)

- 🏗 **Generative AI (Finance)** — Helm-based AI solution on GPU K8s cluster, NVIDIA MIG, monitoring stack
- 📊 **DevOps Helm Standard** — Helm charts for serving LLM & Document Processing models, v1.0 release, GitOps with ArgoCD
- 🖥 **Education Platform** — Operated large-scale GPU multi-cloud cluster (IPSec VPN)
- 🏭 **Manufacturing · Insurance · Public** — OCR/LLM/EWS install, SSO·LDAP·DRM integration, load testing
- 🤖 **[k13d](https://github.com/cloudbro-kube-ai/k13d)** — Building a natural language Kubernetes dashboard ([docs](https://cloudbro-kube-ai.github.io/k13d/latest/))

**@ LINE** — Large-scale distributed database (Apache HBase) operations & tooling · [▶ Job Interview](https://www.youtube.com/watch?v=30_QyLSZbzY)

- 🔄 Led HBase open-source migration (cluster build, load testing, data integrity verification)
- 🛠 [HBH (HitBaseHandler)](https://techblog.lycorp.co.jp/ko/develop-hitbasehandler-to-manage-apache-hbase-cluster) — Designed and built Django-based cluster management tool

### 🏠 Home Lab

An 8-node kubeadm cluster at home that runs **[TT Lab](https://ttlab.hopto.org)**: a hands-on DevOps learning platform (real root shells in isolated lab pods and KubeVirt VMs) and AI services such as a real-time table tennis scoreboard.

| Node | Role | CPU · RAM | GPU | Runs |
|:---|:---|:---|:---|:---|
| **cubi01–03** | Control plane (etcd quorum) | 4 vCPU · 15 GiB each | — | API server, etcd |
| **nuc1, nuc2** | Worker | 22 vCPU · 30 GiB each | RTX 4070 Laptop (8GB) | TT Lab web, CI/CD, AI serving (TTS, LLM) |
| **omen** | GPU worker | 24 vCPU · 61 GiB | RTX 3090 (24GB, time-sliced ×5) | Real-time ball tracking & scoring, table segmentation |
| **loq** | GPU worker | 16 vCPU · 14 GiB | RTX 4060 Laptop (8GB) | Git hosting, registry, ML experiments & fine-tuning |
| **dell** | VM worker | 16 vCPU · 22 GiB | RTX 3060 Laptop (VFIO passthrough) | KubeVirt VMs with GPU |

**Stack** — Kubernetes v1.34 · Cilium 1.20 (Gateway API, FQDN egress policies) · MetalLB L2 · Argo CD · Jenkins · Gitea · Harbor · Keycloak SSO · CloudNativePG · KubeVirt + CDI · NVIDIA GPU Operator · Istio · Airflow · Prometheus · Grafana · OpenTelemetry

**Write-ups** — Postmortems, measurements and study notes from running it are on the [TT Lab blog](https://ttlab.hopto.org/blog).

### 🚀 Side Projects

| Project | Description | Tech |
|:---|:---|:---|
| **[k13d](https://github.com/cloudbro-kube-ai/k13d)** | Natural language Kubernetes dashboard · [docs](https://cloudbro-kube-ai.github.io/k13d/latest/) | Go, Claude Code |
| **fingerscore** | Real-time sports score platform | Next.js, Supabase |
| **ai-shorts-generator** | Automated AI shorts video pipeline | Python, Wan2.1/2.2 |
| **ai-stages-kubevirt** | KubeVirt-based AI training environment | KubeVirt, K8s |

### 🌱 Open Source Contributions

I contribute to the cloud-native and AI-infrastructure projects I run in my home lab, and back each change with measurements from a real cluster. Main focus: **KubeVirt** and **CloudNativePG**.

**Merged**

| Project | PR | Change |
|:---|:---|:---|
| Apache HBase | [#5927](https://github.com/apache/hbase/pull/5927) | Fix `RowTooBigException` on a duplicate increment RPC ([HBASE-28599](https://issues.apache.org/jira/browse/HBASE-28599)) |
| SeaweedFS | [#11755](https://github.com/seaweedfs/seaweedfs/pull/11755) | `weed mini` help: `mini.options` and Docker `filer.toml` pitfalls |
| Grafana Helm charts | [#896](https://github.com/grafana-community/helm-charts/pull/896) | Document that the admin password is only applied on first start |
| llm-d | [#2835](https://github.com/llm-d/llm-d/pull/2835) | Replace vLLM metric names that vLLM no longer exports |
| Helm docs | [#2307](https://github.com/helm/helm-www/pull/2307) | Document that `lookup` only runs for `template`, `install` and `upgrade` |
| alpine/k8s | [#99](https://github.com/alpine-docker/k8s/pull/99) | Point eksctl and jq downloads at their current repositories |

**In review** *(October 2026)*

- **Virtualization** — KubeVirt user-guide [#1040](https://github.com/kubevirt/user-guide/pull/1040) · CDI [#4318](https://github.com/kubevirt/containerized-data-importer/pull/4318) · kubernetes-mcp-server [#1518](https://github.com/containers/kubernetes-mcp-server/pull/1518) · NVIDIA kubevirt-gpu-device-plugin [#222](https://github.com/NVIDIA/kubevirt-gpu-device-plugin/pull/222) · virt-template [#137](https://github.com/kubevirt/virt-template/pull/137)
- **Databases & storage** — CloudNativePG barman-cloud [#1164](https://github.com/cloudnative-pg/plugin-barman-cloud/pull/1164) [#1166](https://github.com/cloudnative-pg/plugin-barman-cloud/pull/1166) · ClickHouse [#126337](https://github.com/ClickHouse/ClickHouse/pull/126337) · zstd [#4847](https://github.com/facebook/zstd/pull/4847) · RocksDB [#15418](https://github.com/facebook/rocksdb/pull/15418) · Harbor [#24164](https://github.com/goharbor/harbor/pull/24164)
- **Kubernetes & networking** — Envoy [#48408](https://github.com/envoyproxy/envoy/pull/48408) · MetalLB [#3156](https://github.com/metallb/metallb/pull/3156) · Argo Workflows [#17246](https://github.com/argoproj/argo-workflows/pull/17246) · k9s [#4298](https://github.com/derailed/k9s/pull/4298) · eBPF Docs [#301](https://github.com/isovalent/ebpf-docs/pull/301) · k8s-sidecar [#661](https://github.com/kiwigrid/k8s-sidecar/pull/661) · podman-compose [#1585](https://github.com/containers/podman-compose/pull/1585) · Keycloak (codecentric) chart [#939](https://github.com/codecentric/helm-charts/pull/939)
- **GPU & AI infrastructure** — NVIDIA GPU Operator [#3086](https://github.com/NVIDIA/gpu-operator/pull/3086) · NVIDIA cloud-native-docs [#524](https://github.com/NVIDIA/cloud-native-docs/pull/524) · DCGM Exporter [#760](https://github.com/NVIDIA/dcgm-exporter/pull/760) · Dynamo [#16465](https://github.com/ai-dynamo/dynamo/pull/16465) · vLLM production-stack [#1147](https://github.com/vllm-project/production-stack/pull/1147) [#1148](https://github.com/vllm-project/production-stack/pull/1148) · LMCache [#5814](https://github.com/LMCache/LMCache/pull/5814) · NeMo [#16396](https://github.com/NVIDIA-NeMo/Speech/pull/16396) · Slinky Slurm operator [#272](https://github.com/SlinkyProject/slurm-operator/pull/272)
- **AI frameworks & apps** — LlamaIndex [#23548](https://github.com/run-llama/llama_index/pull/23548) · models.dev [#10155](https://github.com/anomalyco/models.dev/pull/10155) · LobeHub [#21026](https://github.com/lobehub/lobehub/pull/21026) · MediaPipe [#6381](https://github.com/google-ai-edge/mediapipe/pull/6381) · Gemini cookbook [#1433](https://github.com/google-gemini/cookbook/pull/1433) · Hermes Agent [#140057](https://github.com/NousResearch/hermes-agent/pull/140057) · MiniMind [#889](https://github.com/jingyaogong/minimind/pull/889)
- **Observability & IaC** — Grafana Tempo chart [#898](https://github.com/grafana-community/helm-charts/pull/898) · OpenSearch docs [#13346](https://github.com/opensearch-project/documentation-website/pull/13346) · Ansible docs [#4077](https://github.com/ansible/ansible-documentation/pull/4077) [#4078](https://github.com/ansible/ansible-documentation/pull/4078) · community.general [#12997](https://github.com/ansible-collections/community.general/pull/12997) · Terraform local provider [#533](https://github.com/hashicorp/terraform-provider-local/pull/533)
- **Python web** — python-multipart [#338](https://github.com/Kludex/python-multipart/pull/338) · prometheus-fastapi-instrumentator [#403](https://github.com/trallnag/prometheus-fastapi-instrumentator/pull/403)
- **Robotics** — PX4 Autopilot [#29271](https://github.com/PX4/PX4-Autopilot/pull/29271)

→ [All my open-source pull requests](https://github.com/search?q=is%3Apr+author%3Afjvbn2003+-user%3Afjvbn2003+-org%3Acloudbro-kube-ai+-org%3Akube-ai-dashbaord&type=pullrequests&s=created&o=desc) · write-ups of merged changes on the [TT Lab blog](https://ttlab.hopto.org/blog)

### 🏆 Awards

- 🥈 **Naver Clova AI-Rush 4th** (2021)
- 🥇 **고양시 메이커톤 대상** (2018)
- 📊 KLUE 뉴스 토픽 분류 AI 경진대회 27/256 (상위 11%)

---

<p align="center">
  <i>"Building reliable AI infrastructure, even in air-gapped environments."</i>
</p>

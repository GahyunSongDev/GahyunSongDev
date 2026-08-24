# Hi, I'm Gahyun Song

Cloud/DevOps Engineer who obsesses over zero-downtime deployments and keeping infrastructure invisible to developers. ASU Computer Science graduate, bilingual (English/Korean), U.S. Green Card holder.

Currently studying for my **AWS Certified Solutions Architect – Associate** and looking for Junior/Associate/Entry-level Cloud or DevOps opportunities.

---

## Featured Projects

### EKS GitOps & Blue-Green Deployment — KT Cloud × Groom Bootcamp
[View Repo →](https://github.com/team4-coding-gamja/UNBOX-INFRA.git)

Led a 3-phase infrastructure evolution (MVP CRUD → ECS CI/CD → EKS GitOps) for a 5-microservice system. Self-studied ArgoCD and Argo Rollouts after a mentor's suggestion and delivered a full Blue-Green deployment system with my team — **awarded Best Team (1st out of 4 teams)**.

- **Eliminated 2–3 min downtime** by migrating from ECS Rolling Update to EKS + Argo Rollouts Blue-Green strategy; achieved 100% availability across 5 microservices
- **Reduced build time 68%** (25 min → 8 min) via Gradle dependency caching + Docker layer caching on ECR buildcache; cut image size 66% with multi-stage builds
- **Cut MTTR 90%** by designing Prometheus metric-based Analysis Templates for auto-rollback, with real-time Discord alerts for incident visibility
- Designed an ArgoCD App of Apps pattern for hierarchical GitOps — single-command dev/prod sync across all K8s resources

**Stack:** AWS EKS · ECR · RDS · ElastiCache · MSK · Kubernetes · Helm · Docker · GitHub Actions · ArgoCD · Argo Rollouts · Prometheus · Grafana · Linkerd

---

### Serverless Event-Driven Infrastructure — Code States Bootcamp
[View Repo →](https://github.com/gahyun8876/practice-final.git)

Designed and built a serverless, event-driven backend architecture (API Gateway → Lambda → SNS/SQS) with fully modularized infrastructure-as-code.

- **Cut infrastructure costs 70%** with async event-driven architecture
- **Reduced provisioning time 99%** (2 days → 20 minutes) via Terraform IaC modularization (VPC, ECS, RDS, Lambda)
- **Achieved zero downtime incidents** (previously 5/day) via ALB + ECS Auto Scaling
- Built serverless DynamoDB transaction validation for automated payment confirm/cancel flows; automated CI/CD via GitHub Actions

**Stack:** Node.js · Terraform · Docker · AWS ECS/Fargate/Lambda/RDS/DynamoDB/SNS/SQS/SES/API Gateway · GitHub Actions

---

## Skills

| Category | Tools |
|---|---|
| **Infrastructure** | AWS (EKS, ECR, RDS, ElastiCache, MSK, Lambda, CloudFormation, Amplify), Terraform, Helm |
| **Container & Orchestration** | Docker, Kubernetes, EKS, K3d, Linkerd (Service Mesh) |
| **CI/CD & GitOps** | GitHub Actions, ArgoCD, Argo Rollouts |
| **Observability** | Prometheus, Grafana, CloudWatch |
| **Languages** | Python, Java, C++, Bash, Node.js |

---

## Let's Connect

[LinkedIn](https://linkedin.com/in/gahyun-song-4634b8196) · gahyun8876@gmail.com

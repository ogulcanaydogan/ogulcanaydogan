Platform engineer building security, provenance, and supply-chain integrity tooling for AI systems. LLM training for low-resource languages. Open-source contributor across CNCF and ML infrastructure.

`Go` `Python` `Terraform` `Kubernetes` `AWS` `Docker` `eBPF` `OPA` `Prometheus` `ONNX` `PyTorch`

**Contributing to** &nbsp; [open-telemetry/opentelemetry-collector-contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib) · [moby/moby](https://github.com/moby/moby) · [prometheus/prometheus](https://github.com/prometheus/prometheus) · [sigstore/cosign](https://github.com/sigstore/cosign) · [containerd/nerdctl](https://github.com/containerd/nerdctl) · [tektoncd/pipeline](https://github.com/tektoncd/pipeline) · [open-policy-agent/gatekeeper](https://github.com/open-policy-agent/gatekeeper) · [helm/helm](https://github.com/helm/helm) · [fluxcd/source-controller](https://github.com/fluxcd/source-controller)

### Terraform Registry: AWS Module Library

Production-oriented, reusable modules published on the [Terraform Registry](https://registry.terraform.io/namespaces/ogulcanaydogan).

| Module | Purpose |
| --- | --- |
| [`docker-instance`](https://registry.terraform.io/modules/ogulcanaydogan/docker-instance/aws) | EC2 with Docker & Compose pre-installed (Amazon Linux 2023), 1.2k+ downloads |
| [`vpc`](https://registry.terraform.io/modules/ogulcanaydogan/vpc/aws) | VPC with public/private/database subnets, NAT Gateways, endpoints, flow logs |
| [`ecs-fargate-service`](https://registry.terraform.io/modules/ogulcanaydogan/ecs-fargate-service/aws) | Fargate service with autoscaling, ALB integration, deployment circuit breaker |
| [`ecr-repo`](https://registry.terraform.io/modules/ogulcanaydogan/ecr-repo/aws) | ECR repositories with encryption, lifecycle policies, cross-account access |
| [`alb-https`](https://registry.terraform.io/modules/ogulcanaydogan/alb-https/aws) | Application Load Balancer with HTTPS, ACM certificates, access logging, health checks |
| [`route53-records`](https://registry.terraform.io/modules/ogulcanaydogan/route53-records/aws) | Route53 records with weighted, latency, geolocation, and failover routing |
| [`ssm-ec2`](https://registry.terraform.io/modules/ogulcanaydogan/ssm-ec2/aws) | EC2 access via SSM Session Manager, no SSH keys |
| [`cloudwatch-alarms`](https://registry.terraform.io/modules/ogulcanaydogan/cloudwatch-alarms/aws) | CPU, memory, disk, and network alarms with SNS notifications |
| [`patterns`](https://registry.terraform.io/modules/ogulcanaydogan/patterns/aws) | Security groups with flexible ingress/egress rules, IPv6, prefix lists |

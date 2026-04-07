# cloud-devops-journey
As a Cloud DevOps &amp; Platform SRE supporting the GTIHUD repository, I'm responsible for designing, implementing, and maintaining scalable, secure, and highly available cloud infrastructure on GCP. Role focuses on enabling seamless application delivery through robust CI/CD pipelines, infrastructure automation, and proactive reliability eng practices.

# High_Level_Architecture

Git Repo → Jenkins Pipeline → Docker Build → GCR
                                      ↓
                                 Kubernetes (GKE)
                                      ↓
                               LoadBalancer Service

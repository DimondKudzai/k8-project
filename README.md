### CI/CD Pipeline
This repo uses GitHub Actions for automated builds and deployments.

**Flow:** Push to `main` → Actions builds Docker image → Pushes to Docker Hub → Deploys to K8s cluster

**Pipeline time:** ~22s end-to-end

**Tech:** GitHub Actions, Docker, Kubernetes, YAML
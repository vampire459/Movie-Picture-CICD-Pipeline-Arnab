# Evidence / Screenshots

This folder contains real evidence from the completed CI/CD deployment for this repository.

1. `01-github-actions-success.png`
   - Shows all four required GitHub Actions workflows completed successfully: Frontend CI, Frontend CD, Backend CI, and Backend CD.

2. `02-backend-api-working.png`
   - Shows the deployed backend LoadBalancer `/movies` endpoint successfully returning the movie JSON.

3. `03-frontend-working.png`
   - Shows the deployed React frontend successfully loading the Movie List and Movie Details from the backend API.

4. `04-kubernetes-running.png`
   - Shows `kubectl get pods,svc,deployments`.
   - Backend and frontend pods are Running.
   - Both deployments are 1/1 available.
   - Both services have AWS LoadBalancer hostnames.

5. `05-deployed-image-sha.png`
   - Shows the backend and frontend Kubernetes deployments using ECR images tagged with the Git commit SHA.

All screenshots were captured from the actual GitHub repository, AWS/EKS deployment, and running application for this project.
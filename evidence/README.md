# Evidence / Screenshots Checklist

This project's rubric requires visual proof that the pipelines and the deployed application actually work. These screenshots cannot be produced until you have a real GitHub repository connected to a real AWS account and have run the workflows for real, so none are included here — add them to this folder yourself after deployment.

Capture and place the following files in this folder:

1. `frontend-ci-success.png` — GitHub Actions run of **Frontend Continuous Integration** showing `lint`, `test`, and `build` all green.
2. `backend-ci-success.png` — GitHub Actions run of **Backend Continuous Integration** showing `lint`, `test`, and `build` all green.
3. `frontend-cd-success.png` — GitHub Actions run of **Frontend Continuous Deployment** showing `lint`, `test`, `build_and_push`, and `deploy` all green.
4. `backend-cd-success.png` — GitHub Actions run of **Backend Continuous Deployment** showing `lint`, `test`, `build_and_push`, and `deploy` all green.
5. `backend-api.png` — Browser or `curl` output of `http://<backend-load-balancer>/movies` showing the movie JSON.
6. `frontend-app.png` — The deployed frontend in a browser showing the "Movie List" with movie titles.
7. `kubectl-services.png` (optional) — Output of `kubectl get svc` showing the `frontend` and `backend` `LoadBalancer` services with their external hostnames.

Do not fabricate or reuse screenshots from another project — they must reflect an actual successful run of this repository's workflows and a real deployment.

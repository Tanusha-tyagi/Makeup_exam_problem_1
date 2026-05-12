# DevOps CI/CD Security Platform

## Project Overview
This project demonstrates DevOps automation using:

- Linux Administration
- Git & GitHub Workflow
- CI/CD using GitHub Actions
- SonarQube Integration
- Open Policy Agent (OPA)



## Folder Structure

configs/  
deployments/  
policies/  
reports/  
artifacts/  
scripts/



## Branching Strategy

- master
- development
- staging
- production



## CI/CD Pipeline Stages

1. Source Checkout
2. Build
3. Test
4. Security Validation
5. Deployment



## OPA Policies

- Restrict privileged containers
- Restrict root user execution
- Prevent latest image tag usage



## SonarQube

Static code analysis configured using SonarQube.
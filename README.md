# Symplichain CI/CD Pipeline

This repo contains GitHub Actions workflows for:

- Staging deployment (trigger: staging branch)
- Production deployment (trigger: main branch)

Tech stack:
- React (frontend → S3 + CloudFront)
- Django (backend → EC2)
- GitHub Actions for CI/CD

# byteguard-cicd
ByteGuard Cybersecurity Awareness PLatform - CI/CD Pipeline Project

# ByteGuard - Cyber Threat Detection System

![Build](https://github.com/irdinanst/byteguard-cicd/actions/workflows/build.yml/badge.svg)




![Test](https://github.com/irdinanst/byteguard-cicd/actions/workflows/test.yml/badge.svg)




![Deploy](https://github.com/irdinanst/byteguard-cicd/actions/workflows/deploy.yml/badge.svg)



![Deployment Status](https://img.shields.io/badge/deployment-live-brightgreen)



![Pipeline](https://img.shields.io/badge/pipeline-passing-brightgreen)



![License](https://img.shields.io/badge/license-MIT-blue)



## Live Website
🌐 https://peppy-kelpie-065e30.netlify.app

## Project Overview
ByteGuard is a cloud-deployed Cyber Threat Detection System built as part of the CIT22103 Cloud Computing Final Project at Management and Science University (MSU). The project demonstrates a complete DevOps CI/CD pipeline workflow using GitHub Actions and Netlify cloud deployment.

## Tech Stack
| Technology | Purpose |
|---|---|
| HTML + CSS | Frontend Website |
| GitHub | Source Code Management |
| GitHub Actions | CI/CD Pipeline Automation |
| Netlify | Cloud Deployment + HTTPS |
| GitHub Secrets | Secure Credentials Management |

## CI/CD Pipeline Structure

### 1. Build Pipeline
- Checks out source code
- Sets up Node.js environment
- Creates and installs dependencies
- Runs unit tests
- Validates HTML and CSS structure
- Builds and uploads artifacts

### 2. Test Pipeline
- Dependency security scanning
- File structure verification
- HTML structure testing
- CSS structure testing
- Security headers check
- Automated failure notification

### 3. Deploy Pipeline
- Builds production files
- Deploys automatically to Netlify
- Confirms live deployment URL

## Security
- HTTPS enforced via Netlify
- Credentials stored in GitHub Secrets
- No hardcoded credentials in source code
- Secure pipeline configuration

## Project Structure
byteguard-cicd/
├── .github/
│   └── workflows/
│       ├── build.yml
│       ├── test.yml
│       └── deploy.yml
├── index.html
├── style.css
└── README.md

## How to Run
Just push any changes to the main branch and all 3 pipelines will run automatically. No manual deployment needed.

## Security
We made sure not to hardcode any credentials in our code. All sensitive information like our Netlify token and Site ID are stored safely using GitHub Secrets.

## Team Members
- Irdina Adriana Nasution Binti Muhammad
- Shahin Affruz

## Course Info
CIT22103 Cloud Computing
Management and Science University (MSU)
February 2026

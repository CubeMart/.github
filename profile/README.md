# CubeMart

CubeMart is a cloud-native microservices e-commerce platform built to showcase modern backend engineering, DevOps delivery, GitOps deployment, Kubernetes orchestration, AWS infrastructure, and AI-assisted shopping workflows.

## Overview

CubeMart is organized as a full-stack platform rather than a single application. It combines:

- user-facing storefront and API entrypoint
- distributed backend microservices
- CI/CD automation and GitOps delivery
- infrastructure-as-code for AWS and Kubernetes
- observability-friendly cloud-native service design
- an AI-powered shopping assistant using retrieval-augmented workflows

## Platform Map

- `frontend` handles the storefront and user-facing API flow
- `checkoutservice`, `cartservice`, `paymentservice`, `shippingservice`, and `emailservice` support the core purchase journey
- `productcatalogservice`, `recommendationservice`, `adservice`, and `currencyservice` support browsing and merchandising
- `authservice` manages registration, login, and token validation
- `shoppingassistantservice` powers AI-assisted product discovery
- `gitops` stores deployment manifests and environment overlays
- `infrastructure` provisions AWS networking, state management, and EKS

## Core Repositories

- `frontend`
- `authservice`
- `cartservice`
- `checkoutservice`
- `productcatalogservice`
- `paymentservice`
- `shippingservice`
- `emailservice`
- `recommendationservice`
- `adservice`
- `shoppingassistantservice`
- `currencyservice`
- `loadgenerator`
- `gitops`
- `infrastructure`

## Delivery Workflow

CubeMart follows a staged collaboration model:

1. Work starts in `feature/*` or `docs/*` branches
2. Changes are merged into `dev`
3. Validated work is promoted to `test`
4. Release-ready changes are promoted to `main`

This keeps contribution flow simple and makes the project a strong collaboration and portfolio environment.

## Technology Highlights

- Go
- Python
- Node.js
- Java
- C#
- Docker
- Jenkins
- Kubernetes
- ArgoCD
- Terraform
- AWS
- OpenTelemetry
- OpenAI

## Why CubeMart

- cloud-native application development
- microservices architecture
- DevOps and GitOps workflows
- observability and tracing
- AI-assisted product experiences
- team-based contribution and review practices

## Getting Started

If you're exploring CubeMart for the first time, start with:

- `frontend` for the user-facing entry point
- `authservice` for identity and login flow
- `checkoutservice` for order orchestration
- `shoppingassistantservice` for the AI recommendation workflow
- `gitops` for Kubernetes deployment structure
- `infrastructure` for Terraform-based AWS provisioning

# Week 1: Cloud Foundations (GCP) - Documentation

**Dates:** 24/11/2025 - 29/11/2025
**Status:** Completed
**Project ID:** cloud-roadmap-lab
**Website URL:** https://storage.googleapis.com/cloud-roadmap-lab-samex/index.html

## Overview
This week focused on setting up the Google Cloud environment, securing it with billing alerts, and deploying a serverless static website using Cloud Storage.

---

## Daily Breakdown

### Day 6: Project Hierarchy
- **Concept:** GCP resources are organized into Projects.
- **Action:** Created Project `cloud-roadmap-lab`.
- **Learned:** IAM permissions inherit from the Project level.

### Day 7: FinOps (Billing)
- **Concept:** Cloud costs must be monitored.
- **Action:** Linked Billing Account and created a Budget Alert ($10/month).
- **Tool:** GCP Billing Dashboard.

### Day 8: Cloud Storage (GCS)
- **Concept:** Object Storage (Buckets) vs Block Storage.
- **Action:** Created a Standard Regional bucket in `us-south1`.
- **Learned:** Storage Classes (Standard, Nearline, Coldline, Archive).

### Day 9: Static Website Deployment
- **Concept:** Hosting HTML directly from a bucket (Serverless).
- **Action:** Uploaded `index.html` and configured `allUsers` access.
- **Security:** Modified permissions to allow public viewing.

### Day 10: Networking Concepts
- **Concept:** How users find the site.
- **Learned:**
    - **DNS:** Maps names to IPs.
    - **Load Balancing:** Distributes traffic.
    - **CDN:** Caches content globally for speed.

### Day 11: The CLI (`gcloud`)
- **Concept:** Infrastructure as Code / Automation.
- **Action:** Used Cloud Shell to create/delete resources via terminal.
- **Command:** `gcloud storage buckets create gs://cloud-roadmap-lab-samex-cli-22 --location=us-south1`

---

## 🔧 Skills Acquired
- GCP Console Navigation.
- IAM Basic Permissions (Storage Viewer).
- Cloud Shell & gcloud SDK.
- Markdown Documentation.

## Day 12:** Deployed a serverless website on Google Cloud Storage.

## Accomplishment
- **IAM:** Configured permissions for `allUsers`.
- **Storage:** Managed Standard Storage Buckets.
- **Networking:** Understood DNS, CDN, and Load Balancing concepts.
- **CLI:** Mastered `gcloud storage` commands.
- **Cost:** Set up Billing Budgets to prevent overspending.

**Next Steps:** Week 2 - Compute Engine.

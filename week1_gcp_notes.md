
# Week 1: GCP Foundations

## Day 6: Console & Project
- Created Project: cloud-roadmap-lab
- Project ID: cloud-roadmap-lab

## Day 7: Billing Safety
- Activated $300 free Credits.
- Set Budget Alert to $10/month to monitor credit usage.

## Day 8: Cloud Storage (GCS)
- Created a Standard Bucket: cloud-roadmap-lab-samex
- Region: us-south1(Dallas)
- Uploaded first object.

## Day 9: Static website
- Created index.html.
- Disabled public Access Prevention.
- Granted 'Storage Object Viewer' to 'allUsers'.
- Website URL: https://storage.googleapis.com/cloud-roadmap-lab-samex/index.html

## Day 10: DNS & Load Balancing Concepts
- Analyzed HTTP headers using curl.
- CNAME: Points a domain name to another domain name (used for Buckets).
- Load Balancer: Distributes traffic across multiple servers to prevent crashing.
- CDN: Caches content closer to the user to reduce latency.


## Day 11: Cloud Shell & CLI
- Used Cloud Shell (Ephemeral Linux VM in browser).
- Command: `gcloud auth list` (Check user).
- Command: `gcloud config set project <id>` (Set workspace).
- Command: `gcloud storage buckets create gs://<name>` (Create resource).

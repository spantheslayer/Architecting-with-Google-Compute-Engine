# Deploying Applications to Google Cloud

## 1. You've been asked to write a program that uses Vision API to check for inappropriate content in photos that are uploaded to a Cloud Storage bucket. Any photos that are inappropriate should be deleted. What might be the simplest, cheapest way to deploy in this program?

- Compute Engine
- GKE
- App Engine
- [x] **Cloud Functions**

> ✔️ Correct
> This is the correct answer, because the requirements for simplest and cheapest are met with Cloud Functions. Cloud Functions are for single purpose functions like image analysis. Cloud Functions also can be triggered by Cloud Storage events, so they provide seamless integration. The payment model based on number of request, processing time of request (measured in 100ms units), and then other resources consumed is the most suitable of all options offered above. There is a free tier too. Cloud Functions also provides automatic scaling, high availability, and fault tolerance.

## 2. You have containerized multiple applications using Docker and have deployed them using Compute Engine VMs. You want to save cost and simplify container management. What might you do.

- Rewrite the applications to run in Cloud Functions.
- Rewrite the applications to run in App Engine.
- [x] **Migrate the containers to GKE.**
  > ✔️ Correct
  > This is the correct answer. The applications are containerized, and GKE will help with the resource efficiency and hence cost, automate many aspects of the container management, and provide the best solution for the scenario.
- Write Terraform scripts for all deployment.

## 3. You need to deploy an existing application that was written in .NET version 4. The application requires Windows servers, and you don't want to change it. Which should you use?

- [x] **Compute Engine**
  > ✔️ Correct
  > Because the approach is a lift and shift which is best supported by Compute Engine, because Compute Engine offers full control over virtual machines including operating system. No repackaging would be required.
- App Engine
- GKE
- Cloud Functions

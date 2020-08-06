# Developing, Deploying, and Monitoring in the Cloud

### 1. Why might a GCP customer choose to use Cloud Source Repositories?

- They want to host and manage their own git instance, and they want to integrate with IAM permissions.
- They want to host and manage their own git instance, and they don't want to integrate with IAM permissions.
- [x] **They don't want to host their own git instance, and they want to
      integrate with IAM permissions.**
  > ✔ Correct !
- They don't want to host their own git instance, and they don't want
  to integrate with IAM permissions.

---

### 2. Why might a GCP customer choose to use Cloud Functions?

- Cloud Functions is a free service for hosting compute operations.
- [x] **Their application contains event-driven code that they don't want
      to have to provision compute resources for.**
  > ✔ Correct !
- Cloud Functions is the primary way to run Node.js applications in GCP.
- Their application has a legacy monolithic structure that they want to break apart into microservices with little developer effort.

---

### 3. Why might a GCP customer choose to use Deployment Manager?

- Deployment Manager enforces maximum resource utilization and spending limits on your GCP resources.
- [x] **Deployment Manager is an infrastructure management system for GCP resources.**
  > ✔ Correct !
- Deployment Manager is an infrastructure management system for Kubernetes pods.
- Deployment Manager is a version control system for your GCP
  infrastructure layout.

---

### 4. You want to define alerts on your GCP resources, such as when health checks fail. Which is the best GCP product to use?

- Stackdriver Trace
- [x] **Stackdriver Monitoring**
  > ✔ Correct !
- Stackdriver Debugger
- Deployment Manager
- Cloud Functions

---

### 5. Which statements are true about Stackdriver Logging? Choose all that are true (2 statements)

- [ ] Stackdriver Logging requires that you store your logs in BigQuery
      or Cloud Storage.

- [ ] Stackdriver Logging requires the use of a third-party monitoring
      agent.

- [ ] Stackdriver Logging lets you define uptime checks.

- [x] **Stackdriver Logging lets you define metrics based on your logs.**

  > ✔ Correct !

- [x] **Stackdriver Logging lets you view logs from your applications,
      and filter and search on them.**
  > ✔ Correct !

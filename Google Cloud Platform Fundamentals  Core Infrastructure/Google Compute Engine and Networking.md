# Google Compute Engine and Networking

### 1. True or False: Google Cloud Load Balancing allows you to balance HTTP-based traffic across multiple Compute Engine regions.

- [x] **True**
  > ✔ Correct !
  > With global Cloud Load Balancing, your application presents a single front-end to the world.
- False

---

### 2. Which statement is true about Google VPC networks and subnets?

- Networks are global; subnets are zonal
- [x] **Networks are global; subnets are regional**
  > ✔ Correct !
- Networks are regional; subnets are zonal
- Networks and subnets are global

---

### 3. An application running in a Compute Engine virtual machine needs high-performance scratch space. Which type of storage meets this need?

- SSD persistent
- Standard persistent
- [x] **Local SSD**
  > ✔ Correct !
- Local standard

---

### 4. Choose an application that would be suitable for running in a Preemptible VM.

- An interactive website
- A batch job that cannot be checkpointed and restarted
- [x] **A batch job that can be checkpointed and restarted**
  > ✔ Correct !
- An online relational database

---

### 5. How do Compute Engine customers choose between big VMs and many VMs?

- [x] **Use big VMs for in-memory databases and CPU-intensive analytics; use many VMs for fault tolerance and elasticity**
  > ✔ Correct !
- Use big VMs for fault tolerance and elasticity; use many VMs for in-memory databases and CPU-intensive analytics

---

### 6. How do VPC routers and firewalls work?

- [x] **They are managed by Google as a built-in feature.**
  > ✔ Correct !
- Customers provision virtual machines and run their routers and firewalls in them.
- They are managed by Google in virtual machines, which customers may tune or turn off.
- They are managed by Google in virtual machines, which customers may never modify.

---

### 7. A GCP customer wants to load-balance traffic among the back-end VMs that form part of a multi-tier application. Which load-balancing option should this customer choose?

- The global TCP proxy
- The global HTTP(S) load balancer
- [x] **The regional internal load balancer**
  > ✔ Correct !
- The regional load balancer
- The global SSL proxy

---

### 8. For which of these interconnect options is a Service Level Agreement available?

- [x] **Dedicated Interconnect**
  > ✔ Correct !
- Direct Peering
- Carrier Peering
- VPNs with Cloud Router

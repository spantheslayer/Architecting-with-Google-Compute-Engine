# Google Cloud and Hybrid Network Architecture

## 1. You want a secure, private connection between your network and a Google Cloud network. There is not a lot of volume, but the connection needsto be extremely reliable. Which configuration below would you choose?

- VPN
- [x] **VPN with high availability and Cloud Router.**
  > ✔ Correct !
  > Because this offers a secure extremely reliable connection and is more cost-effective than Cloud Interconnect
- Cloud Interconnect
- VPC peering

## 2. You have a contract with a service provider to manage your Google VPC networks. You want to connect a network they own to your VPC. Both networks are in Google Cloud. Which Connection option should you choose?

- VPN with high availability and Cloud Router.
- Cloud Interconnect
- VPN
- [x] **VPC peering**
  > ✔ Correct !
  > Because VPC peering allows connectivity across two VPC networks regardless of whether they belong to the same project or same organization.

## 3. You are a large bank deploying an online banking service to Google Cloud. The services needs high volume access to mainframe data on-premises. Which connectivity option would likely be best?

- HTTPS
- Peering
- [x] **Cloud Interconnect**
  > ✔ Correct !
  > Because Cloud Interconnect provides high bandwidthand low latency. It does need encryption at the application level.
- VPN

## 4. You are deploying a large-scale web applications with users all over the world and a lot of static content. Which load balancer configuration would likely be the best?

- [x] **HTTP load balancer with SSL configured and the CDN enabled.**
  > ✔ Correct !
  > Because the traffic is HTTP(S), the load balancer should be external and global, and CDN enabled will help performance and cost.
- TCP load balancer with SSL configured.
- HTTP load balancer with SSL configured.
- UDP load balancer with SSL configured and the CDN enabled.

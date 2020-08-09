# Choosing Storage Solutions

## 1. Currently, you are using Firestore to store information about products, reviews, and user sessions. You'd like to speed up data access in a simple, cost-effective way. What would you recommend?

- Move the data to Spanner.
- Move the data to BigQuery.
- Move the data to Cloud Bigtable.
- [x] **Cache the data using Memorystore.**

> ✔ Correct !
> Memorystore provides the best fit when considering data model, performance, scale, cost, and availability.

## 2 .You want to analyze sales trends. To help achieve this, you want to combine data from your on-premises Oracle database with Google Analytics data and your web server logs. Where might you store the data so it is both easy to query and cost-effective?

- Firestore
- Spanner
- [x] **BigQuery**
  > ✔ Correct !
  > BigQuery is a data warehouse used for data analytics,and so is built for this type of use case. It provides the infrastructureto ingest data from many different sources, which is a requirement too.The cost model of paying for storage and then only for queries run isattractive too.
- Cloud SQL

## 3 .You are a global financial services company with users all over the world. You need a database service that can provide low latency worldwide with strong consistency. Which service might you choose?

- Cloud SQL
- [x] **Spanner**

  > ✔ Correct !
  > A key feature of Spanner is scale for relationaldata with strong consistency, and it is globally distributed to provide low latency. The high availability and automatic replication are also strong features for financial services.

- BigQuery
- Firestore

## 4. You need to store user preferences, product information, and reviews for a website you are building. There won't be a huge amount of data. What would be a simple, cost-effective, managed solution?

- BigQuery.
- Cloud SQL.
- [x] **Firestore.**
  > ✔ Correct !
  > Firestore provides automatic scale ACID transactions and live synchronization and is integrated with Google Cloud and Firebase. It also has a free tier.
- Spanner.

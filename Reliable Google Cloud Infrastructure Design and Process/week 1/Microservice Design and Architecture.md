# Microservice Design and Architecture

## 1. You’re building a RESTful microservice. Which would be a valid data format for returning data to the client?

- JSON
- XML
- HTML
- [x] **All of the above.**

> ✔ Correct !
> They have a standard Content-Type that can be set on the response header and are text-based. It is usual to use JSON, but both XML and JSON are valid.

## 2. You’re writing a service, and you need to handle a client sending you invalid data in the request. What should you return from the service?

An XML exception

A 200 error code

A 500 error code

- [x] **A 400 error code**
  > ✔ Correct !
  > 400 is a HTTP status code indicating that a request could not be processed due to an apparent client error.

## 3. Which below would **violate** 12-factor app best practices?

Treat logs as event streams and aggregate logs into a single source.

- [x] **Store configuration information in your source repository for
      easy versioning.**
  > ✔ Correct !
  > Code and config should be separated, because config varies across deployments but code does not. The true test is whether the repository could be open-sourced without compromising any credentials.
- Keep development, testing, and production as similar as possible.
- Explicitly declare and isolate dependencies.

## 4. You’ve re-architected a monolithic web application so state is not stored in memory on the web servers, but in a database instead. This has caused slow performance when retrieving user sessions though. What might be the best way to fix this?

- Move session state back onto the web servers and use sticky sessions in the load balancer.
- Make sure all web servers are in the same zone as the database.
- [x] **Use a caching service like Redis or Memorystore.**
  > ✔ Correct !
  > Services should be stateless, and a service like Redis or Memorystore provides a fast caching service to store state. They enable services to be stateless and support scale and high availability.
- Increase the number of CPUs in the database server.

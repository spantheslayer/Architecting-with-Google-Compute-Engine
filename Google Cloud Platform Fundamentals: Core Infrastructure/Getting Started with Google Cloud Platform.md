# Getting Started with Google Cloud Platform

### 1. True or False: In Google Cloud IAM: if a policy applied at the project level gives you Owner permissions, your access to an individual resource in that project might be restricted to View permission if someone applies a more restrictive policy directly to that resource.

- True
- [x] **False**
  > ✔ Correct !
  > Policies are a union of those applied on resource itself and those inherited from higher levels in the hierarchy. If a parent policy is **less** restrictive, it overrides a more restrictive policy applied on the resource. If a parent policy is **more** restrictive, it does not override a less restrictive policy applied on the resource. Therefore, access granted at a higher level in the hierarchy cannot be taken away by policies applied at a lower level in the hierarchy.

---

### 2. True or False: All Google Cloud Platform resources are associated with a project.

- [x] **True**
  > ✔ Correct !
  > All Google Cloud Platform resources are associated with a project.
- False

---

### 3. Service accounts are used to provide which of the following? (Choose all that are correct. Choose 3 responses.)

- [x] **Authentication between Google Cloud Platform services**
  > ✔ Correct !
- [x] **A way to allow users to act with service account permissions**
  > ✔ Correct !
- [x] **A way to restrict the actions a resource (such as a VM) can
      perform**
  > ✔ Correct !
- [ ] A set of predefined permissions

---

### 4. How do GCP customers and Google Cloud Platform divide responsibility for security?

- All aspects of security are Google's responsibility.
- [x] **Google takes care of the lower parts of the stack, and customers are responsible for the higher parts.**
  > ✔ Correct !
- Google takes care of the higher parts of the stack, and customers are responsible for the lower parts.
- All aspects of security are the customer's responsibility.

---

### 5. Which of these values is globally unique, permanent, and unchangeable, but chosen by the customer?

- The project number
- The project's billing credit-card number
- The project name
- [x] **The project ID**
  > ✔ Correct !

---

### 6. Consider a single hierarchy of GCP resources. Which of these situations is possible? (Choose all that are correct. Choose 3 responses.)

- [x] **There is an organization node, and there is at least one folder.**
  > ✔ Correct !
- [ ] There is no organization node, but there is at least one folder.
- [x] **There is an organization node, and there are no folders.**
  > ✔ Correct !
- [ ] There are two or more organization nodes
- [x] **There is no organization node, and there are no folders.**
  > ✔ Correct !

---

### 7. What is the difference between IAM primitive roles and IAM predefined roles?

- Primitive roles are changeable once assigned. Predefined roles can never be changed.

- Primitive roles only allow viewing, creating, and deleting resources. Predefined roles allow any modification.

- Primitive roles can only be granted to single users. Predefined roles can be associated with a group.

- Primitive roles only apply to the owner of the GCP project. Predefined roles can be associated with any user.

- [x] **Primitive roles affect all resources in a GCP project. Predefined roles apply to a particular service in a project.**

> ✔ Correct !

---

### 8. Which statement is true about billing for solutions deployed using Cloud Marketplace (formerly known as Cloud Launcher)?

- [x] **You pay only for the underlying GCP resources you use, with the possible addition of extra fees for commercially licensed software.**

> ✔ Correct !

- You pay only for the underlying GCP resources you use; Google pays the license fees for commercially licensed software.

- Cloud Marketplace solutions are always free.

- After a trial period, each Cloud Marketplace solution assesses a fixed recurring monthly fee.

---
name: User Story
about: For Final Exam
title: "Create Product in Catalog"
labels: enhancement
assignees: alirezahassani1

---

**As a** product manager  
**I need** to create a product in the catalog  
**So that** customers can see new products and make purchases  
   
### Details and Assumptions
* The product manager has admin access to the system.
* Each product must include a name, description, price, and category.
* All required fields must be validated before submission.
* The system stores product data in the catalog database.
   
### Acceptance Criteria  

```gherkin
Given I am logged in as a product manager
When I enter valid product details and click "Create"
Then the product is saved in the catalog database
```

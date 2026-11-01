# GitHub Actions implementation for Austrix-Advisory 45+  Microservices Application with 
### For GitHub Actions, I recommend a central repository containing reusable workflows.

**Example:**
```
platform-ci-templates/
│
└── .github/
    └── workflows/
        ├── austrix-java-ci.yml
        ├── frontend-ci.yml
        ├── database-ci.yml
        ├── promote-dev.yml
        ├── promote-qa.yml
        ├── promote-uat.yml
        ├── promote-prod.yml
        └── rollback.yml
```


Each application repository calls the central workflows.

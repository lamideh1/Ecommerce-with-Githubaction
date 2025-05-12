# Ecommerce-with-Githubaction
Here’s a full step-by-step guide on what you should do from start to finish for your **E-Commerce CI/CD Capstone Project**:

---

## **Step-by-Step Guide for Capstone Project**

---

### **Task 1: Project Setup**

1. **Create a new GitHub repository**

   * Name: `ecommerce-platform`
   * Initialize with a `README.md` and `.gitignore` (Node)

2. **Create directories inside the repo**

   ```bash
   mkdir -p ecommerce-platform/api
   mkdir -p ecommerce-platform/webapp
   mkdir -p ecommerce-platform/.github/workflows
   ```

---

### **Task 2: Initialize GitHub Actions**

Inside `.github/workflows`, create two files:

* `ci-api.yml`
* `ci-webapp.yml`

These files will contain your CI/CD workflows for backend and frontend.

---

### **Task 3: Backend API Setup**

1. Navigate to `api` and initialize a Node project:

   ```bash
   cd api
   npm init -y
   npm install express jest supertest
   ```

2. **Create a simple Express app** (`api/index.js`) and a test (\`

# 🚀 Cloud Resume Challenge (Azure Edition)

This project is part of the Cloud Resume Challenge inspired by [Forrest Brazeal](https://cloudresumechallenge.dev/). It showcases my practical cloud skills using **Microsoft Azure** and includes:
- A responsive HTML/CSS resume website
- Static hosting via **Azure Blob Storage**
- Version control and CI/CD using **GitHub Actions**
- Future integration of **Azure Functions**, **Cosmos DB**, and **Infrastructure as Code**

---

## 📌 Project Progress

| Stage | Description | Status | Notes |
|-------|-------------|--------|-------|
| 1 | **Azure Fundamentals Certification (AZ-900)** | ✅ Done | Passed and certified |
| 2 | **HTML Resume Created** | ✅ Done | `index.html` completed |
| 3 | **CSS Styling Applied** | ✅ Done | External `styles.css` used |
| 4 | **Website Hosted on Azure Blob Storage** | ✅ Done | Static site deployed: [Live Site](https://crcstoragewe01.z6.web.core.windows.net//) |
| 5 | **HTTPS for Azure Storage URL using Azure CDN** | ✅ Done | Azure CDN profile created |
| 6 | **DNS Domain for Azure CDN endpoint** | ✅ Done | Custom domain added to Azure CDN endpoint |
| 7 | **Frontend JS for Visitor Counter** | 🔜 Pending | Integrate API with resume site |
| 8 | **Azure Cosmos DB / Table Storage** | 🔜 Pending | Store and retrieve visitor count data |
| 9 | **Azure Function Backend API (Visitor Counter)** | 🔜 Pending | Will handle API requests |
|10 | **Python Azure Function (Backend Logic)** | 🔜 Pending | Python code to handle serverless logic |
|11 | **Python Code Testing** | 🔜 Pending | Unit tests to ensure Azure Function logic is reliable and bug-free |
|12 | **Infrastructure as Code (Bicep/Terraform)** | 🔜 Optional | Automate resource provisioning |
|13 | **Source Control & CI/CD** | 🔜 Pending | GitHub repo and workflows to auto-deploy frontend and backend on code changes |
|14 | **CI/CD Pipeline for Backend** | 🔜 Pending | GitHub Actions to run tests and deploy Azure Function and IaC templates automatically |
|15 | **CI/CD Pipeline for Frontend** | 🔜 Pending | Automate frontend deployment to Azure Blob Storage via GitHub Actions, with optional CDN cache purge |
|16 | **Blog Post Summary** | 🔜 Pending | Will write and publish a short blog post reflecting on lessons learned during the Cloud Resume Challenge |


----------


# 🌩️ Cloud Resume Challenge (Azure Edition)

This is my implementation of the [Cloud Resume Challenge](https://cloudresumechallenge.dev/) by Forest Brazeal — an end-to-end full-stack cloud project designed to demonstrate real-world cloud engineering skills.

## 🔗 Current Live Project
**[🌐 View the Live Site](https://wisdomresume.site/)** 

---

## 📸 Final Deployed Website

**Live Website** In progress..

---

As I take on the Cloud Resume Challenge, I’ve been able to earn the Microsoft AZ-900 certification and I also have some background in frontend web design. I’ve built the first version of my resume website using HTML and CSS, and from here, I’ll be documenting the next steps I’m working through as I continue learning and building.

## 📁 1. Static Website Hosting (Azure Blob Storage)

Used Azure Blob Storage to host a static website with an `index.html` and `styles.css`.

- Enabled static website hosting
- Uploaded files into the `$web` container

📸 Screenshot:

Azure static website hosting:
![Azure static website hosting](screenshots/azure-static-hosting.png)

---

## 🔐 2. HTTPS and Custom Domain (via Cloudflare)

Domain was purchased via Namecheap and pointed to Azure via **Cloudflare**:

- Custom domain `wisdomresume.site`
- Free SSL with Cloudflare Universal Certificate
- DNS settings managed on Cloudflare

📸 Screenshot:

Cloudflare DNS Settings:
![Cloudflare DNS Settings](screenshots/cloudfare-dns-settings.png)

Namecheap Custom Nameservers:
![Namecheap Custom Nameservers](screenshots/namecheap-nameservers.png)

---

















---

## 📚 License

This project is licensed under the [MIT License](LICENSE).


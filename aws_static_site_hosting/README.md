# 🌩️ AWS SAM Template — CloudFront + S3 Deployment

**Watch Tutorial:** 

📺 [How to Deploy a Static Website with AWS SAM, S3 & CloudFront](https://www.youtube.com/watch?v=6mmaG3YuEV0&list=PLy5TOS2hGqCm1kT8mA-_FKWDqfvPfXv9C)  


If you found this helpful, check out my YouTube channel for more **project ideas**:  
👉 [Subscribe here](https://www.youtube.com/@CyberBlueCollarBrandon?sub_confirmation=1) — *More Cool Videos Coming Soon*


---

This AWS SAM template provisions everything you need to **host and deliver a static website** using **Amazon S3** and **CloudFront**.  
It provides fast, secure, and cost-efficient global content delivery — perfect for personal sites, portfolios, or small projects.

## 🚀 Quick Start

**1. Build the project**
```bash
sam build
```

**2. Deploy with guided setup**
```bash
sam deploy --guided
```

**3. Upload your site files**  
Once deployment completes, upload your static files (HTML, JS, CSS, images) to the created S3 bucket.

**4. Access your live site**  
The output CloudFront domain will serve your content securely over HTTPS, powered by AWS’s global CDN.

---

## 💡 What’s Included

- **Amazon S3** — Hosts your static files.  
- **Amazon CloudFront** — Distributes your content with caching and HTTPS.  
- **Origin Access Control (OAC)** — Restricts direct S3 access to CloudFront only.  
- **Infrastructure as Code** — Fully managed via AWS SAM and CloudFormation.


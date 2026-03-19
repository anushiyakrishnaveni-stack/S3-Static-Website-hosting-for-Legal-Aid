# ⚖️ JusticeForward: Legal Aid Static Website

[![AWS S3 Hosting](https://img.shields.io/badge/AWS-S3%20Hosting-orange?logo=amazon-aws)](https://aws.amazon.com/s3/)
[![Tailwind CSS](https://img.shields.io/badge/Frontend-Tailwind%20CSS-blue?logo=tailwind-css)](https://tailwindcss.com/)

A high-performance, responsive legal aid platform designed to bridge the gap between low-income individuals and essential legal resources. This project demonstrates a **Serverless Static Website** architecture using Amazon S3.

---

## 🛠️ Technical Architecture
This project leverages **AWS Cloud Infrastructure** to ensure 99.99% availability and cost-efficient scaling.

* **Storage & Hosting:** Amazon S3 (Simple Storage Service)
* **Region:** `ap-southeast-2` (Sydney)
* **Frontend Framework:** Tailwind CSS (via CDN)
* **Deployment Workflow:** Manual S3 Upload & Public Policy Configuration

## 🌟 Key Features
* **Lawyer Directory:** Staff profiles with area-of-practice tagging.
* **Non-Profit Support:** Integrated donation tiers to fund legal representation.
* **Responsive UI:** Mobile-first design ensuring accessibility on all devices.
* **Secure Inquiry Form:** Clean interface for users to submit legal assistance requests.

## ☁️ Cloud Administration Steps
To achieve the deployment seen in the screenshots, the following AWS configurations were implemented:

1.  **S3 Bucket Provisioning:** Created `static-website-6811` with standardized naming conventions.
2.  **Static Website Hosting:** Enabled the hosting property and mapped `index.html` as the entry point.
3.  **Permissions & Access Control:** * Modified "Block Public Access" settings to allow external reach.
    * Applied bucket policies to ensure objects are publicly readable.
4.  **Deployment:** Uploaded the optimized 9.7 KB `index.html` file to the bucket root.

## 📂 Repository Contents
| File | Description |
| :--- | :--- |
| `index.html` | Core website file containing HTML5 and Tailwind CSS logic |
| `README.md` | Project documentation and AWS implementation details |

---

## 👤 Author
**Anushiya Krishnaveni**
*Recent Cloud DevOps Bootcamp Graduate*

---
*Disclaimer: This project is for portfolio purposes. The legal information provided is for demonstration only.*

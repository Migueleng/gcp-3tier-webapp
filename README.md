# GCP 3-Tier Web App Backend (Flask + Cloud SQL + Compute Engine)

This project is a **3-tier web application backend** deployed on **Google Cloud Platform (GCP)**. It demonstrates core skills in **cloud engineering, infrastructure design, networking, automation, and backend deployment** using GCP services.

## 🌐 Live Demo

> 🔗 [http://34.72.193.230:8080](http://34.72.193.230:8080)
> ⚠️ **Note:** This app is hosted on a GCP Compute Engine VM.  
> The demo link may be temporarily unavailable if the VM is shut down to reduce costs.


## ✅ Features

- Flask backend API hosted on GCP Compute Engine
- Google Cloud SQL (PostgreSQL) as the managed database
- VM configured with startup scripts and environment variables
- Traffic exposed through port 8080 (firewall configured)
- GitHub integrated and version controlled

## 📦 Tech Stack

- **Google Cloud Platform (GCP)**
  - Compute Engine
  - Cloud SQL (PostgreSQL)
  - Cloud Shell & IAM
- **Python + Flask**
- **PostgreSQL**
- **Git + GitHub**

## 🗂️ Architecture

User → HTTP Request → GCP VM (Compute Engine, Flask App)
↓
Cloud SQL (PostgreSQL)



## 🚀 Deployment Steps

1. **Set up GCP Project**
2. **Provision Cloud SQL PostgreSQL Instance**
3. **Configure Compute Engine VM**
   - Installed dependencies via `requirements.txt`
   - Flask app launched with `nohup`
4. **Opened Firewall for Port 8080**
5. **Set environment variables**
6. **Pushed source code to GitHub**

## 📁 Project Structure

gcp-3tier-webapp/
└── backend/
├── app.py
├── requirements.txt
└── startup-script.sh


## 👨🏽‍💻 Author

**Sitou Miguel Efraim Agbodjinou**  
🧠 *Aspiring Cloud Engineer | Google Cloud Certified | Python & GCP Projects | Compute Engine • Cloud SQL • DevOps Foundations*  
🌍 Phoenix, AZ  
📧 [mltd1985@hotmail.com](mailto:mltd1985@hotmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/sitou-agbodjinou-96b120358/)

---


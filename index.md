---
layout: default
title: Deal Hub Aggregator
description: Amazon Deal Tracker using Terraform, Kubernetes, and AWS.
---

# 🚀 Deal Hub Aggregator  

## Author  
![Jay Langford](assets/images/cheese.PNG){: .profile-pic }  
**Jay Langford**  

## Overview  
The **Deal Hub Aggregator** is a web application that aggregates and displays trending Amazon deals. The system utilizes the Amazon API to fetch and process product data, including:  

- **Trending Items**  
- **Best Deals**  
- **Product Information**  
- **Price Chart & History**  
- **Predicted Prices**  
- **Direct Amazon Product Links**  

The goal is to provide users with a centralized hub for tracking Amazon deals efficiently while optimizing API usage and storage.  

---

## 🔧 Current Progress  

### Backend Implementation  
The backend is mostly complete with the following implemented:  

✅ **Infrastructure Deployment using Terraform**, automating:  
- Load Balancer  
- Auto Scaling  
- Compute Instances  

✅ **Monitoring & Hosting via:**  
- **Prometheus & Grafana** (deployed as Helm charts in Kubernetes)  
- Tracks API usage and system performance  

---

## 📌 Planned Enhancements  

🚀 **Time-Series Database** (for historical price tracking)  
📦 **S3 Bucket Storage** (short-term & long-term data retention)  

---

## 🔜 Next Steps  

The next phase involves developing the **frontend**:  

🎨 **Tech Stack**: Likely **React** for a modern and smooth UI  
📊 **Data Visualization**: Price trends, deal comparisons, and predictive analytics  
🖥️ **User Interface**: Clean and intuitive design for seamless navigation  

---

## 🔮 Future Enhancements  

🤖 **Machine Learning** for Price Prediction  
🌍 **Multi-Region Price Comparison**  
🔔 **User Alerts** for Price Drops  

---

<style>
@import url('/assets/css/custom.css');

.profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    display: block;
    margin: 10px auto;
}
</style>

Stay tuned for updates! 🚀
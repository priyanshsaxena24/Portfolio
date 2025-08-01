---
title: "YouTube Watch Analysis"
description: "A full-stack project that analyzes YouTube watch history using FastAPI, React, and Chart.js to visualize user activity."
date: 2025-08-01
draft: false
type: "page"
---

**YouTube Watch Analysis** is a full-stack application that visualizes your YouTube watch history using charts and custom metrics. It combines a Python-based backend and a React-based frontend to deliver personalized data insights.

## 🗂 Project Overview

This project parses YouTube watch history data, processes it using FastAPI and Python, and displays meaningful charts on a sleek React interface.

### 📦 Project Structure

- **Backend**: FastAPI + Python scripts (for YouTube API, Selenium, data processing)
- **Frontend**: React + Chart.js (user input + chart rendering)
- **Intermediates**: JSON files to store and merge data

## 🚀 Technologies Used

- **Frontend**: React, Chart.js
- **Backend**: FastAPI, Python, Selenium, Google API Client
- **Tools**: JSON, uvicorn

## 🔌 API Endpoints

- `POST /start-selenium-task`: Triggers a YouTube data extraction task
- `GET /status`: Checks the backend task progress
- `GET /data`: Returns the merged, processed watch data

## 🧪 How to Run the Project

1. **Start Backend**:
    ```bash
    cd backend
    uvicorn main:app --reload
    ```

2. **Start Frontend**:
    ```bash
    npm start
    ```

Then open [http://localhost:3000](http://localhost:3000) in your browser to explore the charts and data.

## 🔓 License

This project is licensed under the MIT License.

## 📁 GitHub Repository

[priyanshsaxena24/Watch_Analytics on GitHub](https://github.com/priyanshsaxena24/Watch_Analytics)


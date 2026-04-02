# 🚀 Test API - JSON Placeholder Wrapper

[![Deploy to Render](https://github.com/toxicbishop/test_api/actions/workflows/deployment.yml/badge.svg)](https://github.com/toxicbishop/test_api/actions/workflows/deployment.yml)

A lightweight and efficient Flask-based API wrapper for the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) service. Built for testing deployments, CI/CD pipelines, and serving as a boilerplate for your next project.

---

## ✨ Features

- ⚡ **Fast & Lightweight**: Built with Python and Flask.
- 📡 **RESTful Architecture**: Follows standard API practices.
- 🔄 **Auto-Deployment**: Integrated with GitHub Actions and Render for seamless CI/CD.
- 🗺️ **Comprehensive Endpoints**: Wraps popular JSONPlaceholder data types.

---

## 🛠️ API Reference

### Home Route
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/` | API Overview & Status |

### Data Endpoints
| Method | Endpoint | Description | Returns |
| :--- | :--- | :--- | :--- |
| `GET` | `/posts` | Retrieves all posts | JSON Array of Posts |
| `GET` | `/comments` | Retrieves all comments | JSON Array of Comments |
| `GET` | `/albums` | Retrieves all albums | JSON Array of Albums |

---

## ⚙️ Local Development

Follow these steps to get the project running locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/toxicbishop/test_api.git
cd test_api
```

### 2️⃣ Set Up Virtual Environment (Optional)
```bash
python -m venv venv
source venv/Scripts/activate  # On Windows
# source venv/bin/activate    # On macOS/Linux
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```bash
python app.py
```
The server will start at: `http://127.0.0.1:5000/`

---

## 🚢 Deployment

This project is configured for automated deployments:
- **CI Tool**: GitHub Actions (`.github/workflows/deployment.yml`)
- **Hosting**: Render (or any WSGI-compatible host)

When you push to the `main` branch, the deployment workflow is triggered, automatically updating your live instance.

---

## 📄 License

This project is open-source and free to use.

---
<p align="center">Made with ❤️ for developers everywhere.</p>

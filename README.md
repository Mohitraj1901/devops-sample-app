# DevOps Sample App 🚀

A simple Python project demonstrating DevOps practices like CI/CD with GitHub Actions, Pytest, Pyright, and Docker.

---

## 📁 Project Structure

devops-sample-app/
├── app/ # Python app code
├── tests/ # Unit tests using Pytest
├── Dockerfile # Containerization setup
├── .github/workflows/ # GitHub Actions CI/CD
├── requirements.txt # Python dependencies
├── pyrightconfig.json # Pyright static type checking


---

## ✅ Project Setup Steps

###
1. Git & GitHub Setup
git init
2. Basic Python Setup
Created main.py with a simple function

Created test_main.py for Pytest unit test

3. Pytest Integration
pip install pytest
pytest
4. Pyright Type Checking
npm install --save-dev pyright
npx pyright
5. Dockerize the App
Created Dockerfile

docker build -t devops-sample-app:v1 .
docker run --rm devops-sample-app:v1
6. GitHub Actions CI/CD Setup
Added .github/workflows/ci.yml to:

Run Pytest

Run Pyright

 ## ✅Build Docker image

🧪 Run Locally
python app/main.py
pytest
npx pyright
📦 Build & Run Docker
docker build -t devops-sample-app:v1 .
docker run --rm devops-sample-app:v1
7.push the code on github

git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/devops-sample-app.git
git push -u origin main

📌 Features
✅ Python code

✅ Static type checking with Pyright

✅ Unit testing with Pytest

✅ CI/CD with GitHub Actions

✅ Dockerized application


Perfect 👍 Adding **badges/shields** will make your README look more professional and polished for GitHub.

Here’s the updated **README.md** with badges included:

````markdown
# US Visa Approval Status Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.95%2B-teal?logo=fastapi)
![MongoDB](https://img.shields.io/badge/MongoDB-Integration-green?logo=mongodb)
![Docker](https://img.shields.io/badge/Docker-Enabled-blue?logo=docker)
![AWS](https://img.shields.io/badge/AWS-Deployed-orange?logo=amazon-aws)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is a **production-ready MLOps application** for predicting **US visa approval status**.

---

## 🚀 Features

- ⚡ **FastAPI** web interface for predictions  
- 🛠️ **Model training pipeline**  
- 📂 **MongoDB integration** for data storage  
- 🐳 **Docker support** for containerization  
- ☁️ **AWS deployment via GitHub Actions** for CI/CD  

---

## ⚙️ Setup

### 1. Clone the repository
```bash
git clone <repo-url>
cd US-visa-approval-status-project
````

### 2. Create and activate a conda environment

```bash
conda create -n visa python=3.8 -y
conda activate visa
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set environment variables

```bash
export MONGODB_URL="mongodb+srv://<username>:<password>@cluster0.mongodb.net/?retryWrites=true&w=majority"
export AWS_ACCESS_KEY_ID=<AWS_ACCESS_KEY_ID>
export AWS_SECRET_ACCESS_KEY=<AWS_SECRET_ACCESS_KEY>
```

---

## 📌 Usage

### 1. Start the FastAPI server

```bash
python app.py
```

Visit 👉 [http://localhost:8080](http://localhost:8080) in your browser.

### 2. Train the model

Send a `GET` request to the `/train` endpoint or visit:

```
http://localhost:8080/train
```

### 3. Make predictions

Fill out the form on the main page and submit to get visa approval predictions.

---

## 📂 Project Structure

* **app.py** → FastAPI application entry point
* **us\_visa/** → Core package (components, pipeline, utils, etc.)
* **requirements.txt** → Python dependencies
* **Dockerfile** → Docker configuration
* **config/** → Model and schema configuration files
* **notebook/** → Jupyter notebooks for EDA & feature engineering

---

## ☁️ AWS CI/CD Deployment

### Steps:

1. **Login** to AWS console
2. **Create IAM user** for deployment

   * Permissions:

     * `AmazonEC2ContainerRegistryFullAccess`
     * `AmazonEC2FullAccess`
3. **Create ECR repo** to store Docker image
4. **Create EC2 machine** (Ubuntu)
5. **Install Docker** on EC2
6. **Configure EC2** as self-hosted runner
7. **Setup GitHub secrets**:

   * `AWS_ACCESS_KEY_ID`
   * `AWS_SECRET_ACCESS_KEY`
   * `AWS_DEFAULT_REGION`
   * `ECR_REPO`

---

## 📜 License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for details.

---

## ✨ Notes

You can further customize this README as needed for your project.

```

---

🔥 This will look very professional on GitHub with badges at the top.  

Do you also want me to add a **demo architecture diagram (pipeline + FastAPI + MongoDB + AWS)** section in the README for extra clarity?
```

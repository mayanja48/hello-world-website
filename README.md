# 🚀 Hello World: My First Cloud Deployment

A simple yet significant "Hello World" website, successfully deployed on **Google Cloud Run**. This project marks my first hands-on experience with cloud infrastructure and the `gcloud` CLI, serving as a foundational step in my cloud development journey.

## 👨‍💻 About Me

I'm **Mayanja Charles**, a passionate and motivated developer from **Uganda**. I am actively exploring cloud technologies and software development with a focus on Google Cloud Platform (GCP). My goal is to build scalable, efficient solutions and contribute to the global tech community.

I am currently preparing to participate in the **Google CLI research study**, and this project is a direct result of my preparation.

## 📁 Project Details

This project demonstrates the end-to-end process of deploying a static website to a fully managed cloud environment.

*   **Frontend:** Basic HTML & CSS
*   **Cloud Service:** Google Cloud Run
*   **Deployment Tool:** Google Cloud CLI (`gcloud`)
*   **Infrastructure Concept:** Serverless Deployment
*   **Source Control:** GitHub

**Live Demo**:  https://github.com/mayanja48/hello-world-website

## 🛠️ How I Deployed This

The deployment was executed using a single command, showcasing the power and simplicity of the `gcloud` CLI:

```bash
gcloud run deploy my-hello-world-service \
  --image=us-docker.pkg.dev/cloudrun/container/hello \
  --region=us-central1 \
  --platform=managed \
  --allow-unauthenticated

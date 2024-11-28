
# Go Web App with DevOps
This project demonstrates an end-to-end DevOps pipeline for a Golang web application. The goal is to automate building, testing, and deploying the Go web app using modern DevOps practices.

# Project Overview
The project automates the following processes:

- Containerization: The Go web app is containerized using Docker with a multi-stage build.
- Deployment on AWS EKS: The application is deployed to a Kubernetes cluster managed by AWS EKS.
- CI/CD Pipeline:
   - GitHub Actions handles Continuous Integration (CI), automating the build and test process.
   - Argo CD handles Continuous Delivery (CD), automating deployment to the Kubernetes cluster.
- Helm: Helm is used to parameterize Kubernetes deployment YAML files, allowing dynamic configuration of variables.
- Ingress & DNS: An Ingress controller exposes the app to the public internet, and DNS mapping points a custom domain to the application.
  
# Technologies Used
Docker, AWS EKS, GitHub Actions, Argo CD, Helm.

# Acknowledgments
This project was created as part of a learning exercise to implement DevOps principles. I referred to the following resources to understand and implement the project:

- YouTube Video: https://www.youtube.com/watch?v=HGu9sgoHaJ0&list=PLdpzxOOAlwvLm5lWlYctUnwaFRIO2Io_5
- GitHub Repository: https://github.com/iam-veeramalla/go-web-app-devops/tree/main


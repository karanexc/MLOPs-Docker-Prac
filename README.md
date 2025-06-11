# MLOPs-Docker-Prac
Docker Fundamentals 

## 🐳 What is Docker?

Docker is a platform that allows developers to build, package, and deploy applications in lightweight, portable containers. These containers encapsulate the app along with its dependencies, ensuring consistent performance across all environments — from development to production.

### 🔑 Key Benefits of Docker

- **Portability** – Run containers across different systems with the same behavior.
- **Isolation** – Containers are independent and don't interfere with each other.
- **Lightweight** – Uses fewer resources than virtual machines.
- **Scalability** – Easily scale services by running multiple containers.

### 🧾 Dockerfile: Blueprint for Images
- FROM: Base image

- COPY / ADD: Add files

- RUN: Install dependencies

- CMD / ENTRYPOINT: Start container

- EXPOSE: Declare ports

---

## 📦 Docker Hub Image

**Repository:** [karanexc/mlops-docker-prac](https://hub.docker.com/repository/docker/karanexc/mlops-docker-prac/general)

---

### 🔹 Pull the Docker Image if you want to view this image

```bash
docker pull karanexc/mlops-docker-prac:latest
```

### 🔹 Push Docker Image to Docker Hub

```bash
docker push <docker_username>/<project_name>:<tags>
```

---

### ▶️ How to Run the Docker Image

After pulling the image from Docker Hub, you can run it as a container using:

```bash
docker run karanexc/mlops-docker-prac
```

If your image expects ports, volumes, or environment variables, use:

```bash
docker run -p 8080:8080 karanexc/mlops-docker-prac
```

### 🗂️ Docker Registry
- Storage for Docker images.

- Public: Docker Hub

- Private: For org-level control

- Cloud: AWS ECR, GCR, Azure ACR

**Benefits:**

* Central image storage

* Version control

* Easy sharing and collaboration



# 🚀 docker-lab: Microservicio Java con Docker

Este proyecto contiene un microservicio desarrollado en Java utilizando Gradle y Docker. El servicio expone una API en el puerto `8085` y está preparado para ser desplegado fácilmente usando `Docker` y `Docker Compose`.

---

## 📂 Archivos RAW

- 🔧 [Dockerfile](https://raw.githubusercontent.com/MariaLazaroVelarde/docker-lab/main/microservicio/Dockerfile)
- 🧱 [docker-compose.yml](https://raw.githubusercontent.com/MariaLazaroVelarde/docker-lab/main/microservicio/docker-compose.yml)

---

## 📦 Construcción de la imagen Docker

```bash
docker build -t marialazaro/up-microservicio:3.0 .

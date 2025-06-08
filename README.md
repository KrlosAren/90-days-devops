# 🚀 Mi Reto de 90 Días de DevOps

![](https://media.licdn.com/dms/image/v2/D4D16AQF4ND-cC_uxZg/profile-displaybackgroundimage-shrink_350_1400/profile-displaybackgroundimage-shrink_350_1400/0/1731367727725?e=1753920000&v=beta&t=80SZ4IOx4V_VDcCBli7aFjYuMhzMos9SRFq8GnV8zc4)

[![Docker](https://img.shields.io/badge/Docker-Ready-blue?logo=docker)](https://docker.com)
[![Node.js](https://img.shields.io/badge/Node.js-Worker-green?logo=node.js)](https://nodejs.org)
[![Flask](https://img.shields.io/badge/Flask-Vote-lightgrey?logo=flask)](https://flask.palletsprojects.com/)
[![Redis](https://img.shields.io/badge/Redis-Cache-red?logo=redis)](https://redis.io)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql)](https://postgresql.org)
[![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-orange?logo=prometheus)](https://prometheus.io)
[![Grafana](https://img.shields.io/badge/Grafana-Visualization-orange?logo=grafana)](https://grafana.com)

> **Este es mi repositorio base** para seguir el **Reto de 90 Días de DevOps** propuesto por **roxsross**.  
> 🌱 Lo estoy adaptando y personalizando para mi propio aprendizaje y práctica.

---

## 🎯 ¿Por qué me sumo a este reto?

Porque **quiero aprender DevOps de forma práctica, divertida y aplicable**, construyendo, rompiendo y mejorando una app real.  
Cada semana representa un nuevo desafío y una nueva oportunidad para crecer como profesional.

📢 *"Si no lo deployás, no lo aprendiste."* — Roxs

---

## 🛠️ ¿Qué contiene este repositorio?

Este proyecto toma como base el [Docker Example Voting App](https://github.com/dockersamples/example-voting-app) y la versión adaptada por **roxsross**, y lo iré personalizando a medida que avance en el reto.  
A lo largo del camino, voy a:

✅ Construir mis propios `docker-compose.yml`  
✅ Automatizar entornos con Ansible  
✅ Crear pipelines CI/CD con GitHub Actions  
✅ Desplegar infraestructura local con Terraform  
✅ Orquestar en Kubernetes  
✅ Monitorear con Prometheus y Grafana  
✅ (Opcional) Llevar la app a AWS  

---

## 🗓️ Mi Plan Semana a Semana

| Semana | Tema                                     |
| ------ | ---------------------------------------- |
| 1      | Linux, Vagrant y Ansible                 |
| 2      | Docker y Docker Compose                  |
| 3      | CI/CD con GitHub Actions                 |
| 4      | Terraform (Provider Local)               |
| 5      | Kubernetes local con Minikube            |
| 6      | Despliegue CI/CD en Kubernetes           |
| 7      | Seguridad en Contenedores                |
| 8      | Troubleshooting y Performance            |
| 9      | (Opcional) Despliegue en AWS             |

---

## 🧩 Arquitectura de la Aplicación

El proyecto se compone de tres servicios principales:

- **Vote**: App Flask para votar (🐱 o 🐶).
- **Worker**: Node.js que procesa votos desde Redis y guarda en PostgreSQL.
- **Result**: Node.js para mostrar resultados en tiempo real.

![](./docs/5.png)

---

## 📸 Screenshots de la app

<div align="center">

| 📦 Aplicación Principal | 📋 Resultados | 📊 🏠 Grafana Home | 🐳 Docker Containers |
|:---:|:---:|:---:|:---:|
| <img src="./docs/2.png" width="200"/> | <img src="./docs/1.png" width="200"/> | <img src="./docs/3.png" width="200"/> | <img src="./docs/4.png" width="200"/> |

</div>

---

## 📂 Estructura inicial del repositorio

```bash
.
├── vote/             # Flask app
├── worker/           # Node.js worker
├── result/           # Resultados en tiempo real
├── views/            # HTML y frontend
├── load-testing/     # Pruebas de carga con k6
├── README.md         # Este archivo
```

---

## 🌟 Créditos

Este reto y la idea original del repositorio provienen de **roxsross**, quien diseñó el programa de 90 Días de DevOps.  
📌 Puedes encontrar su versión original y seguirla aquí 👉 [roxs-devops-project90](https://github.com/roxsross/roxs-devops-project90).

---

## 📄 Licencia

Este proyecto mantiene la licencia MIT del repositorio original. Consulta [LICENSE](LICENSE) para más detalles.

---

## 🙋‍♂️ Sobre mí

Soy **Carlos López Zavarce**, entusiasta del DevOps y en constante aprendizaje.  
📎 Conectemos:

- 🔗 [LinkedIn](https://www.linkedin.com/in/carloslopezzavarce/)
- 💻 [GitHub](https://github.com/KrlosAren)
- 🐦 [X (Twitter)](https://x.com/krlosaren)

---

## 🚀 ¡A por el reto!

Estoy listo para aprender, fallar y crecer.  
¡Vamos con todo! 💪

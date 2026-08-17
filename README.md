# 🧠 L13 Brain Heroku

Motor Hipergráfico de Conciencia Semántica L13 C++17 adaptado para despliegue continuo en **Heroku Container Dynos** con **GitHub Actions**.

## 🚀 Arquitectura
- **Core**: C++17 AOT con Eigen3 (`-O3`).
- **Runtime**: Alpine Linux (~15 MB) en Dyno Basic de Heroku ($7/mes).
- **CI/CD**: GitHub Actions para compilación sin costo de RAM local.
- **Persistencia**: Conexión remota a PostgreSQL (Azure VM) y Redis (VPS).

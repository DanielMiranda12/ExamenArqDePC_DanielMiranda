# Examen Final - Arquitectura de Computadores

**Estudiante:** Daniel Alexander Miranda Vega  
**Código:** 0192086  
**Profesor:** Wilder  
**Institución:** Universidad Francisco de Paula Santander Ocaña (UFPSO)

---

## Descripción del Proyecto
Este repositorio contiene la solución del examen final de Arquitectura de Computadores. Consiste en la automatización del ciclo de vida de una infraestructura en Amazon Web Services (AWS) mediante el uso de **GitHub Actions** (CI/CD) y **AWS CloudFormation** (Infraestructura como Código - IaC).

## Estructura del Repositorio
* `.github/workflows/deploy.yml`: Workflow encargado de validar el template y desplegar la infraestructura en AWS.
* `.github/workflows/destroy.yml`: Workflow encargado de eliminar por completo el Stack de CloudFormation.
* `template/ec2.yaml`: Plantilla de CloudFormation que define la instancia EC2 (Amazon Linux 2023), el Security Group con el puerto 80 abierto y el script UserData con la página web personalizada.

## Tecnologías Utilizadas
* **AWS CloudFormation**
* **GitHub Actions**
* **Git & Git Flow**
* **Apache Web Server (httpd)**
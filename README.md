# CI/CD con Jenkins y Terraform en GCP (Simulado)  
# CI/CD with Jenkins and Terraform on GCP (Simulated)

Este proyecto demuestra c贸mo configurar un pipeline CI/CD utilizando Jenkins como orquestador y Terraform para definir infraestructura en Google Cloud Platform (GCP). Todo est谩 simulado para prop贸sitos de portafolio y presentaci贸n profesional.

This project demonstrates how to set up a CI/CD pipeline using Jenkins as the orchestrator and Terraform to define infrastructure on Google Cloud Platform (GCP). Everything is simulated for portfolio and professional showcase purposes.

---

## 馃敡 Tecnolog铆as utilizadas | Technologies Used

- Jenkins  
- Terraform  
- Bash  
- Python  
- Google Cloud Platform (simulado / simulated)  
- Docker  

---

## 馃幆 Objetivo | Objective

**ES:**  
Implementar un flujo CI/CD que:

1. Define infraestructura b谩sica en GCP con Terraform (simulado)  
2. Instala y configura Jenkins  
3. Ejecuta despliegue autom谩tico de una app Flask usando Jenkins

**EN:**  
Implement a CI/CD flow that:

1. Defines basic infrastructure in GCP with Terraform (simulated)  
2. Installs and configures Jenkins  
3. Automatically deploys a Flask app using Jenkins  

---

## 馃搧 Estructura del proyecto | Project Structure

```
ci-cd-jenkins-terraform/
鈹溾攢鈹€ terraform/              # Infraestructura como c贸digo | Infrastructure as Code
鈹溾攢鈹€ jenkins/                # Jenkinsfile y scripts de automatizaci贸n | Jenkinsfile and automation scripts
鈹溾攢鈹€ app/flask-app/          # Aplicaci贸n de ejemplo con Flask | Flask sample application
鈹溾攢鈹€ diagram.png             # Diagrama arquitect贸nico del flujo CI/CD | Architecture diagram
鈹斺攢鈹€ README.md
```

---

## 馃Ь Detalle de archivos | File Details

### 馃搨 `terraform/`
Contiene archivos simulados para definir una infraestructura b谩sica en GCP usando Terraform.

- `main.tf`:  
  **ES:** Estructura principal del entorno, incluyendo m谩quina virtual Jenkins (simulado).  
  **EN:** Main structure for the environment, including Jenkins virtual machine (simulated).

- `variables.tf`:  
  **ES:** Variables reutilizables para la configuraci贸n.  
  **EN:** Reusable variables for configuration.

- `outputs.tf`:  
  **ES:** Salidas clave como IPs o URLs (simuladas).  
  **EN:** Key outputs like IPs or URLs (simulated).

---

### 馃搨 `jenkins/`

- `Jenkinsfile`:  
  **ES:** Script declarativo que define las etapas del pipeline: Build, Test y Deploy.  
  **EN:** Declarative script that defines pipeline stages: Build, Test, and Deploy.

- `scripts/setup.sh`:  
  **ES:** Script simulado de instalaci贸n/configuraci贸n para Jenkins.  
  **EN:** Simulated setup script for Jenkins installation/configuration.

---

### 馃搨 `app/flask-app/`

Aplicaci贸n Python minimalista para probar el pipeline CI/CD.

- `app.py`:  
  **ES:** Servidor web b谩sico con Flask. Responde en `/`.  
  **EN:** Basic web server using Flask. Responds at `/`.

- `requirements.txt`:  
  **ES:** Dependencias necesarias para instalar la app.  
  **EN:** Required dependencies to run the app.

---

### 馃柤 `diagram.png`

**ES:** Representaci贸n visual del flujo CI/CD: desde el desarrollador hasta el despliegue en GCP, pasando por Jenkins.  
**EN:** Visual representation of the CI/CD flow: from developer to deployment on GCP, via Jenkins.

---

## 馃捈 Sobre m铆 | About Me

**ES:**  
Soy Carlos Rodr铆guez, ingeniero DevOps con m谩s de 10 a帽os de experiencia en la industria automotriz. Me especializo en automatizaci贸n de pipelines CI/CD, infraestructura como c贸digo y consultor铆a t茅cnica para empresas que buscan escalar de forma eficiente y automatizada.

**EN:**  
I'm Carlos Rodr铆guez, a DevOps Engineer with over 10 years of experience in the automotive industry. I specialize in CI/CD pipeline automation, infrastructure as code, and technical consulting for companies aiming to scale efficiently and securely.

> 馃殌 Disponible para colaboraci贸n freelance o consultor铆a | Available for freelance collaboration or consulting

---

## 馃摤 Contacto | Contact

**Email:** [rolocaan@gmail.com]  
**LinkedIn:** [www.linkedin.com/in/carlos-andrés-r-98821455]  
**GitHub:** [rolocaan]

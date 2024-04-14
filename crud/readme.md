# DAW135- Examen Parcial 1 - GT02 ![GitHub Org's stars](https://img.shields.io/github/stars/MinunGR?style=social)
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Escudo_de_la_Universidad_de_El_Salvador.svg/1200px-Escudo_de_la_Universidad_de_El_Salvador.svg.png" alt="LogoUes" width="30%" height="50%">
</p>

# Resolución Examen Parcial #1 DAW

Proyecto realizado tomando como base la práctica realizada en el video de la semana #3, esto incluye un **CRUD** completo con **Maven**, dockerización y gestión del repositorio en **Git**.

## :heavy_check_mark:Tecnología utilizada:
- Java Jdk 17

## :computer:Entorno de Desarrollo utilizado:
- Visual Studio Code

## :heavy_check_mark:Requisitos:
- Docker
- Docker Compose
- CMD, Powershell o cualquier otra terminal

## :speech_balloon:Cómo ejecutar el proyecto:

### Paso 1: Clonar el Repositorio
```bash
git clone https://github.com/MinunGR/Examen-ParcialN1-GT02.git
```

### Paso 2
- Abrir el directorio del proyecto desde la terminal

### Paso 3
- Eliminamos imagenes previamente creadas 
    > docker-compose down --rmi all --volumes

### Paso 4
- Borramos la caché de esas imagenes
    > docker-compose down --remove-orphans

### Paso 5
- Finalmente, corremos nuestro docker-compose.yml usando el siguiente cmd
    > docker-compose up -d

## :busts_in_silhouette:Autores del proyecto:
- Fernando José Barraza Álvarez  
  **BA22025**
- Carlos Guillermo Ortiz Abarca  
  **OA21013**
- David Salomón Martínez Valladares  
  **MV12013**

  
| [<img src="https://avatars.githubusercontent.com/u/61745150?v=4" width=115><br><sub>Fernando José Barraza Álvarez</sub>](https://github.com/MinunGR) | [<img src="https://avatars.githubusercontent.com/u/57274941?v=4" width=115><br><sub>David Salomón Martínez Valladares</sub>](https://github.com/DavidSalomonDev) | [<img src="https://avatars.githubusercontent.com/u/145523801?v=4" width=115><br><sub>Carlos Guillermo Ortiz Abarca</sub>](https://github.com/Carlos-Otz) 
| :---: | :---: | :---: 

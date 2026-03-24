Mini Laboratorio — Análisis y Corrección de Vulnerabilidades SQL Injection
Curso: ISW-1013 Calidad del Software
Universidad: Universidad Técnica Nacional
Cuatrimestre: I Cuatrimestre 2026

Descripción
Este repositorio contiene el trabajo del mini laboratorio enfocado en el análisis, explotación y corrección de vulnerabilidades de seguridad tipo SQL Injection en una aplicación web desarrollada con Python + Flask + SQLite, desplegada mediante Docker.
El laboratorio sigue tres etapas:

Explorar — Montar la aplicación y entender su funcionamiento.
Atacar — Explotar las vulnerabilidades para comprender su impacto.
Corregir — Aplicar buenas prácticas de seguridad en el código.


Tecnologías utilizadas

Python + Flask — Backend de la aplicación web
SQLite — Base de datos
Docker / Docker Compose — Contenerización y despliegue local
Git / GitHub — Control de versiones


Requisitos previos

Git
Docker Desktop
Navegador web actualizado (Chrome o Firefox)
Editor de código (Visual Studio Code recomendado)


Instalación y ejecución
1. Clonar el repositorio
bashgit clone <URL_DEL_REPOSITORIO>
cd sqli_lab_vulnerable_app
1. Levantar la aplicación
bashdocker compose up --build
Una vez iniciada, accedé desde el navegador en:
http://localhost:5000
1. Detener la aplicación
bashdocker compose down

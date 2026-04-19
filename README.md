[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/0V8i2zWk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23629361&assignment_repo_type=AssignmentRepo)
# Lab04: Visualización de Datos en Raspberry Pi con Node-RED 

## Integrantes
Laura Leon\
Camilo Chavista\
Brayan Dueñas

## Documentación

## Visualización de datos en Raspberry Pi con Node-RED

##  Introducción

Node-RED es una herramienta de programación basada en flujos que permite desarrollar aplicaciones mediante la conexión visual de nodos. En este proyecto se implementa un flujo que permite seleccionar un color desde una interfaz gráfica, procesarlo y almacenarlo en un archivo, permitiendo además su visualización en tiempo real.

---

##  Objetivos

### Objetivo General
Desarrollar un flujo en Node-RED que permita la captura, procesamiento y almacenamiento de datos provenientes de un selector de color.

### Objetivos Específicos
- Implementar una interfaz gráfica mediante Dashboard.
- Procesar datos utilizando nodos de función.
- Visualizar datos en tiempo real.
- Almacenar la información en un archivo local.

---

##  Herramientas Utilizadas

- Node-RED  
- node-red-dashboard  
- Navegador web  

---

##  Arquitectura del Flujo

A continuación se muestra el flujo implementado:

![Flujo Node-RED](img/flujo.png)

El flujo sigue una estructura lineal con ramificaciones para visualización y almacenamiento de datos.

---

##  Implementación

### 1. Instalación del Entorno

Se accedió a Node-RED desde: http://10.79.144.165:1880

Posteriormente, se instaló el paquete **node-red-dashboard** desde la opción *Manage Palette*.

---

### 2. Creación del Flujo

Se creó una nueva pestaña (flow) y se añadieron los siguientes nodos:

- Color Picker  
- Function  
- Text Input  
- Write File  
- Debug  

---

### 3. Configuración de Nodos

####  Color Picker
Permite seleccionar un color desde la interfaz gráfica, generando un valor en formato HEX.


## Conclusiones

-Node-RED facilita el desarrollo de aplicaciones mediante programación visual.
-El uso del Dashboard permite crear interfaces interactivas de forma sencilla.
-La modularidad de los nodos permite ampliar fácilmente el sistema.
-Este tipo de implementación es útil en aplicaciones IoT y automatización.

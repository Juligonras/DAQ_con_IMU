# Práctica 2: DAQ con IMU de dispositivos móviles para reconstrucción y clasificación de movimiento

Este repositorio contiene el código y el informe relacionados con la práctica de **Sensores y Actuadores**, donde se utilizó una **Unidad de Medición Inercial (IMU)** de un dispositivo móvil para reconstruir y clasificar el movimiento de un kart.

## 📋 Descripción del proyecto

El objetivo de esta práctica es adquirir datos cinemáticos mediante un teléfono móvil utilizando la plataforma **Edge Impulse**, analizar la información obtenida y reconstruir la trayectoria del movimiento del kart. Se aplican técnicas de filtrado y procesamiento de datos para mejorar la precisión de las mediciones.

## 📂 Contenido del repositorio

- `Sensores_Karts.mlx` – Código en **MATLAB Live Script** para procesamiento de datos.
- `Datos_Karts.json` – Archivo con los datos de aceleración y velocidad angular capturados.
- `Practica_Karts-1.pdf` – Informe detallado de la práctica con procedimientos y resultados.

## 🛠️ Herramientas utilizadas

- **Plataforma de adquisición:** Edge Impulse
- **Lenguaje de programación:** MATLAB
- **Filtros aplicados:** Butterworth pasa-bajo
- **Formato de datos:** JSON
- **Gráficas y análisis:** Aceleraciones, velocidades angulares y trayectorias reconstruidas

## 🚀 Instalación y uso

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tu-usuario/DAQ-IMU-Kart.git
   cd DAQ-IMU-Kart

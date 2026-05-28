# 🎵 Simulador de Microtonos en Python

¡Bienvenido al **Simulador de Microtonos**! Este es un script interactivo basado en consola desarrollado en Python que simula la gestión y reproducción de frecuencias acústicas (microtonos) utilizando los recursos nativos del sistema operativo. 

El programa permite experimentar con la activación de secuencias sonoras dinámicas controlando un "banco" limitado de microtonos disponibles.

---

## 🚀 Características

* **Gestión de Recursos:** Control de un límite máximo de 25 microtonos simultáneos.
* **Reproducción Dinámica:** Genera secuencias de audio reales mediante la librería nativa `winsound`.
* **Patrones de Frecuencia:** Cuenta con una lista predefinida de frecuencias y duraciones para crear texturas sonoras variables según la cantidad de microtonos que actives.
* **Interfaz Interactiva:** Panel de control en consola intuitivo y con validación de errores ante entradas incorrectas.

---

## 🛠️ Requisitos del Sistema

* **Python 3.x** instalado.
* **Sistema Operativo:** Windows (requerido para la librería estándar `winsound`).

---

## 💻 Panel de Opciones

Al ejecutar el programa, tendrás acceso a las siguientes funciones:

| Opción | Acción | Descripción |
| :--- | :--- | :--- |
| **1** | Ver microtonos libres | Muestra cuántos microtonos quedan disponibles en el banco. |
| **2** | Activar microtonos | Elige cuántos activar para reproducir la secuencia de sonido. |
| **3** | Recuperar microtonos | Libera microtonos activos para poder usarlos nuevamente. |
| **4** | Monitorear sonido | Estado actual del ambiente sonoro (microtonos vibrando). |
| **5** | Salir | Cierra el simulador de forma segura. |

---

## 📦 Instalación y Uso

1. **Clona este repositorio** en tu máquina local:
   ```bash
   git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)

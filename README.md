# Planograma - Generador de Diagramas de Gantt

Este proyecto utiliza **Python 3** y **Matplotlib** para generar diagramas de Gantt
mediante una interfaz gráfica construida con **Tkinter**.

## Estructura

- **diagrama/**: Contiene el módulo `generador.py` para crear el diagrama de Gantt.  
- **gantt_proyecto/**: Contiene el archivo principal `main.py`, punto de entrada de la aplicación.  
- **gui/**: Contiene la interfaz Tkinter en `planograma_ui.py`.  
- **modelo/**: Contiene la clase `Actividad` en `actividad.py`.  
- **pruebas/**: Contiene pruebas unitarias en `test_generador.py`.  

## Requisitos

- Python 3.7 o superior  
- Matplotlib  
- (Opcional) Para pruebas unitarias: `unittest` (viene con la instalación estándar de Python)

Instala las dependencias:

```bash
pip install matplotlib

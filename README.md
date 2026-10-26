# Proyecto-ABP-U1-G7-RescueSwarm-
Sistema autónomo de enjambre de drones para evaluación de zonas de desastre - Modelos Discretos ESPE
Avance 1 (40 %): lógica proposicional y de predicados

Proyecto integrador de la asignatura **Modelos Discretos para la Ingeniería** (NRC 32798)
Universidad de las Fuerzas Armadas ESPE · Sede Santo Domingo · Período S-II 2026
Docente: Mgtr. Javier José Cevallos Farías

---

## 📌 Descripción

Después de un desastre natural, las comunicaciones terrestres suelen caer y la evaluación de las zonas afectadas se retrasa. RescueSwarm-AI propone un enjambre de drones que decide, mediante **reglas lógicas verificables**, si puede despegar y explica cada decisión al operador.

En este primer avance se implementa un **validador interactivo** con:

- **10 reglas proposicionales** (batería, viento, visibilidad, temperatura del motor, carga, conexión y sensores).
- **3 reglas de lógica de predicados** (cuantificadores ∀ y ∃) sobre un enjambre simulado de tres drones.
- Una interfaz web creada con **Gradio**, ejecutable en Google Colab.

## 🧠 Contenidos de la asignatura aplicados

| Unidad | Aplicación en el proyecto | Estado |
|---|---|---|
| 1. Lógica proposicional y de predicados | Reglas de seguridad de vuelo, tabla de verdad, equivalencias, inferencia y cuantificadores | Avance 1 |
| 2. Conteo, probabilidad y complejidad | Combinatoria de patrones de escaneo y complejidad algorítmica | Avance 2 (pendiente) |
| 3. Grafos, árboles y autómatas | Grafo del terreno, árbol de decisión y autómata del dron | Avance 3 (pendiente) |

## ⚙️ Requisitos

- Cuenta de Google (para usar Google Colab) **o** Python 3.9 o superior.
- Librería [Gradio](https://www.gradio.app/): `pip install gradio`

## ▶️ Cómo ejecutar

### En Google Colab (recomendado)

1. Abre [Google Colab](https://colab.research.google.com/) y crea un cuaderno nuevo.
2. Copia el contenido del archivo del avance 1 en una celda (o sube el archivo).
3. Ejecuta la celda. La primera línea instala Gradio.
4. Abre el enlace que aparece al final (`Running on public URL`) o usa la interfaz que se muestra en el cuaderno.

### En local

```bash
pip install gradio
python rescueswarm_avance1.py

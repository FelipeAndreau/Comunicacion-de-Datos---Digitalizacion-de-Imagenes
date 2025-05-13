
# TP Integrador - Comunicación de datos - 2025

## Trabajo Práctico Integrador
**Ingeniería aplicada a la comunicación de datos**

### Objetivo
Desarrollar una aplicación web, de escritorio o móvil que aborde problemáticas relacionadas con la transmisión de datos, digitalización de señales y medios. El software debe representar, simular o resolver aspectos teóricos y/o prácticos de la asignatura.

---

## Etapa 1 - Diseño y planificación (30%)
**Entrega: 16/5 (S32) - 16/5 (S31/S33)**

- Elegir una propuesta de las siguientes.
- Definir la arquitectura de la aplicación.
- Seleccionar herramientas y tecnologías a utilizar.
- Crear mockups o bocetos de la interfaz.

**Producto de entrega:**
- Documento con propuesta elegida, arquitectura, descripción de tecnologías y boceto.
- Formato editable (.docx).
- Mockup como link (Figma, Zeplin, etc.).
- Máximo dos carillas.

**Criterios de aceptación:**
- Fecha de entrega respetada.
- Documento editable (.docx).
- Mockup como link.
- Documento máximo dos carillas.

---

## Etapa 2 - Desarrollo (40%)
**Entrega: 16/6 (S32) - 20/6 (S31/S33)**

- Desarrollo del software con funcionalidades básicas.
- Prototipo funcional.

**Productos de entrega:**
- Código fuente (GitHub o comprimido).
- Video demostrativo (máx. 6 minutos).
- Ejecutable o APK para testing.

**Criterios de aceptación:**
- Fecha de entrega respetada.
- Código fuente accesible.
- Video demostrativo claro (máx. 6 minutos).
- Instrumento ejecutable para pruebas.

---

## Etapa 3 - Defensa del Proyecto (30%)
**Entrega: 30/6 (S32) - 4/7 (S31/S33)**

- Demo en modalidad coloquio.
- Justificación teórica de decisiones.
- Presentación en PowerPoint.

**Productos de entrega:**
- Presentación PowerPoint (máx. 8 slides).
- Ejecutable para la cátedra.

**Criterios de aceptación:**
- Slide con descripción del grupo.
- Explicación del funcionamiento de la aplicación.
- Justificación teórica de la funcionalidad.
- Demo máximo de 15 minutos.
- Aplicación ejecutable final.

---

# Propuestas de Desarrollo

## 1. Simulador de Conversión de Señales (ADC - Digitalización de Señales)

### Funcionalidades
- Generar señales analógicas (sinusoides, cuadradas, ruido).
- Simular muestreo (8 kHz, 44.1 kHz).
- Cuantizar señales (8, 16, 24 bits).
- Visualizar original vs. digitalizada.
- Aplicar Teorema de Nyquist y aliasing.

### Tecnologías sugeridas
- Python (Matplotlib, NumPy).
- WebApp (React, D3.js).

---

## 2. Conversor de Audio Analógico a Digital

### Funcionalidades
- Grabación en tiempo real.
- Conversión de tasas de muestreo (8 kHz a 96 kHz).
- Cuantización de bits (8, 16, 24 bits).
- Comparar espectros antes/después.
- Exportar en WAV o MP3.

### Tecnologías sugeridas
- Python (pydub, librosa).
- WebApp (WebRTC, Web Audio API).

---

## 3. Digitalización de Imágenes

### Funcionalidades
- Cargar imágenes en alta resolución.
- Aplicar muestreo (100x100, 500x500, 1000x1000).
- Reducir profundidad de bits (1, 8, 24 bits).
- Comparar original vs. digitalizada.
- Aplicar compresión de tamaño.

### Tecnologías sugeridas
- Python (OpenCV, PIL).
- WebApp (React, Canvas API).

---

## 4. Transmisión Digital de Señales y Compresión

### Funcionalidades
- Convertir señales analógicas a paquetes digitales.
- Aplicar compresión (PCM, ADPCM, MP3).
- Simular errores de transmisión.
- Visualizar señal reconstruida.

### Tecnologías sugeridas
- Python (sockets, scipy.signal).
- WebApp (WebSockets, Web Audio API).

---

## 5. Codificación de Datos

### Funcionalidades
- Cargar texto (directo o .txt).
- Calcular frecuencia de símbolos.
- Construir árbol y tabla (Huffman, Shannon-Fano).
- Codificar y decodificar mensaje.
- Comparar tasa de compresión, eficiencia.
- Visualizar tabla de símbolos y códigos.
- Graficar frecuencias y códigos.
- Comprimir imágenes en blanco y negro.

### Tecnologías sugeridas
- Python (Tkinter, PySimpleGUI, matplotlib).
- JavaScript (HTML/CSS, Chart.js, D3.js).
- Estructuras recomendadas: árboles binarios, colas de prioridad (heapq).

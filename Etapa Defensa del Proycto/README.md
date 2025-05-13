
# 🖼️ Digitalización de Imágenes - TP Integrador UTN 2025

Aplicación interactiva desarrollada para el Trabajo Práctico Integrador de la materia Comunicación de Datos (UTN Facultad Regional La Plata - Ingeniería en Sistemas).

Permite simular la digitalización de imágenes mediante técnicas de muestreo, cuantización y compresión.

---

## 🎯 Funcionalidades

- ✅ Carga de imágenes locales en alta resolución.
- ✅ Reducción de resolución (muestreo): 100x100, 500x500, 1000x1000.
- ✅ Reducción de profundidad de bits (cuantización): 1 bit, 8 bits.
- ✅ Visualización comparativa entre imagen original y digitalizada.
- ✅ Exportación comprimida a JPG (70% calidad).

Cumple todos los requisitos de las etapas 1, 2 y 3 del proyecto.

---

## 💻 Tecnologías utilizadas

- React JS (Frontend)
- Canvas API (Procesamiento de imágenes)
- HTML5 + CSS3

---

## 📂 Estructura del proyecto

```
src/
├── components/
│   ├── Header.js
│   ├── ImageUploader.js
│   ├── ProcessControls.js
│   ├── ResultViewer.js
│   └── DownloadCompressed.js
├── App.js
├── App.css
└── index.js
```

---

## 🚀 Instalación y ejecución

Requisitos: Node.js versión >=18.

```bash
git clone https://github.com/FelipeAndreau/digitalizacion-imagenes.git
cd digitalizacion-imagenes
npm install
npm start
```

Accedé a la aplicación en `http://localhost:3000`.

---

## 📝 Uso

1. Seleccioná una imagen desde tu PC.
2. Aplicá un tipo de muestreo y cuantización.
3. Visualizá la imagen digitalizada.
4. Podés descargar la imagen comprimida usando el botón correspondiente.

---

## 🎨 Captura de ejemplo

(opcional) Agregar imagen en `docs/demo.png`

```
![Captura de ejemplo](docs/demo.png)
```

---

## 👨‍💻 Autores

- Alumno: Feipe Andreau
- Carrera: Ingeniería en Sistemas UTN - Facultad Regional La Plata
- Año: 2025

---

## 📋 Licencia

Este proyecto fue desarrollado exclusivamente para fines académicos.

# PICTURE VIEWER - Visor de imágenes JPG georreferenciadas

![PICTURE VIEWER](https://github.com/germancruzram/PICTURE_VIEWER/raw/main/PICTURE_VIEWER.png)

## 📋 Descripción

**PICTURE VIEWER** es una aplicación de escritorio desarrollada en Python que permite visualizar imágenes JPG georreferenciadas incrustados en sus metadatos EXIF. La aplicación extrae las coordenadas geográficas y muestra las imágenes en un mapa interactivo.

**[⬇️ Descargar última versión](https://github.com/germancruzram/PICTURE_VIEWER/releases/download/PICTURE_VIEWER/PICTURE.VIEWER.v1.0.zip)**

## ✨ Características principales

- 📊 **Procesamiento de metadatos EXIF**: Extracción automática de coordenadas GPS y fecha de captura
- 🖼️ **Generación de miniaturas optimizadas**: Versiones redimensionadas para visualización eficiente
- 🗺️ **Visualización en mapa interactivo**: Integración con Folium para mostrar imágenes geolocalizadas
- 🌐 **Múltiples capas de mapa**: Soporte para vista estándar y satelital
- 📝 **Visualización de metadatos**: Muestra nombre de archivo, coordenadas y fecha de captura
- 🖱️ **Interfaz gráfica intuitiva**: Creada en python

## 📖 Instrucciones de uso

1. Inicie la aplicación PICTURE VIEWER
2. Haga clic en "Seleccionar carpeta de imágenes" y elija una carpeta que contenga imágenes JPG con datos GPS
3. Presione "Procesar imágenes" para extraer los metadatos y crear las miniaturas
4. Haga clic en "Ver mapa" para visualizar las imágenes en un mapa interactivo

### En el mapa interactivo, puede:
- ✅ Hacer clic en los marcadores para ver las imágenes y sus metadatos
- ✅ Cambiar entre vista de mapa y vista satelital
- ✅ Hacer zoom y desplazarse por el mapa
- ✅ Guardar la vista actual como imagen

## 🔧 Detalles técnicos

- 🧭 **Conversión de coordenadas**: Transforma coordenadas DMS (grados, minutos, segundos) a grados decimales
- 🖼️ **Procesamiento de imágenes**: Crea miniaturas optimizadas (450x450 píxeles) para mejorar el rendimiento
- 💾 **Almacenamiento**: Las miniaturas se guardan en una subcarpeta "reescalado" dentro del directorio de imágenes
- 🌐 **Visualización web**: Genera un archivo HTML con el mapa y lo muestra en un componente QWebEngineView
- 🔐 **Codificación Base64**: Las imágenes se codifican en Base64 para incrustarlas directamente en el mapa HTML

## ⚠️ Limitaciones actuales

- Solo procesa imágenes en formato JPG/JPEG
- Requiere que las imágenes contengan metadatos GPS
- La aplicación está actualmente en fase BETA-1

## 👨‍💻 Autor

<div align="center">
  <h3>Germán Ahmed Cruz Ramírez</h3>
  
  <p>
    <a href="https://www.linkedin.com/in/german-cruz-ram-in24/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <a href="https://github.com/germancruzram">
      <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
    </a>
  </p>
</div>

---

<div align="center">
  <p>© 2025 Germán Ahmed Cruz Ramírez. Todos los derechos reservados.</p>
  <p>
    <a href="https://github.com/germancruzram/PICTURE_VIEWER/issues">Reportar Problemas</a> •
  </p>
</div>



# PICTURE VIEWER
## Visor de imágenes JPG georreferenciadas

![PICTURE VIEWER](https://github.com/germancruzram/PICTURE_VIEWER/blob/main/PICTURE_VIEWER.png?raw=true)

PICTURE VIEWER es una aplicación de escritorio desarrollada en Python que permite visualizar imágenes JPG con datos de georreferenciación (GPS) incrustados en sus metadatos EXIF. La aplicación extrae las coordenadas geográficas y muestra las imágenes en un mapa interactivo, creando una experiencia similar a la visualización de archivos KMZ.

## ✨ Características principales

- **📊 Procesamiento de metadatos EXIF**: Extracción automática de coordenadas GPS y fecha de captura
- **🖼️ Generación de miniaturas optimizadas**: Versiones redimensionadas para visualización eficiente
- **🗺️ Visualización en mapa interactivo**: Integración con Folium para mostrar imágenes geolocalizadas
- **🌐 Múltiples capas de mapa**: Soporte para vista estándar y satelital
- **📝 Visualización de metadatos**: Muestra nombre de archivo, coordenadas y fecha de captura
- **🖱️ Interfaz gráfica intuitiva**: Desarrollada con PyQt5 para una experiencia de usuario amigable

<a id="uso"></a>

📖 Uso
<div align="center"> <table> <tr> <td align="center"><b>Paso 1</b></td> <td align="center"><b>Paso 2</b></td> </tr> <tr> <td>Inicie la aplicación PICTURE VIEWER</td> <td>Haga clic en "Seleccionar carpeta de imágenes" y elija una carpeta que contenga imágenes JPG con datos GPS</td> </tr> <tr> <td align="center"><b>Paso 3</b></td> <td align="center"><b>Paso 4</b></td> </tr> <tr> <td>Presione "Procesar imágenes" para extraer los metadatos y crear las miniaturas</td> <td>Haga clic en "Ver mapa" para visualizar las imágenes en un mapa interactivo</td> </tr> </table> </div>

En el mapa interactivo, puede:
✅ Hacer clic en los marcadores para ver las imágenes y sus metadatos
✅ Cambiar entre vista de mapa y vista satelital
✅ Hacer zoom y desplazarse por el mapa
✅ Guardar la vista actual como imagen


🔧 Detalles técnicos
🧭 Conversión de coordenadas: Transforma coordenadas DMS (grados, minutos, segundos) a grados decimales
🖼️ Procesamiento de imágenes: Crea miniaturas optimizadas (450x450 píxeles) para mejorar el rendimiento
💾 Almacenamiento: Las miniaturas se guardan en una subcarpeta "reescalado" dentro del directorio de imágenes
🌐 Visualización web: Genera un archivo HTML con el mapa y lo muestra en un componente QWebEngineView
🔐 Codificación Base64: Las imágenes se codifican en Base64 para incrustarlas directamente en el mapa HTML


⚠️ Limitaciones actuales
Solo procesa imágenes en formato JPG/JPEG
Requiere que las imágenes contengan metadatos GPS en formato EXIF
La aplicación está actualmente en fase BETA-1

<a id="autor"></a>
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
    <a href="LICENSE.md">Licencia MIT</a> •
    <a href="https://github.com/germancruzram/PICTURE_VIEWER/issues">Reportar Problemas</a> •
    <a href="https://github.com/germancruzram/PICTURE_VIEWER/blob/main/CONTRIBUTING.md">Contribuir</a>
  </p>
</div>



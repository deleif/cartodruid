# Herramientas de apoyo en los trabajos de campo. Uso de CartoDruid

## 📚 Descripción
CartoDruid es una aplicación creada por el Instituto Tecnológico Agrario de Castilla y León (ITACyL) diseñada para facilitar el trabajo de campo.  La aplicación está diseñada como una herramienta de apoyo para el trabajo de campo, facilitando el uso de información geográfica en entornos sin conexión. Su objetivo es permitir tanto la consulta como la edición de datos geoespaciales fuera de la oficina.

Para ello, CartoDruid ofrece la visualización y modificación de capas vectoriales y raster almacenadas en el propio dispositivo. Actualmente, es compatible con el formato Sqlite y se está desarrollando la integración de archivos Shapefile (.shp) de ESRI, tanto en modo lectura como escritura.

## 🔍 Objetivos del Curso
- Conocer las funcionalidades básicas de CartoDruid.
- Aprender a importar y exportar datos geográficos.
- Crear capas de SIGPAC para Aragón.
- Editar y capturar de datos en campo.
- Integrar CartoDruid con bases de datos geoespaciales.
- Optimizar flujos de trabajo para proyectos SIG en móvil.

## 📚 Contenido del repositorio
- **config**: ficheros xml de configuración de los proyectos SIGPAC para cada provincia de Aragón.
- **data**: enlaces de descarga de bases de datos SQLite.
- **documentacion**: manual del seminario y presentaciones de los temas.
- **sql**: script que crea la estructura de la base de datos SIGPAC por provincia compatible con CartoDruid.


## 📚 Contenido del Curso
**Módulo 1: Introducción a CartoDruid y SIG Móviles**
   - ¿Qué es CartoDruid?
   - Diferencias entre CartoDruid y otros SIG móviles.
   - Instalación de CartoDruid en Android.
   - Conceptos clave: mapas offline y capas.
   - Formatos soportados. 
   - Configuración inicial.
   - Primeros pasos en la interfaz.
  
   
**Módulo 2: Creación y Gestión de Proyectos SIG en CartoDruid**
   - Estructura de un proyecto en CartoDruid.
   - Creación y configuración de capas.
   
**Módulo 3: Obtener la capa de recintos SIGPAC de Aragón para CartoDruid**
   - Localizar la capa SIGPAC de cada provincia.
   - Exportar la Capa SIGPAC a una Base de datos Spatialite.
   - Crear la capa SIGPAC definitiva y copiar datos desde la capa descargada.
   - Construir capas auxiliares, comprimir y crear índices espaciales.
   - Cargar la capa de SIGPAC en CartoDruid.
   
**Módulo 4: Recogida y edición de datos en campo**
   - Importación de datos de inspección y de capas trabajadas en QGIS 
   - Uso del GPS y de marcadores para localizar parcelas en campo. 
   - Mediciones y registros en campo con CartoDruid.  
     - Medición de líneas y superficies sobre Ortofoto. 
     - Medición y registro mediante edición de capa. 
   - Edición y actualización de datos sobre el terreno.. 
   - Gestión de fotografías georeferenciadas en Cartodruid. 
   - Exportación de datos tomados en CartoDruid (SpatiaLite, CSV, KML, Fotografías y GeoJSON) y visualización en QGIS. 

**Módulo 5: Manejo de medidor láser (BOSCH GLM 150-27C)**
   - Ajustes y puesta en marcha.
   - Medición directa e indirecta. Otras.
   - Transmisión de datos.


**Módulo 6: Generar MBTiles con QGIS**
   - Configurar proyecto. 
   - Proceso “Genera teselas XYZ (MBTiles)”.


## 🛠️ Requisitos
- Dispositivo Android compatible.
- Conocimientos básicos de QGIS (recomendado, pero no obligatorio).

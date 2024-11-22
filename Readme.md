Taller de visualización de datos
---

### Presentación

Buenos días/tardes/noches, espero que lea detenidamente este documento, el cual escribí con esmero para brindar una experiencia agradable en el trabajo previo al taller.

En el siguiente proyecto se encuentra una versión reducida del esquema de trabajo **Cookie Cutter**. La carpeta principal incluye este **Readme.md** (en formato markdown), que sirve como introducción y catálogo de todas las herramientas que el proyecto posee. Contiene también una licencia de uso (en este proyecto es Creative Commons), un archivo **requirements.txt** con los nombres (y, opcionalmente, las versiones) de las librerías necesarias para ejecutar los códigos, y el archivo **.gitignore**, que permite evitar que Git registre cambios innecesarios o archivos pesados.

Sobre las carpetas: es una buena práctica mantener todo organizado. Este es el esquema básico que se busca establecer:  

- **Datos:** Todo lo relacionado con los datos (crudos, procesados o finales) debe encontrarse en esta carpeta. Aunque aquí no se incluye por simplicidad, sería apropiado manejar subcarpetas para clasificar estas etapas.  
- **Códigos:** En esta carpeta se almacenan todos los archivos de código del proyecto. Las buenas prácticas indican que cada archivo debe enfocarse en un único objetivo. Por ejemplo, el archivo **ETL.ipynb** (siglas de *Extract-Transform-Load*) se utiliza exclusivamente para la creación de la base de datos, mientras que el archivo **Trabajo.ipynb** será su espacio de trabajo durante el taller.  
- **Reportes:** Cualquier resultado (numérico o visual) o registro de funcionamiento (*logs*) derivado de su trabajo debe ser guardado en esta carpeta.  

---

### Objetivo

El objetivo del taller es que usted sea capaz de tomar una base de datos limpia y crear tres figuras que, en conjunto, permitan mostrar algún análisis extraído de la información contenida en dicha base.  

Para esto, se le pedirá un documento en formato PDF a modo de póster pequeño, que incluya un título principal, las tres figuras y un espacio de texto que **complemente** las figuras. Es importante destacar que **el texto no debe reemplazar las imágenes**, sino únicamente hacerlas más legibles.

---

### Pre-requisitos

#### Materiales

- Un notebook, tableta o computadora portátil que permita programar en Python.

#### Conocimientos

- Manejo básico de Python (Computación Científica I), de manera que pueda seguir las instrucciones contenidas en la carpeta **Datos**.  
Cualquier persona que pueda completar el listado de cuatro pasos incluido está en plenas capacidades para asistir al taller.  

Si carece de al menos una de estas condiciones, pero desea participar, póngase en contacto a la brevedad con el encargado, Diego Farías Salazar (información de contacto más adelante).

---

### Recomendaciones (No obligatorias, DIY)

En orden de lo más sencillo a lo más elaborado:  

1. Instalar Anaconda, ya que incluye todas las librerías que se usarán en el proyecto.  
2. Usar intérpretes como Visual Studio Code para manejar todo el proyecto.  
3. Crear un entorno virtual para el proyecto.  

---

### Contactos

- **Encargado:** Diego Farías Salazar  
  - Teams o correo: dfarias2017@udec.cl  
  - WhatsApp (si ya tiene mi número, de lo contrario utilice medios oficiales).  

- **Monitor:** Juan Ortega Flores  
  - Teams o correo: juortega2019@udec.cl  

- **Monitor:** Sebastián Pulgares Codelia  
  - Teams o correo: spulgares2017@udec.cl  

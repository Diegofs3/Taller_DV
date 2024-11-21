# Contexto
El trabajo de limpieza de base datos es algo que, lamentablemente, no alcanzaremos a incluir en el taller.
De esta forma, la mayoria de el trabajo de extracción, limpieza y tratamiento de los datos crudos serán entragados en forma de jupyter notebook y está escrito para que únicamente deban ejecutar todo el codigo.
Si alguien quiere conocer más información sientase libre de contactarme por teams o por correo

## 1) Descarga de los datos

Ingrese a la url https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/ 
Desde aqui descargue los archivos *"Titulados-Ed-Superior-202X.rar"*, por defecto (y a mi criterio) se espera que descargue los años 2022 y 2023. Si desea extender los años considerados, corre netamente a su criterio y capacidades.
**Importante** Los archivos descargados los debe almacenar en la carpeta *Datos* donde está guardado este mismo archivo.

## 2) Descomprimir los .rar

No se complique la vida, solo seleccione la opcion de "*Descomprimir/Extraer aquí*" de modo que ambos .rar creen una carpeta con su respectivo nombre

## 3) Ejecute el jupyter notebook ETL.ipynb

Recuerde que el archivo es uno de los 2 que se encuentra en la carpeta *"Códigos"* del proyecto. Abrá el archivo, considere las siguientes condiciones:

- Si solo descargo el proyecto y no tiene ninguna libreria instalada, corrá todas las celdas.
- Si usted usa Anaconda o creo un entorno virtual usando el requeriments.txt, comente o elimine la primera celda y corrá todas las demas.

## 4) Verificación

Entre al codigo *"Trabajo.ipynb"* y cargue la base de datos ejecutando las primeras celdas. Tome un pantallazo y contacte con Diego Farías, cuándo le de el visto bueno, puede considerarlo una aceptación formal al taller.
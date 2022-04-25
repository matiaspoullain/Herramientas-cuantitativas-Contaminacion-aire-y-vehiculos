# <p align="center">Curso de posgrado: Herramientas cuantitativas para el abordaje de problemáticas socio-ambientales</p>
### <p align="center">Instituto del Cálculo - Universidad de Buenos Aires - Mayo 2022</p>
## <p align="center">Caso de estudio 1: Contaminación del aire y circulación vehicular</p>
#### <p align="center">Lic. Matias Poullain, Lic. Juan Martín Guerrieri</p>
---
Este caso de estudio, se divide en dos partes: una teórica y una práctica.

En la parte teórica se introducirá la problemática sanitaria y ambiental de los contaminantes en el aire y como es medida su concentración en la atmósfera. También se realizará una introducción a los conceptos de clima y meteorología y su monitoreo en Argentina por el Servicio Meteorológico Nacional (SMN). Por último, se abordan los desafíos de estudiar y análizar series temporales multivariadas haciendo énfasis en una metodología novedosa, un modelo llamado Prophet.

En la parte práctica se realizará una aplicación de lo visto en la parte teórica a un caso particular. Se analizará la relación entre la concentración de un contaminante atmosférico, el NO<sub>2</sub> troposférico, con la circulación vehícular y con variables meteorológicas en la Ciudad Autónoma de Buenos Aires durante los últimos años, incluyendo al período de cuarentena obligatoria impuesto con el fin de amortiguar el contagio del virus SARS-CoV-2.

En este repositorio se encuentran todos los archivos que serán utilizados en este caso de estudio. Los archivos relacionados a la parte teórica se encuentran en la carpeta **Teórica** mientras que los de la parte práctica se encuentran en las otras carpetas del repositorio:
* La carpeta **Notebooks** contiene las notebooks que componen los ejercicios de la práctica.
* La carpeta **Datos** contiene los datos previamente descargados y preprocesados que serán utilizados en las notebooks.
* La carpeta **Mapas** contiene mapas base que se utilizarán en las notebooks.
* La carpeta **Modelos** contiene un modelo previamente entrenado que será utilizado en una de las notebooks.

Este formato de organización de los archivos fue pensado para que los alumnos puedan seguir y completar las consignas de la práctica sin necesidad de descargar ninguna de las bases de datos ni modelos ni realizar todo el procesamiento en sus computadoras. Desde las notebooks se puede acceder directamente a Google Colab y correr todo desde la nube. Sin embargo, también se tiene la posibilidad de clonar el repositorio en local y realizar la práctica en ese entorno, para los alumnos más experimentados en la programación que así lo deseen.

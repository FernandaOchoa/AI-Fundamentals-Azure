# Compilación de un bot con QnA Maker y Azure Bot Service

La IA de conversación es una carga de trabajo de inteligencia artificial que se ocupa del diálogo entre los agentes de la IA y los usuarios humanos.

## Configuración del entorno de trabajo

Para este módulo haremos uso de los Jupyter Notebooks.

<div align="justify">Los cuadernos de Jupyter son ambientes de computación interactiva que le permite al usuario hacer el reporte de alguna computación incluyendo código, gráficos, ecuaciones, imágenes, videos, entre otros. En cristiano, esto quiere decir que podemos explicar con detalle cada paso en el trabajo que estemos realizando y hacerlo ameno de leer para otras personas.</div>

* Creamos un recurso de Machine Learning 
    * ![](https://docs.microsoft.com/es-es/azure/includes/media/aml-create-in-portal/create-workspace.gif)
* Escribimos la información para configurar nuestro entorno de trabajo
    * **Workspace name:** *Nombre*
    * **Subscription:** *Seleccionamos nuestra suscripción*
    * **Resource Group:** *El nombre de nuestro grupo de recursos(folder)*
    * **Location:** *Region*
* Una vez configurado, seleccionamos **Revisar y Crear**
* Para ver el recurso, seleccione **Ir al Recurso**
* Del portal del espacio de trabajo, seleccione **Launch Studio** para ir al Azure Machine Learning Studio.
    * ![](../images/ml0.gif)

* Configuramos los clusters de cómputo
    * Navegamos a Azure ML **Compute** 
    * ![](../images/ml1.png)
    * Clic en **New Compute**
    * ![](../images/ml2.png)
    * Seleccionamos el tamaño de la VM y damos clic en **create**
    * ![](../images/ml3.png)

* Creamos un nuevo cuaderno
    * ![](../images/ml4.gif)
    
Ahora tenemos listo nuestro entorno de trabajo.

## Lab 01: 

Los bots son una forma popular de proporcionar soporte técnico a través de varios canales de comunicación. En este módulo se describe cómo usar el servicio QnA Maker y Azure Bot Service para crear un bot que responda a las preguntas de los usuarios.
En este laboratorio crearemos un bot que responda a las preguntas de los usuarios.

### Instrucciones

1.  Abra el cuaderno [**11 - QnA Bot.ipynb**](../notebooks/11 - QnA Bot.ipynb) en su entorno de trabajo. 
    
2.  Siga las instrucciones del cuaderno para completar el laboratorio.
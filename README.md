# WhatsApp messages bulk sending 📩

Este notebook (python) te permite enviar mensajes masivos de WhatsApp.  

* El insumo principal es una [hoja excel](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/blob/main/01_input/list_phone_sms.xlsx) que contenga los números y mensajes de interés. 📝
* La ejecución del [notebook](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/blob/main/02_codes/01_send_wsp_selenium.ipynb) no impide realizar otras tareas en simultáneo con tu portátil/pc. 🤗 
* Al finalizar, se obtiene un [reporte](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/blob/main/03_output/report_send_wsp_07-02-22.xlsx) sobre el estado de envío de los mensajes según número de contacto ¡Así validas sí todos los sms fueron entregados con éxito! 💯  

<p align="center">
  <img src="https://c.tenor.com/O29iHtSG6OsAAAAC/jim-carrey-jim-carrey-typing.gif"/>
</p>


## Carpetas
📁 [01_input](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/tree/main/01_input): Contiene el excel con los números y mensajes a enviar, así como el chromDriver.exe.  
📁 [02_codes](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/tree/main/02_codes): Contiene el notebook que realiza la automatización del envío de mensajes.  
📁 [03_output](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/tree/main/03_output): Contiene el reporte final de los estados de envío.

## Requisitos   
* Instalar los paquetes:  
`pip install pandas`  (data manipulation)  
`pip install selenium`  (scraping)    
`pip install webdriver_manager`  (scraping)  
`pip install datetime` (current date)  
`pip install pytz` (time zone)

## Aplicación
* **PASO 1:** Descargar el repositorio.  
* **PASO 2:** Cumplir con los requisitos previos.  
* **PASO 3:** Modificar las rutas del directorio.
* **PASO 4:** Modificar el nombre del archivo y las columnas del excel importado en las líneas de código que dependan de este.
* **PASO 5:** Ejecutar el notebook.
* **PASO 6:** Esperar que el código haga su magia.  
* **PASO 7 (opcional):** Intentar de nuevo con los números que tuvieron problemas con la recepción del mensaje. 


## Notas
* Los número de teléfono **no necesariamente** deben estar guardados previamente en la cuenta de WhatsApp desde dónde se enviarán los mensajes.  
* Se recomienda probar al menos 2 veces con aquellos números que no recibieron el mensaje de forma efectiva (**paso 7**).
* La correcta ejecución del código depende de una conexión **estable** de internet.  
* Cambiar el tiempo total de envío establecido por mensaje (16 seg) depende de tu **velocidad** de internet.  



## Advertencia
Este código no está afiliado, autorizado, mantenido, patrocinado ni respaldado de ninguna manera por WhatsApp ni de sus filiales o subsidiarias. Este es un software independiente y no oficial. **Solo utilizarlo para fines acádemicos**. El **uso comercial** de este código/repo está estrictamente **prohibido**. 


<p align="center">
  <img src="https://c.tenor.com/WKWonIB6gjIAAAAC/police-siren-siren.gif"/>
</p>



Agradecimientos a [Ramesh Kumar](https://github.com/inforkgodara). El código principal se baso en uno de sus [repositorios](https://github.com/inforkgodara/whatsapp-bulk-messages-without-saving-contacts)  

📬 Escríbeme a mi correo **marden.arteaga@unmsm.edu.pe** para cualquier duda/problema/sugerencia con este repositorio.  
 




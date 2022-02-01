# WhatsApp messages bulk sending 📩

Este notebook (python) te permite enviar mensajes masivos de WhatsApp.  

* El insumo principal es una [hoja excel](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/blob/main/01_input/list.xlsx) que contenga los números y mensajes de interés. 📝
* La ejecución del [notebook](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/blob/main/02_codes/01_send_wsp_selenium.ipynb) no impide realizar otras tareas en simultáneo con tu portátil/pc. 🤗 
* Al finalizar, se obtiene un [reporte](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/blob/main/03_output/report_send_wsp_30-01-22.xlsx) sobre el estado de envío de los mensajes según número de contacto ¡Así validas sí todos los sms fueron entregados! 💯
![](https://cdn.dribbble.com/users/3377233/screenshots/6958190/busy_texting.gif)

## Carpetas
📁 [01_input](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/tree/main/01_input): Contiene el excel con los números y sus mensajes de interés, así como el chromDriver.exe (versión 97.0.4692.71).  
📁 [02_codes](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/tree/main/02_codes): Contiene el notebook que realiza la automatización del envío de mensajes.  
📁 [03_output](https://github.com/braulio-arteaga/WhatsApp-messages-bulk-sending/tree/main/03_output): Contiene el reporte final de envío de mensajes.

## Requisitos   
* Descargar el chromeDriver.exe ([click aquí](https://chromedriver.chromium.org/downloads)) según la versión de tu navegador chrome. 
* Instalar los siguinetes paquetes:  
`pip install pandas`  (data manipulation)  
`pip install selenium`  (scraping)    
`pip install webdriver_manager`  (scraping)  
`pip install datetime` (current date)  
`pip install pytz` (time zone)

## Aplicación



## Notas
* Los número de teléfono **no necesariamente** deben estar guardados previamente en la cuenta de WhatsApp desde dónde se realizará el envío de mensajes.  
* La correcta ejecución del código depende de una conexión **estable** de internet.  
* Evitar reducir el tiempo de envío de mensaje (17 seg) que se estableció en el código. Depende de tu **velocidad** de internet.


## Advertencia
Este código no está afiliado, autorizado, mantenido, patrocinado ni respaldado de ninguna manera por WhatsApp ni de sus filiales o subsidiarias. Este es un software independiente y no oficial. **Solo utilizarlo para fines acádemicos**. El **uso comercial** de este código/repo está estrictamente **prohibido**. 

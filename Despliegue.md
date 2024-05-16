#Pasos para realizar el despliegue de una aplicativo web en azure


Iniciar sesión en Azure Portal

Ve a https://portal.azure.com e inicia sesión con tu cuenta de Azure.


Crear un plan de App Service

En el menú de Azure Portal, haga clic en "Crear un recurso".
Busca "App Service Plan" y selecciónalo.
Configura el plan con un nombre, suscripción, grupo de recursos, ubicación y nivel de precios.
Haz clic en "Revisar y crear" y luego en "Crear".


Crear un servicio de aplicaciones

En el menú, haz clic en "Crear un recurso" nuevamente.
Busca "Web App" y selecciónala.
Configura la App Service con un nombre de host único, suscripción, grupo de recursos, plan de App Service (el que creaste antes) y sistema operativo.
Haz clic en "Revisar y crear" y luego en "Crear".


Subir el código de tu página web

Una vez creada la App Service, ábrela.
En el panel de la izquierda, haga clic en "Centro de implementación".
Selecciona un método de implementación (ej: FTP, Git local, Github, etc).
Sigue las instrucciones para subir tus archivos de la página web.


Acceder a tu página web

Una vez subidos los archivos, haz clic en la URL predeterminada en la descripción general de la App Service.
La URL tendrá el formato:https:///<nombre-app-service>.azurewebsites.net
Verás tu página web en funcionamiento.


Configuraciones adicionales (opcional)

Puedes configurar dominios personalizados, certificados SSL, escalado automático y muchas otras opciones desde el panel izquierdo de la App Service.

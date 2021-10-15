# SSOO-tarea02
##### Nombre del autor: Brenda Araya Bermudez
##### Correo institucional: brenda.arayab@alumnos.uv.cl
Para obtener los datos de los items del videojuego "**Warframe**", se debe de usar **curl**, **redireccionamiento (>)** y **jq**.
 
Primero se utiliza **curl https://api.warframe.market/v1/items** para acceder y mostrarlos en consola, sin embargo todos estos datos son muy abrumantes a la vista y poco entendibles, por ende para ordenarlos y mostrar solamente lo requerido **(id e item_name)** se utilizara **jq** para realizar un filtro a la informacion y luego guardarla en un archivo .json llamado **items.json**.
 
Se decidio eliminar parte de la informacion para realizar el filtrado debido a que era mas sencillo que filtrarlo directamente, por lo tanto se usa **"del"** y asi se elimina **thumbs** y **url_name** para solo dejar **id** **y** **item_name**.
 
Una vez resuelto el filtrado de datos, ya se puede redireccionar hacia un archivo -json con **>**, guardandolo en el archivo llamado **items.json** que mencionamos anteriormente.
Ya finalizado el proceso se muestra el mensaje **JSON CREADO CON EXITO** (utilizando **echo**) mostrando que si se logro realizar el ejercicio.

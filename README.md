# SSOO-tarea02
##### Nombre del autor: Brenda Araya
##### Correo institucional: brenda.arayab@alumnos.uv.cl
### Para obtener los datos de los items del videojuego "**Warframe**", se debe de usar curl, redireccionamiento y JQ.
### Primero se utiliza **curl https://api.warframe.market/v1/items** para acceder y mostrarlos en consola, sin embargo todos estos datos son muy abrumantes a la vista y poco entendibles, por ende para ordenarlos y mostrar solamente lo requerido **(id e item_name)** se utilizara JQ para realizar un filtro a la informacion y luego guardarla en un archivo .json llamado **items.json**

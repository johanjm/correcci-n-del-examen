# correcci-n-del-examen

Integrantes
--------------
Quinatoa Johán

Quisaguano Bryan

Rea Jhosef

Sánchez Antony


Twitter
-------------------
Primero para crear un enlace con Twitter usamos las claves generadas por la cuenta de dessarrollador de la aplicacion, al realizar el enlace debemos obtener información con tres distintas locaciones las cuales se guardaran en una base de datos en couchDB, el código se ejecuta 2 vecess más cambiando las locaciones. Para el segundo paso se puede implementar el mismo código con la peculiaridad que en lugar de realizar locaciones simplemente colocamos un track, en este caso es JuegosOlimpicos. Y de igual manera se guarda en la base de datos en couchDB.


Facebook
-----------------
Para realizar una extracción de datos mediante facebook, nos ayudamos de la libreria facebook-scraper, con la cual podemos conectarnos y como página de busqueda a la cual nos conectaremos, se ha seleccionado Olympic que es la cuenta oficial de los juegos olimpicos. Una vez realizada la conexion formamos el json al cual se extraeran los datos, ademas de realizar la conexion a couchDB.


TikTok
----------------------
Para el caso de tiktok se realiza un scraping y así obtener archivos csv de la plataforma, las cuentas seleccionadas, han sido Olympic y 7Olympic cuanta oficial de los juegos olimpicos y una aficionada respectivamente.

<img src="https://github.com/johanjm/correcci-n-del-examen/blob/main/img/tiktok.png" alt="i1"/>

Archivos csv listos.

<img src="https://github.com/johanjm/correcci-n-del-examen/blob/main/img/csvtik.png" alt="img18"/>

Traspaso a MySQL
---------------------------
Para poder emplear esto he usado la herramienta XAMP, para poder habilitar los servidores.

<img src="https://github.com/johanjm/correcci-n-del-examen/blob/main/img/xamp.jpg" alt="img18"/>

Ahora se ha importado los archivos csv generados para tiktok en una base de datos nueva, esto se realiza para los 2 csv

<img src="https://github.com/johanjm/correcci-n-del-examen/blob/main/img/upmysql.jpg" alt="img18"/>

Se puede evidenciar los resultados

<img src="https://github.com/johanjm/correcci-n-del-examen/blob/main/img/mysqlready.jpg" alt="img18"/>




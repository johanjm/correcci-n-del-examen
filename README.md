# correcci-n-del-examen
Twitter
-------------------
Priimero para crear un enlace con Twitter usamos las claves generadas por la cuenta de dessarrollador de la aplicacion, al realizar el enlace debemos obtener información con tres distintas locaciones las cuales se guardaran en una base de datos en couchDB, el código se ejecuta 2 vecess más cambiando las locaciones. Para el segundo paso se puede implementar el mismo código con la peculiaridad que en lugar de realizar locaciones simplemente colocamos un track, en este caso es JuegosOlimpicos. Y de igual manera se guarda en la base de datos en couchDB.

1. Se crea el enalce con couchDB y python para que el scrpit pueda recolectar los datos de twitter y los vaya escribiendo en la base de datos, en este caso la base de datos se llama "twitter1", con el código adjunto "1.py"

![Captura de Pantalla 2021-08-30 a la(s) 21 11 33](https://user-images.githubusercontent.com/66568293/131430411-d08fbd47-5aa8-4f9c-88d9-412b9c965de3.png)

2. Se crea el enalce con couchDB y python para que el scrpit pueda recolectar los datos de twitter y los vaya escribiendo en la base de datos, en este caso la base de datos se llama "twitter2", con el código adjunto "2.py"

![Captura de Pantalla 2021-08-30 a la(s) 21 15 53](https://user-images.githubusercontent.com/66568293/131430764-37ab9c29-d83a-4278-b780-9c51c92d2b18.png)





TikTok
----------------------
Para el caso de tiktok se realiza un scraping y así obtener archivos csv de la plataforma, las cuentas seleccionadas, han sido Olympic y 7Olympic cuanta oficial de los juegos olimpicos y una aficionada respectivamente.

<img src="https://github.com/johanjm/correcci-n-del-examen/blob/main/img/tiktok.png" alt="i1"/>

Archivos csv listos.

<img src="https://github.com/johanjm/correcci-n-del-examen/edit/main/img/csvtik.PNG" alt="img18"/>

Traspaso a MySQL
---------------------------
Para poder emplear esto he usado la herramienta XAMP, para poder habilitar los servidores.

<img src="https://github.com/johanjm/correcci-n-del-examen/edit/main/img/xamp.JPG" alt="img18"/>

Ahora se ha importado los archivos csv generados para tiktok en una base de datos nueva, esto se realiza para los 2 csv

<img src="https://github.com/johanjm/correcci-n-del-examen/edit/main/img/upmysql.JPG" alt="img18"/>

Se puede evidenciar los resultados

<img src="https://github.com/johanjm/correcci-n-del-examen/edit/main/img/mysqlready.JPG" alt="img18"/>




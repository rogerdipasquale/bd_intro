# Práctica introductoria a Base de Datos Relacionales

¿Cómo Ejecutarla?

Se puede trabajar con SQLite, utilizando el standalone https://www.sqlite.org/2019/sqlite-tools-win32-x86-3280000.zip . Para utilizar la base de ejemplo, descomprimir el zip, colocar en la misma carpeta el archivo de base de datos elegido, y ejecutar sqlite3.exe

desde la consola, ejecutar .open [archivo]

Por ejemplo, 
sqlite> .open ejemplos_bd1

Se puede ver el esquema creado con
sqlite> .schema

Y ejecutar cualquier consulta, incluso a través de varias líneas, finalizándola con ;


Para mayor referencia:
https://www.sqlite.org/cli.html

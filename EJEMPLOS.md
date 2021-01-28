# EJEMPLOS

Como ya he explicado en el apartado anterior, el comando wget en resumen sirve para descargar paquetes de páginas web:

el comando es muy simple. Para utilizarlo, simplemente escribimos "wget" seguido del enlace del archivo

`wget www.sitiocualquiera.com/archivo.zip` (o una extensión cualquiera, depende de que sea el archivo)
                

## Ejemplo de descarga simle:
Un ejemplo simple es la descarga de un fondo de pantalla. En mi caso quiero descargarlo de la página wallhaven.cc 

Quiero descargar el siguiente fondo, y tengo su enlace copiado.

![ejemplo fondo](https://github.com/mloparj10/wget/blob/main/images/ejemplo%20fondo.jpg)

  Escribimos: 
  
`wget https://w.wallhaven.cc/full/ox/wallhaven-oxkjgm.jpg`

Aquí podemos observar como lo ha descargado:

![Descarga de imagen](https://github.com/mloparj10/wget/blob/main/images/Fondo%20de%20pantalla%20descarga.png)
  
  La pregunta es:¿Donde se ha descargado?. Pues bien, el archivo se descarga donde nos encontramosa actualmente. En mi caso se ha descargado dentro de /root, 
  ya que lo estaba probando desde la consola de Root.
  
## Descarga Simple, seleccionando la ruta:
  Para ello ejecutamos el mismo comnando que el anterior, pero esta vez añadimos el parámetro -P (P mayuscula, importante) e indicamos el directorio. En mi caso lo quiero 
  guardar en /home/usuario/Descargas
    
`wget https://w.wallhaven.cc/full/ox/wallhaven-oxkjgm.jpg -P /home/usuario/Descargas `

![Descarga de imagen seleccionando directorio](https://github.com/mloparj10/wget/blob/main/images/Descarga%20imagen%20directorio.png)
    
Una vez ejecutado realizo el comando ls /home/usuario/Descargas para ver si se ha descargado. Y efectivamente, ahí está.
 
![Ls a descargas](https://github.com/mloparj10/wget/blob/main/images/Ls%20a%20descargas.png)

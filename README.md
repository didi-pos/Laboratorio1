<div align="center">
<h1>Laboratorio 1</h1>
<p>
  <br>
  <b>Didier Posse y Oscar Grande</b>
  <br>
  <em>Primer punto</em>
</p>
</div>
<hr>
<ol>
  <li>
    <ul>
      <li><b>Rufus:</b> Antes de bootear la memoria se instala la imagen (.iso) del sistema operativo que se desea colocar en la memoria, hay que tener en cuenta
      que Rufus solo sirve para colocar una sola imagen en la USB. luego se descarga el software "Rufus" desde su misma pagina web, después de instalarla y ejecutarla,
      uno le da los permisos que requiere, luego aparece una barra para seleccionar la imagen que uno quiere pasarle a la USB, uno eleije el tipo de partición que le
      resulte más comodo, uno puede elegir sistema de destino (BIOS o UEFI), después de darle siguiente aparece una alerta de formateo de la USB donde uno le dira
      "Aceptar" y ahi ya tendriamos la memoria booteable.</li>
      <li><b>Ventoy:</b> Después de tener instaladas las imagenes (.iso) que uno quiere colocar en la USB, uno va a la pagina de "Ventoy", uno descarga el software,
      después de instalarlo y ejecutarlo aparece una barra el cual uno puede seleccionar la USB y elejir el estilo de partición, configurar la partición. Por cosiguiente
      se instala Ventoy en la USB y simplemente se copia y pega en la USB las imagenes para que queden guardadas en la USB que se debe llamar "Ventoy".</li>
    </ul>
  </li>
  
  <li>El bootloader es el software que se inica al inicio, osea el software de arranque para cargar el sistema operativo (SO), es el que controla el hardware pa que
  se inicie el software en un inico, desde un dispositivo booteable, osea de arranque. El GRUB (GRand Unified Bootloader), como lo dice en el nombre, es un gestor de
  arranque multiple el cual se encarga de arrancar varios sistemas operativos, significa que es una parte importante de los sitemas operativos para hacer su inicialización
  y uno puede elegir que sistema operativo quiere que se cargue.</li>
  
  <li>Practicamente es la compatibilidad de los archivos con los sistemas operativos, osea que hay tipos de archivos que son compatibles con Windows y otro tipo de archivos
  compatibles con Linux, porque cada sistema operativo tinene una forma de leer los archivos, por eso las descargas de apkicaciones hay diferentes links de instalación por
  sistema operativo. Los sistemas de archivos son: FAT32, exFAT, NTFS, HFS+, APFS, EXT4.</li>
  
  <li>Es el sistema para dividir el disco duro, formas de partir el disco, en secciones logicas independientes, donde el sistema operativo trata como si fueren unidades de
  almacenamiento separadas. Los sistemas de particiones que hay son:
  <ul>
      <li><b>Partición Primaria:</b> Es la partición principal del disco duro, se puede arrancar el sistema operativo desde esta, ya que contiene los archivos de arranque. 
      Un disco puede tener hasta 4 particiones primarias o 3 primarias y 1 extendida.</li>
      <li><b>Partición Extendida:</b> Es un tipo de partición que no se utiliza directamente para guardar datos, sino que funciona como un contenedor para crear dentro de ella 
      varias particiones lógicas, esto se usa porque el límite de las primarias es de solo 4, entonces con una extendida se pueden crear más particiones.</li>
      <li><b>Partición Lógica:</b> Son las particiones que se crean dentro de la partición extendida, estas sí se pueden usar para almacenar datos o instalar sistemas operativos. 
      El sistema las reconoce como si fueran discos independientes.</li>
    </ul>
  </li>
</ol>

<hr>
<div align="center">
<p>
  <em>Segundo punto</em>
</p>
</div>
<hr>

<img width="600" height="756" alt="image" src="https://github.com/user-attachments/assets/25c87f1d-fc52-4639-b48d-2b1ae308cfc2"/>

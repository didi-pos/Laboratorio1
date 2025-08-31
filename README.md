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
  <li>Las dos son software booteables, pero Rufus solo sirve para colocar una imagen (.iso), y Ventoy funciona para colocar tantas imagenes quepan en la USB.
    <br>
    <ul>
      <li><b>Rufus:</b> Antes de bootear la memoria se instala la imagen (.iso) del sistema operativo que se desea colocar en la memoria, hay que tener en cuenta
      que Rufus solo sirve para colocar una sola imagen en la USB. luego se descarga el software "Rufus" desde su misma pagina web, después de instalarla y ejecutarla,
      uno le da los permisos que requiere, luego aparece una barra para seleccionar la imagen que uno quiere pasarle a la USB, uno eleije el tipo de partición que le
      resulte más comodo, uno puede elegir sistema de destino (BIOS o UEFI), después de darle siguiente aparece una alerta de formateo de la USB donde uno le dira
      "Aceptar" y ahi ya tendriamos la memoria booteable.</li><br>
      <li><b>Ventoy:</b> Después de tener instaladas las imagenes (.iso) que uno quiere colocar en la USB, uno va a la pagina de "Ventoy", uno descarga el software,
      después de instalarlo y ejecutarlo aparece una barra el cual uno puede seleccionar la USB y elejir el estilo de partición, configurar la partición. Por cosiguiente
      se instala Ventoy en la USB y simplemente se copia y pega en la USB las imagenes para que queden guardadas en la USB que se debe llamar "Ventoy".</li><br>
    </ul>
  </li>
  
  <br>
  
  <li>El bootloader es el software que se inica al inicio, osea el software de arranque para cargar el sistema operativo (SO), es el que controla el hardware pa que
  se inicie el software en un inico, desde un dispositivo booteable, osea de arranque. El GRUB (GRand Unified Bootloader), como lo dice en el nombre, es un gestor de
  arranque multiple el cual se encarga de arrancar varios sistemas operativos, significa que es una parte importante de los sitemas operativos para hacer su inicialización
  y uno puede elegir que sistema operativo quiere que se cargue.</li>
  
  <br>
  
  <li>Practicamente es la compatibilidad de los archivos con los sistemas operativos, osea que hay tipos de archivos que son compatibles con Windows y otro tipo de archivos
  compatibles con Linux, porque cada sistema operativo tinene una forma de leer los archivos, por eso las descargas de apkicaciones hay diferentes links de instalación por
  sistema operativo. Los sistemas de archivos son: FAT32, exFAT, NTFS, HFS+, APFS, EXT4.</li>
  <br>
  <li>Es el sistema para dividir el disco duro, formas de partir el disco, en secciones logicas independientes, donde el sistema operativo trata como si fueren unidades de
  almacenamiento separadas. Los sistemas de particiones que hay son:
    
  <br>
    
  <ul>
      <li><b>Partición Primaria:</b> Es la partición principal del disco duro, se puede arrancar el sistema operativo desde esta, ya que contiene los archivos de arranque. 
      Un disco puede tener hasta 4 particiones primarias o 3 primarias y 1 extendida.</li><br>
      <li><b>Partición Extendida:</b> Es un tipo de partición que no se utiliza directamente para guardar datos, sino que funciona como un contenedor para crear dentro de ella 
      varias particiones lógicas, esto se usa porque el límite de las primarias es de solo 4, entonces con una extendida se pueden crear más particiones.</li><br>
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

<div align="center">
  <img width="300" alt="image" src="https://github.com/user-attachments/assets/25c87f1d-fc52-4639-b48d-2b1ae308cfc2"/>
  <br>
  
  <p>
    Durante el proceso, descargamos desde la página oficial la versión de Ubuntu compatible con Windows. Luego, buscamos la aplicación Rufus en internet, la instalamos en
    el computador e insertamos la memoria USB. Tras formatearla, utilizamos Rufus para crear la memoria booteable con la imagen de Ubuntu. A continuación, reiniciamos el
    equipo e ingresamos a la BIOS, donde configuramos el orden de arranque para que la prioridad estuviera en la memoria USB. Una vez hecho esto, el sistema inició desde
    la unidad booteada y comenzó la instalación de Ubuntu. Finalmente, seguimos los pasos de instalación hasta concluir el proceso. Tras unos minutos, se habilitó la
    opción para crear el usuario del nuevo sistema operativo, completando satisfactoriamente la instalación.
  </p>
  
  <br>
  <img width="400" alt="image" src="https://github.com/user-attachments/assets/ea94b1bc-378f-4378-b199-ca28c8df9156"/>
  <br>
  
  <p>
    Seguimos un proceso similar, el cual descargamos en la pagina de Ventoy, el software de Vnetoy, luego de abrirla se coloca la USB en el puerto del pc y uno configura
    la compatibilidad de archivos y el sistema de partición, después se instala el Ventoy en la USB, la USB queda booteable y le cambia el nombre de la USB a Ventoy,
    ya cuando esta configurada la USB, ingresamos los archivos .iso, o sea la imagen de windows 11 y la imagen de Ubuntu y ya queda para arrancar la USB y poder
    instalar Ubuntu.
  </p>
</div>

<hr>

<div align="center">
<p>
  <em>Tercer punto</em>
</p>
</div>

<hr>

<div align="center">
  <img width="400" src="https://github.com/user-attachments/assets/4696a416-97bf-44c2-b539-9756ae29ff72"/>
  <br>

  <p>
    Primero se hace la repartición del disco, yo le coloque 70GB a la partición donde instale Ubuntu y uno escoge la compatibilidad de archivos,
    NTFS es el más común.
  </p>

  <br>
  <img width="400" src="https://github.com/user-attachments/assets/39a1fb9d-75da-4b10-b5be-9c94397b36cc"/>
  <br>
  
  <p>
    Luego se hace todo el proceso que explique de instalar Ventoy en la memoria USB y pasar las imagenes (.iso) a la memoria para ponerla bootear con ella.
  </p>
  
  <br>
  <img width="400" src="https://github.com/user-attachments/assets/93bfa0e3-58a5-46e8-890a-a474f519f1c1"/>
  <br>
  
  <p>
    Después se reinicia el computador e ingresa uno a la BIOS con la tecla asignada para entrar, ahí uno selecciona la unidad de memoria de arranque
    para iniciar el computador.
  </p>

  <br>
  <img width="400" src="https://github.com/user-attachments/assets/b6ad4484-1382-4790-9325-069690d6a912"/>
  <br>
  
  <p>
    Siguiente a eso aparece la interfaz de Ventoy en el cual uno puede seleccionar las imagenes (.iso) que uno copio en la memoria, cuando uno selecciono
    una, uno puede elegir como quiere arrancar, uno por lo general elige el boot normal.
  </p>

  <br>
  <img width="400" src="https://github.com/user-attachments/assets/04979e30-13e1-491f-af08-dd748c91524b"/>
  <br>
  
  <p>
    Luego aparece como tal la interfaz de Ubuntu y los pasos que uno debe seguir para instalarlo como uno quiere.
  </p>

  <br>
  <img width="400" src="https://github.com/user-attachments/assets/cffd85ba-5327-4129-9e7a-aa803c999b00"/>
  <br>
  
  <p>
    Ubuntu te da la opción de instalar o probar su sistema operativo, pero uno que quiere instalarlo elige la primera opción.
  </p>

  <br>
  <img width="400" src="https://github.com/user-attachments/assets/e8d065b4-6b5e-4358-9c4f-52d716e1b794"/>
  <br>
  
  <p>
    Este paso es muy importante, ya que aqui uno elige en que unidad de memoria o en que partición uno quiere instalar Ubuntu, Ubuntu te da la facilidad
    de escoger si quieres instalar Ubuntu junto a Windows, el cual es la opción que queremos esoger, pero también se puede formatear el disco de la computadora
    o una forma de escoger personalizada.
  </p>

  <br>
  <img width="400" src="https://github.com/user-attachments/assets/0fdad69c-9c83-45bc-93b3-88f68799d8e7"/>

  <br>
  
  <p>
    Aquí uno elige la partición en la que uno quiere Ubuntu y cuantas GB uno quiere darle a esa unidad.
  </p>

  <br>
  <img width="400" src="https://github.com/user-attachments/assets/78021305-84ba-490e-af0d-a6a51cdf8cb2"/>

  <br>
  
  <p>
    Después de crear una cuenta para Ubuntu y de seleccionar la región, se demora un poco mientras se instala y te da la opción de reiniciar la pc para aplicar los cambios.
  </p>

  <br>
  <img width="400" src="https://github.com/user-attachments/assets/b80a4544-ba4c-4833-a62a-7dbf7ec15dc7"/>
  <br>
  
  <p>
    Luego de que se reiniciara y uno quitara la unidad USB donde arranco el Ubuntu, aparece que ya fue instalado el Ubuntu.
  </p>

   <br>
  <img width="400" src="https://github.com/user-attachments/assets/78cb62af-1aae-45b3-9ae4-7bec9d8c7174"/>
  <br>
  
  <p>
    Finalmente cada vez que uno inicie la computadora, van aparecer todas estas opciones donde las importantes son dos, una para iniciar Ubuntu y otra para iniciar Windows.
  </p>
</div>

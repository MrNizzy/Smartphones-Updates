<a href="https://github.com/Nizzy0128/Smartphones-Updates"><img src="https://i.ibb.co/RbZx3Hf/Smartphones.png" alt="Smartphones" border="0"><br />

* [TWRP](https://twrp.me/Devices/) - TWRP Devices
* [Pixel Experience](https://download.pixelexperience.org) - Pixel Experience Downloads
* [Google](https://www.android.com/intl/es_es/gms/) - Google Services
* [Android](https://www.android.com) - Android News
* [OpenGapps](https://opengapps.org) - Google Apps
* [LineageOS](https://download.lineageos.org) - LineageOS
* [Magisk](https://magiskmanager.com) - Magisk Manager
* [LuckyPatcher](https://luckypatcher.co/apk-download-app/) - Lucky Patcher

# WIKI

## ¡Importante!
Algunos dispositivos requieren liberar el ```Bootloader``` si no saben como se hace, buscar un vídeo en YouTube o Foros de como hacer este procedimiento ya que para muchas marcas (Samsung, Xiaomi, Motorola, Sony Xperia, etc) son totalmente diferentes los métodos.

### _INSTALAR:_

* [Descargar/Download](https://github.com/Nizzy0128/Smartphones-Updates/raw/master/TWRP/adb-setup.exe) - Herramienta ADB

```
adb-setup.exe
```

### _Instalar herramienta TWRP:_

#### PROCEDIMIENTO PARA LA INSTALACIÓN DEL TWRP:

* [Descargar/Download](https://github.com/Nizzy0128/Smartphones-Updates/raw/master/TWRP/AUTO%20%5BTWRP%5D.zip) - Herramientas ADB (Archivos que permiten la ejecución de los comandos)
* Descomprimir:
```
AUTO [TWRP].zip
```
* [Descargar/Download]() - TWRP dependiendo de su dispositivo. (Carpetas de arriba)
* Descomprimir:
```
twrp.zip
```
[Descargar/Download](https://twrp.me/Devices/) - TWRP para otros dispositivos (En caso de no hallarlo en la lista)
</br>
* Pasar el Archivo ```twrp.img``` a la carpeta donde se encuentran las herramientas ADB.
* Para poder continuar, debemos poner nuestro smartphone en modo fastboot. Si no sabes como hacerlo solo busca en [Google](https://google.com/) ```¿Cómo entrar al modo fastboot en un <Nombre del dispositivo>?``` ahí saldrán muchos foros y/o vídeos de como hacerlo, aunque es muy fácil.
* Por último conectamos el dispositivo al computador y ejecutamos el archivo:
```
FLASH RECOVERY AUTO.bat
```
### NOTA:
* El archivo ```FLASH RECOVERY AUTO.bat``` nos hará el proceso de los pasos extra automaticamente, en caso de no funcionar, hacer los pasos extra manualmente.

#### STEP/PASO Extra #1:
* Abrir consola de comandos en la carpeta:
```Ctrl``` + ```Shift``` -> ```Abrir consola de comandos aquí```
* Si no funciona, abrimos la consola de comandos con el comando ```Windows``` + ```R``` y escribimos ```cmd```, luego damos enter y en la consola escribimos ```cd ..``` hasta quedar en la ruta ```C:\``` luego copiamos la ruta de donde se encuentre la carpeta del ```AUTO [TWRP].zip``` y después escribimos ```cd``` + La Ruta. Quedaría algo así ```cd C:\Users\Nizzy0128\Documents\GitHub\Smartphones-Updates\TWRP\AUTO [TWRP]```

* En caso que no funcione ninguna de estás formas y en el primer paso les salga ```Abrir la ventana de PowerShell aquí```, pueden seguir el siguiente vídeo:

<a href="https://bit.ly/2Ujp1KD"><img src="https://i.ibb.co/tcbpVH3/maxresdefault.jpg" alt="Smartphones" border="0"><img/><br />

#### STEP/PASO Extra #2:
* []()Para poder continuar, debemos poner nuestro smartphone en modo fastboot. Si no sabes como hacerlo solo busca en [Google](https://google.com/) ```¿Cómo entrar al modo fastboot en un <Nombre del dispositivo>?``` ahí saldrán muchos foros y/o vídeos de como hacerlo, aunque es muy fácil.
* Una vez este en modo fastboot, conectamos el dispositivo al computador, y ejecutamos el siguiente comando para saber si nuestro equipo reconoce el dispositivo: ```fastboot devices``` si no lo reconoce no debe salir nada.
* Luego que nos cercioremos de que lo reconozca, procederemos a instalar el ```twrp.img```. Para ello escribimos el siguiente comando:
```
fastboot recovery twrp.img
```
Hay que fijarnos si el proceso se hizo correctamente, de no serlo saldrá algún error.

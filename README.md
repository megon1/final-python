# final-python

clase 11
Investigar ¿Qué es el pip y porque lo actualizamos?


pip es un sistema de gestión de paquetes utilizado para instalar y administrar paquetes de software escritos en Python. Muchos paquetes pueden ser encontrados en el Python Package Index (PyPI). Python 2.7.9 y posteriores (en la serie Python2), Python 3.4 y posteriores incluyen pip (pip3 para Python3) por defecto.

pip es un acrónimo recursivo que se puede interpretar como Pip Instalador de Paquetes o Pip Instalador de Python.1​

Interfaz línea de comando

Salida de pip install virtualenv
Una ventaja importante de pip es la facilidad de su interfaz de línea de comandos, el cual permite instalar paquetes de software de Python fácilmente desde solo una orden:

pip install nombre-paquete
Los usuarios también pueden fácilmente desinstalar algún paquete:

pip uninstall nombre-paquete
Otra característica particular de pip es que permite gestionar listas de paquetes y sus números de versión correspondientes a través de un archivo de requisitos. Esto nos permite una recreación eficaz de un conjunto de paquetes en un entorno separado (p. ej. otro ordenador) o entorno virtual. Esto se puede conseguir con un archivo correctamente formateado requisitos.txt y la siguiente orden:

pip install -r requisitos.txt
Con pip es posible instalar un paquete para una versión concreta de Python, sólo es necesario reemplazar ${versión} por la versión de Python que queramos: 2, 3, 3.4, etc:

pip${versión} install nombre-paquete

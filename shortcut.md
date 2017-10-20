#ATAJOS EN GNU/LINUX

En notación de Backus-Naur

![Icono GDM] (./ignu.png Viva Gnu)

##GNOME (3 Shell) 

- Meta (tecla de windows): abre panel lateral
- Control Q: quitar programa
- Control W: cerrar ventana
- Alt Tabulador: alternar entre programas
- Alt y tecla de encima del tabulador: Alternar entre dos ventanas del mismo programa
- Control ALT ↓: cambiar entre escritorio
- meta espacio: Cambio de idioma
- Meta : maximizar ventana

##TEXTO

- Control +: Ampliar fuente
- Control -: Reducir fuente
- Control c: copiar
- Control v: Pegar
- Control X: Cortar
- Shift ←↑→↓: Subrayar de carácter en caracter
- Control Shift ←↑→↓: Subraya palabras enteras
- Control ALT O (vocal): pasar a modo pagina web 

##Terminal

- Control alt T: Sacar terminal
- Control mayus t: abrir otra pestaña
- Alt nº: Cambias a la pestaña X
- Control mayus P: instalador paquetes, dentro de el en Package control: install Package y desde ahi tienes paquetes 
- Control mayus U Nº: Metemos caracter unicode

- Control C: interrumpir un programa
- Control Z: Pasar a segundo plano
- fg 1: vuelve a primer plano

- Control mayus C: Copiar
- Control mayus V: Pegar
- Control l: Borrar pantalla
- Display: visor de imagenes
- Control D: terminar fichero

- y luego tenemos readline

- ls: list files. muestra el directorio
- cd: change directory
- Mkdir: make dir
- RMdir: remove directory (solo si esta vacio)
- RM: remove. Quitar un archivo
- rm -rf (**r**ecursivo **f**orce)
- cat: concatenar archivos
- cat fichero > fichero2 lo redirecciona del A al B
- tambien hay dobles redirecciones, <<

git:

- clone
- commit
- status
- add (vigilar nuevos ficheros)
  git a -u (remove deleted files)
- pull
- push

## Comandos que unen
- cat: concatenar archivos
- cat fichero > fichero2 lo redirecciona del A al B
- paste: unir en vertical    Ejemplo: archivo1.txt archivo2.txt

- join: Combinacion

## Comandos que dividen
- tail - 2 archivo : mirar la cola del archivo
tail -f (deja el fichero abierto)
- head mirar cabecera
- cut: Corta vertical ==> cut -d " " f l
f es fila, F1 fila uno por ejemplo
- split: divide horizontal

## Comandos que filtran


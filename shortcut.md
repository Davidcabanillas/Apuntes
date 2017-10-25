# ATAJOS EN GNU/LINUX

En notación de Backus-Naur

![Icono GDM] (./ignu.png Viva Gnu)

## GNOME (3 Shell) 

- Meta (tecla de windows): abre panel lateral
- Control Q: quitar programa
- Control W: cerrar ventana
- Alt Tabulador: alternar entre programas
- Alt y tecla de encima del tabulador: Alternar entre dos ventanas del mismo programa
- Control ALT ↓: cambiar entre escritorio
- meta espacio: Cambio de idioma
- Meta : maximizar ventana

## TEXTO

- Control +: Ampliar fuente
- Control -: Reducir fuente
- Control c: copiar
- Control v: Pegar
- Control X: Cortar
- Shift ←↑→↓: Subrayar de carácter en caracter
- Control Shift ←↑→↓: Subraya palabras enteras
- Control ALT O (vocal): pasar a modo pagina web 

## Terminal

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
- mkdir: make dir
- rmdir: remove directory (solo si esta vacio)
- rm: remove. Quitar un archivo
- rm -rf (**r**ecursivo **f**orce)
- cat: concatenar archivos
- cat fichero > fichero2 lo redirecciona del A al B
- tambien hay dobles redirecciones, <<

## git:

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

## Comandos que trabajan con texto
- grep: filtra
- ed: editor sin venta
- sed: lo mismo
- vi: (mejorado)

- copmandos en vi, valen los de la terminal, se activa con !
## Comandos que filtran

- Split (n) → 
- man 1 → herramientas terminal 
- man 2→ Nucleo sistema operativo
- man 3→ Lenguaje de programacion

tambien puede usarse info

## Otros
- wget paginaweb: descargar de internet
- bc: calculadora basica, se sale con control D
	- "obase": base de salida
	- "ibase": base de entrada
	- base=16 o 10 o 8, cambia la base

- cal: calendario
- xargs: ejecuta con argumentos
- rsync: hace copias de seguridad (varios equipos)
- mysqldump: volcado de la base de datos
- date: muestra la fecha (backups rotativos)
- history: muestra el historial
- fg <n>: trae un proceso a primer plano
- jobs: Lista todos los procesos detenidos
- ps aux: vemos los procesos
- kill <pid>: Matamos el proceso
- kill -9 <pid>: matar por la fuerza
-
-
-
- touch: 
- tr: Transalate, Traduce/cambia una serie de letras por otras.  Ejemplo cat shk.txt | tr "Ai" "a!"   Esto cambiaria la A=a y i=!
- tr -s "A" "a": squeeze, aprieta, cambia todas las A por una a
- tr "A-Z" "a-z": cambia todas las mayusculas a minusculas, el guion indica rango
	"\t": tabulaciones
	"\n": new line
	"cd": conjunto complementario

- uniq: deja filas unicas. -c: cuenta
- sort: ordena. -n: Numerico

- telnet 
- ssh: igual que telnet pero seguro
- nc -l 2222: redirige todo lo que entre

## Para buscar
- grep: filtra
	- i: ignora mayus/minus
	- l: linea
	- n: 
	- b: bit en el que esta
	- c: cuenta las veces que aparece la palabra
- find: Busca ficheros
	- Ejemplo: find . -name "algo": busca en la carpeta ficheros que tengan "algo" en el nombre
- xargs: pasa lo hecho por el comando anterior a otro, ejecuta con argumentos
	- Ejemplo seq 1 9 | xargs echo: ejecuta la secuencia de 1-9 y la carga en el echo
- wich: Donde esta instalado

- > tubo
- 2> tubo2

chmod: permisos 


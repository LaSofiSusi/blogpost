# Sofia esta estudiando
Este "BLOG" es solo para aprender a usar git y github.

## Ya me falta bastante poco
Aunque son las 1:37AM estoy realmente emocionada de estar casi por terminar el curso de platzi, a sido bastante genial entender todo tan rapido y ponerlo en practica.

## Quieres aprender hacer una llave SSH?
* para crear una clave SSH tenemos que introducir lo siguiente
  >ssh-keygen -t rsa -b 4096 -C "tu@email.com"

* luego de eso te preguntara donde quieres guardar la llave ssh, por defecto lo guarda en una carpeta
oculta llama .ssh
* Podemos adicionalmente colocar una clave a esta llave para agregar una capa adicional de seguridad

* Ya habiendo creado nuestra llave debemos de verificar si el programa SSH esta corriendo en nuestro
sistema.
  > eval $(ssh-agent -s)

* Esto nos devolvera connn un PID si el proceso esta corriendo o no en nuestra maquina
* Ahora para agregar nuestra llave a nuestro sistema debemos de hacerlo con el siguiente codigo.
  > ssh-add ~/.ssh/LLAVE PRIVADA

* Si agregaste una clave adicional a tu llave SSH aqui te pedira esa clave.

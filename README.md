# udemySass
curso de sass impartido por udemy

1.- Instalacion de sass: Seguir los pasos descritos en su pagina web oficial http://sass-lang.com/install

2.- Conexion de carpetas: Para enlazar las carpetas se debe colocar "sass --watch origen:destino" para este caso se uso "sass --watch sass:css"

NO hay que cerrar la ejecucion del comando anterior, ya que esto permite la compilacion de los cambios realizados.

3.- La nomensclatura para trabajar los estilos en SASS es:
elemento1{
  caracteristica
  elemento2{
    caracteristica
    elemento3{
      caracteristica
    }
  }
}

Con esto se tiene lo mismo que en CSS pero de manera ordenada. En CSS se veria asi:

elemento1{
  caracteristica
}
elemento1 elemento2{
  caracteristica
}
elemento1 elemento2 elemento3{
  caracteristica
}

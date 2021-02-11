# HostHome — Docs


<style>
.md-footer-copyright #text {
    display: none
}

.md-footer-copyright .md-footer-copyright__highlight #text {
    display: block
}
</style>

<p align="center">
    <img style="border-radius: 10px; width: 1000px;" src="https://raw.githubusercontent.com/HostHome-of/website/main/src/static/images/banner.png" />
</p>

---

##### — Index

* [Documentacion](/)
    * [Como crearse una cuenta](/cuentas/)
    * [Los CLIs](/cli/)
        * [Instalacion con Node o con yarn](/cli/node/)
        * [Python que seria con pip](/cli/python/)
    * [Lenguages de programacion](/len/)
        * [Lenguage de C# o Csharp](/len/cs)
        * [Python en el que tiene especificaciones](/len/python)
        * [Nodejs lo mismo que con python](/len/nodejs)
        * [Scala tutorial en los docs](/len/scala)
        * [Clojure nuevo](/len/clojure)

---

## — Introduccion

HostHome es una arganizacion para poder hacer hosting gratis para todo el mundo con caracteristicas que otras companias de hosting no tiene. A la hora de crearse un hosting los clientes siempre nos recomiendan gracias a la gran facilidad de configuracion y arranque y por los tutoriales por video que le enseñamos a la gente.

Lo que solemos hacer por aqui es mejorar nuestras habilidades y con eso poder mejorar esta empresa gracias a los usuarios que hacen lo siguiente dependiendo de donde venga el error ya que puede estar en nuestro documentos, la pagina web o incluso nuestros CLIs y siempre estaremos en agradecimiento con esos usuarios.

   1. Lo reportan en nuetro [GitHub](https://github.com/HostHome-of)
   2. Siempre instentan crear un nuevo issue o pueden hacer un pull request tambien en nuestro `GitHub`

## — Nuestros CLIs

Como muchos usuarios se pregunataran es de donde pueden instalarse los CLIs ya que hay 2 formas de instalarlos pero con administradores de paquetes diferentes tanto como en el lenguage y el uso. Cuando nos referimos al uso significa que por ejemplo con el de `pip` para abrir el comando de ayuda no hay que ponerlo con nada, pero con el de node se puede ver esa pantalla de ayuda como en el de `node` en el que tienes que meter la bandera `-h` o tambien se puede poner `--help`. Otra diferencia seria por ejemplo que con el de `pip` para eliminar un host puedes hacer `hosthome eliminar` pero para el de `node` puedes poner (La unica eleccion) `hosthome --eliminar` pero no tiene ninguna acortacion.

En esta pequeña introduccion de los CLIs.

* Si alguien quiere instalarselo con `node` porque quiere/puede que sea mas facil puede ir a esta [pagina](/cli/node)
* Por si alguien no le gusta el de node **siempre** puede hacerlo con el de [pip](/cli/pip)
* Ademas en la documentacion de node tambien enseñamos como instalarselo con yarn ya que con yarn es mas seguro y rapido.

## — Metodos de pago

Por defecto hosthome no requiere tener ningun metodo de pago pero hay una cosa mala. La cosa mala es que al llegar a los 2 hosts HostHome ya no te dejara crearte mas hosts *pero* si te compras un plan mejor puedes llegar a tener mas hosts o incluso poder tener asta hostings limitados.

## — .hosthome

La gente piensa que no hay que tocar el archivo de **.hosthome** ya que abajo hay un texto que dice en (palabras resumidas) `No tocar sino contactar y mirar licencia`, En general es recomendable no tocar el archivo porque puedes hacer que algo no falle ya que puedes rellenar algo con un "misspell".

El ejemplo de un archivo **.hosthome**

```python
run = "Tu comando de arranque"
len = "lenguage de programacion"

----- ADVERTENCIA
...
```

#### Estructura

Como puedes ver el archivo es bastante simple con dos variables `run` y `len`. El lenguage de programacion solo sirve para algunos especificos en el que el CLI lo rellenara por ti (que es lo mejorable). En el index siempre puedes ver el lenguage que estan validados. 

Si quieres ver los lenguages oviamente enstan en el index, si quieres saver como instalar un CLi *tambien* puedes verlo en el index de ariba. Las variables siempre tienen que estar redondeadas por " no por ', si no la maquina es bugeara y tu host sera eliminado, tu seras baneado de la web por una semana. Nuestra inteligencia artificial podra verlo.

## — Redes sociales y contribuicion

* 🏢 Nuestro [github](https://github.com/HostHome-of/)
* 💪 Ayudanos a mejorar
    * 🐛 Encontrar [bugs](https://github.com/HostHome-of/Documentacion/issues/new)
    * 🆙 Mejorar [docs](https://github.com/HostHome-of/Documentacion/compare?expand=1)
* 👑 Creador [maubg-debug](https://github.com/maubg-debug)

## — Licencia

* HostHome esta bajo la licencia de [GNU](https://github.com/HostHome-of/website/blob/main/LICENSE.md)
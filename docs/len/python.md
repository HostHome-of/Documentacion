<style>
.md-footer-copyright #text {
    display: none
}

.md-footer-copyright .md-footer-copyright__highlight #text {
    display: block
}
</style>

# Como empezar

Lo primero oviamente sera como crearse un proyecto nuevo ya que sin projecto bueno... No haces nada. Si quieres hostear con python deberas tener un archivo llamado `requirements.txt` por si quieres instalarte alguna dependencia.

## Crearse un archivo

Esto es bastante simple. Simplemente te tienes que crear un archivo o los que necesites que sean de python (No tienen que terminar con `.py` p `.pym`), porque cuando te vas a crear un nuevo proyecto tienes que especificar como sera el archicvo de arranque como podras ver en el CLI de node o de pypi en el que estan tambien documentados en esta pagina.

## Dependencias (Opcional)

En HostHome hemos visto toda clase de gente que se equivoca a la hora de poner dependencias en su hosting como por ejemplo se crear un `setup.py` pero eso esta `MAL`. Para tener unas dependencias tendras que crearte un archivo llamado `requirements.txt` o simplemente ejecutando este comando.

```
nano requirements.txt
```

Dentro de ese requirements.txt podras poner todas tus dependencias y asi seria un ejemplo de un archivo `requirements.txt`

Requirements.txt (Ejemplo)

```
appnope==0.1.0
backcall
```

Esto es necesario ya que sin el y tu programa necesita dependencias fallara
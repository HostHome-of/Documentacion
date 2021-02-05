
# CLI | Node

## Instalacion

Puedes instalartelo con [npm](https://www.npmjs.com/package/@maubg/hosthome-cli) or you can install it with [yarn](https://yarnpkg.com/package/@maubg/hosthome-cli)

### Node - instalacion

```
C:\> npm i -g @maubg/hosthome-cli
 (( □□□□□□□... )) Recieven package ...
```

Notar como le ponemos la bandera **-g** esto es muy importante ya que si no le ponermos esa bandera el CLI sera reconocido como un "package" o como un modulo y no queremos eso. Entoces hay que hacerlo *global*

Tambien se puede cambiar el `npm i` por el `npm install` ya que el comando es exactamente igual. Tambien abria que dejar el `@maubg/` porque si no npm no encontrara el modulo y no lo instalara como un CLI.

![CLI-Node](https://raw.githubusercontent.com/HostHome-of/website/main/src/static/images/cli.png)

### Yarn - instalacion

Una opcion preferiblemente mejor es instalarlo con [yarn](https://yarnpkg.com/package/@maubg/hosthome-cli) ya que yarn hace una instalacion mas rapida.

```
C:\> yarn global add @maubg/hosthome-cli
 [ ############################............... ] Reciebing package ...
```

En este comando podemos ver de que le ponemos `global` por la misma razon a la que le ponermos una bandera (**-g**) para que se instale global mente.

Yarn a dejado de utilizar el comando `install` y lo a remplazado por el comando `add` eso hay que tenerlo en cuenta para que nuestra instalacion de el CLI de yarn funcione.

![CLI-Node](https://raw.githubusercontent.com/HostHome-of/website/main/src/static/images/cli-yarn.png)
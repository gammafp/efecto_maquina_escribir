# Efecto máquina de escribir

[DEMO](https://gammafp.github.io/efecto_maquina_escribir/)

Un pequeño script que ayuda a crear un efecto de máquina de escribir

El script se llama ```maquina.js```
se enlaza y para usarlo se puede hacer lo siguiente: 

En el HTML: 

```
<div id="maquina"></div>
```
 ```
         const configM = {
            id: "maquina", // Id del elemento contenedor
            texto: "Hola. Bienvenido :D" // Texto que se ejecutará
        }

        const iniciar = new MaquinaEscribir(configM);
        iniciar.iniciarMaquina();
 ```
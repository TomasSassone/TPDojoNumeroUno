# Ejemplo Documentación Dojos
![Tinkercad](./img/ArduinoTinkercad.jpg)


## Integrantes 
- Tomás Sassone
- Martín Simone
- Federico Rossello
- Maria Schiaffino
- Matías Villalba


## Proyecto: Contador binario.
![Tinkercad](./img/ContadorBinario.png)


## Descripción
El gobierno de la ciudad quiere actualizar los semáforos que tiene instalados. La empresa  “UTNFRA Robotics” ganó la licitación y ahora les toca a los desarrolladores de la empresa generar  un proyecto low cost que cumpla con las especificaciones que el gobierno de la ciudad nos  impone, a saber las especificaciones son las siguientes.

**Primer consigna:**
1- El semáforo tiene que tener 2 leds de cada color como mínimo, en caso de que uno se  rompa. 
2- Tiene que implementar los tiempos correctos como se detallan a continuación. 3- El verde dura 5 segundos. 
4- El amarillo dura 3 segundos. 
5- Rojo dura 5 segundos. 
6- Tiene que tener señalización para personas no videntes como se detalla a  continuación. (Buzzer o piezo)
7- Durante el rojo: Tiene que sonar 2 vez por segundo en un tono FUERTE. 


## Función principal
Esta funcion se encarga de encender y apagar los leds.

B0, B1, B2, B3 son #define que utilizamos para agregar los leds, asociandolo a pines de la placa arduino.

(Breve explicación de la función)

~~~ C (lenguaje en el que esta escrito)
void EncenderBinario(int estado3, int estado2,int estado1,int estado0)
{
  digitalWrite(B3,estado3);
  digitalWrite(B2,estado2);
  digitalWrite(B1,estado1);
  digitalWrite(B0,estado0);
}
~~~

## :robot: Link al proyecto
- [proyecto](https://www.tinkercad.com/things/aOYiibnDjWu)

---
### Fuentes
- [Consejos para documentar](https://www.sohamkamani.com/how-to-write-good-documentation/#architecture-documentation).

- [Lenguaje Markdown](https://markdown.es/sintaxis-markdown/#linkauto).

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

- [Tutorial](https://www.youtube.com/watch?v=oxaH9CFpeEE).

- [Emojis](https://gist.github.com/rxaviers/7360908).

---







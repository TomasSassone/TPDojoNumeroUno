# Trabajo práctico grupal Dojos - Primer consigna
![Tinkercad](./img/ArduinoTinkercad.jpg)


## Integrantes 
- Martín Simone
- Federico Rossello
- Maria Schiaffino
- Matías Villalba
- Tomás Sassone

## Proyecto: Contador binario.
![image](https://user-images.githubusercontent.com/72427373/234022612-30f17132-d89a-46d8-ab93-b0dc16d35ca2.png)


## Descripción
El gobierno de la ciudad quiere actualizar los semáforos que tiene instalados. La empresa  “UTNFRA Robotics” ganó la licitación y ahora les toca a los desarrolladores de la empresa generar  un proyecto low cost que cumpla con las especificaciones que el gobierno de la ciudad nos  impone, a saber las especificaciones son las siguientes.

**Primer consigna:**
1. El semáforo tiene que tener 2 leds de cada color como mínimo, en caso de que uno se rompa. 
2. Tiene que implementar los tiempos correctos como se detallan a continuación. 
4- El verde dura 5 segundos. 
4. El amarillo dura 3 segundos. 
5. Rojo dura 5 segundos. 
6. Tiene que tener señalización para personas no videntes como se detalla a  continuación. (Buzzer o piezo)
7. Durante el rojo: Tiene que sonar 2 vez por segundo en un tono FUERTE. 


## Función principal
La función empieza encendiendo el LED rojo por 5 segundos, al mismo tiempo que hace sonar el Buzzer con intervalos de medio segundo por la misma cantidad de tiempo. Luego ambos se apagan para encenderse el LED amarillo por 3 segundos, y por último éste se apaga y se enciende el LED verde por otros 5 segundos, cuando el LED verde se apaga, la función vuelve a comenzar.

~~~ C (lenguaje en el que esta escrito)
void loop()
{
  Serial.println("Inicia la funcion");
  Serial.println("Se enciende el semaforo rojo y se ejecuta la funcion 'titilar_buzzer'");
  prender(LEDROJ);
  titilarBuzzer(5);
  //delay(5000);
  apagar(LEDROJ);
  Serial.println("Se apaga el buzzer y el led rojo y se enciende el amarillo");               
  prender(LEDAMA);
  delay(3000);
  apagar(LEDAMA);
  Serial.println("Se apaga el led amarillo y se enciende el verde");               
  prender(LEDVER);
  delay(5000);
  apagar(LEDVER);
  Serial.println("Termina la funcion");               
}
~~~
### Link a los proyectos individuales:
- **Código Simone**: https://www.tinkercad.com/things/59JFMMUNXJy-smashing-hango-elzing/editel?sharecode=RyhmHt8iyIxD6rXJl_Qejh3F6JswjkwmnDtfDBG48AQ
- **Código Rossello**: https://www.tinkercad.com/things/apowO6ruCgk-ingenious-turing-bojo/editel?sharecode=BHMXS_B8_SMPxHeZN1rOwnd0Dvywdt7wrqlUDBAfrkk
- **Código Schiaffino**: https://www.tinkercad.com/things/10qGufkSAB1-brilliant-densor/editel?sharecode=oEnLGT-2U7SThnIi5KY-WkN-3ZVpxC7Ybp-m8PfOIUA
- **Código Villalba**: https://www.tinkercad.com/things/lNCvABa1HKT-copy-of-matias-villalba-ejercicio-2-4-div-d/editel?sharecode=EJFfDO2ZyNUy4bPHWqmhLceneGhBtowOyD50hmNN1Sg
- **Código Sassone**: https://www.tinkercad.com/things/5eB6TfLInHc-ingenious-kup-wolt/editel?sharecode=g73MXUOwZ1ez2ICqHsApRXK4MoKPoOfsh-24o9ul6yE

## :robot: Link al proyecto
- [Proyecto](https://www.tinkercad.com/things/5eB6TfLInHc-ingenious-kup-wolt/editel?sharecode=g73MXUOwZ1ez2ICqHsApRXK4MoKPoOfsh-24o9ul6yE)

---
### Fuentes
- [Consejos para documentar](https://www.sohamkamani.com/how-to-write-good-documentation/#architecture-documentation).

- [Lenguaje Markdown](https://markdown.es/sintaxis-markdown/#linkauto).

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

- [Tutorial](https://www.youtube.com/watch?v=oxaH9CFpeEE).

- [Emojis](https://gist.github.com/rxaviers/7360908).

---







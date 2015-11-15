# Grado de Ingeniería Informática

## Práctica 7: Diseño Adaptativo, Despliegue en Heroku, Mejoras

<p align="Center">
    <img src="http://aqrateinfotech.com/Quizz/image/quiz.png" title="Quiz." width="300" height="150">
</p>

---
#### *Descripción de la Práctica:*

    + Añada a la práctica anterior del Quiz:

        + Diseño adaptativo (véase CSS adaptable a móviles en YouTube)
        + Despliegue en Heroku (véase Despliegue en Heroku en YouTube)
        + Defina una clase Respuesta cuyo constructor admita como argumento:
            + Una función
            + Una expresión regular regexp (el constructor lo convierte internamente a formato función así: function(x) { return x.match(regexp); })
            + Una cadena string o un número number (el constructor lo convierte a formato función así: function(x) { return x === 'string'; } o bien function(x) { return x === number; })
            + Un objeto Respuesta es siempre una función que recibe un argumento con la respuesta escrita por el alumno y retorna true si y sólo si la respuesta es correcta.
            + Añada una clase Pregunta de la que heredan PreguntaCorta (que se representa en la vista mediante un input) y PreguntaLarga (que se representará mediante una textarea).



> [*Enlace a la página personal*](http://alu0100498820.github.io "*Enlace a la página personal*")

---

> [*Enlace repositorio*](https://github.com/alu0100498820/P7SYTW "*Enlace repositorio*")

---

> [*Despliegue de la Aplicación en el IAAS*](http://10.6.128.95:8080/ "*Despliegue de la Aplicación en el IAAS*")

---

> [*Despliegue de la Aplicación en el <img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/a9/Heroku_logo.png/220px-Heroku_logo.png"> *](http://10.6.128.95:8080/ "*Despliegue de la Aplicación en el Heroku*")


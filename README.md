# Ejemplo de Microservicio en NodeJS

El archivo App.js contiene el microservicio.

Es necesario efectuar un npm update para actualizar los paquetes.

No se incluyo un .gitIgnore por lo que los paquetes también se suben, no obstante y como aclaración esto no es una buena practica en el mundo real.

Cada Microservicio posee su propio branch. Deberá clonar el branch y trabajar sobre el mismo en su propio repositorio GitHub dado que las Github actions y el manejo de Secrets y variables deberá efectuarlo en su propio repo.

Una vez generados los archivos de IaC, DockerFiles, Actions. Al finalizar el trabajo, deberán subirlos a este repositorio utilizando un nuevo branch con su propio nombre. 

**Mucho cuidado, no subir cambios directo sobre los branches de los microservicios o sobre la rama main.**
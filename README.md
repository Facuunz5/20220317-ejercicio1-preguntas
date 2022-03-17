
Ejercicio 1
===========
Responde en este fichero a las siguientes preguntas: 

1. ¿Cómo se configura el email de manera global en GIT?
Respuesta: Con el comando git config --global user.email "ejemplo@correo.com". 

2. ¿Qué es un Pull Request?
Respuesta: És una petición que se le hace al creador de un repo cuando forqueamos
el mismo, lo modificamos y le solicitamos al propietario que se realicen los cambios 
modificamos. 

3. ¿Para qué sirve HEAD en GIT?
Respuesta: És el puntero, nos indica dónde nos encontramos, en qué rama.

4. ¿En cuántos estados diferentes puede estar un fichero en GIT?
Respuesta: Commiteado, modificado o staged(preparado).

5. ¿Qué número identifica de manera única a cada commit?
Respuesta: El hash que genera ese commit.

6. ¿Cómo retrocederías en los commits para tener el directorio de trabajo como lo tenías hace 3 commits?
Respuesta: Usando git reset --hard HEAD~3

7. ¿Cómo explicarías un conflicto en GIT?
Respuesta: Un conflicto se genera cuando queremos mergear una rama a su 'base' y en
esa misma 'base' se ha creado nuevo contenido, con lo cual hay diferencias de la base de 
la rama y hay que corregir las diferencias.

8. ¿Con qué comando dejaríamos de tener el directorio bajo control de versiones?
Respuesta: sudo rm -rf .git

9. ¿Cómo añadirías la URL de un repositorio remoto?
Respuesta: 

10. ¿Cómo explicarías qué ha ocurrido cuando tras la ejecución de un comando de GIT nos responde: "You are in 'detached HEAD' state"?
Respuesta: Que no nos encontramos en una rama anclada a la base del repo, en una orphan branch. 

# actividad-01
Primera actividad de la clase metodología y gestión de proyectos 
## Ejercicio 0. Creación del proyecto actividad-01 en Github
Link del proyecto creado: [https://github.com/cacarchi/actividad-01/projects/1](https://github.com/cacarchi/actividad-01/projects/1)
![image](https://user-images.githubusercontent.com/84252458/150907974-315f50f4-814d-4e8b-bd7f-4c892adfd98d.png)

## Ejercicio 1. Crear las tareas en el kanban de Github que consideres necesarias para este proyecto. Las tareas se pueden crear a partir de las actividades que hay a continuación.
Link de tareas creadas: [https://github.com/cacarchi/actividad-01/issues](https://github.com/cacarchi/actividad-01/issues)
![image](https://user-images.githubusercontent.com/84252458/150908372-f28f67fb-cd94-4f6f-9c7c-201161f0eb42.png)

## Ejercicio 2. Creación de la rama develop a partir de main
Desde la rama main se crea la rama "develop":
```
git checkout -b develop
```
[Tarea 1](https://github.com/cacarchi/actividad-01/issues/1)

## Ejercicio 3. Creación de la rama feature-1 y añadir la clase A con los atributos: foo bar
Desde la rama develop se crea la rama "feature-1":
```
git checkout -b feature-1
```
Se crea la claseA y se añaden los atributos. Seguido se agregan los cambios:
```
git add .
```
Se commitea el cambio:
```
git commit -m "Añadiendo la clase A y los atributos foo y bar"
```
[Tarea 2](https://github.com/cacarchi/actividad-01/issues/2)

## Ejercicio 4. Mergear feature-1 con develop
Se cambia a la rama "develop":
```
git checkout develop
```
Mergear rama feature-1 con la rama develop:
```
git merge feature-1
```
[Tarea 3](https://github.com/cacarchi/actividad-01/issues/3)

## Ejercicio 5. Mergear develop con main y generar la etiqueta v1.0
Se cambia a la rama "main"
```
git checkout main
```
Mergear rama develop con la rama main:
```
git merge develop
```
Crear etiqueta "v1.0":
```
git tag -a v1.0 -m "version 1.0"
```
[Tarea 4](https://github.com/cacarchi/actividad-01/issues/4)

## Ejercicio 6. Creación de la rama feature-2 y añadir la clase B
Se cambia a la rama "develop"
```
git checkout develop
```
Desde la rama develop se crea la rama "feature-2":
```
git checkout -b feature-2
```
Se crea la claseB. Seguido se agregan los cambios:
```
git add .
```
Se commitea el cambio:
```
git commit -m "Añadiendo la clase B"
```
[Tarea 5](https://github.com/cacarchi/actividad-01/issues/5)

## Ejercicio 7. Creación de la rama feature-3 y añadir la clase C
Se cambia a la rama "develop"
```
git checkout develop
```
Desde la rama develop se crea la rama "feature-3":
```
git checkout -b feature-3
```
Se crea la claseC. Seguido se agregan los cambios:
```
git add .
```
Se commitea el cambio:
```
git commit -m "Añadiendo la clase B"
```
[Tarea 6](https://github.com/cacarchi/actividad-01/issues/6)

## Ejercicio 8. Mergear feature-2 con develop
Se cambia a la rama "develop":
```
git checkout develop
```
Mergear rama feature-2 con la rama develop:
```
git merge feature-2
```
[Tarea 7](https://github.com/cacarchi/actividad-01/issues/7)

## Ejercicio 9. Mergear feature-3 con develop
Se cambia a la rama "develop":
```
git checkout develop
```
Mergear rama feature-3 con la rama develop:
```
git merge feature-3
```
Se resuelven los conflictos:
![ejercicio9_conflictos](https://user-images.githubusercontent.com/84252458/150911066-a2832551-a9fa-42ee-a768-0ada70ed88b5.png)
Se hace commit para guardar los cambios:
```
git commit -m "Se corrigen los conflictos al mergear feature3 con develop"
```
[Tarea 8](https://github.com/cacarchi/actividad-01/issues/8)

## Ejercicio 10. Mergear develop con main y creación de la etiqueta v2.0
Se cambia a la rama "main"
```
git checkout main
```
Mergear rama develop con la rama main:
```
git merge develop
```
Crear etiqueta "v2.0":
```
git tag -a v1.0 -m "version 2.0"
```
[Tarea 9](https://github.com/cacarchi/actividad-01/issues/9)

## Ejercicio 11. Creación de rama hotfix-1 a partir de main y añadir un atributo lorem en clase A
Se cambia a la rama "main"
```
git checkout main
```
Desde la rama main se crea la rama "hotfix-1":
```
git checkout -b hotfix-1
```
Se agrega el atributo lorem a la clase A. Seguido se agregan los cambios:
```
git add .
```
Se commitea el cambio:
```
git commit -m "Se agrega atributo lorem en la rama hotfix-1"
```
[Tarea 10](https://github.com/cacarchi/actividad-01/issues/10)

## Ejercicio 12. Mergear rama hotfix-1 con main y creación de etiqueta v2.1
Se cambia a la rama "main"
```
git checkout main
```
Mergear rama hotfix-1 con la rama main:
```
git merge hotfix-1
```
Crear etiqueta "v2.1":
```
git tag -a v2.1 -m "version 2.1"
```
[Tarea 11](https://github.com/cacarchi/actividad-01/issues/11)

## Subir tags al remoto
Para subir las etiquetas al repositorio remoto:
```
git push --tags
```

## Subir las ramas creadas al remoto
Para subir las ramas creadas al repositorio remoto:
```
git push --set-upstream origin [nombre_rama]
```

## GitFlow
Para revisar el flujo de trabajo clic en el siguiente link: [GitFlow](https://github.com/cacarchi/actividad-01/network)
![image](https://user-images.githubusercontent.com/84252458/150913363-da4e5457-6f68-4d54-ab65-377d27062439.png)

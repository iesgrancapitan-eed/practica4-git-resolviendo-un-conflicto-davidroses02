## 1. Asegúrate de que tienes configurado el editor Visual Studio Code como tu editor de Git. (git config --global core.editor "code --wait")


## 2. Crea un repositorio local y avanza en la rama "master" añadiendo un fichero "index.html" con la estructura básica html. El body estará vacío

![1](img/1.png)

Creo el primer commit -> fichero vacío en el master. Para después avanzar en las dos ramas.

## 3. Crea y salta a "rama-1". Avanza en un commit con tu nombre de pila en un párrafo dentro del body

![2](img/2.png)

![3](img/3.png)

## 4. Vuelve a la rama master

## 5. Crea y salta a "rama-2". Avanza en un commit con tu apellido en un párrafo dentro del body

![4](img/4.png)

## 6. Muestra el estado del repositorio de forma gráfica y resumida

![5](img/5.png)


## 7. Haz un merge a rama-1. Intentas fusionar ambas ramas. Aparecerá un conflicto porque ambos commits trabajan en la misma porción <body></body> de un mismo archivo index.html. Git no será capaz de fusionarlas directamente. 

![6](img/6.png)

## 8. El editor VS Code reconoce los conflictos de fusión. Las diferencias se resaltan y hay acciones en línea para aceptar los cambios. Deja un único párrafo con tu nombre de pila y apellido.

## 9. Una vez que se resuelto el conflicto confirma el archivo en conflicto para que pueda realizar esos cambios

## 10. Muestra de nuevo el estado del repositorio de forma gráfica y resumida

![7](img/7.png)

## 11. Vuelve a la rama master y realiza otro merge. Es una fusión fast-forward. Los dos commits a fusionar tienen relación de ancestro Entonces el merge no produce un commit nuevo, sencillamente avanza la rama, "avance rápido"


## 12. Visualiza las ramas que han sido fusionadas con la rama master

![8](img/8.png)

## 13. Elimina las ramas correctamente fusionadas (sin asterisco) para quedarte SOLO con la rama master. 

![9](img/9.png)

## 14. Realiza una copia a este repositorio remoto

## 15. Recuerda añadir estas instrucciones con los pantallazos en el fichero README.md

## 16. En GitHub entra en Insights/network y visualiza el gráfico del repositorio con los merge y cinco commits 

![10](img/10.png)

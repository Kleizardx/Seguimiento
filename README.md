# Seguimiento
Pagina para seguimiento de tareas

La idea de la pagina es generar un seguimiento de tareas, como bien dice el titulo de la pagina.
El motivo por el cual me decidi por este tipo de pagina, es que trabajo en una empresa de telecomunicaciones, llegan muchas tareas diarias las cuales es dificil realizar un seguimiento exacto.
Espero poder mediante esta WEB poder organizar mejor mi dia, semana, mes.
Seria una especia de ToDo, con la diferencia que a esta tambiens se podra agrega un seguimiento de materiales, pedidos, listado de stock, rendimiento.


Commands de GIT, espero en algun momento saberlos de memoria, para no tener que utilizar el machete.

Comandos.
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Kleizardx/PagSeguimiento.git
git push -u origin main


git remote add origin https://github.com/Kleizardx/PagSeguimiento.git
git branch -M main
git push -u origin main


git init: indicarle que en ESE directorio, donde ejecutamos este comando, será usado con GIT.
git add .: agregar todos los archivos creados, modificados, eliminados al estado 2 (stage)
git commit -m “Mensaje”: mensaje obligatorio para indicar que hemos cambiado por ejemplo, al estado 3.
Git log --oneline: para conocer los códigos de los commits realizados.
Git checkout rama: para cambiar de rama o ir a un commit específico (debemos conocer su código anteriormente) 
git merge rama: debemos estar en MASTER para fusionar.
git branch rama: creación de una rama (si queremos eliminar una rama ponemos git branch -D nombre-rama)

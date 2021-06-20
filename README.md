# Ubunu
Aprendiendo Git y GitHub con sus comandos iniciales, los cuales se muestran a continuación.

git init  # para inicializar git en una carpeta de trabajo apropiada
git add . # para agregar los archivos o carpetas al staging area 
git status # muestra el estado del contenido de la carpeta de trabajo
git status -s # muestra el estado del contenido de forma resumida
git add "mi_carpeta" # tambien se pueden agregar uno por uno, las comillas dobles hacen parte del comando porque es un string que nostros vamos a asignar como nombre o descripción
git commit -m "descripción corta del commit"  # hace una captura de ese repositorio
git log # muestra información referente a los commit y modificaciones realizadas
git log --oneline # muestra información corta.
git branch # muestra el branch en el cual se está trabajando
git branch nombre_nuevo # permite crear una rama nueva el cual tendrá el nombre asignado nombre_nuevo
git branch switch nombre_nuevo # permite cambiar a una rama libre
git remote add nombre_remoto_nuevo URL_del_respositorio_a_usar # permite agregar desde consola git nuestro repositorio local al servidor en la nuebe de GitHub, en este punto aún el contenido no es visible.
git remote -v # permite visualizar las creaciones remotas activas
git remote remove nombre_remoto_nuevo # elimina el repositorio remoto que se especifique, también puede usar rm en vez de remove.
git push -u nombre_remoto_nuevo nombre_del_branch # este envía a nuestro repositorio remoto el contenido que se encuentra en nuestro repositorio local.


Ing. Jormer Bermúdez Quintero

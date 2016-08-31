##Tarea 2
##Luis Trinidad Ortiz Cisneros
##Uso de comando *git rebase* 

 La primer cosa que hay que entender es que el comando *git rebase* resuelve el mismo problema que el comando *git merge*. Ambos comandos están diseñados para integrar cambios de una rama a otra, pero lo hacen en diferentes maneras.<-

 Como una alternativa a *git merge*, se puede usar el comando *git rebase* que incorpora la rama paralela al proyecto a la punta de la rama master, incorporando efectivamente todos los commits nuevos. Pero contrario a *merge*, *rebase* reescribe la historia del proyecto al crear nuevos commits por cada commit en la rama original

 El mayor beneficio de *rebase* es que se obtiene un historial de proyecto más limpio, pero reescribir la historia de un proyecto puede ser potencialmente catastrófico para el flujo de trabajo colaborativo. Y menos importante, *rebase* hace que se pierda el contexto provisto por el comando *merge*

 Por último, el comando *git rebase* nos sirve en una *pull request* pues de ser aceptada la petición, ordenará en una línea temporal todos los nodos hasta el nuestro, aunque esto debe hacerse con mucha precaución tanto del que envía la petición como del que la acepta.

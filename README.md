Primero que nada buenos dias
1- Lo que yo hice es guardar en el localStorage las tareas, tareas es un objeto que lleva id, {task:str, isCheck:bool} de eso el resto de los resto de los componentes agarran y leen
2- Todo los boton check y eliminar estan separados en componentes, tasklist es una tabla que invoca a estos botones, el boton añadir no esta separado, esta directemente dentro de taskinput
Para reflejas los cambios utilizo useState y useEffect(este guarda los cambios el el localstorage)
3- Aprendi a utilizar react-route-dom de aqui https://www.youtube.com/watch?v=xE7TBCR6cj0, el video esta casi obsoleto ya que switch ya no existe y en su lugar debe usarse routes pero casi lo mismo es

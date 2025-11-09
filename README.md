# Primero que nada, buenos días

1. Lo que yo hice es guardar en el **localStorage** las tareas.  
   `tareas` es un objeto que lleva `id`, `{ task: string, isCheck: boolean }`.  
   De eso, el resto de los componentes agarran y leen.

2. Todos los botones **check** y **eliminar** están separados en componentes.  
   `TaskList` es una tabla que invoca a estos botones.  
   El botón **añadir** no está separado, está directamente dentro de `TaskInput`.  
   Para reflejar los cambios utilizo **useState** y **useEffect** (este guarda los cambios en el localStorage).

3. Aprendí a utilizar **react-router-dom** de aquí:  
   [https://www.youtube.com/watch?v=xE7TBCR6cj0](https://www.youtube.com/watch?v=xE7TBCR6cj0)  
   El video está casi obsoleto, ya que `Switch` ya no existe y en su lugar debe usarse `Routes`, pero es casi lo mismo.

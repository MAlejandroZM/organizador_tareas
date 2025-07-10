# 📝 Gestor de Tareas en Java (Swing)

Este proyecto es una **aplicación de escritorio** hecha en Java utilizando **Swing** que permite gestionar tareas con diferentes niveles de prioridad, notas personalizadas, y estado de finalización. Las tareas pueden ser guardadas y cargadas desde un archivo de texto (`tareas.txt`).

Características

- Agregar tareas con:
  - Nombre
  - Prioridad (Alta, Media o Baja)
  - Nota personalizada
- Marcar tareas como completadas
- Eliminar tareas existentes
- Visualizar estado y prioridad con estilos personalizados
- Guardar tareas en archivo `.txt`
- Cargar tareas previamente guardadas

Tecnologías Usadas

- Java SE 8 o superior
- Swing (para la interfaz gráfica)
- Clases estándar de Java (`ArrayList`, `JList`, `JPanel`, `JOptionPane`, `File`, `Scanner`, etc.)

 Interfaz de Usuario

- Lista visual de tareas con colores por prioridad:
  - 🔴 Alta: Rojo
  - 🟠 Media: Naranja
  - 🟢 Baja: Verde
- Las tareas completadas se muestran con un color distinto
- Al hacer clic sobre una tarea, se muestra su nota


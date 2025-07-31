# Tareas Diarias

Este proyecto es un **lista** construido con React Native y Expo, pensado para seguir un orden en las tareas diarias






## Estructura del proyecto
task-mvp/
├─ App.js

├─ app.json

├─ package.json

├─ node_modules/

├─ assets/

├─ navigation/

│  └─ AppNavigator.jsx

├─ screens/

│  ├─ TaskListScreen.jsx

│  └─ AddTaskScreen.jsx

└─ components/

   └─ TaskItem.jsx


- App.js: Punto de entrada. Importa y renderiza AppNavigator.

- navigation/AppNavigator.js: Stack de pantallas (Lista y Crear tarea).

- screens/

-- TaskListScreen.js: Muestra el listado de tareas.

-- AddTaskScreen.js: Formulario para agregar nuevas tareas.

-- components/TaskItem.js: Componente para renderizar cada tarea.

## Como ejecutar la app?

-- npm start

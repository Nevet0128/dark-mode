## Cómo usar

1. Añadir **data-Dark** como atributo a las etiquetas que se deseen cambiar de fondo y letra.

2. Añadir un botón con el id **darkMode-btn**.

- En la sección de estilos añadir :

  ```css
  #darkMode-btn {
  }
  #darkMode-btn:hover {
  }
  ```

- Dar el formato que se deseé.

3. Para aplicar el _dark mode_, añadir en la sección de estilos :

   ```css
   .darkMode-Theme {
   }
   ```

- Cambiar el fondo y color de fuente que se deseé.

4. Integrar el archivo **_dark_mode.js_** al documento.

- En este archivo se encuentran los emojis ☀️ y 🌙. Al momento de integrar por primera vez el contenido del botón añadirá ☀️ haciendo referencia al **_light mode_**. Al presionar el botón cambiará el emoji a 🌙 y el fondo y color de letra que previamente se debió de configurar al **_dark mode_**.

Esta configuración se guarda dentro del navegador del usuario.

# Mongoose Plugin ToJSON

Este plugin de Mongoose proporciona una funcionalidad adicional para convertir los documentos de Mongoose en objetos JSON.

## Instalación

Puedes instalar el plugin utilizando npm:
1. Abre una terminal en la carpeta raíz de tu proyecto.
2. Ejecuta el siguiente comando para instalar el plugin:

    ```bash
    npm install mongoose-plugin-tojson
    ```

3. Una vez instalado, puedes importar el plugin en tu archivo de configuración de Mongoose y utilizarlo en tus modelos.

    ```javascript
    const mongoose = require('mongoose');
    const toJSONPlugin = require('mongoose-plugin-tojson');

    // ...

    // Aplica el plugin a tu esquema de Mongoose
    schema.plugin(toJSONPlugin);

    // ...
    ```

¡Y eso es todo! Ahora tus documentos de Mongoose se podrán convertir fácilmente en objetos JSON utilizando el método `toJSON()`.

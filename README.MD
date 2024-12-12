### Contenedor php que implementa SAP NetWeaver SDK
- Ingresar datos de sistema SAP en el archivo ./src/env.php
- Ejecutar ```docker compose up```
- Ingresar por navegador
- Presionar botón "Conectar"
- Si la conexión fue exitosa retornara un valor parecido al siguiente  
    ```
    Conectado
    Resultado de funcion STFC_CHANGINGarray(2) { ["COUNTER"]=> int(2) ["RESULT"]=> int(1) }
    ```
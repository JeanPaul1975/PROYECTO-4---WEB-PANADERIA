# Configuración del VSC con Live Sass Compiler

1. instalar el LIve Sass Compiler
2. segundo tener una estructura básica de "assets", donde dentro tenga una carpeta "scss"
3. En VSC voy a: rueda de VSC/configuración/editar en settings.json
4. Se abre una pestaña
5. En esa pestaña pegar este código
6. En el json se incluye este código

```bash
    "liveSassCompile.settings.formats":[    
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "~../css"
        },
        {
            "format": "compressed",
            "extensionName": ".min.css",
            "savePath": "~../css"
        }
    ],

'''



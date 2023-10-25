# Creación de Estructura en el Registro de Windows para Siemens PLM Software

Este script de shell crea una estructura en el Registro de Windows para configurar Siemens PLM Software. Puede ser útil para la gestión de servidores de licencias y configuración de paquetes.

## Configuración

Antes de ejecutar el script, asegúrate de configurar las siguientes variables:

- `RegistroBase`: La clave base en el Registro de Windows donde se almacenarán los valores.
- `NombreServidor`: El nombre del servidor de licencias.
- `Puerto`: El puerto para el servidor de licencias.
- `IDBundle`: Los paquetes por defecto separados por punto y coma.

## Uso

1. Ejecuta el script proporcionando los valores necesarios.
2. El script creará la estructura en el Registro de Windows con la configuración deseada.

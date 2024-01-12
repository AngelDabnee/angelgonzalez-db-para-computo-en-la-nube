# Reporte Técnico: Instalación de MongoDB como Sistema Gestor de Bases de Datos NoSQL
# Presentación de MongoDb Atlas. 
Esta sección la tenemos dentro de imagenes con capturas de pantalla referente a la instalación. 
## 1. Justificación de la Selección del Servidor:

MongoDB ha sido seleccionado como el sistema gestor de bases de datos NoSQL para esta instalación debido a las siguientes razones:

- **Flexibilidad en el Esquema de Datos:** MongoDB permite el almacenamiento de datos no estructurados o semi-estructurados, lo que lo hace adecuado para aplicaciones con requisitos de esquema dinámico.

- **Escalabilidad Horizontal:** MongoDB es capaz de escalar horizontalmente, distribuyendo datos a través de múltiples servidores para manejar grandes volúmenes de información y tráfico.

- **Comunidad Activa:** MongoDB cuenta con una comunidad activa de desarrolladores y una amplia documentación, lo que facilita el soporte y la resolución de problemas.

## 2. Descripción del Proceso de Instalación:

### Paso 1: Descarga de MongoDB

Accede al [sitio oficial de MongoDB](https://www.mongodb.com/try/download/community) y descarga la versión de la comunidad compatible con tu sistema operativo.

### Paso 2: Instalación en Windows

1. Ejecuta el instalador descargado.
2. Sigue las instrucciones del asistente de instalación.
3. Asegúrate de seleccionar la opción "Install MongoDB as a Service" para la ejecución automática con el sistema.

### Paso 3: Instalación en Linux

1. Utiliza los comandos del sistema de gestión de paquetes de tu distribución (apt para Ubuntu, yum para CentOS).

```bash
# Ubuntu
sudo apt-get update
sudo apt-get install -y mongodb

# CentOS
sudo yum install -y mongodb-org

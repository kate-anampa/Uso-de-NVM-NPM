

# Instalación y Uso de NVM y NPM


## Instalación de NVM 

1. Descargar e instalar https://github.com/coreybutler/nvm-windows/releases/download/1.1.12/nvm-setup.exe
2. Abril terminal
3. Verificamos la instalacion ejecutando
 ```sh
    nvm --v
 ```
4. Luego instalamos la version 20.14.0
 ```sh
    nvm install 20.14.0
 ```
5. Instalamos 3 versiones mas y usamos la version

 ```sh
    nvm use 20.14.0
 ```

## Importancia de NVM

- **Flexibilidad:** Permite a los desarrolladores alternar entre diferentes versiones de Node.js, lo cual es útil para probar aplicaciones en distintos entornos.
- **Compatibilidad:** Facilita la instalación de la versión específica de Node.js requerida por diferentes proyectos sin conflictos.
- **Mantenimiento:** Simplifica el proceso de actualización y gestión de versiones, evitando problemas de compatibilidad entre versiones de Node.js y módulos npm.


## ¿Por que usar utilizar NPM ?

Aunque Node.js LTS (Long Term Support) es estable y recibe soporte a largo plazo, usar NPM junto con NVM ofrece varios beneficios:

- **Múltiples versiones:** NVM permite instalar y cambiar entre múltiples versiones de Node.js, lo que es esencial para desarrollar y mantener proyectos que dependen de diferentes versiones.
- **Ecosistema de paquetes:** NPM proporciona acceso a una vasta colección de módulos y herramientas que facilitan el desarrollo de aplicaciones.
- **Actualizaciones y compatibilidad:** NPM y NVM facilitan mantener tus proyectos actualizados y compatibles con las últimas versiones de Node.js, sin estar limitado a una sola versión LTS.

En resumen, utilizar NVM y NPM juntos proporciona una mayor flexibilidad y control sobre el entorno de desarrollo, lo que resulta en una mejor gestión de dependencias y versiones de Node.js.

# Resumen de Comandos

Inicializar proyecto:
 ```
 npm init 

  ```
Instalar dependencias de producción:
 ```
  npm install <nombre_paquete>
```
Instalar dependencias de desarrollo: 
 ```
npm install <nombre_paquete> --save-dev
 ```
Instalar dependencias globales:
 ```
  npm install -g <nombre_paquete>
 ```

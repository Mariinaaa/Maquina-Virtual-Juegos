# Maquina-Virtual-Marina-y-Cristina
Este proyecto incluye dos programas que implementan una Máquina Virtual Simple para un juego de barcos y una simulación del juego de las Torres de Hanoi. Ambos programas hacen uso de la estructura de datos `Pila` para gestionar los elementos de cada juego.

## Contenido:
- `MaquinaVirtualSimple.js`: Implementa una máquina virtual que carga y ejecuta un programa de instrucciones para un juego de hundir barcos.
- `TorresDeHanoi.js`: Simula el juego de las Torres de Hanoi, donde los discos deben ser movidos de una torre a otra siguiendo ciertas reglas.
- `index.js`: Punto de entrada para seleccionar y ejecutar uno de los dos juegos.
- `README.md`: Descripción del proyecto, instrucciones de instalación y uso.

## Estructura de Datos Usada: Pila
Ambos programas hacen uso de una estructura de datos tipo `Pila` para gestionar elementos de manera eficiente:
- La **pila** permite gestionar la creación y movimiento de barcos en `MaquinaVirtualSimple`.
- En `TorresDeHanoi`, las torres son representadas mediante pilas para simular el apilamiento y movimiento de discos.

## Instrucciones de Instalación:
1. Descarga los archivos.
2. Asegúrate de tener [Node.js](https://nodejs.org/) instalado.
3. Navega a la carpeta y ejecuta el siguiente comando para instalar las dependencias necesarias:
   npm install
4. Y para ejecutarlo se hace desde la terminal poniendo este comando:
   node index.js


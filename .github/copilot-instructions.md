# Feria Andina · instrucciones para agentes de IA

## Stack
- Front: React + TypeScript + Redux Toolkit + Vitest (carpeta /web)
- Back: Node + Express + PostgreSQL (carpeta /api)

## Comandos
- Instalar dependencias: npm install
- Correr tests: npm test
- Revisar estilo: npm run lint

## Convenciones
- TypeScript estricto: no usar `any`.
- Tipado explicito en parametros y valores de retorno de funciones.
- Nombres del dominio, variables y mensajes de error/tests en español: producto, pedido, cooperativa.
- Commits con Conventional Commits (feat:, fix:, docs:, test:).

## No hacer
- No agregar dependencias nuevas sin avisar.
- No leer ni modificar archivos .env.
- No cambiar la estructura de carpetas.
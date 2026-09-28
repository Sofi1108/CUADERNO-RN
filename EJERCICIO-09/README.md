# Ejercicio 09 - Interfaz bancaria

## Qué he aprendido

- Componer una pantalla compleja.
- Detectar repetición.
- Crear componentes mantenibles.

## Respuesta a la pregunta de comprensión

Convertiría el saldo, las acciones y cada movimiento en componentes si se reutilizan. La cabecera puede quedarse en `App` porque es específica de esta pantalla. Los movimientos deben usar un componente porque comparten estructura y solo cambian sus datos.

## Qué he modificado

- He añadido tres acciones rápidas: Enviar, Ingresar y Pagar.

## Resultado

La pantalla muestra el saludo, el saldo, acciones rápidas y cuatro movimientos creados mediante un componente reutilizable.

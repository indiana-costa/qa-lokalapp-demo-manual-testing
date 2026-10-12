# Plan de Pruebas — Lokal App (Hamburguesería)

## 1. Objetivo

Verificar el funcionamiento de las principales funcionalidades de la aplicación Lokal App para una hamburguesería, identificando posibles errores y validando que los comportamientos observados sean coherentes con los resultados esperados.

## 2. Alcance de las pruebas

Las pruebas incluyen las siguientes funcionalidades:

- Agregar y eliminar productos del carrito.
- Modificar la cantidad de productos.
- Validar precios y totales.
- Personalizar productos mediante ingredientes extras y exclusión de ingredientes.
- Agregar acompañamientos.
- Completar y validar los datos del cliente.
- Seleccionar las modalidades de envío a domicilio y retiro en tienda.
- Verificar las tarifas y los totales según la modalidad seleccionada.
- Revisar la información del pedido y las observaciones.
- Verificar la generación del mensaje del pedido para WhatsApp.

## 3. Fuera del alcance

- Pruebas de rendimiento y carga.
- Pruebas de seguridad.
- Pruebas de compatibilidad con múltiples navegadores y dispositivos.
- Validación del procesamiento real de pagos.
- Validación de la recepción del pedido por parte de la hamburguesería.

## 4. Ambiente de pruebas

- **Aplicación:** Lokal App — demo de hamburguesería.
- **URL:** https://lokalapp.com.ar/demo
- **Sistema operativo:** Windows.
- **Navegador:** Google Chrome.
- **Tipo de pruebas:** pruebas funcionales manuales.
- **Herramientas de documentación:** Microsoft Excel.
- **Evidencias:** capturas de pantalla de los resultados relevantes, cuando estén disponibles.

## 5. Enfoque de pruebas

Se realizarán pruebas funcionales manuales, siguiendo los casos de prueba definidos en la planilla.

Se contemplan:

- Pruebas positivas: verificar el funcionamiento esperado de las funcionalidades.
- Pruebas negativas: verificar las validaciones de campos obligatorios.
- Pruebas de integración del flujo: verificar la coherencia de los datos entre el carrito, el resumen del pedido y el mensaje preparado para WhatsApp.
- Pruebas de cálculo: comparar los importes mostrados con los valores esperados.

## 6. Criterios de entrada

- La aplicación de demostración debe estar accesible.
- Las funcionalidades incluidas en el alcance deben estar disponibles.
- Los casos de prueba deben estar documentados.

## 7. Criterios de salida

- Los casos de prueba planificados deben ejecutarse o quedar documentados como pendientes o bloqueados.
- Los resultados deben registrarse en la planilla.
- Las diferencias entre el resultado esperado y el obtenido deben documentarse.
- Las observaciones relevantes deben registrarse en el informe de pruebas.

## 8. Gestión de incidencias y observaciones

Los comportamientos que no coincidan con un requisito conocido se documentarán como posibles defectos.

Cuando no exista un requisito que permita determinar si un comportamiento es incorrecto, se registrará como observación para su análisis, sin clasificarlo automáticamente como defecto.

## 9. Entregables

- Plan de pruebas.
- Planilla de casos de prueba.
- Informe de ejecución de pruebas.
- Evidencias relevantes de la ejecución, cuando estén disponibles.

## 10. Riesgos y limitaciones

La aplicación utilizada es una demo y no se dispone de una especificación formal de requisitos. Por este motivo, algunos comportamientos se evaluarán según lo observado en la aplicación y se documentarán como observaciones cuando no sea posible confirmar el resultado esperado mediante un requisito.
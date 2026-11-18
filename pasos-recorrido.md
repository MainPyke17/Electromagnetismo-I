# Recorrido del flujo principal — https://mdw.unkcode.com

Video: <PEGAR ENLACE DE GOOGLE DRIVE>

Rol: **Cliente (compra sin cuenta)**. No hace falta registrarse.

1. **Inicio** (`https://mdw.unkcode.com/`): ver el catálogo y bajar hasta "Con stock para entregar".
2. **Detalle de producto**: abrir "Absolut Repair Molecular Máscara" (Loreal Professionnel, $ 35.020,00). En "Unidades" escribir **9999** y tocar **Agregar al carrito** (muestra "Agregado al carrito.").
3. **Carrito** (`/carrito`): aparece el producto con 9999 unidades. Tocar **Continuar al checkout**.
4. **Checkout** (`/checkout`): completar Nombre `Ana`, Apellido `Prueba`, Correo `ana.prueba@ejemplo.com`, Teléfono `1155554444`, DNI `30123456`. Entrega: **Retiro en el local**. Pago: **Mercado Pago**. Tocar **Confirmar pedido**.
5. **Caso de error del negocio**: el pedido NO se crea y arriba del formulario aparece el mensaje **"Las unidades deben ser un entero entre 1 y 1000"**.
6. **Carrito**: volver a `/carrito`, cambiar las unidades a **1** y tocar **Actualizar**. Luego **Continuar al checkout**.
7. **Checkout**: completar los mismos datos y tocar **Confirmar pedido**. Aparece **"Tu pedido #N quedó creado, pero todavía no está pagado"**, con la reserva por 15 minutos, el enlace privado de **/seguimiento/...** y los botones **Reintentar el pago** y **Ver mi pedido**.
8. **Vista de teléfono** (ancho 390 px, iPhone 13): Inicio → Producto → Agregar al carrito (1 unidad) → Carrito → Continuar al checkout, mostrando el formulario adaptado a celular.

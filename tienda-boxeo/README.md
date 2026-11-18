# Tienda de boxeo (fastwraps): retomada en noviembre de 2026

Notas de trabajo de la tienda de vendas de boxeo ya preparadas (fastwraps). Va aparte de Mimosa Rituals, que está en la raíz del repositorio.

## Punto de partida (18/11/2026)

- La tienda se abrió hace aproximadamente un año: dominio, proveedores y Klaviyo ya configurados.
- Se dejó justo antes de crear anuncios y empezar a vender.
- Hay **stock propio en casa**: no se usa AutoDS ni dropshipping.
- Objetivo: revisar la tienda entera, cambiar el estilo si hace falta, lanzarla bien y después anunciarla.

## Preguntas por resolver

- [ ] Nombre de la tienda y dominio.
- [ ] Conectar Shopify (y Klaviyo) en el chat para revisarla.
- [ ] Inventario en casa: modelos, tallas, colores y unidades de cada uno.
- [ ] Coste por unidad (lo que se pagó al proveedor).
- [ ] Envíos: empresa (Correos, SEUR, Packlink…), desde dónde, coste real por paquete y embalaje.
- [ ] Mercados: ¿solo España o también otros países?
- [ ] Proveedor: ¿sigue activo para reponer? Plazo y pedido mínimo.
- [ ] Estilo de la tienda: ¿se mantiene el tema actual o se rediseña?

## Lecciones de Mimosa Rituals que aplicar aquí

- **Pedido de prueba completo antes de encender anuncios.** Pago real, notificaciones, preparación y reembolso. En Mimosa el primer pedido (#1001) falló después de lanzar.
- **Teléfono obligatorio en el checkout** desde el principio (las mensajerías lo piden).
- **Una sola versión de envíos en todas partes:** barra superior, ficha, preguntas frecuentes, políticas y tarifas del checkout deben coincidir.
- **Afirmaciones que se puedan sostener:** nada de reseñas o estadísticas inventadas, "más vendidos" con 0 ventas ni precios tachados que nunca existieron (en España el precio de referencia tiene que ser el más bajo de los 30 días anteriores).
- **Datos legales completos:** aviso legal, NIF, teléfono y dirección de contacto, banner de cookies.
- **Klaviyo:** bienvenida con código y carrito abandonado. No activar a la vez las automatizaciones de Shopify (emails duplicados).
- **Comprobar qué tema está publicado** después de cada cambio (en Mimosa se volvió a publicar el antiguo sin querer).
- **Anuncios:** empezar con poco presupuesto y pausar, no borrar, si algo falla.

## Primera revisión de la tienda (18/11/2026)

Tienda: **Vendra** (1xww9u-ci.myshopify.com), plan Basic, EUR, email de contacto soporte@vendra.es.

**Tema**
- Publicado: "Copia de Dawn". Sin publicar: "Dawn" y "Horizon".
- Pendiente: revisar el contenido y el estilo del tema.

**Producto**: uno solo, "Vendas diseñadas para entrenamientos diarios", con 3 fotos.
- Tallas S/M/L. [x] Precio bajado de 30 € a **24,99 €** (18/11).
- [x] Stock puesto a **25 por talla** en Calle Mercedes Formica 1 (18/11). Antes estaba a 0 y la tienda salía agotada.
- [ ] Peso 0 kg en las variantes: poner el peso real (lo usan las etiquetas de envío).
- [ ] Coste por unidad vacío: ponerlo para ver el margen.
- [ ] Título poco claro para Google y anuncios ("Vendas diseñadas para entrenamientos diarios"). SEO sin título ni descripción. Fotos sin texto alternativo.
- [ ] Opción "Tamaño de accesorio": renombrar a "Talla".
- [ ] Comprobar que existe la página /pages/guia-de-tallas.
- [ ] Afirmaciones a confirmar: "lavable a máquina", "acolchado integrado", "velcro reforzado".

**Envíos** (una ubicación: Calle Mercedes Formica 1, Las Rozas).
- España: Estándar 2,99 € (hasta 44,99 €), **gratis desde 45 €** (2 vendas), y Premium 24/48 h a 7 €. [x] Umbral bajado de 60 € a 45 € (18/11).
- [ ] La política dice "gratis a partir de 50 €"; hay que cambiarla a 45 € (texto en `politicas-corregidas.md`, falta pegarlo). Revisar también el tema (barra superior, preguntas frecuentes).
- [x] Baleares quitada de la zona de envío (18/11), como dice la política: solo península.
- [ ] Tarifas sin confirmar con el coste real de la mensajería.

**Legal**
- [x] Aviso legal, privacidad, reembolso (14 días), envíos y términos redactados.
- [ ] NIF "en trámite de alta" en el aviso legal y la privacidad; Número de IVA vacío en Contacto.
- [ ] Términos: dicen "los precios publicados no incluyen impuestos" (en España, a consumidores, los precios deben incluir el IVA) y hacen referencia a legislación de EE. UU.
- [ ] Reembolso: menciona protectores bucales y ropa interior, que no se venden.
- [ ] Dirección: el aviso legal dice "Madrid" y Contacto "Las Rozas de Madrid" (unificar).

**Otros**
- Dominio principal: el de myshopify. [ ] Conectar vendra.es (el correo ya usa ese dominio).
- Pedidos: 1 (#1001, 23/02/2026, reembolsado; probablemente una prueba). 2 clientes.
- Descuentos: ninguno activo.
- Pagos: la política de privacidad menciona MONEI y PayPal. [ ] Comprobar que están activos.
- Klaviyo, Judge.me y GA4/Meta se mencionan en la privacidad, pero no he podido comprobar las apps instaladas (el conector no las muestra).

- [ ] Políticas: el conector no puede editarlas. Cambios listos para pegar en `politicas-corregidas.md`.

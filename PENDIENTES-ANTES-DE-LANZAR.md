# Mimosa Rituals — Pendientes antes de lanzar la tienda

Última revisión: 29 de septiembre de 2026.
Tema a lanzar: **"Copia de LaunchYourStore-Blocky Copy"** (ID 199746945401), ahora sin publicar.
El tema publicado ahora mismo es el antiguo ("LaunchYourStore-Blocky Copy"): **no lanzar con ese**
(muestra "Devoluciones fáciles y gratis", que contradice la política de reembolso).

## 🔴 Comprobar que es cierto (legal / reclamaciones)

- [ ] **"100% Natural – ingredientes de origen vegetal"** (portada, iconos) y pie de página. Gua Sha facial = resina, cepillo facial = silicona, diadema = sintético. Son accesorios, no llevan "ingredientes".
- [ ] **"Apto para veganas" / "Cruelty-Free"**: los cepillos corporales son de "cerdas naturales" (normalmente pelo de jabalí). Confirmar con el proveedor.
- [ ] **"Hecho a mano / artesanal / pequeños lotes"** (portada y pie) vs "preparamos bajo demanda con nuestros proveedores" (mismo bloque).
- [ ] **Etiqueta "OFERTA" y precios tachados** (13 de 17 productos). En España el precio de referencia debe ser el más bajo de los 30 días anteriores. Si nunca se vendió al precio tachado, quitarlo.
- [ ] **Estadísticas "encuesta interna a 150 clientas" (93 %, 88 %, 91 %)** en portada y ficha de producto. La tienda tiene 0 ventas.
- [ ] **Testimonios de Laura M., Marta G. y Sofía R.** (portada y ficha de producto).
- [ ] **5 estrellas + "Valorado por nuestras clientas"** en todos los productos.
- [ ] **"En stock, listo para enviar"**: texto fijo, sale aunque el producto se agote, y choca con "bajo demanda".
- [ ] **Título "Anticelulítico"** en la Tabla de Gua Sha Corporal (promesa de efecto difícil de demostrar).
- [ ] **Reseñas a cambio de un 10 %**: configurar Judge.me para marcarlas como incentivadas.

## 🟠 Envíos (decidir una sola versión y aplicarla en todas partes)

- [ ] **Envío gratis**: la barra superior dice desde 40 €, la tarifa de España desde 55 €, y 40 variantes están en el perfil "AutoDS Free Shipping" (siempre gratis).
- [ ] **Plazos**: "Envío 15-25 días" (portada) vs "Preparamos y enviamos en 1-2 días laborables" (pestaña de la ficha).
- [ ] **Internacional**: "Envío internacional / enviamos a la mayoría de países", pero solo está activo el mercado España.
- [ ] **Stock**: varios productos tienen solo 10 unidades con seguimiento de inventario. Comprobar la sincronización con AutoDS o activar "seguir vendiendo sin stock".
- [ ] **Precinto**: preguntar al proveedor si la esponja konjac, el cepillo facial y el Gua Sha llegan precintados (la excepción de higiene de la política solo se aplica si están precintados).
- [ ] **Devoluciones**: decidir a dónde envía el cliente las devoluciones (el proveedor de AutoDS normalmente no las acepta).

## 🟡 Textos de productos (los puedo corregir yo si me lo pides)

- [ ] Diadema Spa: la descripción dice "Color: rosa (versión de marca)", pero hay 10 colores.
- [ ] Ritual Completo y Spa en Casa: solo se elige el color del Gua Sha. ¿Qué aroma de vela y qué colores de esponja, diadema y cepillo recibe el cliente?
- [ ] Ritual Antiedad: menciona "Cepillo de Cepillado en Seco"; en la tienda se llama "Cepillo de Masaje Corporal SPA".
- [ ] Pie de página: "autocuidado facial", pero la mitad del catálogo es corporal.
- [ ] Pestaña "Detalles del producto": texto genérico igual en todos los productos.
- [ ] Bloque oculto "Devoluciones fáciles y gratis" en la ficha del tema nuevo: no reactivarlo (contradice la política).

## ⚖️ Legal y configuración

- [ ] **Aviso legal**: falta (nombre o razón social, NIF, dirección, datos de registro).
- [ ] **Contacto**: faltan el número de IVA/NIF y el número comercial.
- [ ] **Privacidad**: el texto "llámenos al ," tiene el teléfono vacío.
- [ ] **Términos del servicio**: cambiar los 3 enlaces `https://www.claudeusercontent.com/policies/...` por `https://<tu-dominio>/policies/...` (shipping-policy, refund-policy, privacy-policy).
- [ ] **Condiciones de venta**: opcional (plantilla en `politicas/04-condiciones-de-venta.html`).
- [ ] **Pagos**: activar Shopify Payments o PayPal y hacer un pedido de prueba de principio a fin.
- [ ] **Banner de cookies**: activarlo en Configuración → Privacidad del cliente.
- [x] **Dominio propio**: mimosarituals.com conectado (CDmon).
- [ ] **Notificaciones**: revisar los emails de pedido y envío (en español y con la marca).
- [ ] **Publicar el tema nuevo** (ID 199746945401) cuando todo lo anterior esté revisado.

## 📣 Marketing y apps

- [x] Código `BIENVENIDA10` creado (10 %, un solo uso por cliente, compatible con descuentos de envío).
- [x] Pop-up de bienvenida en el tema nuevo (sección "Pop-up de bienvenida" del pie). Código en `tema/mr-welcome-popup.liquid`.
- [ ] Probar el pop-up en la vista previa: registrarse con un email real y comprobar que aparece el código y que el cliente queda "suscrito" en Clientes.
- [ ] Activar el banner de cookies (Configuración → Privacidad del cliente → Banner de cookies, región UE).
- [x] Klaviyo instalado y conectado. Si algún día usas su pop-up, desactiva el del tema para que no salgan dos.
- [ ] Judge.me: activar la petición de reseñas por email (14-20 días) y marcar como "incentivadas" las del 10 %.
- [ ] Página de seguimiento: comprobar qué app la gestiona (AutoDS, Parcel Panel…) y que funcione.
- [ ] Barra superior: decidir si se mantiene "DEJA TU RESEÑA Y CONSIGUE UN 10%" junto al 10 % de bienvenida (dos ofertas del 10 %).


### Klaviyo (flujos creados en borrador el 30/09/2026)

- [x] Flujo "Mimosa · Bienvenida (código BIENVENIDA10)": se activa al entrar en "Lista de email"; email 1 inmediato con el código y email 2 a los 3 días solo si no ha comprado.
- [x] Flujo "Mimosa · Carrito abandonado": se activa con "Checkout Started"; email 1 a la hora y email 2 a las 24 h; sale del flujo al comprar.
- [x] Dominio de envío send.mimosarituals.com: 6 registros DNS añadidos en CDmon, verificado y activado en Klaviyo (30/09/2026).
- [x] Remitente de los 4 emails: "Mimosa Rituals <hola@mimosarituals.com>". Las respuestas llegan a ecom.am.sl@gmail.com.
- [ ] (Opcional) Crear un buzón real hola@mimosarituals.com (reenvío de correo en CDmon o Google Workspace) y ponerlo como dirección de respuesta.
- [ ] Cambiar también el remitente por defecto de la cuenta en Klaviyo (Configuración → Email) para las campañas futuras.
- [x] Datos de la cuenta en Klaviyo: nombre "Mimosa Rituals" y dirección en España.
- [x] "Lista de email" cambiada a confirmación simple (el código llega al momento).
- [ ] Integración Shopify → Klaviyo: comprobar que los suscriptores de Shopify (pop-up del tema) se sincronizan con "Lista de email".
- [x] Pruebas enviadas y flujos de bienvenida y carrito abandonado ACTIVOS (30/09/2026).
- [ ] No activar a la vez las automatizaciones de Shopify Messaging (se enviarían emails duplicados).

## 📦 AutoDS y proveedores (revisado el 30/09/2026)

- [ ] **Packs sin proveedor**: Ritual Cuerpo, Spa en Casa, Ritual Completo, Piel Radiante, Relax & Calma, Firmeza & Contorno y Antiedad no están en AutoDS; Ritual Facial está como "untracked". Sus pedidos NO se envían solos: hay que pedir cada componente a mano (o crear el pack en AutoDS como producto con varios proveedores).
- [ ] **Variantes sin enlazar**: Gua Sha Facial tiene 18 variantes en Shopify y 16 en AutoDS; Esponja Konjac tiene 6 en Shopify y 7 en AutoDS. Revisar qué variantes no tienen proveedor.
- [ ] **Sin stock en el proveedor**: 4 variantes del Gua Sha Facial, 3 de la Esponja Konjac, 1 de la Vela y 1 del Cepillo Facial tienen stock 0 en AliExpress, pero en Shopify figuran con 10 unidades. Activar la sincronización de stock de AutoDS o buscar otro proveedor.
- [ ] **Poco stock en el proveedor**: Piedra Pómez (3), Cepillo de Cerdas (3), Cepillo SPA (5) y varias variantes con 1-6 unidades.
- [ ] **Tabla de Gua Sha Corporal**: el envío del proveedor (6,32 €) no es gratis y AutoDS lo tiene calculado para EE. UU.; comprobar el coste real a España. Coste total aprox. 13,48 € para un precio de 18,95 €.
- [ ] **Piedra Pómez**: margen de unos 2,40 € antes de comisiones; subir el precio o venderla solo en packs.
- [ ] **Plazo real**: los proveedores indican unos 14 días de transporte más 1-3 días de preparación. Ajustar los textos de la tienda ("1-2 días laborables" vs "15-25 días").
- [ ] **Método de pago en AutoDS**: añadir tarjeta o saldo para que AutoDS pueda comprar al proveedor de forma automática.

## ✅ Ya revisado y coherente

- Devoluciones: 30 días en la política, la ficha, la tabla comparativa y las preguntas frecuentes.
- Políticas de reembolso, envíos y términos: coherentes entre sí; IVA incluido en todas.
- Contenido de cada pack: coincide con los productos.
- Botón de portada: lleva al Gua Sha Facial (precio de entrada 14,95 €).

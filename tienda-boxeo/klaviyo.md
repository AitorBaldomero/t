# Vendra: Klaviyo (revisión del 20/11/2026)

Cuenta "Vendra" (YyT8Yb), remitente soporte@vendra.es. Incrustación de Klaviyo activa en el tema.

## Lo que había
- Pop-up "Ventana emergente de correo electrónico" (Vq2HYR): PUBLICADO. Sale a los 5 s; si se cierra o se envía, no vuelve hasta pasado 1 día; no sale a quien ya se suscribió. Promete "10 % de descuento en tu primer pedido".
- El botón "UNIRSE" añade a la lista **"Lista de correo electrónico" (RGgSdE)**.
- El flujo vivo "Captación de Leads Pop Up" (XVbEnx) se activa con **otra lista: "Pop Up- Captación de emails" (T5Mirz)**. → Nadie del pop-up recibía el código.
- El email del flujo da el código **VENDRA10**, que **no existía en Shopify**.
- Asunto del email: "Email n.º 1 Subject" (texto de plantilla).
- Las dos listas con doble confirmación; la pantalla de gracias del pop-up está en inglés ("THANKS FOR SIGNING UP!").
- Flujo duplicado en borrador "Captación de Lead-Pop Up" (UGBUZL), sin uso.
- Flujo "Carrito Abandonado" (RjB9YD) en vivo.

## Arreglado (20/11)
- [x] Código **VENDRA10** creado en Shopify: 10 %, todos los productos, un uso por cliente, combinable con envío gratis.
- [x] Asunto del email: "Tu 10 % de bienvenida: VENDRA10" + texto de vista previa.
- [x] Listas RGgSdE y T5Mirz en confirmación simple (el código llega al momento).

## Pendiente (en la web de Klaviyo, el conector no puede cambiarlo)
- [ ] Pop-up → botón "UNIRSE" → cambiar la lista a **"Pop Up- Captación de emails"**.
- [ ] Pop-up → paso de gracias: traducir ("¡Gracias por unirte! Revisa tu email: te hemos enviado tu código VENDRA10").
- [ ] (Opcional) archivar el flujo en borrador "Captación de Lead-Pop Up".
- [ ] Prueba: abrir la web en incógnito, registrarse con un email real y comprobar que llega VENDRA10 y que funciona en el checkout.

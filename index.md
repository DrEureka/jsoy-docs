# Política de Privacidad — SJoy

**Última actualización:** 19 de julio de 2026

SJoy es una aplicación de demostración de e-commerce multi-país desarrollada por **Dramadan**. Esta política describe cómo se trata la información en la app.

---

## 1. Alcance de la aplicación

SJoy es una aplicación de **demostración** con fines educativos y de evaluación. No comercializa productos reales, no procesa pagos reales y no envía productos. Los pagos son simulados (95% éxito, 5% fallo aleatorio) y los productos mostrados provienen de APIs públicas de prueba.

---

## 2. Datos que se almacena localmente

Todos los datos del usuario se guardan **únicamente en el dispositivo** mediante Hive CE (almacenamiento local cifrado). **No se envían a servidores propios ni a terceros.** La información almacenada incluye:

- **Datos de cuenta:** nombre, email y hash de contraseña (registro local, nunca se transmite a servidores externos).
- **Direcciones de envío** guardadas por el usuario (datos ficticios o de prueba).
- **Tarjetas de pago** registradas (simulación, no se procesan pagos reales).
- **Historial de órdenes** generadas durante el uso de la app.
- **Lista de deseos y productos vistos recientemente.**
- **Historial de búsquedas.**
- **Preferencias de configuración** (idioma, país, moneda).

**No se solicita, almacena ni transmite** información de salud, ubicación, contactos, identificadores del dispositivo, ni credenciales de redes sociales.

---

## 3. Conexiones de red

La app se conecta a **APIs públicas de productos** para obtener catálogos. Estas conexiones son de solo lectura y no envían datos del usuario:

- **FakeStore API** (`fakestoreapi.com`)
- **DummyJSON** (`dummyjson.com`)
- **Platzi Fake Store** (`api.escuelajs.co`)

Las solicitudes solo incluyen headers técnicos estándar (`Accept`, `Content-Agent`, `User-Agent`). **No se envían datos personales, tokens ni identificadores** a estos servicios.

Las imágenes de productos se cargan desde CDNs asociados a las APIs anteriores mediante `cached_network_image`.

---

## 4. Permisos del sistema

La aplicación **no solicita permisos especiales** al sistema operativo. No accede a:

- Cámara.
- Almacenamiento externo.
- Ubicación.
- Contactos.
- Micrófono.

El único permiso utilizado es **acceso a red** (internet) para cargar catálogos de productos e imágenes.

---

## 5. Servicios de terceros

La app **no integra servicios de analítica, publicidad ni rastreo**. En particular, no usa:

- Google Analytics, Firebase Analytics ni ningún SDK de analítica.
- Redes publicitarias (AdMob, Meta, etc.).
- Pasarelas de pago reales.
- SDKs de redes sociales.
- Servicios de telemetría o crash reporting.

Las únicas conexiones externas son las APIs de productos mencionadas en la sección 3.

---

## 6. Cookies y tecnologías de seguimiento

**No se utilizan cookies, tokens de rastreo, fingerprinting ni tecnologías similares.** La app no contiene componentes web embebidos que pudieran generar cookies de terceros.

---

## 7. Seguridad de los datos locales

- Las contraseñas se almacenan como **hash criptográfico** (no en texto plano).
- Los datos se guardan en el almacenamiento privado de la app (Hive CE), protegido por el sistema operativo.
- Al desinstalar la aplicación, **todos los datos se eliminan permanentemente** del dispositivo.

---

## 8. Menores de edad

La aplicación no está dirigida a menores de 13 años. Dado que no se recopilan datos personales en servidores externos, esta restricción aplica únicamente al uso responsable de la demo.

---

## 9. Cambios a esta política

Cualquier actualización de esta política se publicará en este mismo repositorio con una nueva fecha de "Última actualización". Se recomienda revisarla periódicamente.

---

## 10. Contacto

Si tenés preguntas sobre esta política o sobre la app, podés contactarnos:

- **Desarrollador:** Dramadan
- **Email:** dramadan.dev@gmail.com

---

## 11. Aviso importante

> Esta aplicación es un **prototipo / demo técnica**. No debe usarse como tienda real de comercio electrónico. Los productos, precios, pagos y órdenes son **completamente ficticios o de prueba**. No se realizan transacciones monetarias reales. Cualquier parecido con datos reales es coincidencia.

---

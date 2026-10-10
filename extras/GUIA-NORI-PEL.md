# Guía NORI-PEL: planilla de productos, cartel QR y Google Maps

Link del catálogo: https://leonel03ponce-afk.github.io/CATALOGO-NORI-PEL/

---

## 1. Planilla de productos (cambiar el catálogo sin tocar código)

Planilla: https://docs.google.com/spreadsheets/d/143ymDJawHPQegHPXRa0PLyBRhiOK5JGcDwPaHxwdIhA/edit

### Activarla (una sola vez)

1. **Cargar los productos.** Abrí la planilla, andá a **Archivo → Importar → Subir** y elegí el archivo `planilla-productos.csv` (está en la carpeta `extras` del repositorio).
   - En "Ubicación de importación" elegí **Reemplazar hoja de cálculo**.
   - **Destildá** "Convertir texto en números, fechas y fórmulas".
   - Tocá **Importar datos**.
2. **Compartirla para que la página la pueda leer.** Tocá **Compartir** (arriba a la derecha) → en "Acceso general" elegí **Cualquier persona que tenga el vínculo** → rol **Lector** → **Listo**.
   Así cualquiera puede *ver* la lista de productos (que ya es pública en la página), pero nadie puede modificarla.
3. **Darle permiso al dueño para editar.** En **Compartir**, agregá el email del dueño como **Editor**.

Para comprobar que funciona, abrí el catálogo y bajá hasta el pie de página: tiene que decir **"Lista de productos actualizada ✓"**. Si no aparece, revisá el paso 2.

### Cómo se usa

| Columna | Qué poner |
|---|---|
| **Producto** | El nombre como querés que aparezca. |
| **Foto** | El link directo de la foto. Si la foto está en Google Drive, pegá el link de compartir (tiene que estar compartida con "cualquier persona con el vínculo"). En postimg, usá el "Direct link", el que termina en `.jpg`, `.png` o `.webp`. |
| **Oferta** | `SI` para que aparezca en "Ofertas de la semana". Vacío = no está en oferta. |
| **Categoría** | Vacío = se ubica solo en la sección que corresponde. Si escribís una sección (`Limpieza`, `Bazar`, `Escobas`, `Plásticos`, `Aromatizantes`, `Rollos de cocina`, `Nuestras marcas`, `Otros`), va ahí. Si escribís un nombre nuevo (por ejemplo `Pileta`), se crea una sección nueva con ese nombre. |
| **Mostrar** | `NO` para ocultar un producto sin borrarlo (por ejemplo, si no hay stock). |

- **Agregar un producto:** escribilo en una fila nueva al final.
- **Los cambios aparecen solos** en la página. Puede tardar unos minutos; si no se ve, recargá la página.
- Los productos **sin foto** no aparecen en el catálogo, pero sí cuando alguien los busca.
- Si un día la planilla falla, la página muestra la última lista que cargó bien. Nunca queda vacía.

---

## 2. Cartel con código QR

Archivos en la carpeta `extras`:
- `cartel-qr.pdf`: para imprimir en hoja A4. Conviene a color y en papel grueso, o plastificado.
- `cartel-qr.png`: para mandar por WhatsApp o subir a redes.
- `qr-catalogo.svg`: el QR solo, por si lo querés poner en otro diseño (bolsas, tarjetas, stickers).

El QR abre: https://leonel03ponce-afk.github.io/CATALOGO-NORI-PEL/

Dónde ponerlo: en el mostrador, en la vidriera y en la puerta. Así lo ven también con el local cerrado.

---

## 3. Perfil de Google Maps (Google Business Profile)

Lo tiene que crear **el dueño con su cuenta de Google**, porque Google verifica que el negocio sea suyo. Después puede agregarte como administrador para que lo manejes vos.

### Pasos

1. Entrar a **https://business.google.com** con la cuenta de Google del dueño.
2. Buscar "NORI-PEL". **Si ya aparece en Maps, elegir "Reclamar este negocio"** en vez de crear uno nuevo; si no, crearlo.
3. Completar con los datos de abajo.
4. **Verificar:** Google ofrece video del local, llamada o carta al domicilio. El video suele ser lo más rápido: hay que filmar el cartel de afuera, el interior y algo que pruebe que es el dueño (por ejemplo, abrir la caja o mostrar algún papel del negocio).
5. Una vez verificado: **Configuración del perfil → Personas y acceso → Agregar**, con tu email como **Administrador**.

### Datos para copiar y pegar

- **Nombre:** NORI-PEL
- **Categoría principal:** buscá "Proveedor de productos de limpieza". Si no aparece, elegí la más parecida que tenga "productos de limpieza".
- **Categorías adicionales:** "Tienda de artículos para el hogar" y "Bazar" (o las más parecidas que aparezcan).
- **Dirección:** Av. Juan Domingo Perón 217, Villa de Mayo, Provincia de Buenos Aires
- **Teléfono:** +54 9 11 6423-3586
- **Sitio web:** https://leonel03ponce-afk.github.io/CATALOGO-NORI-PEL/
- **Enlace para hacer pedidos** (en "Más" → "Pedidos" o "Enlaces", si aparece): el mismo link del catálogo.
- **Horarios:**
  - Lunes a viernes: 08:00 a 13:00 y 14:00 a 18:00 (en Google se cargan como dos turnos el mismo día)
  - Sábado: 08:00 a 13:00
  - Domingo: cerrado

**Descripción** (hasta 750 caracteres):

> NORI-PEL es un negocio de productos de limpieza y bazar en Villa de Mayo. Tenemos papel higiénico de marca propia, rollos de cocina, lavandina, detergentes, desinfectantes, escobas, secadores, trapos, baldes, fuentones, bolsas de residuos, insecticidas, aromatizantes, macetas y artículos de plástico para el hogar. Vendemos por unidad y por bulto. Mirá el catálogo completo en nuestra página y hacé tu pedido por WhatsApp: elegís los productos, elegís si lo retirás en el local o te lo enviamos, y te confirmamos por mensaje. Estamos en Av. Juan Domingo Perón 217.

> ⚠️ Antes de publicarla, confirmá con el dueño que **venden por bulto** y que **hacen envíos**. Si alguna de las dos no es cierta, borrala de la descripción.

### Fotos para subir (las que más ayudan)

1. **Frente del local**, de día, con el cartel visible. Es la que usa Google para que te reconozcan al llegar.
2. **Interior**, mostrando las góndolas llenas.
3. **El mostrador con el cartel del QR.**
4. **Productos de marca propia** (papel higiénico NORI-PEL).
5. **Logo** y una foto de **portada**. Para la portada sirve la imagen `cartel-qr.png`.

### Después de crearlo

- **Pedí reseñas** a los clientes de siempre: después de un pedido, mandales por WhatsApp el link de reseña (está en el perfil, en "Pedir reseñas"). Las reseñas son lo que más sube el negocio en Google Maps.
- **Respondé todas las reseñas**, también las malas, con calma y en pocas palabras.
- Cuando cambien las ofertas, **publicá una "Novedad"** en el perfil con foto del producto y el link del catálogo.

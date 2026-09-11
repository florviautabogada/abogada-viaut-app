# El Tablón

Clasificados de trabajo en digital, con la lógica de una revista de avisos: dos lados,
**OFREZCO** y **BUSCO**, conviviendo en la misma página. Demo funcional con 32 avisos
ficticios. Todo corre en el navegador: sin servidor y sin base de datos.

## Cómo abrirla

Doble clic en `el-tablon.html`. Nada que instalar.

## La idea

No es una bolsa de empleo donde sólo las empresas publican. Publica cualquiera: el que
tiene un oficio, una profesión, un producto para revender, una hora libre; y también el
que necesita algo resuelto. Entran oficios, changas, cuidados, clases, costura, reventa
de productos y trabajo online.

## Círculos

La misma aplicación sirve para cuatro ámbitos distintos, y el círculo define quién ve los
avisos y quién puede publicar:

| Círculo | Para quién |
|---|---|
| Barrio de Almagro | Vecinas y vecinos de la zona |
| Gremio — Seccional Capital | Personas afiliadas |
| Organismo | Personal, uso interno |
| Entre amigas y conocidas | Círculo cerrado por invitación |

Se pueden crear más. Un círculo nuevo necesita alguien que lo administre, una regla de
quién entra y unos treinta avisos para que no parezca vacío el primer día.

## Qué hace

- **Tablón** — avisos en columnas, con sello OFREZCO o BUSCO, rubro, código de aviso,
  zona, modalidad, disponibilidad y referencia de precio. Filtros por tipo, rubro,
  modalidad y palabra clave; se ordena por fecha, rubro o zona.
- **Publicar aviso** — formulario con vista previa en vivo: se ve exactamente cómo va a
  quedar en el tablón antes de publicarlo. El aviso propio queda destacado.
- **Guardados** — los avisos marcados para volver después.
- **Mi actividad** — los avisos propios, con baja, y los mensajes enviados.
- **Cómo funciona** — los círculos y las reglas de la casa.

## Decisión de diseño que conviene mantener

**Los datos de contacto no se publican.** Quien se interesa responde por el tablón y cada
persona decide a quién le pasa su teléfono. Es la diferencia entre esto y pegar un papel
en la puerta del almacén, y evita que los avisos se scrapeen para spam.

## Los datos

Se guardan en el navegador (localStorage), solo en la computadora donde la usás.

Los avisos de ejemplo son ficticios y no corresponden a personas reales.

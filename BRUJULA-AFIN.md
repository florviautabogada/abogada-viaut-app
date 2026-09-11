# Brújula Afín

App de citas basada en afinidad (no en swipe a ciegas). Es una demo funcional completa,
con 16 perfiles ficticios. Todo corre en el navegador: no hay servidor, no hay base de
datos y nada se envía a ningún lado.

## Cómo abrirla

Doble clic en `brujula-afin.html`. Se abre en el navegador y funciona. Nada que instalar.

## Qué hace

- **Descubrir** — un perfil por vez, ordenado por afinidad. Cada perfil muestra la brújula
  con el puntaje, el desglose de dónde sale ese número y los motivos en texto.
- **Buscar** — filtros reales: palabra clave, edad, distancia, qué busca la persona,
  afinidad mínima, solo verificados e intereses en común. Se ordena por afinidad,
  cercanía, edad o nombre.
- **Matches** — cuando el interés es mutuo se abre la conversación. El chat responde
  automáticamente (es una demo).
- **Mi perfil** — nombre, edad, ciudad, bio, intereses, qué buscás, a quién querés ver y
  hasta qué distancia. Abajo está el cuestionario de cinco ejes.
- **Seguridad** — bloquear y reportar desde el menú `···` de cualquier perfil. A quien
  bloqueás desaparece de todas las pantallas y se puede desbloquear desde Mi perfil.

## Cómo se calcula la afinidad

Puntaje de 0 a 100 con cuatro componentes:

| Componente | Peso | Cómo se mide |
|---|---|---|
| Ejes | 40 % | Distancia promedio entre las cinco respuestas del cuestionario |
| Intereses | 30 % | Intereses en común sobre el total del perfil más corto |
| Intención | 20 % | Coincidencia entre lo que busca cada una de las dos personas |
| Cercanía | 10 % | Cuánto se pasa la distancia del límite que pusiste |

Cambiar cualquier cosa en Mi perfil recalcula todos los puntajes al instante.

## Los datos

Se guardan en el navegador (localStorage), solo en la computadora donde la usás.
"Borrar todo y empezar de cero", en Mi perfil, los limpia.

Los 16 perfiles son inventados para esta demo y no representan a personas reales.

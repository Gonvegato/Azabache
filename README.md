# Azabache

La revista de la familia: lo que juegas, lees, ves y escribes, valorado y contado. Es **Atrio del móvil con casa propia y menos cosas**:
mismo paquete (`com.gonzalo.gamerate`) y misma firma, así que **se instala encima de Atrio** y se queda con todo (tus notas, tu cuenta, tu
pareja, tus maquetas). Las otras apps la siguen encontrando donde estaba (los colores de Atrio, «Abrir en Azabache»).

Hermana de [Hiedra](https://github.com/Gonvegato/hiedra) (juegos), [Marfil](https://github.com/Gonvegato/lectura-app) (libros) y
[Cobalto](https://github.com/Gonvegato/cobalto) (escribir). Azabache **no añade juegos ni libros**: se añaden, se juegan y se leen en sus apps,
y aquí aparecen solos, con su estado, sus horas y sus portadas, para valorarlos. Las películas, las series y tus categorías propias siguen
aquí tal cual (con su «Añadir»).

## 1.2.0: como sus hermanas

- **La portada en la ficha**: una casilla «Portada» (la misma imagen que en Hiedra o en Marfil) en la primera fila de cada ficha, junto al
  estado o a la nota, como en sus hermanas. Entra sola en las maquetas que ya tenías (si no la quieres, se quita en «Editar»).
- **Portadas en las listas**, encendidas de serie (Ajustes → Apariencia las apaga), con el tamaño de las listas de Hiedra y Marfil.
- Los estados se llaman como en Hiedra y Marfil: **Pendiente · Jugando/Leyendo · Abandonado** (antes «En lista» y «Dropeado»).
- «← Azabache» en las listas (decía «← Atrio»), y los textos que aún nombraban a Atrio.

## 1.1.5: tus subrayados de Marfil, aquí

- Los subrayados que haces en Marfil (su nodo ligero `subrayados`) salen en Azabache: en «La cita» de la portada (y su widget), en el Diario
  (el día que los subrayaste), en la casilla «Subrayados y notas» de la ficha del libro y en el buscador. Tocar una cita abre ese libro en
  Marfil. Los del lector viejo de Atrio se conservan.

## 1.1.4

- Al oír el sello de una hermana solo se baja lo de esa (antes, lo de las tres, con los capítulos de Cobalto enteros, cada vez). Y si dos
  hermanas sellan a la vez, no se pierde ninguna.

## 1.1.3

- «Leer en Marfil» (en la portada y en cada obra de Escritos) abre Marfil **leyendo esa obra** (Marfil 0.12.3 o más nueva).

## 1.1.2: «Jugar» y «Leer» van a la ficha exacta

- «Jugar» en una ficha que vino de Hiedra abre Hiedra **en ese juego** (y, si es del PC, directo a jugar); «Leer» en un libro de Marfil abre
  Marfil **en ese libro** (Marfil 0.12.2 o más nueva, por la clave del libro). Antes solo abrían la app.

## 1.1.1

- Azabache escucha también `marfil/lstamps` (el sello de lo leído de cada libro): los minutos de hoy salen en el Diario en cuanto cierras el libro
  en Marfil, sin esperar a que Marfil suba su biblioteca.

## 1.1.0: las mismas portadas que en Hiedra y Marfil, y los Escritos en Marfil

- **Portadas**: un juego o un libro enseña aquí la misma portada que tiene en Hiedra o en Marfil. Las de internet viajan con la ficha (`pu`;
  Hiedra manda también la caja automática de libretro, `pa`), y las que pusiste de tu galería llegan por kDrive (hace falta el token en
  Ajustes). Hiedra 0.3.0 y Marfil 0.12.0 o más nuevas.
- **Escritos**: con Marfil en el móvil, «Leer en Marfil →» (en la portada y en Escritos) abre Marfil en sus Escritos, donde cada obra de
  Cobalto se lee con su lector. Sin Marfil, se siguen leyendo aquí.

## 1.0.0: la primera

- **Lo que se queda de Atrio**: la portada de revista (cabecera, número y fecha, las barras de lectura, «En portada», tu pareja), las
  categorías y sus páginas, la valoración (nota, criterios, reseña), las casillas de cada página y cómo se colocan («Editar»), el Diario, las
  Cifras, las sagas, la pareja (recomendaciones, reacciones, su diario), los widgets, la apariencia (temas, fondos, letras, iconos), la cuenta,
  kDrive, las copias y actualizarse sola desde tu kDrive (`Azabache-<versión>.apk`).
- **Lo que se va** (se juega, se lee y se escribe en sus apps): el lector, todo lo del PC (streaming, encender, capturas, mando), Escribir,
  Descubrir y «Siguiente», los duelos de libros, las guías, el progreso por capítulos y partes, los apuntes rápidos, la casilla de capítulos,
  importar de Goodreads y Bookmory, y añadir juegos o libros a mano.
- **Lo que llega de las hermanas** (`docs/CONTRATO-DATOS.md`): cada juego de Hiedra y cada libro de Marfil es una ficha aquí (en curso o
  valorada según su estado allí), con su nombre, plataforma o autor, horas, páginas, duraciones, fechas y portada; lo que valoras es tuyo y no se
  toca. Una ficha que llega ya pasada o leída está «sin valorar» hasta que le pongas nota. En el Diario y el calendario salen lo jugado (Hiedra),
  lo leído (Marfil) y las palabras escritas (Cobalto) de cada día. Y **Escritos**, en el menú: los capítulos que diste por terminados en Cobalto,
  para leerlos aquí.
- En las páginas, «Jugar» abre Hiedra y «Leer» abre Marfil (si están en el móvil), en la ficha de ese juego o de ese libro.

## Capturas

Generadas en el ordenador con fichas de ejemplo (`Capturas6Test`): [portada](docs/capturas/r1_portada.png) · [portada abajo](docs/capturas/r2_portada_abajo.png) ·
[biblioteca](docs/capturas/r3_biblioteca.png) · [ficha valorada](docs/capturas/r4_ficha_valorado.png) · [ficha en curso](docs/capturas/r5_ficha_jugando.png) ·
[libro](docs/capturas/s1_libro.png) · [Escritos](docs/capturas/p01_escritos.png) · [Diario](docs/capturas/diario_1_dias.png) · [calendario](docs/capturas/diario_2_calendario.png) ·
[Cifras](docs/capturas/p05_estadisticas.png) · [ajustes](docs/capturas/p06_perfil.png) · [servicios y copias](docs/capturas/p07_ajustes.png) · [apariencia](docs/capturas/p11_apariencia.png) ·
[de noche](docs/capturas/r7_noche.png) · [editando una página](docs/capturas/r8_diseno.png).

## Cómo se trabaja

- Pruebas: `gradle :app:testDebugUnitTest` (0 fallos). `HermanasTest` cubre lo que se lee de las hermanas y cómo se refleja. Con
  `-Proborazzi.test.record=true` se graban las capturas (`app/build/outputs/roborazzi/`).
- Versión nueva: subir `versionCode`/`versionName` (`app/build.gradle.kts`), `gradle :app:assembleRelease` y
  `python3 herramientas/subir-version.py Azabache-<versión>.apk` la deja en tu kDrive para que los móviles se actualicen solos. El
  `versionCode` debe seguir por encima del último de Atrio (131).
- Nace de `Atrio-Suite-2.0/movil` (commit `e2c20b7`): lo quitado sigue en el código pero sin ningún camino que lleve a ello (se irá
  borrando con calma). Atrio del PC sigue siendo Atrio y lee el mismo nodo de la cuenta.

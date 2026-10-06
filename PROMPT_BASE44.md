# Prompt para Base44 — App interactiva de Conocimiento del Medio (6º Primaria)

> **Cómo usarlo:** copia todo lo que hay dentro del bloque de abajo y pégalo en Base44.
> Antes, sustituye el apartado **«CONTENIDOS DEL TEMA»** por el título y los apartados reales del tema
> (puedes pegar el índice del libro o el resumen del tema tal cual).

---

```
Crea una aplicación web educativa, interactiva y muy visual llamada "Explora y Aprende – 6ºB",
para que alumnos de 6º de Primaria (11-12 años) jueguen y aprendan los contenidos de un tema de
Conocimiento del Medio. Debe tener dos modos: MODO ALUMNO (juego) y MODO PROFE (control y adaptaciones),
con atención especial a alumnado con DISLEXIA y con TDAH / déficit de atención. Todo en español.

==================================================
1. CONTENIDOS DEL TEMA  (sustituir por el tema real)
==================================================
Título del tema: [ESCRIBE AQUÍ EL TÍTULO DEL TEMA]
Apartados:
  1. [Apartado 1 – ideas clave]
  2. [Apartado 2 – ideas clave]
  3. [Apartado 3 – ideas clave]
  4. [Apartado 4 – ideas clave]
Vocabulario clave: [palabra – definición corta], [palabra – definición corta], ...

Con estos contenidos, genera automáticamente: 1 "isla" o mundo por apartado, mini-lecciones,
tarjetas de vocabulario y al menos 10 preguntas por apartado (de varios tipos). El profe podrá
editarlo todo después.

==================================================
2. ESTILO VISUAL
==================================================
- Estética de videojuego amable: mapa de aventura con islas/mundos (uno por apartado) que se
  desbloquean al completar el anterior. Colores vivos pero no estridentes, esquinas redondeadas,
  iconos grandes, ilustraciones y emojis en cada concepto.
- Mascota-guía (por ejemplo, un búho explorador llamado "Cono") que da instrucciones, anima y
  celebra los aciertos con animaciones cortas.
- Botones grandes (mínimo 48px), mucho espacio en blanco, una sola tarea por pantalla.
- Diseño responsive: debe funcionar perfectamente en tablet, ordenador y pizarra digital.

==================================================
3. MODO ALUMNO (jugar y aprender)
==================================================
Entrada: el alumno elige su nombre de una lista (creada por el profe) y su avatar. Sin contraseñas.

Para cada isla/apartado:
  a) "Aprende" – mini-lección en 3-5 tarjetas visuales (imagen + frase corta + botón de audio).
  b) "Juega" – juegos variados sobre ese apartado:
     - Test de opción múltiple con imágenes.
     - Verdadero o falso con deslizamiento (tipo swipe).
     - Arrastrar y soltar: clasificar conceptos en categorías.
     - Unir parejas (concepto ↔ definición o imagen).
     - Ordenar secuencias/procesos (línea del tiempo, pasos, ciclos).
     - Memory de tarjetas con vocabulario.
     - Completar huecos eligiendo entre palabras.
     - Mapa o imagen interactiva: tocar la parte correcta.
  c) "Reto final" – mini-examen de la isla; al superarlo gana una medalla y desbloquea la siguiente.

Gamificación:
- Estrellas por acierto, medallas por isla, barra de progreso visible, colección de insignias.
- Feedback inmediato y positivo: si falla, explicación corta + pista + segundo intento
  (nunca mensajes negativos ni sonidos de error fuertes).
- "Repaso inteligente": las preguntas falladas vuelven a aparecer más tarde.
- Gran reto final del tema que mezcla todas las islas, con diploma descargable/imprimible.

==================================================
4. MODO PROFE (protegido con PIN de 4 cifras)
==================================================
Acceso desde un icono discreto de candado; pide PIN (por defecto 1234, modificable).

4.1 Gestión de alumnos
- Crear/editar/eliminar alumnos (nombre + avatar). Importar lista pegando nombres.
- A cada alumno se le asigna un PERFIL DE ADAPTACIÓN: "Estándar", "Dislexia", "TDAH",
  "Dislexia + TDAH" o "Personalizado". Al entrar el alumno, la app aplica su perfil automáticamente.

4.2 Ajustes de adaptación (activables por alumno y también para toda la clase)
  DISLEXIA
  - Tipografía accesible (OpenDyslexic, Lexend o Atkinson Hyperlegible).
  - Tamaño de letra (normal / grande / muy grande), interlineado y espaciado entre letras ampliados.
  - Fondo color crema o pastel a elegir (evitar blanco puro), texto gris oscuro (no negro puro).
  - Lectura en voz alta (texto a voz) de enunciados y respuestas, con resaltado palabra a palabra.
  - Texto alineado a la izquierda, sin cursivas ni mayúsculas largas; frases cortas.
  - Menos opciones por pregunta (2 o 3 en vez de 4).
  - Preguntas con apoyo de imagen y opción de responder por voz o por imagen en lugar de escribir.
  - Desactivar preguntas de escritura libre / ortografía.
  TDAH / DÉFICIT DE ATENCIÓN
  - Sesiones cortas: nº de preguntas por ronda configurable (3, 5, 8, 10).
  - "Modo foco": oculta todo lo que no sea la pregunta actual, sin animaciones de fondo.
  - Temporizador visual (barra o reloj que se vacía) o sin tiempo; quitar la presión del cronómetro.
  - Descansos activos automáticos cada X minutos (mini-pausa de movimiento o respiración de 30 s).
  - Recompensas más frecuentes y visibles (estrella en cada acierto, mini-celebración).
  - Instrucciones paso a paso, de una en una, con icono y audio.
  - Reducir o quitar sonidos y animaciones; checklist visual de "qué me falta" en la isla.
  GENERALES
  - Nivel de dificultad por alumno: Básico / Medio / Avanzado.
  - Activar/desactivar cada isla y cada tipo de juego.
  - Modo alto contraste y control de volumen.

4.3 Editor de contenidos
- Editar el título del tema, apartados, mini-lecciones, vocabulario y preguntas.
- Añadir preguntas de cualquier tipo, con imagen opcional, marcar dificultad y apartado.
- Botón "Generar más preguntas con IA" a partir del texto de un apartado.

4.4 Seguimiento y resultados
- Panel con tabla de alumnos: progreso por isla, % de aciertos, tiempo jugado, medallas.
- Detectar los conceptos que más falla cada alumno y la clase (gráfico de barras sencillo).
- Semáforo por alumno (verde = lo domina, amarillo = repasar, rojo = necesita apoyo).
- Exportar resultados (CSV o imprimir) y reiniciar progreso de un alumno o de la clase.

4.5 Modo clase / pizarra digital
- Proyectar un juego en grupo: preguntas en grande, el profe revela la respuesta y lleva
  la puntuación por equipos.

==================================================
5. DATOS (entidades)
==================================================
- Student: nombre, avatar, perfil_adaptacion, ajustes (JSON), nivel, estrellas, medallas.
- Topic: título, descripción.
- Section (isla): topic, orden, título, icono, color, mini_lecciones (lista), activa.
- Question: section, tipo, enunciado, opciones, respuesta_correcta, explicación, pista,
  imagen, dificultad.
- Vocabulary: section, palabra, definición, imagen.
- Attempt: student, question, correcta, intento, fecha, tiempo.
- TeacherSettings: pin, ajustes de clase por defecto.

==================================================
6. REQUISITOS FINALES
==================================================
- Interfaz 100% en español, lenguaje sencillo y cercano para niños de 11-12 años.
- Accesibilidad: buen contraste, navegación con teclado, textos alternativos en imágenes.
- Rendimiento ligero; sin publicidad ni enlaces externos para los alumnos.
- Precarga el tema indicado arriba con contenidos de ejemplo completos para poder usar la app
  desde el primer momento.
```

---

## Consejos para iterar en Base44

Una vez generada la app, puedes pedirle mejoras con mensajes cortos, por ejemplo:

- «Añade un juego tipo "¿Quién quiere ser millonario?" para el reto final.»
- «En el perfil Dislexia, que la lectura en voz alta se active sola al cargar cada pregunta.»
- «Añade una pantalla de bienvenida con la mascota explicando cómo se juega.»
- «Haz que el panel del profe muestre una gráfica de progreso semanal de la clase.»

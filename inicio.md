| ID | Historia de usuario (Simplificada) | RF / RNF | Criterios de aceptación y UI (Nivel estudiante) |
| --- | --- | --- | --- |
| **HU01** | Como **Visitante**, quiero **ver todos los cursos** para saber qué ofrece el centro sin tener que crear una cuenta.

 | RF04 | - La web muestra una lista de todos los cursos.<br>

<br>- Se puede entrar a ver la información de cada uno sin poner contraseña.

 |
| **HU02** | Como **Visitante**, quiero **registrarme con mi email** para poder apuntarme a las clases.

 | RF01, RF02 | - El sistema comprueba que el email no se haya usado antes.

<br>

<br>- Envía un link al correo para verificarlo obligatoriamente.

<br>

<br>- La cuenta se queda esperando a que Secretaría la apruebe.

 |
| **HU03** | Como **Administrador**, quiero **ver las cuentas nuevas** para aceptarlas o rechazarlas.

 | RF19 | - Hay una pantalla con una lista de usuarios "Pendientes".<br>

<br>- Botones verdes (Aceptar) y rojos (Rechazar) fáciles de usar.

 |
| **HU04** | Como **Usuario**, quiero **buscar cursos por nombre o tema** para encontrar rápido lo que me interesa.

 | RF05 | - Al escribir, la lista se actualiza al instante.<br>

<br>- Hay filtros (botones) para elegir temas, fechas o si quedan plazas.

 |
| **HU05** | Como **Alumno**, quiero **apuntarme a un curso** para reservar mi sitio en clase.

 | RF03, RF07 | - El botón "Matricularse" solo funciona si tienes 18 años o más y la cuenta está aprobada.

<br>

<br>- El sistema avisa si dos clases coinciden a la misma hora y no te deja apuntarte.

 |
| **HU06** | Como **Alumno**, quiero **apuntarme a la lista de espera** si el curso está lleno, por si alguien se borra.

 | RF10, RF11 | - Si no hay plazas, aparece el botón "Lista de espera".

<br>

<br>- Si queda un hueco libre, te avisa y tienes solo 24 horas para aceptar.

<br>

<br>- Nadie del personal puede mover la lista a mano.

 |
| **HU07** | Como **Alumno**, quiero **borrar mi matrícula yo mismo** antes de que empiecen las clases para no tener problemas.

 | RF09 | - El botón de cancelar solo se ve antes del primer día de clase.

<br>

<br>- Al darle, el sitio pasa automático al primero de la lista de espera.

 |
| **HU08** | Como **Alumno**, quiero **ver mi horario** para saber a qué aula tengo que ir.

 | RF27 | - Solo veo los horarios de los cursos donde estoy apuntado.<br>

<br>- Muestra los días, las horas y el número de la clase. |
| **HU09** | Como **Alumno**, quiero **ver si tengo faltas de asistencia** para saber cuántas clases me he perdido.

 | RF28 | - Pantalla con iconos verdes (fui), rojos (falté) y amarillos (justificado).<br>

<br>- Es imposible ver las faltas de otros compañeros.

 |
| **HU10** | Como **Profesor**, quiero **ver qué cursos doy y quiénes son mis alumnos** para preparar la clase.

 | RF12 | - Pantalla privada que solo muestra mis asignaturas, no las de otros profesores.

 |
| **HU11** | Como **Profesor**, quiero **pasar lista en clase** para llevar el control de quién asiste.

 | RF13 | - Tabla fácil donde hago clic al lado de cada nombre para poner si ha venido o no.

 |
| **HU12** | Como **Administrador**, quiero **crear o editar cursos** para tener la información al día.

 | RF06, RF16 | - Formularios sencillos para cambiar texto o fechas.<br>

<br>- Al borrar, el curso se "oculta" de la vista pública pero los datos no se borran para siempre de la base de datos.

 |
| **HU13** | Como **Administrador**, quiero **poner aulas a los cursos** sin que dos grupos se mezclen.

 | RF22, RF23 | - El sistema avisa si el aula es muy pequeña para tantos alumnos.

<br>

<br>- Se asigna el aula para todo el curso, sin preocuparse de qué ordenadores tiene dentro.

 |
| **HU14** | Como **Administrador**, quiero **descargar listas en PDF** para tener el papeleo del centro impreso.

 | RF30 | - Botón de "Descargar PDF" al lado de cada lista de alumnos u horarios.

 |
| **HU15** | Como **Administrador**, quiero **dar los diplomas** al final, mientras que el profesor pone las notas.

 | RF29 | - El profesor pone la nota, pero el botón "Emitir Certificado" solo le funciona al Administrador.

 |
| **HU16** | Como **Usuario**, quiero **recuperar mi contraseña** si se me olvida, usando mi email.

 | RF20 | - Enlace "Olvidé mi contraseña" en la pantalla de inicio.

<br>

<br>- Envía un correo con un link seguro para cambiarla.

 |
| **HU17** | Como **Visitante**, quiero **ver fotos y detalles del curso** para saber si me gusta antes de apuntarme.

 | RF04 | - La pantalla del curso muestra una foto chula, el nombre del profesor y las plazas libres.

 |
| **HU18** | Como **Usuario**, quiero **poder usar la web sin ratón** por si tengo problemas visuales.

 | RNF10 | - Todo se puede usar con la tecla `Tab` del teclado.

<br>

<br>- Hay un botón para poner colores de alto contraste.

 |
| **HU19** | Como **Visitante**, quiero **ver rápido si un curso está lleno** sin tener que entrar a leerlo.

 | RF16 | - Se usan etiquetas de colores: Verde "Abierto", Rojo "Lleno".

 |
| **HU20** | Como **Usuario**, quiero **saber si me equivoco al escribir** (ej. si el email ya existe) sin que la página parpadee.

 | RNF04 | - Textos rojos pequeños debajo de la casilla donde me he equivocado, que salen al instante. |
| **HU21** | Como **Alumno**, quiero **descargar un papel que diga que estoy matriculado** para tener pruebas. | RF30 | - Botón "Bajar resguardo" que genera un PDF con mis datos y los del curso.

 |
| **HU22** | Como **Alumno**, quiero **que me avisen si me cambian de aula** para no perderme el primer día.

 | RF18, RN19 | - Campanita de notificaciones arriba a la derecha que se pone roja si hay avisos nuevos. |
| **HU23** | Como **Alumno**, quiero **ver mis notas y descargar mis diplomas** cuando termine todo.

 | RF29 | - Se ven separados los cursos en los que estoy ahora y los que ya aprobé.

 |
| **HU24** | Como **Alumno**, quiero **poder decir que SÍ quiero la plaza de la lista de espera** desde la web.

 | RF11 | - Me sale un aviso grande al entrar a la web diciendo "¡Tienes plaza! Te quedan 23 horas para confirmar".

 |
| **HU25** | Como **Alumno**, quiero **ver claro hasta qué día puedo darme de baja** sin que me penalicen.

 | RF09 | - Un cartel que diga "Puedes cancelar hasta el 10 de octubre". Si pasa el día, el botón rojo de cancelar desaparece.

 |
| **HU26** | Como **Profesor**, quiero **poner notas rápido** al final del curso.

 | RF29 | - Una tabla parecida a Excel donde escribo los números rápido sin tener que abrir alumno por alumno.

 |
| **HU27** | Como **Profesor**, quiero **ver un gráfico simple con las faltas** para saber si alguien falta mucho. | RF12, RF13 | - Un gráfico de quesito que me muestra quiénes son los que más faltan de un vistazo. |
| **HU28** | Como **Profesor**, quiero **recibir avisos si la Secretaría me cambia las clases**.

 | RF18, RN19 | - Me sale un mensaje automático si me cambian el aula o la hora de la clase. |
| **HU29** | Como **Profesor**, quiero **bajar mi lista de alumnos a un Excel o PDF** para imprimirla.

 | RF30 | - Solo puedo descargar a los alumnos de mis propias clases, no los de todo el centro.

 |
| **HU30** | Como **Profesor**, quiero **ver mi horario como en Google Calendar** para aclararme mejor. | RF27 | - Pantalla con un calendario por semanas con bloques de colores por cada clase. |
| **HU31** | Como **Administrador**, quiero **saltarme la lista de espera si hay una urgencia muy grave**.

 | RF26 | - Puedo arrastrar a alguien arriba en la lista, pero la web me obliga a escribir un texto explicando por qué lo he hecho para que quede guardado.

 |
| **HU32** | Como **Administrador**, quiero **decirle al sistema quién es profesor y quién es alumno** al aprobar las cuentas.

 | RF21 | - Un menú desplegable al lado de cada usuario nuevo para asignarle su rol antes de darle a "Aceptar".

 |
| **HU33** | Como **Administrador**, quiero **ver gráficos de cómo va el centro** nada más entrar.

 | RF14 | - Una pantalla principal con números grandes: "5 cursos llenos", "20 plazas libres", etc.

 |
| **HU34** | Como **Administrador**, quiero **cancelar un curso vacío y explicar por qué lo hago**.

 | RF17, RN15 | - Solo me deja cancelarlo si hay 0 matriculados. El botón "Guardar" no funciona hasta que escriba el motivo en la caja de texto.

 |
| **HU35** | Como **Administrador**, quiero **borrar a un alumno yo mismo si a él se le rompe el ordenador**.

 | RF24 | - Botones de emergencia en mi panel para dar de baja a la gente de forma manual en casos raros.

 |
| **HU36** | Como **Usuario**, quiero **que la web se vea bien en mi móvil** para hacer cosas en el autobús.

 | RNF03 | - El menú de arriba se convierte en un botón de tres rayas (hamburguesa) para no ocupar pantalla en móviles.

 |
| **HU37** | Como **Usuario**, quiero **ver un mensaje amable si busco algo y no hay nada** para no liarme. | RF05 | - En vez de una pantalla en blanco, sale un dibujo chulo y dice "No hay cursos de eso, prueba con otra cosa" y un botón para limpiar la búsqueda. |
| **HU38** | Como **Usuario**, quiero **ver que la web está cargando** para no hacer doble clic por error. | RNF04 | - Cuando le doy a "Guardar", el botón da vueltas (spinner) y no me deja volver a darle hasta que acabe. |
| **HU39** | Como **Usuario**, quiero **saber si mi nueva contraseña es buena** mientras la escribo. | RNF02 | - Salen unos iconos (check) que se ponen verdes cuando pongo letras, números y es suficientemente larga. |
| **HU40** | Como **Administrador**, quiero **ver mensajitos arriba cuando hago algo bien** sin que me molesten. | RF19 | - Si apruebo a 5 alumnos seguidos, sale un aviso verde de "Aprobado" arriba y desaparece solo a los 3 segundos, para poder seguir trabajando. |
| **HU41** | Como **Alumno / Profesor**, quiero **guardar mi horario en Google Calendar** para que el móvil me avise antes de clase. | UX / RF27 | - Botón "Añadir a mi calendario" que descarga un archivo `.ics` compatible con teléfonos. |
| **HU42** | Como **Usuario registrado**, quiero **ver un resumen de mis cosas al entrar** para ir directo al grano. | UX / Dash | - Nada más hacer login, veo tarjetas grandes con "Tu próxima clase es a las 18:00" o "Tienes 1 aviso nuevo". |
| **HU43** | Como **Usuario**, quiero **poder cambiar el idioma de la web** porque el centro está en Xàbia.

 | RNF / UX | - Arriba hay banderitas o un menú para elegir Español, Valenciano o Inglés, y la web se acuerda de mi elección. |
| **HU44** | Como **Alumno**, quiero **descargar el temario del curso en PDF** antes de apuntarme. | UX / RF04 | - En la ficha pública del curso hay un botón con el icono de un clip para descargar el programa completo. |
| **HU45** | Como **Administrador**, quiero **que las listas súper largas carguen poco a poco** para que la web no vaya lenta. | UX / RNF | - Si hay 500 alumnos, la pantalla muestra los primeros 30, y al bajar con el ratón (scroll) cargan los demás solos. |
| **HU46** | Como **Profesor**, quiero **mandar un mensaje a todos los alumnos de mi clase a la vez** para avisarles de cosas. | UX / Comms | - Un botón de "Nuevo anuncio" en mi clase que envía un aviso masivo a los estudiantes (ej. "Traed lápiz mañana"). |
| **HU47** | Como **Usuario**, quiero **un botón para pedir que borren todos mis datos** si dejo de ir al centro. | GDPR / Legal | - En la sección "Mi Perfil", un botón rojo de "Eliminar cuenta" que manda una solicitud a la Secretaría por temas de privacidad.

 |
| **HU48** | Como **Usuario nuevo**, quiero **ver flechas y globitos de ayuda la primera vez que entro** para aprender a usar esto. | UX / Onboarding | - Un mini-tutorial paso a paso que me señala dónde está el horario y dónde puedo ver las notas. |
| **HU49** | Como **Usuario**, quiero **poner la web en modo oscuro** para que no me moleste la luz por la noche. | UX / UI | - Un icono de luna/sol en el menú que cambia todos los colores de la web de blanco a tonos negros/grises. |
| **HU50** | Como **Usuario**, quiero **que la web recuerde quién soy** para no tener que poner el email y la contraseña todos los días. | UX / Auth | - Una casilla de "Recordarme" al hacer login que mantiene mi sesión abierta de forma segura en mi dispositivo móvil u ordenador. |
| **HU51** | Como **Usuario**, quiero **ver una "ruta de migas de pan" (breadcrumbs) arriba** para saber exactamente dónde estoy y volver atrás sin perderme. | UX / UI | - Texto tipo enlace en la parte superior: `Inicio > Cursos > Idiomas > Inglés B1`. Cada palabra anterior se puede clicar para volver. |
| **HU52** | Como **Alumno**, quiero **rellenar mi matrícula paso a paso (Wizard)** para no agobiarme viendo un formulario gigante de golpe. | UX / UI | - El formulario se divide en 3 pantallas (Datos, Confirmación, Pago/Resguardo). Arriba hay una barra de progreso que dice "Paso 1 de 3". |
| **HU53** | Como **Administrador**, quiero **hacer clic en los títulos de las columnas** de una tabla para ordenar los nombres alfabéticamente al instante. | UX / UI | - Al tocar la palabra "Nombre" o "Fecha" en la cabecera de la tabla, aparece una flechita y la lista se ordena de la A a la Z sin recargar la web. |
| **HU54** | Como **Usuario**, quiero **que el teclado parpadee solo en la primera casilla** al abrir un formulario para empezar a escribir sin usar el ratón. | UX / Acces. | - Al cargar la web de "Login", el cursor de texto (focus) ya está dentro de la casilla "Email" automáticamente. |
| **HU55** | Como **Visitante**, quiero **ver un carrusel de fotos deslizable en la ficha del curso** para ver cómo son las aulas y materiales. | UX / UI | - Debajo del título del curso hay varias fotos que puedo pasar tocando unas flechas laterales o deslizando el dedo en el móvil. |
| **HU56** | Como **Usuario**, quiero **ver un asterisco rojo (*) en las casillas obligatorias** y que se pongan rojas si me las salto. | UX / UI | - Si intento enviar el formulario dejando un hueco vacío, el borde de la caja se pone rojo y sale un texto debajo que dice "Este dato es obligatorio". |
| **HU57** | Como **Profesor**, quiero **deslizar con el dedo a los lados (scroll horizontal)** si mi tabla de alumnos es muy ancha para verla bien en el móvil. | RNF03 | - La tabla de asistencia no se rompe ni deforma la web; simplemente me deja moverla hacia la izquierda y derecha dentro de su cuadro. |
| **HU58** | Como **Administrador**, quiero **arrastrar y soltar (Drag & Drop) a los alumnos en la lista de espera** para cambiarles el orden rápido en caso de urgencia. | RF26 / UX | - Hay un icono de puntitos al lado del nombre que, al mantenerlo pulsado, me deja arrastrar la fila arriba o abajo visualmente. |
| **HU59** | Como **Usuario**, quiero **cerrar las ventanas emergentes (Modales) pulsando la tecla "Escape"** para no tener que buscar la "X" con el ratón. | UX / Acces. | - Cualquier aviso o ventana flotante se cierra al instante si toco la tecla `Esc` de mi teclado o si hago clic fuera de la caja blanca. |
| **HU60** | Como **Usuario**, quiero **ver una página amigable si escribo mal la dirección web (Error 404)** para no asustarme y volver al inicio. | UX / UI | - Sale un dibujo de "Página no encontrada" y un botón grande que dice "Volver a la página principal" en vez de códigos raros del servidor. |
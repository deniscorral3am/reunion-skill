# Claude Meetings en tus llamadas de venta

Por Denís Corral · @deniscorralvillarraso en Instagram · [Sell Your AI](https://sellyourai.io)

Anthropic ha metido a Claude dentro de las videollamadas. Se llama **Claude Meetings**: lo añades a tu Google Meet,
entra como un participante más, le hablas en voz alta o por el chat y, mientras habláis, te va montando el
documento, la pizarra o el plan en directo. Cuando colgáis, tienes las notas, las tareas y la transcripción en la
página de la reunión.

Para una agencia de IA esto vale oro: preparas la llamada de venta con tu equipo con Claude delante, en la llamada
con el cliente Claude toma nota de todo, y al colgar tienes la propuesta escrita **con sus palabras**. Este documento
te explica cómo activarlo paso a paso y cómo lo usaría yo. Al final tienes un prompt para pegarlo en Claude y que te
prepare tu próxima llamada.

> Datos sacados del artículo oficial de Anthropic (claude.com/resources/articles/claude-meetings) y de su centro de
> ayuda (support.claude.com/en/articles/18325154), a 12/11/2026. Es una beta: puede cambiar. Si algo no te cuadra,
> manda lo que diga la ayuda oficial.

---

## 1. Qué es y qué hace

- **Entra en la llamada como un participante visible.** Lo añades tú o se une solo si tienes el auto-join.
- **Le hablas como a una persona.** Dices «Claude» en voz alta o le escribes en el chat de Meet, y responde **por
  escrito** en el chat (por defecto). Si se lo pides hablando, te pregunta quién habla para confirmarlo.
- **Construye en directo.** Documentos, pizarras o diapositivas que se montan mientras el equipo los va retocando, y
  se quedan pegados a la página de la reunión.
- **Te comparte un resumen antes de acabar** si se lo pides.
- **Puede quedarse hasta 8 horas** y avisa antes de irse. Lo puedes pausar, reanudar o sacar de la llamada.
- **Después de la reunión**, en la página de esa reunión en claude.ai: notas, resumen, tareas (action items),
  transcripción, el plan, la pizarra y todo lo que se hizo. Los de tu organización que estaban invitados reciben un
  correo con el resumen y el enlace, y pueden verlo, editarlo y compartirlo dentro de la organización.
- **Luego le puedes preguntar** por reuniones pasadas a las que tienes acceso desde un chat normal.
- **Usa tus herramientas conectadas** con tus permisos: la primera vez te pregunta y, si dices que sí, vale para las
  siguientes. Ojo: una respuesta en el chat de la llamada la ve todo el mundo que está en ella.
- **Qué guarda:** la transcripción, el resumen y descripciones de lo que se ve en pantalla. **El audio no se guarda.**

## 2. Lo que tienes que saber antes (la letra pequeña)

| | |
|---|---|
| Estado | Beta, en Claude y Claude Desktop |
| Planes | Solo **Team** y **Enterprise** |
| Plataforma | Solo **Google Meet** (con Google Calendar). Otras plataformas, «pronto» |
| En Team | Viene **activado por defecto**; un admin puede desactivarlo |
| En Enterprise | Lo **activa un admin**, para toda la organización o parte |
| No disponible (beta) | En organizaciones con ZDR (retención cero de datos), HIPAA-ready o CMEK |
| Invitados externos | Por defecto **no entra** si hay alguien de fuera y **se va** si entra después. El admin puede permitirlo |
| Precio (beta) | Notas, transcripción y respuestas sin herramientas conectadas: incluidas en Team y Enterprise. Documentos, pizarras y demás artefactos: gratis hasta el 10/02/2027. Lo que usa herramientas conectadas cuenta contra tu uso y puede costarle a la organización |
| Socios | Anthropic dice que trabaja con Gong, Attention, Granola, Fireflies.ai y Otter para que puedas mandar la transcripción a tus herramientas **pronto**. Aún no hay ninguna disponible |

**El punto clave para ventas:** tu cliente es un invitado externo. Cuando el admin lo permite, en esas llamadas
Claude **escucha, toma notas y publica un aviso en el chat, pero no contesta**. Lo que dice el cliente entra en las
notas y la transcripción, y el cliente **no** recibe la página ni el correo de resumen. Es decir: con el cliente
delante, Claude es tu tomador de notas; el trabajo en directo (documentos, pizarras, respuestas) es para tus
reuniones internas.

---

## 3. Cómo activarlo paso a paso

### 3.1 Ten el plan correcto
Necesitas Claude **Team** o **Enterprise**. Para una agencia pequeña, Team es lo normal. Comprueba que tu
organización no tiene ZDR, HIPAA-ready ni CMEK (en la beta no está disponible ahí).

### 3.2 Que esté encendido en tu organización
El admin lo controla en **Ajustes de la organización → Productos → Claude Meetings (beta)**: apagado, encendido para
los roles que lo incluyan o encendido para todos. En Team viene encendido; en Enterprise lo tiene que encender él.
Ahí mismo hay un ajuste aparte para que Claude pueda usar los conectores de los miembros en las reuniones.

### 3.3 Invitados externos (para tus llamadas con clientes)
En el mismo sitio, el ajuste «Reuniones con invitados externos»: solo reuniones internas o permitidas. Si no eres
admin, pídeselo:

> «¿Puedes permitir Claude Meetings en reuniones con invitados externos? Lo quiero para tomar notas en las llamadas
> con clientes; siempre les aviso de que se transcribe.»

### 3.4 Conecta Google Calendar y añade a Claude
Conecta Google Calendar (el admin tiene que haberlo habilitado antes para la organización). Luego abre **Meetings**
en Claude, elige una reunión de tu calendario y pulsa **«Add Claude»**. Normalmente entra sin pedir permiso; si lo
pide, el anfitrión lo admite.

### 3.5 Auto-join (opcional)
En **Ajustes → Capacidades → Meetings** eliges si se une solo a todas tus reuniones o a todas menos las de uno a
uno. Esto lo pones tú: el admin no lo puede poner por ti.

### 3.6 Conecta las herramientas que quieras que consulte
Si quieres que en mitad de una reunión te busque un dato (CRM, documentos, correo…), esas herramientas tienen que
estar conectadas a Claude. Recuerda que esas respuestas cuentan contra tu uso.

### 3.7 Haz una prueba sin cliente
Monta una reunión con un compañero, añade a Claude y prueba: pregúntale algo en voz alta, pídele que empiece un
documento y, al acabar, mira la página de la reunión. Mejor fallar aquí que delante de un cliente.

---

## 4. Cómo usarlo en tu agencia

### La llamada de venta

**Antes (reunión interna, Claude a tope).** Prepara la llamada con tu socio o tu equipo en un Meet con Claude:
- «Claude, haz una pizarra con lo que sabemos de [cliente]: su web, su sector y lo que nos contó al escribirnos.»
- «Escribe las preguntas de diagnóstico: su proceso hoy, sus números, quién decide y qué ha probado.»
- «Comparte un resumen antes de acabar con lo que tenemos que averiguar en la llamada.»

**El aviso de consentimiento.** Anthropic pide asegurarte de que todos están de acuerdo con que se transcriba. En la
invitación pon algo así:

> «En la llamada me ayuda Claude, un asistente de IA: toma notas y transcribe la conversación para que no se me
> escape nada. No se graba el audio. Si prefieres que no esté, dímelo y lo quito.»

Y al empezar, dilo en voz alta. Si dice que no, saca a Claude y toma notas a mano.

**Durante (con el cliente).** Si tu admin permite invitados externos, Claude entra, avisa en el chat y toma notas sin
contestar. Tú te dedicas a escuchar y a sacarle **sus números** (leads al mes, cuánto vale un cliente, cuánto tardan
en contestar) y **sus frases**: todo queda en la transcripción. Si no está permitido, Claude no entra: toma notas a
mano o usa otra herramienta con su permiso.

**Al colgar: la propuesta con sus palabras.** Con las notas y la transcripción de la página de la reunión, pídele a
Claude (en otra reunión interna o en un chat) la propuesta:
- **Sus palabras:** el problema tal como lo contó él, con frases literales de la transcripción.
- **Lo que le cuesta no hacer nada**, en euros al mes, con **los números que dio él** (lo supuesto, marcado).
- **La solución** sin tecnicismos (nada de «agente», «n8n» o «LLM»).
- **Tres opciones** de precio, con la recomendada marcada.
- **Plazos y siguientes pasos.**

Si tienes la skill `/propuesta`, pásale la transcripción y te la monta. Manda el resumen el mismo día y presenta la
propuesta en una segunda llamada, no por correo.

### El onboarding de un cliente nuevo
Antes de la llamada de arranque, reunión interna con Claude: pizarra con lo que se ha vendido, accesos que faltan,
tareas y responsables. Con el cliente en la llamada, Claude toma nota de cada acceso y cada detalle que te da. Al
colgar, en la página tienes las tareas: conviértelas en el plan de la primera semana.

### La reunión de seguimiento
Antes del seguimiento mensual, pregúntale a Claude por las reuniones pasadas con ese cliente («¿qué nos pidió en la
última reunión y qué quedó pendiente?»). Así llegas sabiendo qué prometiste y qué has cumplido.

### La reunión semanal de tu agencia
Aquí Claude trabaja al 100 %: le pides el estado de cada cliente (si tienes el CRM conectado), monta el plan de la
semana en directo y reparte las tareas.

---

## 5. Lo que no tienes que hacer

- Meter a Claude en una llamada sin avisar de que transcribe.
- Contar con que te conteste delante del cliente: con invitados externos solo toma notas.
- Enseñar al cliente una propuesta sin revisarla tú.
- Inventarte cifras o casos en la propuesta: solo sus números y los tuyos reales.
- Contar con que entra en Zoom o Teams: de momento solo Google Meet.

---

## 6. El prompt para Claude

Pégalo en Claude (mejor en un proyecto o en Claude Code) y contesta sus preguntas.

```
Quiero usar Claude Meetings (Claude dentro de Google Meet, beta en planes Team y Enterprise) en mi agencia para
cerrar más clientes. Ayúdame paso a paso, en español, corto y sin tecnicismos, y pregúntame una sola cosa cada vez.
No inventes cifras ni casos: si algo es una estimación, dilo.

1. ACTIVARLO. Pregúntame qué plan de Claude tengo (Team o Enterprise), si soy admin y si mis llamadas son con
   gente de fuera de mi organización. Dime qué tengo que activar o pedir al admin (Claude Meetings, invitados
   externos y conectores en reuniones) y cómo hacer una prueba sin cliente. Recuerda que con invitados externos
   Claude solo toma notas y no contesta.

2. EL CLIENTE. Pregúntame a quién tengo la próxima llamada (nombre, web, sector, lo que me ha contado) y qué
   servicio de IA le quiero vender.

3. ANTES DE LA LLAMADA. Escríbeme el aviso de consentimiento para la invitación (Claude transcribe, no se graba
   el audio, si no quiere lo quito), las preguntas de diagnóstico (proceso, números, quién decide, qué ha probado)
   y lo que le pediré a Claude en la reunión interna para prepararla.

4. AL COLGAR. Cuando te pegue las notas y la transcripción de la reunión, escribe la propuesta: su problema con
   sus palabras literales, lo que le cuesta no hacer nada en euros al mes con sus números (marca lo supuesto),
   la solución sin tecnicismos, tres opciones de precio con la recomendada marcada y los siguientes pasos.

5. EL SEGUIMIENTO. El mensaje para mandarle el resumen hoy y proponerle la llamada para presentar la propuesta.

Empieza por el paso 1.
```

---

Sell Your AI · Claude y Claude Meetings son marcas de Anthropic; Google Meet y Google Calendar, de Google.

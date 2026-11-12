# Claude Meetings en tus llamadas de venta

Por Denís Corral · @deniscorralvillarraso en Instagram · [Sell Your AI](https://sellyourai.io)

Anthropic ha metido a Claude dentro de las videollamadas. Se llama **Claude Meetings**: lo invitas a tu Google Meet,
entra como un participante más, le preguntas en voz alta o por el chat y, mientras habláis, te va montando el
documento, la pizarra o el plan en directo. Cuando colgáis, tienes las notas, las tareas y la transcripción en la
página de la reunión.

Para una agencia de IA esto es oro en la llamada de venta: el cliente te cuenta su problema y, al colgar, ya tienes
la propuesta escrita **con sus palabras**. Este documento te explica cómo activarlo paso a paso y cómo lo usaría yo en
una llamada de venta. Al final tienes un prompt para pegarlo en Claude y que te prepare tu próxima llamada.

> Datos sacados del artículo oficial de Anthropic (claude.com/resources/articles/claude-meetings) y de su centro de
> ayuda, a 12/11/2026. Es una beta: puede cambiar. Si algo no te cuadra, manda lo que diga la ayuda oficial.

---

## 1. Qué es y qué hace

- **Entra en la llamada como un participante visible.** Lo añades tú o se une solo (auto-join), y publica un aviso
  en el chat de la reunión para que todos sepan que está.
- **Le hablas como a una persona.** Le preguntas en voz alta o por el chat y responde **por escrito** (por defecto).
- **Construye en directo.** Documentos, pizarras y otros artefactos que se van montando mientras el equipo los edita
  a la vez.
- **Puede compartir un resumen antes de acabar**, para cerrar la llamada con todo el mundo de acuerdo.
- **Después de la reunión**, en la página de esa reunión en claude.ai tienes: notas, tareas (action items),
  transcripción, el plan y la pizarra.
- **Usa tus herramientas conectadas** (las que tengas conectadas a Claude), siempre con tu permiso: la primera vez
  te pregunta.
- **Qué guarda:** la transcripción, el resumen y descripciones de lo que se ve en pantalla. **El audio no se guarda.**

## 2. Lo que tienes que saber antes (la letra pequeña)

| | |
|---|---|
| Estado | Beta |
| Planes | Solo **Team** y **Enterprise** (no Free, Pro ni Max) |
| Plataforma | Solo **Google Meet** de momento (otras plataformas, «pronto») |
| En Team | Viene **activado por defecto**; un admin puede desactivarlo |
| En Enterprise | Lo tiene que **activar un admin** |
| No disponible | En organizaciones con ZDR (retención cero de datos), HIPAA-ready o CMEK |
| Invitados externos | Por defecto **no entra** si hay gente de fuera de tu organización; el admin puede permitirlo |
| Precio | Notas y transcripción, gratis. Documentos, pizarras y demás artefactos, gratis hasta el 10/02/2027. Las respuestas que usan una herramienta conectada cuentan contra tu uso |

**El punto clave para ventas:** tu cliente es un invitado externo. Si no cambias nada, Claude no entrará en tu
llamada de venta. Lo tiene que permitir el admin de tu organización (mira el paso 3.3).

---

## 3. Cómo activarlo paso a paso

### 3.1 Ten el plan correcto
Necesitas Claude **Team** o **Enterprise**. Si estás en Pro o Max, no te sale. Para una agencia pequeña, Team es lo
normal. Comprueba también que tu organización no tiene ZDR, HIPAA-ready ni CMEK activados (si es así, no está
disponible).

### 3.2 Que esté encendido en tu organización
- **Team:** ya viene encendido. Si no lo ves, pregunta al admin (o, si el admin eres tú, revisa los ajustes de la
  organización en claude.ai).
- **Enterprise:** el admin tiene que activarlo en los ajustes de la organización.

### 3.3 Permite invitados externos (imprescindible para ventas)
Por defecto Claude no se une si en la reunión hay alguien de fuera de tu organización. Para usarlo con clientes, el
admin tiene que **permitir reuniones con invitados externos** en los ajustes de Claude Meetings de la organización.
Si no eres admin, pídeselo con este mensaje:

> «¿Puedes permitir que Claude Meetings se una a reuniones con invitados externos? Lo quiero usar en las llamadas con
> clientes; siempre les aviso de que se transcribe.»

### 3.4 Conecta Google Meet y tu calendario
Claude tiene que poder entrar en tus reuniones de Google Meet: sigue los pasos de la ayuda oficial
(support.claude.com/en/articles/18325154) para conectarlo y elegir si se une solo (auto-join)
o solo cuando lo añades tú.

### 3.5 Conecta las herramientas que quieras que consulte
Si quieres que en mitad de la llamada te busque un dato (tu CRM, tus documentos, tu correo…), esas herramientas
tienen que estar conectadas a Claude. La primera vez que use una te pedirá permiso. Recuerda que estas respuestas
cuentan contra tu uso.

### 3.6 Haz una prueba sin cliente
Monta una reunión contigo y un compañero (o con otra cuenta tuya), añade a Claude y prueba: pregúntale algo en voz
alta, pídele que empiece un documento y, al acabar, mira la página de la reunión en claude.ai. Mejor fallar aquí que
delante de un cliente.

---

## 4. Cómo usarlo en una llamada de venta de tu agencia

La idea: tú te dedicas a escuchar y a hacer buenas preguntas; Claude toma nota de todo y te deja la propuesta casi
hecha. El cliente ve que trabajas con IA de verdad, que es justo lo que le vas a vender.

### Antes de la llamada
- Prepara en Claude (en un chat o proyecto) lo que sabes del cliente: su web, su sector, lo que te contó al
  escribirte. Así llegas con preguntas concretas.
- Ten listo tu guion de diagnóstico: su proceso hoy, sus números (cuántos leads o clientes, cuánto vale cada uno,
  cuánto tardan en contestar), quién decide y qué ha probado ya.
- **Aviso de consentimiento:** en la invitación pon una línea como:

  > «En la llamada me ayuda Claude, un asistente de IA: toma notas y transcribe la conversación para que no se me
  > escape nada. No se graba el audio. Si prefieres que no esté, dímelo y lo quito.»

### Al empezar
- Claude publica un aviso en el chat. Aun así, **dilo en voz alta**: «Como te puse en la invitación, Claude está
  tomando notas y transcribiendo. ¿Te parece bien?». Si dice que no, sácalo de la llamada y toma notas a mano.
- Avisar a todos de que se transcribe no es opcional: es lo que pide Anthropic y lo que pide el sentido común.

### Durante la llamada
Pídele cosas así (en voz alta o por el chat):
- «Claude, empieza un documento con el problema de [cliente] tal como lo está contando.»
- «Apunta los números que acaba de decir: leads al mes, cuánto vale un cliente y cuánto tardan en contestar.»
- «Haz una pizarra con su proceso actual, paso a paso, y marca dónde se pierde el cliente.»
- «¿Qué le pasaba a [cliente parecido] en nuestro CRM?» (solo si tienes la herramienta conectada y das permiso).
- «Antes de acabar, comparte un resumen: problema, números, qué haríamos y siguientes pasos.»

Truco: deja que el cliente vea cómo se monta la pizarra de su proceso. Ver su problema dibujado mientras habla es
más potente que cualquier presentación.

### Al colgar: la propuesta con sus palabras
En la página de la reunión en claude.ai tienes notas, tareas, transcripción, plan y pizarra. Con eso pídele a
Claude la propuesta:

- **Sus palabras:** el problema tal como lo contó él, con frases literales de la transcripción.
- **Lo que le cuesta no hacer nada**, en euros al mes, calculado con **los números que dio él** (y lo que sea
  supuesto, marcado como supuesto).
- **La solución** sin tecnicismos (nada de «agente», «n8n» o «LLM»).
- **Tres opciones** de precio, con la recomendada marcada.
- **Plazos y siguientes pasos.**

Si tienes la skill `/propuesta`, pásale la transcripción y te la monta en ese formato.

Mándale el resumen el mismo día y presenta la propuesta en una segunda llamada (no por correo).

### Si el cliente es externo y Claude no entra
Es lo que pasa por defecto. Opciones:
1. Pide al admin que permita invitados externos (paso 3.3).
2. Mientras tanto, úsalo en tus reuniones internas: preparar la llamada con tu socio, revisar la propuesta, la
   reunión semanal de la agencia.

---

## 5. Lo que no tienes que hacer

- Meter a Claude en una llamada sin avisar de que transcribe.
- Prometer al cliente cosas que salen de la IA sin revisarlas: la propuesta la revisas tú antes de enseñarla.
- Inventarte cifras o casos en la propuesta: solo sus números y los tuyos reales.
- Contar con que entra en Zoom o Teams: de momento solo Google Meet.

---

## 6. El prompt para Claude

Pégalo en Claude (mejor en un proyecto o en Claude Code) y contesta sus preguntas.

```
Quiero usar Claude Meetings (Claude dentro de Google Meet, beta en planes Team y Enterprise) en mis llamadas de
venta para cerrar más clientes. Ayúdame paso a paso, en español, corto y sin tecnicismos, y pregúntame una sola
cosa cada vez. No inventes cifras ni casos: si algo es una estimación, dilo.

1. ACTIVARLO. Pregúntame qué plan de Claude tengo (Team o Enterprise), si soy admin y si mis llamadas son con
   gente de fuera de mi organización. Dime qué tengo que activar o pedir al admin (incluido permitir invitados
   externos, que por defecto está apagado) y cómo hacer una prueba sin cliente.

2. EL CLIENTE. Pregúntame a quién tengo la próxima llamada (nombre, web, sector, lo que me ha contado) y qué
   servicio de IA le quiero vender.

3. ANTES DE LA LLAMADA. Escríbeme el aviso de consentimiento para la invitación (Claude transcribe, no se graba
   el audio, si no quiere lo quito) y las preguntas de diagnóstico: su proceso, sus números, quién decide y qué
   ha probado.

4. DURANTE LA LLAMADA. Dame la lista de frases exactas que le diré a Claude en la reunión: empezar el documento
   con su problema, apuntar sus números, montar la pizarra de su proceso y compartir el resumen antes de acabar.

5. AL COLGAR. Cuando te pegue las notas y la transcripción de la reunión, escribe la propuesta: su problema con
   sus palabras literales, lo que le cuesta no hacer nada en euros al mes con sus números (marca lo supuesto),
   la solución sin tecnicismos, tres opciones de precio con la recomendada marcada y los siguientes pasos.

6. EL SEGUIMIENTO. El mensaje para mandarle el resumen hoy y proponerle la llamada para presentar la propuesta.

Empieza por el paso 1.
```

---

Sell Your AI · Claude y Claude Meetings son marcas de Anthropic; Google Meet, de Google.

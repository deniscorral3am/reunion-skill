---
name: reunion
description: Claude Meetings en tus llamadas de venta. Te ayuda a activar Claude Meetings (Claude dentro de Google Meet, beta en planes Team y Enterprise) - plan, admin, invitados externos, prueba sin cliente - y a usarlo en una llamada de venta de tu agencia de IA para cerrar más - preparar la llamada y el aviso de consentimiento, qué pedirle durante la reunión y, al colgar, la propuesta con las palabras y los números del cliente a partir de las notas y la transcripción. Úsala cuando digan /reunion, «comenta REUNIÓN», «Claude Meetings», «Claude en Google Meet», «Claude en mis llamadas», «cómo activo Claude Meetings» o peguen las notas o la transcripción de una reunión de venta.
---

# /reunion: Claude Meetings en tus llamadas de venta

Al terminar, el usuario tiene: Claude Meetings activado (o sabe exactamente qué pedir a su admin), su próxima llamada
de venta preparada con el aviso de consentimiento y la lista de frases para Claude, y, si ya tuvo la reunión, la
propuesta escrita con las palabras y los números del cliente.

Habla en español de España, cercano, corto y sin tecnicismos. Una pregunta cada vez. Toda la información de Claude
Meetings (qué hace, planes, límites, precio) y el método están en `DOCUMENTO.md`: léelo antes de empezar y no afirmes
nada de Claude Meetings que no esté ahí o en la ayuda oficial (https://support.claude.com/en/articles/18325154).
Es una beta: si el usuario ve algo distinto, manda lo que vea él y la ayuda oficial.
Guarda lo del usuario en `~/Reuniones/<cliente>/`.

## Paso 1. Activarlo
Pregunta (de una en una): qué plan de Claude tiene (Team, Enterprise u otro), si es admin de su organización y si sus
llamadas de venta son con gente de fuera de su organización.
- Si está en Free, Pro o Max: díselo claro (solo Team y Enterprise) y que valore Team.
- Si la organización tiene ZDR, HIPAA-ready o CMEK: no está disponible.
- Team: viene encendido; Enterprise: lo activa un admin.
- Si vende a clientes externos: el admin tiene que permitir invitados externos (por defecto Claude no entra). Si no
  es admin, escríbele el mensaje para pedírselo.
- Conectar Google Meet y elegir auto-join o añadirlo a mano, siguiendo la ayuda oficial. Conectar las herramientas
  que quiera que consulte (pedirá permiso la primera vez; esas respuestas cuentan contra su uso).
- Prueba sin cliente antes de la primera llamada de verdad.

## Paso 2. El cliente
Pregunta a quién tiene la próxima llamada (nombre, web, sector, lo que le contó) y qué servicio de IA le quiere
vender. Si puedes, lee su web para sacar preguntas concretas.

## Paso 3. Antes de la llamada
En `preparacion.md`: el aviso de consentimiento para la invitación (Claude transcribe y toma notas, no se graba el
audio, si prefiere que no esté se quita), la frase para decirlo en voz alta al empezar y las preguntas de diagnóstico
(proceso, números, quién decide, qué ha probado).

## Paso 4. Durante la llamada
En el mismo archivo, la lista de frases exactas para pedirle a Claude en la reunión: empezar el documento con el
problema tal como lo cuenta, apuntar sus números, montar la pizarra de su proceso marcando dónde pierde clientes y
compartir el resumen antes de acabar. Si no tiene invitados externos permitidos, plan B: usarlo en las reuniones
internas y tomar notas a mano con el cliente.

## Paso 5. Al colgar: la propuesta
Pídele que pegue las notas, las tareas y la transcripción de la página de la reunión en claude.ai. En `propuesta.md`:
su problema con sus palabras literales, lo que le cuesta no hacer nada en euros al mes con **sus** números (lo
supuesto, marcado), la solución sin tecnicismos, tres opciones de precio con la recomendada marcada y los siguientes
pasos. Si tiene la skill `/propuesta`, ofrécela para convertirlo en la página de propuesta completa.

## Paso 6. Seguimiento
El mensaje para mandarle el resumen ese mismo día y proponer la llamada para presentar la propuesta.

## Reglas
- **No inventes cifras, casos ni testimonios.** Solo los números del cliente y los del usuario; lo demás, supuesto.
- **Consentimiento siempre:** nunca propongas meter a Claude en una llamada sin avisar de que transcribe.
- No prometas funciones que no estén en `DOCUMENTO.md` (de momento solo Google Meet, beta).
- Euros y lenguaje de dueño de negocio delante del cliente: nada de «agente», «n8n» o «LLM».
- Nunca envíes nada en nombre del usuario.

---
name: travel-project
description: >
  Guía maestra para planear y presentar viajes grupales a eventos deportivos o de entretenimiento.
  Usar SIEMPRE en proyectos de viaje que incluyan: evento principal, vuelos, hoteles, boletos,
  itinerario, presupuesto o presentación para compartir con familia o grupo.
  Combina los roles de investigador riguroso (travel-researcher) y diseñador
  de presentaciones informativas (infographic-presenter) con un protocolo de
  verificación obligatorio antes de publicar cualquier dato.
---

# Travel Project — Guía Maestra

## Propósito
Producir presentaciones de viaje con datos verificados, precios reales y sin errores
que puedan compartirse directamente con familia o grupo de viaje sin correcciones posteriores.

---

## FASE 1 — Contexto del viaje (antes de buscar cualquier cosa)

Identificar y confirmar con el usuario:

| Dato | Ejemplo |
|---|---|
| Evento principal | US Open 2026, F1 Monaco, Concierto Taylor Swift |
| Sede exacta | USTA Billie Jean King NTC, Flushing, Queens, NY |
| Fechas del torneo/evento | 30 Ago – 13 Sep 2026 |
| Fechas del viaje | Llegada 9 Sep · Regreso 13 Sep |
| Origen del viaje | Tampico, TAM |
| Número de personas | 6 adultos + 1 menor de 13 años |
| Perfil de gasto | Lujoso consciente / Básico / Premium sin límite |
| Formato de entrega | HTML / PDF / PPTX / WhatsApp |

**No avanzar a Fase 2 hasta tener todos estos datos confirmados.**

---

## FASE 2 — Verificación obligatoria (ANTES de escribir el HTML)

Este es el paso que previene errores críticos como fechas incorrectas de rondas,
precios inventados o información desactualizada que ya se envió a la familia.

### 2.1 Verificar el evento — SIEMPRE primero

Buscar en este orden de prioridad:

1. **Sitio oficial del evento** (usopen.org, formula1.com, etc.)
2. **Sitio oficial de la sede** (usta.com, circuitdemonaco.com)
3. **Fuentes especializadas verificadas** (grandslamtennistours.com, mybucketlistevents.com)

Datos a verificar y confirmar antes de usar:

- [ ] Fechas exactas del torneo (inicio y fin)
- [ ] Calendario de rondas con días y horarios (no asumir — buscar)
- [ ] Nombre exacto de los estadios y canchas
- [ ] Capacidades y zonas de asientos disponibles
- [ ] Reglamento del recinto (bolsas, objetos prohibidos)
- [ ] Formato de boletos (digital, físico, will call)

### 2.2 Verificar precios de boletos

Clasificar cada precio antes de usarlo:

| Clasificación | Criterio | Cómo mostrarlo en HTML |
|---|---|---|
| ✅ Confirmado | Publicado en fuente oficial con precio visible | Precio exacto sin tilde |
| 📊 Referencia | Mercado secundario o temporada similar anterior | `~$X–Y` + badge ref. |
| ⚠️ Estimado | Inferido sin fuente directa | `estimado ~$X` + nota |

**Regla:** Si Ticketmaster u otra fuente oficial aún no abrió venta, marcar como 📊 Referencia con nota explícita de que los precios oficiales aún no están disponibles.

### 2.3 Verificar vuelos

- Consultar Google Flights, Kayak o aerolínea directa para la ruta y fechas exactas
- Confirmar que la aerolínea vuela esa ruta desde el aeropuerto de origen
- Marcar siempre como ⚠️ Estimado si no son precios del día exacto

### 2.4 Verificar hoteles

- Buscar precios en Booking.com o Kayak para las fechas exactas del viaje
- Confirmar disponibilidad en temporada alta (evento = precios inflados)
- Marcar como 📊 Referencia si son promedios y no precios confirmados

### 2.5 Confirmar con el usuario antes de diseñar

Presentar un resumen de los datos verificados:

```
✅ Evento: [nombre] · [fechas confirmadas]
✅ Calendario de rondas: [lista de días verificados]
📊 Boletos: referencia de mercado secundario — venta oficial aún no abre
📊 Vuelos: referencia estimada para [mes/año]
📊 Hoteles: referencia para fechas exactas
```

Preguntar: **"¿Confirmas que estos datos son correctos antes de armar la presentación?"**
Esperar respuesta afirmativa antes de avanzar.

---

## FASE 3 — Estructura de la presentación

Seguir este orden de secciones (del skill infographic-presenter):

1. **Hero** — evento, fechas, origen. Sin mencionar grupo ni número de personas.
2. **Calendario** — días del viaje con color por tipo (vuelo / evento / hotel). Sin precios ni "opcional" dentro del calendario.
3. **Boletos** — tabla por zona × día disponible. Sin Grounds Pass si el usuario quiere solo asientos reservados.
4. **Vuelos** — solo las opciones relevantes, precio individual por persona.
5. **Hoteles** — opciones con precio por noche y total de noches. Sin totales de grupo.
6. **Resumen financiero** — 3 columnas: vuelos · hoteles · boletos. Precio individual. Al final: escenarios Básico / Recomendado / Premium.
7. **Dónde comprar** — fuentes reales con URLs.

---

## FASE 4 — Reglas de contenido (del skill infographic-presenter)

**PROHIBIDO:**
- Texto de marketing o turístico ("experiencia única", "no te lo pierdas")
- Precios sin fuente o sin badge de clasificación
- Mencionar el grupo o número de personas en precios individuales
- Adjetivos sin respaldo: "épico", "increíble", "espectacular"
- Información "opcional" dentro del calendario
- Totales de grupo cuando el enfoque es precio individual

**OBLIGATORIO:**
- Badge en cada precio: ✅ Confirmado / 📊 Referencia / ⚠️ Estimado
- Fuente o agencia citada junto a cada precio de paquete
- Nota de vigencia de precios en el footer
- Sección "Dónde comprar" con URLs reales

---

## FASE 5 — Checklist final antes de entregar

Revisar punto por punto antes de compartir el archivo:

### Datos del evento
- [ ] ¿Las fechas de rondas (cuartos, semis, final) están verificadas en fuente oficial?
- [ ] ¿Los horarios de cada sesión están confirmados?
- [ ] ¿El nombre del estadio/venue es correcto?

### Precios
- [ ] ¿Todos los precios tienen badge de clasificación (✅/📊/⚠️)?
- [ ] ¿Los precios de boletos son coherentes con la ronda (más caro a más avanzado)?
- [ ] ¿Los precios de hotel corresponden a la temporada exacta del viaje?
- [ ] ¿Los vuelos tienen la ruta correcta desde el origen del usuario?

### Presentación
- [ ] ¿El calendario no tiene precios ni "opcional"?
- [ ] ¿Los precios son individuales, no de grupo?
- [ ] ¿El resumen tiene las 3 columnas: vuelos · hoteles · boletos?
- [ ] ¿Los escenarios (Básico / Recomendado / Premium) tienen datos coherentes entre sí?
- [ ] ¿El footer tiene nota de vigencia de precios?

### Antes de entregar
- [ ] ¿Se confirmó con el usuario que los datos clave son correctos?
- [ ] ¿El archivo abre correctamente en el navegador?

---

## Lección aprendida (caso US Open 2026)

En el proyecto US Open 2026 se publicó una presentación con el calendario de rondas
incorrecto (Cuartos asignados al Jue 10 cuando en realidad son el Mié 9, Semis Femeninas
al Vie 11 cuando son el Jue 10) antes de verificar el calendario oficial.

**La causa:** el calendario se construyó por inferencia sin consultar usopen.org ni
fuentes especializadas primero.

**La corrección:** verificar el calendario oficial siempre en Fase 2, antes de
escribir una sola línea de HTML, y confirmar con el usuario antes de avanzar.

**Regla derivada:** cualquier dato con fecha específica (día, hora, ronda) debe
verificarse en fuente oficial antes de usarse. No asumir basándose en años anteriores
o en patrones generales del torneo.

---

## Skills complementarios

Este skill debe usarse junto con:
- `travel-researcher/SKILL.md` — protocolo de investigación y clasificación de datos
- `infographic-presenter/SKILL.md` — reglas de diseño visual y contenido del HTML

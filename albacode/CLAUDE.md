# Proyecto: ALBACODE

> Este archivo se carga **solo cuando trabajas dentro de esta carpeta**. Contiene lo que
> es cierto para este proyecto y no para el resto del vault.
> Las reglas globales siguen vigentes: están en el `CLAUDE.md` de la raíz del vault.

---

## Qué es

Empresa propia de Anthony, fundada tras su salida de
[[../../wiki/entidades/intezia.md|Intezia]] en septiembre de 2026. Ofrece tres líneas de
servicio: **automatización de procesos**, **especializaciones en IA** y **desarrollo a
medida**.

A diferencia de los demás proyectos del vault, ALBACODE no es un cliente: es el negocio
propio de Anthony. Aquí él es el proveedor, no el consultor contratado por un tercero.

- **Estado:** activo <!-- activo | en pausa | cerrado -->
- **Empezó:** 2026-09-11 (decisión de fundarlo)
- **Arranque operativo:** 2026-09-13, al día siguiente de cerrar el último compromiso con
  Intezia (Sesión 2 de Bolipuerto, sábado 2026-09-12)

## Objetivo

Convertir la experiencia de Anthony en IA aplicada y automatización en un negocio propio
que facture, partiendo de cero en marca y cartera, con pymes venezolanas como primer
mercado y dos clientes pagos como meta de cierre de noviembre de 2026.

## Quién participa

- Fundador y único operador: Anthony Bastidas
- Sin equipo. Esta restricción es la que gobierna todas las decisiones de alcance: lo que
  no pueda ejecutar una sola persona, no entra al plan.

---

## Reglas propias de este proyecto

- **Tres líneas en el catálogo, una sola en construcción.** Anthony decidió abrir las tres
  desde el inicio. Para que sea ejecutable por una persona sola, se separa lo que se
  *ofrece* de lo que se *construye*: el material demostrable, los casos y el guion de venta
  se construyen de uno en uno, empezando por automatización. Revisión honesta del orden a
  las seis semanas (~2026-10-25) si automatización no ha producido cliente.
- **Mercado inicial: pymes venezolanas.** Ciclo de venta corto, cobro sin fricción y
  posibilidad de reunión presencial. El mercado internacional queda para cuando haya casos
  demostrados.
- **Posicionamiento:** el 80/20 de Anthony — la IA bien usada resuelve el 80% de los
  problemas prácticos; el 20% restante exige criterio humano. Ver `SOUL.md`. No se vende
  "IA" en abstracto, se vende el 80% automatizado con criterio en el resto.
- **Precios por paquete cerrado, nunca por hora.** Cobrar por hora castiga la velocidad, que
  es justamente la ventaja de trabajar con IA. Los primeros tres clientes se cobran bajo a
  cambio del permiso escrito de publicar el caso.
- **50% por adelantado desde el primer cliente**, sin excepciones.
- **No inventar cifras de mercado.** Cualquier precio o dato de costo va con fuente o se
  marca como pendiente de verificar. Esto vale especialmente para los trámites legales y
  fiscales venezolanos, que deben consultarse con un contador y no con internet.

### Límites con Intezia — no negociables

Anthony no firmó acuerdo de no competencia, así que legalmente puede ofrecer servicios
similares. La línea no es legal, es de reputación, y en un mercado pequeño esa es la
restricción que más pesa.

- **No abordar a los clientes de Intezia**: Bolipuerto, Grupo Corpos, Venemergencia,
  Hidrocaven, Credicard, Dr. Care. Si alguno busca a Anthony por iniciativa propia, es otra
  conversación — pero la iniciativa nunca sale de él.
- **No reutilizar material de Intezia**: decks, workbooks, sets de prompts y dashboards
  hechos allí son de Intezia. El programa de ALBACODE se construye desde cero.
- **No replicar sus instrumentos de medición** con otro nombre. El aprendizaje de que hay
  que medir es de Anthony; el instrumento concreto, no.
- **Sí puede declarar su paso por Intezia** y lo que hizo allí: es su trayectoria
  profesional y va en CV y web con naturalidad.

Si alguna petición futura roza estos límites, **díselo antes de ejecutarla**.

---

## Dónde vive qué

```
albacode/
├── CLAUDE.md       ← este archivo
├── raw/
│   ├── entrada/    ← material que solo concierne a este proyecto
│   └── procesadas/
├── salida/         ← documentos y artefactos del negocio
│   ├── Roadmap_ALBACODE.html          ← roadmap de arranque, 4 fases hasta fin de 2026
│   └── Manual_Operacion_ALBACODE.html ← funciones del fundador, captación de clientes y
│                                        estrategia de marketing para Venezuela
└── notas/          ← decisiones, borradores, material de trabajo
```

**Nada suelto:** ningún documento generado va directo en la raíz de este proyecto.

---

## Estado actual

Recién fundado el 2026-09-11. Existe el roadmap de arranque
([[salida/Roadmap_ALBACODE.html|Roadmap_ALBACODE.html]]) con cuatro fases hasta fin de año:
Existir (13-20 sept), Evidencia (21 sept - 18 oct), Primeros clientes (19 oct - 15 nov) y
Formalizar y repetir (16 nov - 31 dic).

Nada ejecutado todavía. El primer bloque de trabajo real arranca el 2026-09-13.

**El obstáculo identificado como número uno** no es comercial sino de evidencia: el GitHub
de Anthony (`github.com/AnthonyAle2607`) tiene cinco repositorios sin descripción, ninguno
de IA ni de automatización, y contradice lo que promete su CV. Es el primer sitio donde
mira un cliente o un reclutador, y hoy juega en contra. Arreglarlo es la Fase 1.

## Decisiones tomadas

- **2026-09-11** — Se funda ALBACODE con tres líneas de servicio (automatización, IA,
  desarrollo), mercado inicial en pymes venezolanas, y como apuesta principal a dedicación
  completa. Se adoptó la regla "tres en el catálogo, una en construcción" para hacer
  ejecutable la decisión de abrir las tres a la vez: la alternativa —construir las tres en
  paralelo con un fundador solo— choca con el tercer filtro de decisión de Anthony
  ("que sea factible en la práctica", ver `SOUL.md`).
- **2026-09-11** — Se fijaron los límites éticos con Intezia pese a no existir acuerdo
  firmado, por criterio de reputación en un mercado pequeño.
- **2026-09-11** — Estrategia de marketing definida sobre cuatro investigaciones al mercado
  venezolano (panorama digital, viabilidad de pauta, networking B2B, competencia). Las
  decisiones de canal, con su razón:
  - **TikTok orgánico como prioridad 1.** Es la coincidencia rara que ordena todo: tiene la
    mayor audiencia alcanzable del país (70-84% de adultos con internet), **nadie puede
    pautar ahí** porque TikTok no habilita creación de cuentas publicitarias para Venezuela,
    y de todos los competidores locales identificados solo uno publica en esa red.
  - **WhatsApp Business como canal de cierre**, con cuenta separada de la personal. En
    Venezuela es infraestructura comercial de facto, también en B2B. Nunca difusión masiva.
  - **LinkedIn descartado para prospección**, solo credibilidad. Sus 5,6-6,4M de cuentas
    venezolanas son techo teórico (buena parte diáspora) sin evidencia de actividad local.
  - **Nada de webinars ni transmisiones en vivo como eje**: el 90% de los hogares sufre
    cortes eléctricos. Todo pregrabado, corto y descargable.
  - **Publicar precios**, aunque sea un "desde". Ninguna empresa venezolana del sector lo
    hace — es diferenciación instantánea y de costo cero.
  - **No pautar hasta tener un caso publicable.** Sí es posible pautar desde Venezuela (el
    obstáculo es bancario, no de sanciones; se resuelve con tarjeta virtual USD de Zinli,
    Neomoon o Airtm), pero pagar tráfico hacia un perfil sin pruebas es quemar dinero.
- **2026-09-11** — Se identificó como jugada de mayor apalancamiento **fundar la comunidad de
  IA aplicada que no existe en Caracas**: GDG Caracas murió en junio de 2017 y Caracas
  Blockchain Week no tiene ediciones desde 2023. Convocar y facilitar es el oficio de
  Anthony, y le daría posición de autoridad sin comprarla.

## Pendientes

- [ ] Verificar que el nombre ALBACODE esté libre: registro mercantil, redes y dominio
- [ ] Definir cuántos meses puede sostener sin facturar (determina si acepta trabajo por
      horas en paralelo)
- [ ] Consultar con un contador venezolano la figura legal y fiscal que conviene
- [ ] Definir el mecanismo de cobro internacional antes del primer cliente de fuera
- [ ] Conseguir cotizaciones reales de dos o tres proveedores locales para fijar precios
- [ ] Verificar si Meta restringe el objetivo "clic a WhatsApp" para cuentas venezolanas
      (fuente única sin confirmar por Meta; si es cierto afecta toda la pauta de conversión)
- [ ] Verificar si el gremio de TI **Cavedatos** es la misma entidad a cuyo nombre se
      facturaba la propuesta de Bolipuerto. Si lo es, hay contacto previo aprovechable — pero
      el vínculo pasaría por Intezia, no por Anthony
- [ ] Conseguir entrada al **Startup Venezuela Summit 2026** (21-23 octubre, Caracas), que cae
      justo al inicio de la Fase 2 de captación
- [ ] Abrir cuenta en Zinli, Neomoon o Airtm para tener la tarjeta virtual USD lista antes de
      necesitar pautar

---

## Skills y subagentes propios

*Si este proyecto desarrolla necesidades repetitivas, pueden vivir aquí sus propias
herramientas en `.claude/skills/` y `.claude/agents/` dentro de esta carpeta.*

*Regla: no crees una skill de proyecto hasta haber hecho la tarea a mano tres veces.*

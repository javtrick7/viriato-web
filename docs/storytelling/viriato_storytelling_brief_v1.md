# Viriato Web - Storytelling Brief v1

> Fecha: 2026-03-06
> Repo: `viriato-web`
> Estado: documento base para iterar antes de tocar la web

## 1. Objetivo editorial

Este documento define la base narrativa de `viriato-web` antes de reescribir textos o abrir nuevas paginas. La web actual ya apunta a ideas buenas, pero todavia no ordena con suficiente fuerza lo que hace singular al proyecto: una explotacion real que funciona a la vez como sistema productivo, laboratorio vivo y origen de una herramienta digital util.

La tarea de este brief es resolver cuatro cosas:

1. Dar una tesis mas clara y mas memorable.
2. Evitar el tono institucional generico o el manifiesto vacio.
3. Introducir `MindFarm` como producto de verdad, no solo como enlace externo.
4. Anclar cada mensaje fuerte a una base real o marcarlo como placeholder.

### Defaults ya cerrados

- Eje narrativo: `sistema vivo`
- Audiencia principal: `doble foco`
- Tono: `sereno con nervio`
- Politica de claims: `validado + placeholders marcados`
- Navegacion objetivo:
  - `MindFarm` en el menu principal debe abrir una pagina interna
  - esa pagina debe incluir un CTA directo a `mindfarm-app`

## 2. Benchmark de referentes oficiales

Los referentes se han usado para estudiar estructura narrativa, orden de argumentos y relacion entre mision, prueba y participacion. No se trata de copiar estetica ni de importar promesas ajenas.

### OpenTEAM

Fuente oficial: <https://openteam.community/>

Lo que hacen bien:

- Presentan tecnologia, investigacion y comunidad como un mismo ecosistema.
- No abren con features; abren con una mision compartida y una red de actores.
- La sensacion es de infraestructura abierta al servicio de agricultores y suelo.

Patron util para Viriato:

- Hablar de sistema y comunidad antes que de modulos.
- Presentar el conocimiento como algo que se construye en red y se comparte.

Lo que no conviene copiar:

- Un tono demasiado ecosistemico puede diluir la materialidad del campo real de Viriato.

### Climate Farmers

Fuente oficial: <https://climatefarmers.org/>

Lo que hacen bien:

- Construyen una causa clara y reconocible.
- La red y la transformacion del territorio aparecen antes que la tecnologia.
- Invitan a formar parte de un movimiento, no solo a consumir una solucion.

Patron util para Viriato:

- La colaboracion debe presentarse como una forma de construir herramientas utiles desde campo real.
- Conviene que la web deje ver ambicion, no solo correccion tecnica.

Lo que no conviene copiar:

- Un exceso de tono de movimiento puede quitar precision a la parte producto.

### Organic Valley

Fuente oficial: <https://www.organicvalley.coop/>

Lo que hacen bien:

- La cooperativa y los agricultores son el centro del relato.
- La legitimidad no se declara: se desprende de a quien sirven y desde donde hablan.
- Lo cooperativo funciona como credencial, no como adorno.

Patron util para Viriato:

- Viriato debe sonar a proyecto arraigado en una explotacion y en una cooperativa, no a web de startup.
- La palabra "cooperativa" tiene que aportar sentido, no solo contexto legal.

Lo que no conviene copiar:

- No convertir todo el relato en identidad institucional; aqui tambien hay laboratorio y producto.

### Farm Hack

Fuente oficial: <https://farmhack.org/>

Lo que hacen bien:

- El discurso es practico, compartible y orientado a resolver problemas reales.
- La apertura se expresa como utilidad y transferencia, no solo como principio abstracto.

Patron util para Viriato:

- Cuando hablemos de codigo abierto y conocimiento abierto, debe notarse para que sirve eso en una finca.
- La apertura debe conectarse con replicabilidad y accesibilidad.

Lo que no conviene copiar:

- Un tono demasiado maker puede restar seriedad si se aplica a toda la web.

### farmOS

Fuente oficial: <https://farmos.org/>

Lo que hacen bien:

- Explican el producto con claridad funcional.
- El software se entiende rapido porque deja claro que hace, para quien y con que filosofia.
- El hecho de ser open source se integra en la propuesta de valor, no queda aparte.

Patron util para Viriato:

- La futura pagina `MindFarm` debe explicarse como producto en lenguaje operativo.
- El visitante debe salir sabiendo que hace la herramienta hoy.

Lo que no conviene copiar:

- Un exceso de enumeracion funcional puede enfriar la historia si no se conecta con el campo real.

### CropX

Fuente oficial: <https://cropx.com/>

Lo que hacen bien:

- Producto explicado con mucha nitidez: datos, interpretacion, accion.
- Relacion directa entre lectura del suelo y decisiones agronomicas.
- La promesa de eficiencia esta articulada como mecanismo, no solo como slogan.

Patron util para Viriato:

- `MindFarm` debe hablar de decisiones mas claras, no solo de analitica.
- "Sostenible y rentable" debe sostenerse con palancas concretas.

Lo que no conviene copiar:

- El tono corporativo o demasiado comercial chocaria con la identidad cooperativa de Viriato.

### agrifoodTEF

Fuente oficial: <https://agrifoodtef.eu/>

Lo que hacen bien:

- Presentan infraestructura, testeo y capacidad de validacion con mucha credibilidad.
- La institucion se entiende porque se ven los casos de uso, la experimentacion y la transferencia.

Patron util para Viriato:

- `Living Lab` debe sonar a capacidad instalada y a marco de prueba, no solo a idea inspiradora.
- La credibilidad institucional se gana con estructura, metodo y escenarios de colaboracion.

Lo que no conviene copiar:

- Un tono excesivamente europeo o programatico haria perder cercania con agricultores.

### LILAS4SOILS

Fuente oficial: <https://www.lilas4soils.eu/>

Lo que hacen bien:

- Hacen visible la logica de living labs: experimentacion, red, aprendizaje y replicacion.
- El suelo aparece como eje material y no como recurso retorico.

Patron util para Viriato:

- La pagina `Living Lab` debe insistir en que la finca es infraestructura de investigacion aplicada.
- Conviene hablar de transferencia y conocimiento util, no solo de monitorizacion.

Lo que no conviene copiar:

- No perder la escala concreta del proyecto en una retorica de red demasiado amplia.

### Sintesis de patrones que si conviene adoptar

- Abrir con una idea madre clara, no con una descripcion blanda.
- Mostrar el proyecto como sistema antes de listar partes.
- Dar una prueba concreta temprano: campo real, frecuencia de lectura, modelo operativo, flujo real.
- Separar bien el rol de cada pagina.
- Tratar la colaboracion como continuacion natural del proyecto, no como formulario final.
- En la pagina de producto, explicar resultado operativo antes que arquitectura tecnica.

## 3. Diagnostico del sitio actual

### Lo que ya funciona

- La arquitectura en tres niveles esta bien orientada.
- La home ya intenta explicar problema, vision y estructura.
- `Proyecto` y `Living Lab` tienen una division razonable de temas.
- El tono general no cae en tecnosolucionismo hueco.

### Lo que hoy suena generico o flojo

- La home describe bien, pero impacta poco: informa antes de tensar.
- Varias frases podrian pertenecer a muchos proyectos de agrotech o sostenibilidad.
- Hay poca sensacion de prueba temprana. Se tarda en notar que esto ya existe de verdad.
- La promesa de `MindFarm` esta repartida y rebajada. No aparece como producto central.

### Lo que se repite sin generar avance

- "finca real + ciencia + tecnologia" aparece varias veces, pero con formulaciones similares.
- "agricultura regenerativa" y "tecnologia accesible" se repiten como ideas declaradas, no siempre como consecuencia de algo concreto.
- `Proyecto` y `Home` comparten demasiado terreno conceptual.

### Lo que falta

- Falta una pagina de producto `MindFarm`.
- Falta una explicacion clara de "gemelo digital" en lenguaje comprensible.
- Falta una union explicita entre sostenibilidad, precision y rentabilidad.
- Falta un ledger de claims para no mezclar hechos operativos con aspiracion o benchmarking.

### Diagnostico de navegacion

Problema actual:

- `MindFarm` en el menu apunta directamente a la app externa.
- Eso impide construir un relato de producto.
- El visitante salta de narrativa institucional a herramienta sin puente.

Cambio recomendado:

- `MindFarm` debe pasar a ser una pagina interna.
- La app externa debe vivir como CTA principal dentro de esa pagina.

## 4. Arquitectura narrativa propuesta

### Idea fuerza

Viriato no es una finca con una app al lado. Es una explotacion real que se convierte en laboratorio vivo y en herramienta util para pequenas explotaciones.

### Promesa principal

Convertir una finca real en un sistema capaz de producir alimento, generar conocimiento aplicado y traducir datos del suelo en decisiones mas claras.

### Promesa corta para la home

Agricultura real, investigacion aplicada y decisiones mas claras para pequenas explotaciones.

### Pilares de mensaje

#### 1. Campo real, no laboratorio aislado

La legitimidad del proyecto nace en que todo se prueba en una explotacion real, con suelo, clima y limites reales.

#### 2. Living Lab con vocacion de transferencia

El objetivo no es solo medir. Es producir conocimiento util, replicable y conectado con el territorio.

#### 3. Producto util, no demo conceptual

`MindFarm` debe presentarse como herramienta operativa para monitorizar, interpretar y decidir, no como visualizacion bonita.

#### 4. Agricultura de precision accesible

La precision aqui no significa complejidad innecesaria. Significa regar mejor, leer mejor el suelo y reducir decisiones a ciegas.

#### 5. Sostenibilidad con mecanismo economico

La sostenibilidad debe explicarse tambien como mejor uso del agua, menos error y mas aprendizaje acumulado. Es decir, como condicion de resiliencia y de rentabilidad.

### Tono

Sereno con nervio:

- frases claras
- sin grandilocuencia
- con un punto de ambicion
- con mas contraste y mas precision

### Vocabulario recomendado

Usar:

- explotacion real
- laboratorio vivo
- conocimiento aplicado
- decisiones mas claras
- leer el suelo
- agricultura de precision accesible
- gemelo digital
- transferencia
- campo real
- herramienta util

Evitar o rebajar:

- revolucionar
- transformar el mundo
- IA sin contexto
- smart farming como etiqueta vacia
- innovacion por la innovacion
- eficiencia sin explicar de donde sale

### Regla de oro de redaccion

Cada pagina debe sumar una capa nueva:

- `Home` abre la tesis.
- `Proyecto` explica el sistema.
- `Living Lab` demuestra el marco experimental.
- `MindFarm` aterriza el producto.
- `Colaboraciones` propone formas concretas de entrar.
- `Contacto` cierra sin ruido.

## 5. Ledger de claims

| Claim | Estado | Uso recomendado | Base |
|---|---|---|---|
| Viriato integra explotacion, living lab y herramienta digital | Validado | Si | `docs/user_guides/estructura_proyecto_global.md` |
| El living lab esta integrado en una explotacion real | Validado | Si | `docs/user_guides/estructura_proyecto_global.md` |
| MindFarm convierte datos de suelo, clima y manejo en decisiones operativas | Validado | Si | `MindFarm-app/docs/mindfarm_product_spec_v1.md` |
| El sistema trabaja con monitorizacion continua cada 15 min | Validado | Si | `config/projects/viriato_lab.yaml`, `docs/user_guides/Informes_tecnicos/metricas_mvp.md` |
| El gemelo digital basado en FAO-56 esta operativo en version MVP | Validado | Si | `docs/user_guides/Informes_tecnicos/informe_gemelo_digital_v1_estado_y_mejoras.md` |
| Existe un despliegue operativo en Padul | Validado | Si | `config/projects/viriato_lab.yaml` |
| Sierra de Gata y Padul forman parte del marco territorial del proyecto | Validado | Si, explicando que el despliegue activo hoy esta en Padul | `MindFarm-app/docs/mindfarm_product_spec_v1.md` |
| Ahorro de ~150.000 litros por temporada | Placeholder | Solo con disclaimer claro de benchmark | `MindFarm-app/docs/mindfarm_product_spec_v1.md` |
| Ahorro del 30-40% de agua | Placeholder | Solo como potencial basado en literatura, no como resultado propio | `MindFarm-app/docs/playbook.md`, `MindFarm-app/docs/mindfarm_product_spec_v1.md` |
| Colaboracion activa con CICYTEX | No usar | No hasta poder sostenerla formalmente | hoy hay alineacion cientifica y referencias, no colaboracion demostrada en la web |
| Primer campo de Extremadura con gemelo digital | No usar | No | no hay base suficiente |
| Rentabilidad demostrada | No usar | No como claim cerrado | hoy puede hablarse de potencial economico y mejor decision, no de ROI probado |

### Formula recomendada para claims sensibles

- `validado`: usar sin problema
- `placeholder`: usar solo si se marca como estimacion, benchmark o potencial
- `no usar`: retirar de la web hasta tener evidencia suficiente

## 6. Arquitectura de informacion recomendada

- `Home`
  - Rol: abrir la tesis del proyecto en menos de 10 segundos
- `Proyecto`
  - Rol: explicar por que existe Viriato y como se organiza el sistema completo
- `Living Lab`
  - Rol: demostrar la capacidad experimental y la logica de validacion
- `MindFarm`
  - Rol: actuar como pagina de producto y puente hacia la herramienta real
- `Colaboraciones`
  - Rol: abrir la puerta a universidades, centros, proyectos y aliados tecnologicos con propuestas mas concretas
- `Contacto`
  - Rol: cierre directo, breve y sin retorica redundante

## 7. Copy deck por pagina

Los textos siguientes son base de trabajo. No son version final cerrada; son una propuesta ya orientada a implementacion.

### 7.1 Home

#### Rol

Explicar rapido que Viriato es un sistema vivo: explotacion real, investigacion aplicada y producto util.

#### Estructura recomendada

1. Hero
2. El problema
3. Un sistema vivo en tres capas
4. MindFarm como consecuencia tangible
5. Prueba de realidad
6. CTA final

#### Copy propuesto

**Eyebrow**

Viriato · explotacion real · living lab · producto digital

**Titular**

Una finca que produce alimento, conocimiento y decisiones mas claras

**Subtitulo**

Viriato convierte una explotacion real en laboratorio vivo y en herramienta util para pequenas explotaciones. Agricultura regenerativa, investigacion aplicada y un producto digital para leer mejor el suelo y decidir mejor en campo.

**CTA principal**

Conocer el proyecto

**CTA secundario**

Ver MindFarm

**Seccion: El problema**

Las pequenas explotaciones tienen cada vez menos margen para decidir a ciegas. El agua cuesta mas, el clima se vuelve menos predecible y muchas herramientas de agricultura de precision siguen pensadas para otra escala, otro presupuesto y otra realidad.

**Seccion: Un sistema vivo**

Viriato no separa artificialmente produccion, investigacion y herramienta. La explotacion genera preguntas reales. El living lab las convierte en experimentacion y datos. MindFarm traduce ese trabajo en decisiones operativas.

**Seccion: MindFarm**

MindFarm es la capa de producto de este sistema. No es una app decorativa: es la herramienta que convierte datos de suelo, clima y manejo en una lectura operativa de la finca.

**Seccion: Prueba de realidad**

Hoy ya existe un despliegue operativo en campo, con lectura continua cada 15 minutos y un gemelo digital MVP basado en FAO-56 para recomendacion de riego y proyeccion.

**CTA final**

Si quieres entender el sistema completo, explorar el living lab o entrar en la herramienta, este proyecto ya se puede recorrer de extremo a extremo.

### 7.2 Proyecto

#### Rol

Explicar por que existe Viriato, a quien quiere servir y como se relacionan sus tres capas.

#### Estructura recomendada

1. Hero
2. Por que existe ahora
3. Tres capas, un solo sistema
4. A quien sirve
5. Territorios y lineas
6. Principios

#### Copy propuesto

**Eyebrow**

El proyecto

**Titular**

No construimos tecnologia para el campo desde fuera del campo

**Subtitulo**

Viriato nace para demostrar que una pequena explotacion puede ser al mismo tiempo sistema productivo, infraestructura de investigacion aplicada y origen de una herramienta digital util.

**Seccion: Por que existe ahora**

El problema no es solo tecnologico. Es de escala, de contexto y de acceso. Las pequenas fincas necesitan herramientas mas claras, mas asequibles y mas arraigadas en su realidad material.

**Seccion: Tres capas**

`Viriato Agropecuaria` sostiene la produccion real. `Viriato Living Lab` convierte la finca en entorno de experimentacion. `MindFarm` transforma datos y aprendizaje en decision operativa.

**Seccion: A quien sirve**

Sirve a pequenas explotaciones que necesitan decidir mejor, a instituciones que buscan infraestructura de validacion en campo y a proyectos de innovacion agraria que quieren construir herramientas transferibles.

**Seccion: Territorios**

Padul funciona hoy como banco operativo de despliegue y aprendizaje. Sierra de Gata aparece como territorio de extension, investigacion aplicada y lineas futuras de trabajo.

**Seccion: Principios**

Campo real antes que promesa. Conocimiento aplicado antes que retorica. Herramienta util antes que complejidad gratuita.

### 7.3 Living Lab

#### Rol

Demostrar que el living lab es capacidad real de experimentacion y transferencia, no una etiqueta inspiracional.

#### Estructura recomendada

1. Hero
2. Que significa aqui living lab
3. Del suelo a la decision
4. Que se valida en campo
5. Que conocimiento se quiere transferir
6. CTA a colaboracion y a producto

#### Copy propuesto

**Eyebrow**

Living Lab

**Titular**

Investigacion aplicada que pisa suelo real

**Subtitulo**

El living lab de Viriato usa la propia explotacion como infraestructura de investigacion. Aqui se sensorizan procesos reales, se prueban modelos agronomicos y se valida si una herramienta sirve o no sirve en campo.

**Seccion: Que significa aqui living lab**

No es un showroom tecnologico. Es un marco de experimentacion incrustado en la vida de una finca, con sus restricciones, sus tiempos y sus decisiones reales.

**Seccion: Del suelo a la decision**

El flujo importa porque muestra que no hablamos de un concepto abstracto: lectura de suelo, transmision, almacenamiento, analitica y recomendacion terminan en una decision concreta.

**Seccion: Que se valida**

Monitorizacion continua, modelo FAO-56, logica de balance hidrico, proyecciones y forma de presentar recomendaciones comprensibles para quien tiene que decidir.

**Seccion: Transferencia**

El objetivo no es acumular datos. Es producir conocimiento util, replicable y conectable con otras pequenas explotaciones y otros contextos mediterraneos.

**CTA**

Ver como ese trabajo se convierte en producto en MindFarm.

### 7.4 MindFarm

#### Rol

Actuar como pagina de producto y puente claro entre el relato institucional y la herramienta real `mindfarm-app`.

#### Estructura minima obligatoria

1. Que es MindFarm
2. Que problema resuelve
3. Que significa aqui "gemelo digital"
4. Como funciona
5. Sostenibilidad y rentabilidad
6. Modulos o capacidades actuales
7. Que esta operativo y que esta en evolucion
8. CTA principal a la app
9. CTA secundario a `Living Lab` o `Proyecto`

#### Copy propuesto

**Eyebrow**

MindFarm

**Titular**

Agricultura de precision para decidir mejor en campo real

**Subtitulo**

MindFarm es el producto digital nacido dentro de Viriato Living Lab. Convierte datos de suelo, clima y manejo en una lectura operativa de la finca: que esta pasando, que puede pasar y que decision conviene tomar hoy.

**Seccion: Que es MindFarm**

No es solo un dashboard. Es una herramienta de interpretacion y apoyo a la decision para pequenas explotaciones que necesitan mas claridad y menos intuicion ciega.

**Seccion: Que problema resuelve**

Muchas fincas trabajan con poca visibilidad sobre el estado hidrico real del suelo, con decisiones de riego apoyadas en experiencia, calendario o senales demasiado tardias. MindFarm busca reducir esa zona ciega.

**Seccion: Que significa aqui gemelo digital**

Aqui "gemelo digital" no significa una copia futurista de la finca. Significa una representacion operativa de su estado hidrico y agronomico que combina datos reales del suelo, meteorologia, reglas agronomicas y escenarios de decision.

**Seccion: Como funciona**

MindFarm integra lecturas de suelo, contexto meteorologico y modelos de balance hidrico para convertir datos dispersos en una recomendacion interpretable. El objetivo no es mostrar mas variables, sino ayudar a leer mejor lo que esas variables significan.

**Seccion: Sostenibilidad y rentabilidad**

La promesa de sostenibilidad no se apoya en retorica verde. Se apoya en mecanismos concretos:

- menos agua mal aplicada
- decisiones de riego mas claras
- mejor lectura del suelo y del riesgo
- registro y aprendizaje acumulado temporada tras temporada
- tecnologia accesible para pequena escala

La promesa economica tampoco debe sonar a ROI magico. Debe presentarse como potencial de mejor uso de recursos, menos error y mas capacidad de decidir con criterio.

**Seccion: Capacidades actuales**

- monitorizacion de variables de suelo
- recomendacion de riego
- analitica derivada basada en FAO-56
- proyeccion y lectura tipo gemelo digital

**Seccion: Hoy / en evolucion**

Hoy MindFarm ya funciona como MVP operativo para monitorizacion y decision de riego en el despliegue activo. En evolucion quedan la ampliacion multi-finca, nuevas lineas de cultivo, mas validacion local y nuevas capas de interpretacion.

**CTA principal**

Entrar en MindFarm

**CTA secundario**

Entender el Living Lab

#### Nota de posicionamiento

La pagina `MindFarm` debe sonar a producto, no a pagina institucional reciclada. Tiene que dejar claro:

- para quien existe
- que resuelve hoy
- por que el gemelo digital importa en lenguaje llano
- por que su propuesta puede ser sostenible y rentable sin inflar el mensaje

### 7.5 Colaboraciones

#### Rol

Pasar de una invitacion generica a una propuesta mas concreta de colaboracion.

#### Estructura recomendada

1. Hero
2. Con quien queremos colaborar
3. En que lineas
4. Que ofrece Viriato como entorno
5. CTA directo

#### Copy propuesto

**Titular**

Colaborar para construir herramientas utiles desde campo real

**Subtitulo**

Viriato esta abierto a colaboraciones con universidades, centros de investigacion, administraciones y proyectos de innovacion que quieran trabajar con una combinacion poco habitual: explotacion real, living lab y producto digital en la misma arquitectura.

**Perfiles prioritarios**

- universidades y centros que necesiten entorno de validacion en campo
- proyectos de innovacion agraria orientados a transferencia
- aliados tecnologicos interesados en sensorizacion, gemelo digital o decision support

**Lineas de colaboracion**

- agricultura regenerativa y salud del suelo
- monitorizacion y modelado agronomico
- transferencia tecnologica para pequenas explotaciones
- producto digital y gemelo digital aplicado

**Propuesta de valor**

Viriato ofrece contexto real, infraestructura experimental y una capa de producto donde el aprendizaje puede aterrizar en herramienta util.

### 7.6 Contacto

#### Rol

Cierre limpio, cercano y sin volver a contar la historia completa.

#### Copy propuesto

**Titular**

Hablemos

**Subtitulo**

Si quieres conocer el proyecto, explorar el living lab o entrar en MindFarm como herramienta, estaremos encantados de conversar.

**Version aun mas corta**

Si esto conecta con tu trabajo, tu finca o tu curiosidad, escribenos.

## 8. Recomendaciones de implementacion posterior

Estas decisiones no se ejecutan en esta fase, pero el documento las deja cerradas para la siguiente iteracion:

1. Anadir `src/pages/mindfarm.astro`.
2. Cambiar `BaseLayout.astro` para que `MindFarm` apunte a la nueva pagina interna.
3. Mantener un CTA visible desde esa pagina a `https://mindfarm-demo.streamlit.app`.
4. Reforzar la presencia de `MindFarm` en:
   - `Home`
   - `Proyecto`
   - `Living Lab`
   - `Colaboraciones`
5. Revisar los CTA de la home para que el recorrido natural sea:
   - entender el sistema
   - entender el producto
   - entrar en la herramienta

## 9. Checklist de validacion editorial

El documento se considerara bien implementado si al leer la futura web ocurre esto:

- En menos de 10 segundos se entiende la relacion entre Viriato, Living Lab y MindFarm.
- Un agricultor detecta utilidad practica sin sentirse expulsado por jerga tecnica.
- Un partner institucional reconoce capacidad real de validacion y de colaboracion.
- `MindFarm` deja de parecer un enlace suelto y pasa a comportarse como producto.
- Ningun claim ambicioso queda sin clasificar.

## 10. Fuentes base usadas para este brief

### Fuentes internas

- `../../src/pages/index.astro`
- `../../src/pages/proyecto.astro`
- `../../src/pages/living-lab.astro`
- `../../../MindFarm/docs/user_guides/estructura_proyecto_global.md`
- `../../../MindFarm/config/projects/viriato_lab.yaml`
- `../../../MindFarm/docs/user_guides/Informes_tecnicos/informe_gemelo_digital_v1_estado_y_mejoras.md`
- `../../../MindFarm/docs/user_guides/Informes_tecnicos/metricas_mvp.md`
- `../../../MindFarm-app/docs/mindfarm_product_spec_v1.md`
- `../../../MindFarm-app/docs/playbook.md`

### Referentes oficiales externos

- <https://openteam.community/>
- <https://climatefarmers.org/>
- <https://www.organicvalley.coop/>
- <https://farmhack.org/>
- <https://farmos.org/>
- <https://cropx.com/>
- <https://agrifoodtef.eu/>
- <https://www.lilas4soils.eu/>

### Nota final

El trabajo de reescritura posterior debe usar este criterio constante:

No hacer una web que diga "tenemos buenas ideas".
Hacer una web que deje claro que aqui ya hay un sistema en marcha, una herramienta naciendo del campo y una invitacion seria a construir sobre ello.

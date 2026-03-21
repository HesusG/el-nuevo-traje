---
theme: seriph
title: '¿Cómo se Viste el Docente Digital?'
info: 'Resumen de la conferencia del Prof. Ronghuai Huang — Aplicaciones para docentes mexicanos'
author: 'Basado en la conferencia de Prof. Ronghuai Huang (黄荣怀)'
transition: slide-left
mdc: true
drawings:
  persist: false
---

<style>
@import './styles/theme.css';
</style>

<!-- SLIDE 1: PORTADA -->

<div class="bg-teal-gradient" style="position:absolute;inset:0;z-index:-1"></div>

<div style="display:flex;flex-direction:column;justify-content:center;height:100%;color:#fff;text-align:center">
<div class="seccion-badge" style="color:#FFD54F;border-color:#FFD54F;align-self:center">Programa de Invierno · INFOTEC · China-América Latina</div>

# ¿Cómo se Viste el Docente Digital?

## Lecciones desde la experiencia china para la práctica docente en México

<div style="margin-top:32px;font-family:var(--font-mono);font-size:0.8rem;opacity:0.85">
Basado en la conferencia del Prof. Ronghuai Huang (黄荣怀)<br>
Instituto de Aprendizaje Inteligente · Universidad Normal de Beijing<br>
Cátedra UNESCO de Inteligencia Artificial en Educación
</div>
</div>

<div class="watermark" style="color:#fff">教育</div>

---

<!-- SLIDE 2: ¿QUIÉN ES HUANG? -->

<div class="bg-cream" style="position:absolute;inset:0;z-index:-1"></div>
<div class="bg-dots" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-teal);border-color:var(--c-teal)">El Ponente</div>

# ¿Quién es Ronghuai Huang?

<div style="display:grid;grid-template-columns:1fr 1fr;gap:32px;margin-top:16px">
<div>

<v-clicks>

- **Co-director** del Instituto de Aprendizaje Inteligente de la Universidad Normal de Beijing

- **Titular** de la **Cátedra UNESCO de IA en Educación** — investigación, cooperación y desarrollo de capacidades

- Investiga **educación inteligente**, ambientes digitales de aprendizaje e IA aplicada a la educación

- Trabaja con universidades, gobiernos y organismos internacionales para el uso **responsable e inclusivo** de la IA

- Enfoque en el **ODS 4**: educación inclusiva, equitativa y de calidad para todos

</v-clicks>

</div>
<div style="display:flex;align-items:center;justify-content:center">
<img src="/img/huang-portrait.png" style="max-height:320px;border-radius:8px;box-shadow:6px 6px 0 rgba(0,0,0,0.1)" />
</div>
</div>

---

<!-- SLIDE 3: ¿POR QUÉ NOS IMPORTA EN MÉXICO? -->

<div class="bg-dark" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-yellow);border-color:var(--c-yellow)">Relevancia</div>

# ¿Por qué importa esto en México?

<div style="display:grid;grid-template-columns:1fr 1fr;gap:24px;margin-top:16px">
<div>

### Lo que dice Huang

<v-clicks>

- Tener acceso a tecnología **no garantiza** aprendizaje significativo — la **brecha de uso** es el verdadero reto

- Los docentes **no saben cómo integrar** tecnología de manera pedagógica

- La **trinidad imposible**: calidad + escala + personalización — históricamente no se logran las tres

- La IA generativa **no es una ola más**, obliga a repensar los cimientos del sistema educativo

</v-clicks>

</div>
<div style="display:flex;align-items:center;justify-content:center;padding:10px">
<img src="/img/impossible-trinity.png" style="max-height:300px;border-radius:8px;opacity:0.9" />
</div>
</div>

---

<!-- SLIDE 4: EL DIAGNÓSTICO — DIAGRAMA -->

<div class="bg-grid" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-red);border-color:var(--c-red)">El Problema</div>

# La Trinidad Imposible en Educación

<div style="display:flex;justify-content:center;margin:12px 0">

```mermaid {scale: 0.7}
graph TD
    A["🎯 <b>Calidad</b><br>Educación de<br>alta calidad"] --- B["📈 <b>Escala</b><br>Acceso a<br>gran escala"]
    B --- C["🧩 <b>Personalización</b><br>Aprendizaje<br>individualizado"]
    C --- A
    D["🤖 <b>IA</b><br>Nuevas<br>posibilidades"]
    D -.-> A
    D -.-> B
    D -.-> C
    style A fill:#C62828,color:#fff
    style B fill:#C62828,color:#fff
    style C fill:#C62828,color:#fff
    style D fill:#FFD54F,color:#1a1a1a,stroke:#E65100
```

</div>

<v-click>

> La educación personalizada de alta calidad solo es posible en clases pequeñas o instituciones de élite. Los sistemas a gran escala dependen de modelos estandarizados. **La IA abre nuevas posibilidades** para equilibrar las tres metas.

</v-click>

---

<!-- SLIDE 5: TRANSICIÓN — PARTE 1 -->

<div class="bg-red-gradient" style="position:absolute;inset:0;z-index:-1"></div>

<div class="slide-transicion" style="color:#fff">
<div class="numero-seccion" style="color:#fff">路</div>

# La Ruta China: Del Diagnóstico a la Acción

<p style="font-size:1.05rem;opacity:0.9;max-width:600px;margin:16px auto 0">
¿Cómo un país con 280 millones de estudiantes abordó estos problemas?
</p>
</div>

---

<!-- SLIDE 6: LA ESCALA DEL DESAFÍO — DATA SLIDE -->

<div class="bg-dark" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-yellow);border-color:var(--c-yellow)">La Escala</div>

<h1 style="color:#fff">El Sistema Educativo Más Grande del Mundo</h1>

<div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:24px;margin-top:32px;text-align:center">

<v-click>
<div>
<div class="dato-grande">280M</div>
<div class="dato-label" style="color:#bbb;opacity:1">Estudiantes</div>
</div>
</v-click>

<v-click>
<div>
<div class="dato-grande">440,000</div>
<div class="dato-label" style="color:#bbb;opacity:1">Escuelas</div>
</div>
</v-click>

<v-click>
<div>
<div class="dato-grande">18.7M</div>
<div class="dato-label" style="color:#bbb;opacity:1">Docentes</div>
</div>
</v-click>

</div>

<v-click>

<div style="display:grid;grid-template-columns:1fr auto 1fr;gap:16px;margin-top:32px;align-items:center">
<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);text-align:center;padding:10px 14px">
<p style="color:#ccc;font-size:0.8rem;margin:0"><strong style="color:#FFD54F">> 92%</strong> matrícula preescolar</p>
</div>
<div style="color:#555;font-size:1.5rem">·</div>
<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);text-align:center;padding:10px 14px">
<p style="color:#ccc;font-size:0.8rem;margin:0"><strong style="color:#FFD54F">> 60%</strong> tasa bruta educación superior</p>
</div>
</div>

</v-click>

<div class="watermark" style="color:rgba(255,255,255,0.03)">CHINA</div>

---

<!-- SLIDE 7: EQUIDAD A ESCALA -->

<div class="bg-cream" style="position:absolute;inset:0;z-index:-1"></div>
<div class="bg-dots" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-teal);border-color:var(--c-teal)">Equidad</div>

# Equidad a Escala: Los Datos de China

<div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px;margin-top:20px">

<div class="tarjeta" style="text-align:center;padding:12px" v-click>
<div class="dato-grande" style="font-size:2.2rem;color:var(--c-teal)">97%</div>
<p style="font-size:0.75rem;margin-top:4px">Hijos de migrantes en escuelas públicas</p>
</div>

<div class="tarjeta" style="text-align:center;padding:12px" v-click>
<div class="dato-grande" style="font-size:2.2rem;color:var(--c-teal)">97%</div>
<p style="font-size:0.75rem;margin-top:4px">Niños con discapacidad en educación obligatoria</p>
</div>

<div class="tarjeta" style="text-align:center;padding:12px" v-click>
<div class="dato-grande" style="font-size:2.2rem;color:var(--c-teal)">150M</div>
<p style="font-size:0.75rem;margin-top:4px">Estudiantes con beca anualmente</p>
</div>

</div>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:12px">

<div class="tarjeta" style="text-align:center;padding:12px" v-click>
<div class="dato-grande" style="font-size:2.2rem;color:var(--c-teal)">~100%</div>
<p style="font-size:0.75rem;margin-top:4px">Escuelas con acceso a internet</p>
</div>

<div class="tarjeta" style="text-align:center;padding:12px" v-click>
<div class="dato-grande" style="font-size:2.2rem;color:var(--c-teal)">98%</div>
<p style="font-size:0.75rem;margin-top:4px">Aulas con equipamiento multimedia</p>
</div>

</div>

<div class="pregunta-reflexion" style="margin-top:12px;padding:8px 14px;font-size:0.8rem" v-click>
La infraestructura digital es prerrequisito para la innovación. <strong>Estos números demuestran que la inclusión a escala no es utopía — es política pública con ejecución sostenida.</strong>
</div>

---

<!-- SLIDE 8: TRES ETAPAS -->

<div class="bg-grid" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-cobalt);border-color:var(--c-cobalt)">Paso 1</div>

# Tres Etapas de Evolución Digital

<div style="margin:16px auto;max-width:700px">

```mermaid {scale: 0.75}
graph LR
  A["🔢 Digitización<br><em>Convertir lo analógico<br>a formato digital</em>"] --> B["⚙️ Digitalización<br><em>Mejorar y automatizar<br>procesos existentes</em>"]
  B --> C["🔄 Transformación<br>Digital<br><em>Rediseñar cultura,<br>valores y propósitos</em>"]
  style A fill:#E3F2FD,stroke:#1565C0,stroke-width:2px
  style B fill:#BBDEFB,stroke:#1565C0,stroke-width:2px
  style C fill:#1565C0,color:#fff,stroke:#0D47A1,stroke-width:2px
```

</div>

<v-clicks>

- **Digitización** cambia formatos (escanear documentos, crear archivos digitales)
- **Digitalización** mejora procesos (sistemas de gestión, plataformas en línea)
- **Transformación Digital** redefine la identidad y el propósito del sistema educativo

</v-clicks>

<div class="pregunta-reflexion" style="margin-top:10px;padding:8px 14px;font-size:0.8rem" v-click>
💡 <strong>Reflexiona:</strong> ¿En qué etapa consideras que se encuentra tu institución?
</div>

---

<!-- SLIDE 9: PLATAFORMA NACIONAL + 3C/3I -->

<div class="bg-cream" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-cobalt);border-color:var(--c-cobalt)">Paso 2</div>

# La Estrategia 3C + 3I en Acción

<div style="display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-top:12px">
<div>

### Las 3C

<v-clicks>

- **Conexión** — Conectividad universal. Sin acceso confiable, la educación digital no llega a todos
- **Contenido** — Recursos digitales de calidad, culturalmente relevantes
- **Cooperación** — Colaboración institucional nacional e internacional

</v-clicks>

### Las 3I

<v-clicks>

- **Integración** — Fusión presencial + en línea
- **Inteligencia** — IA adaptativa y gobernanza inteligente
- **Internacionalización** — Marco de colaboración global

</v-clicks>

</div>
<div style="display:flex;flex-direction:column;justify-content:center;align-items:center;gap:12px">

<img src="/img/smart-platform.png" style="max-height:160px;border-radius:6px" />

<div class="tarjeta" style="text-align:center;padding:10px;width:100%;background:var(--c-teal);color:#fff;border-color:var(--c-teal)">
<div style="font-family:var(--font-display);font-weight:900;font-size:1.4rem;line-height:1">47M recursos · 61B visitas</div>
<div style="font-family:var(--font-mono);font-size:0.65rem;margin-top:4px;color:#FFD54F">Plataforma Nacional — la más grande del mundo · acceso abierto y gratuito</div>
</div>

</div>
</div>

---

<!-- SLIDE 10: EDUCACIÓN INTELIGENTE + IMAGE -->

<div class="bg-cobalt-gradient" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:#FFD54F;border-color:#FFD54F">Paso 3</div>

<h1 style="color:#fff">La Meta: Educación Inteligente</h1>

<div style="display:grid;grid-template-columns:1.2fr 0.8fr;gap:20px;margin-top:12px">
<div>

<p style="color:rgba(255,255,255,0.9);font-size:0.85rem;margin-bottom:12px">Según Huang, no es educación tradicional con herramientas digitales. Es una forma de educación <strong>claramente definida</strong> para la era de la inteligencia.</p>

<div class="tarjeta" style="background:rgba(255,255,255,0.12);border-color:rgba(255,255,255,0.3);color:#fff;padding:10px 14px;margin-bottom:8px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.85rem">Alta Experiencia de Aprendizaje</h4>
<p style="color:rgba(255,255,255,0.9);font-size:0.72rem">Estudiantes profundamente involucrados y motivados. Apoyo continuo e interacción significativa.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.12);border-color:rgba(255,255,255,0.3);color:#fff;padding:10px 14px;margin-bottom:8px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.85rem">Adaptabilidad del Contenido</h4>
<p style="color:rgba(255,255,255,0.9);font-size:0.72rem">Currículo y recursos que se adaptan dinámicamente a las necesidades y progreso de cada estudiante.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.12);border-color:rgba(255,255,255,0.3);color:#fff;padding:10px 14px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.85rem">Eficiencia Docente</h4>
<p style="color:rgba(255,255,255,0.9);font-size:0.72rem">La tecnología libera al docente de tareas repetitivas para enfocarse en mentoría, guía y creatividad.</p>
</div>

</div>
<div style="display:flex;align-items:center;justify-content:center">
<img src="/img/future-classroom.png" style="max-height:300px;border-radius:8px;opacity:0.9" />
</div>
</div>

---

<!-- SLIDE 11: 4 FUTUROS -->

<div class="bg-dark" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-yellow);border-color:var(--c-yellow)">Visión 2050</div>

<h1 style="color:#fff">Los Cuatro Futuros de la Educación</h1>

<p style="color:#bbb;font-size:0.8rem;margin-bottom:12px">Del Libro Blanco de Educación Inteligente de China (2025)</p>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:14px">

<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);padding:12px 14px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:4px">👨‍🏫 Docentes del Futuro</h4>
<p style="color:#ccc;font-size:0.75rem">Ya no transmisores de conocimiento, sino <strong>diseñadores de experiencias de aprendizaje</strong> y orquestadores de la colaboración humano-IA.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);padding:12px 14px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:4px">🏫 Aulas del Futuro</h4>
<p style="color:#ccc;font-size:0.75rem">Ambientes dinámicos y flexibles que <strong>fusionan espacios físicos y virtuales</strong> para aprendizaje interactivo y personalizado.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);padding:12px 14px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:4px">🏛️ Escuelas del Futuro</h4>
<p style="color:#ccc;font-size:0.75rem"><strong>Ecosistemas abiertos de aprendizaje</strong> integrados en la comunidad, no espacios institucionales aislados.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);padding:12px 14px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:4px">📖 Centros de Aprendizaje</h4>
<p style="color:#ccc;font-size:0.75rem">Educación <strong>permanente y a demanda</strong>, sirviendo a personas en todas las etapas de la vida.</p>
</div>

</div>

---

<!-- SLIDE 12: CITA MID-DECK + HAR -->

<div class="bg-teal-gradient" style="position:absolute;inset:0;z-index:-1"></div>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:24px;height:100%;align-items:center">
<div style="padding:20px">
<div class="cita-grande" style="color:#fff;font-size:1.2rem;max-width:100%;padding-left:20px">
La tecnología se encarga de lo rutinario. Los seres humanos se dedican a pensar, sentir y crear significado.
</div>
<div class="cita-autor" style="color:#FFD54F;opacity:1;margin-top:16px">— Prof. Ronghuai Huang</div>

<div style="margin-top:24px;color:rgba(255,255,255,0.85);font-size:0.8rem;line-height:1.6">
<strong>Marco HAR:</strong> Humanos + Avatares de IA + Gemelos Digitales + Robots forman un ecosistema colaborativo donde <strong>el educador humano sigue siendo central</strong> — insustituible en empatía, ética y creatividad.
</div>
</div>
<div style="display:flex;align-items:center;justify-content:center;padding:10px">
<img src="/img/har-framework.png" style="max-height:340px;border-radius:8px;opacity:0.9" />
</div>
</div>

---

<!-- SLIDE 13: 5 COMPETENCIAS CIUDADANO DIGITAL -->

<div class="bg-cream" style="position:absolute;inset:0;z-index:-1"></div>
<div class="bg-dots" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-cobalt);border-color:var(--c-cobalt)">Competencias</div>

# 5 Competencias del Ciudadano Digital

<p style="font-size:0.8rem;opacity:0.7;margin-bottom:8px">Publicadas por Huang en <em>Horizontes de la AIU (IAU Horizons)</em> — lo que tus estudiantes necesitan para prosperar</p>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;font-size:0.85rem">

<div style="display:flex;align-items:flex-start;gap:10px;padding:8px 0" v-click>
<span style="font-family:var(--font-display);font-weight:900;font-size:1.8rem;color:var(--c-cobalt);line-height:1">1</span>
<div><strong>Aprendizaje activo a lo largo de la vida</strong><br><span style="font-size:0.78rem;opacity:0.8">Actualizar continuamente conocimientos y habilidades en un mundo cambiante</span></div>
</div>

<div style="display:flex;align-items:flex-start;gap:10px;padding:8px 0" v-click>
<span style="font-family:var(--font-display);font-weight:900;font-size:1.8rem;color:var(--c-cobalt);line-height:1">2</span>
<div><strong>Creatividad en el uso de la IA</strong><br><span style="font-size:0.78rem;opacity:0.8">No solo consumir contenido generado — colaborar creativamente con sistemas inteligentes</span></div>
</div>

<div style="display:flex;align-items:flex-start;gap:10px;padding:8px 0" v-click>
<span style="font-family:var(--font-display);font-weight:900;font-size:1.8rem;color:var(--c-cobalt);line-height:1">3</span>
<div><strong>Adaptabilidad en entornos laborales flexibles</strong><br><span style="font-size:0.78rem;opacity:0.8">Roles dinámicos que exigen flexibilidad y desarrollo continuo de nuevas capacidades</span></div>
</div>

<div style="display:flex;align-items:flex-start;gap:10px;padding:8px 0" v-click>
<span style="font-family:var(--font-display);font-weight:900;font-size:1.8rem;color:var(--c-cobalt);line-height:1">4</span>
<div><strong>Resiliencia ante la incertidumbre</strong><br><span style="font-size:0.78rem;opacity:0.8">Navegar cambios tecnológicos y sociales acelerados manteniendo la capacidad de aprender</span></div>
</div>

<div style="display:flex;align-items:flex-start;gap:10px;padding:8px 0" v-click>
<span style="font-family:var(--font-display);font-weight:900;font-size:1.8rem;color:var(--c-cobalt);line-height:1">5</span>
<div><strong>Prosperar en entornos de IA</strong><br><span style="font-size:0.78rem;opacity:0.8">Coexistencia productiva entre inteligencia humana e inteligencia artificial</span></div>
</div>

</div>

<div class="pregunta-reflexion" style="margin-top:8px;padding:8px 14px;font-size:0.8rem" v-click>
💡 De estas cinco, <strong>¿cuál es la que menos desarrollas en tus estudiantes actualmente?</strong>
</div>

---

<!-- SLIDE 14: TRANSICIÓN — TU PRÁCTICA -->

<div class="bg-amber-gradient" style="position:absolute;inset:0;z-index:-1"></div>

<div class="slide-transicion" style="color:var(--bg-carbon)">
<div class="numero-seccion" style="color:var(--bg-carbon)">✦</div>

# ¿Y esto qué significa para tu práctica?

<p style="font-size:1.05rem;opacity:0.85;max-width:600px;margin:16px auto 0">
Del modelo chino al Traje del Docente — conexión con tu formación
</p>
</div>

---

<!-- SLIDE 15: MAPEO HUANG → TRAJE + IMAGE -->

<div style="position:absolute;inset:0;z-index:-1;background:linear-gradient(135deg, #F5F0E8 60%, rgba(123,31,162,0.08) 100%)"></div>

<div class="seccion-badge" style="color:var(--c-socio);border-color:var(--c-socio)">Conexión con tu formación</div>

# De Huang al Traje del Docente

<div style="display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-top:8px">
<div>

<div class="traje-col socio" style="margin-bottom:8px" v-click>
<strong style="color:var(--c-socio)">Socioemocional</strong><br>
<span style="font-size:0.8rem">Docentes humanos son <em>irremplazables</em> en empatía, guía ética y creatividad. El marco HAR coloca al humano como centro.</span>
</div>

<div class="traje-col tech" style="margin-bottom:8px" v-click>
<strong style="color:var(--c-tech)">Tecnología Pedagógica</strong><br>
<span style="font-size:0.8rem">Superar la brecha de uso: integración profunda de tecnología Y pedagogía. Los 4 pilares de la pedagogía digital son clave.</span>
</div>

<div class="traje-col innov" style="margin-bottom:8px" v-click>
<strong style="color:var(--c-innov)">Innovación</strong><br>
<span style="font-size:0.8rem">De receptor pasivo a <em>liderazgo activo</em>. Los "4 todos" transforman cada elemento, proceso y campo del sistema.</span>
</div>

<div class="traje-col design" v-click>
<strong style="color:var(--c-design)">Diseño Instruccional</strong><br>
<span style="font-size:0.8rem">El docente del futuro: <em>diseñador de experiencias</em> y orquestador humano-IA. Contenido que se adapta dinámicamente.</span>
</div>

</div>
<div style="display:flex;align-items:center;justify-content:center">
<img src="/img/traje-mapping.png" style="max-height:340px;border-radius:8px" />
</div>
</div>

---

<!-- SLIDE 16: PREGUNTAS 1+2 MERGED — DESAFÍOS Y PRIORIDADES -->

<div class="bg-dark" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-yellow);border-color:var(--c-yellow)">Preguntas 1 y 2</div>

<h1 style="color:#fff">¿Qué es más desafiante y qué necesita más desarrollo?</h1>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-top:12px">

<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);padding:10px 14px;border-left:4px solid var(--c-tech)" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.85rem">🔴 Tecnología Pedagógica — Prioridad Alta</h4>
<p style="color:#ccc;font-size:0.72rem">La <strong>brecha de uso</strong> es el reto central: la infraestructura avanzó más rápido que la innovación pedagógica. Los 4 pilares de la pedagogía digital son el camino de cierre.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);padding:10px 14px;border-left:4px solid var(--c-design)" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.85rem">🔴 Diseño Instruccional — Prioridad Alta</h4>
<p style="color:#ccc;font-size:0.72rem">Los <strong>"4 todos"</strong> exigen rediseñar metas, contenidos y procesos. El docente debe diseñar <strong>trayectorias de aprendizaje personalizadas</strong>.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);padding:10px 14px;border-left:4px solid var(--c-innov)" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.85rem">🟡 Innovación — En Transición</h4>
<p style="color:#ccc;font-size:0.72rem">El <strong>despertar sistémico</strong> exige pasar de receptor pasivo a liderazgo activo. Transformación digital = cambio de identidad, no de herramientas.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.10);border-color:rgba(255,255,255,0.3);padding:10px 14px;border-left:4px solid var(--c-socio)" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.85rem">⚡ Socioemocional — Insustituible, Bajo Presión</h4>
<p style="color:#ccc;font-size:0.72rem">Lo que la IA <strong>no puede reemplazar</strong>. Pero está bajo presión: creatividad con IA, resiliencia ante incertidumbre y coexistencia humano-IA son desafíos nuevos.</p>
</div>

</div>

---

<!-- SLIDE 17: PREGUNTA 3 — CÓMO APOYAN LAS INSTITUCIONES -->

<div class="bg-teal-gradient" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:#FFD54F;border-color:#FFD54F">Pregunta 3</div>

<h1 style="color:#fff">¿Cómo pueden las instituciones apoyar este nuevo perfil?</h1>

<p style="color:rgba(255,255,255,0.9);font-size:0.78rem;margin-bottom:8px">Huang propone 5 caminos constructivos — los cimientos institucionales de la educación inteligente:</p>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:10px">

<div style="display:grid;grid-template-columns:1fr;gap:8px">

<div class="tarjeta" style="background:rgba(255,255,255,0.12);border-color:rgba(255,255,255,0.3);color:#fff;padding:8px 12px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.82rem">1. Priorizar el Desarrollo Docente</h4>
<p style="color:rgba(255,255,255,0.9);font-size:0.68rem"><strong>La inversión de mayor retorno</strong> para mejorar los sistemas educativos en la era digital.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.12);border-color:rgba(255,255,255,0.3);color:#fff;padding:8px 12px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.82rem">2. Comunidades de Aprendizaje</h4>
<p style="color:rgba(255,255,255,0.9);font-size:0.68rem"><strong>Redes colaborativas</strong> como motor de construcción de conocimiento.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.12);border-color:rgba(255,255,255,0.3);color:#fff;padding:8px 12px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.82rem">3. Adopción Ética de Tecnología</h4>
<p style="color:rgba(255,255,255,0.9);font-size:0.68rem">Supervisión ética, transparencia y rendición de cuentas.</p>
</div>

</div>
<div style="display:grid;grid-template-columns:1fr;gap:8px">

<div class="tarjeta" style="background:rgba(255,255,255,0.12);border-color:rgba(255,255,255,0.3);color:#fff;padding:8px 12px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.82rem">4. Planificación Sostenible</h4>
<p style="color:rgba(255,255,255,0.9);font-size:0.68rem"><strong>Estrategias a largo plazo</strong> que trasciendan ciclos políticos.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.12);border-color:rgba(255,255,255,0.3);color:#fff;padding:8px 12px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.82rem">5. Colaboración Multisectorial</h4>
<p style="color:rgba(255,255,255,0.9);font-size:0.68rem">Gobierno, industria, academia y sociedad civil: <strong>ecosistemas alineados</strong>.</p>
</div>

<div class="tarjeta" style="background:rgba(255,255,255,0.12);border-color:rgba(255,255,255,0.3);color:#fff;padding:8px 12px" v-click>
<h4 style="color:var(--c-yellow);margin-bottom:2px;font-size:0.82rem">+ IA Demostrablemente Benéfica</h4>
<p style="color:rgba(255,255,255,0.9);font-size:0.68rem">La meta no es IA segura sino IA donde la <strong>evidencia de impacto positivo</strong> guíe su despliegue.</p>
</div>

</div>
</div>

---

<!-- SLIDE 18: SÍNTESIS — 5 IDEAS -->

<div class="bg-grid" style="position:absolute;inset:0;z-index:-1"></div>

<div class="seccion-badge" style="color:var(--c-teal);border-color:var(--c-teal)">Síntesis</div>

# 5 Ideas de Huang para tu Práctica

<div style="margin-top:12px">

<v-clicks>

<div style="display:flex;align-items:flex-start;gap:14px;margin-bottom:10px">
<div style="min-width:40px;height:40px;background:var(--c-teal);color:#fff;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-weight:900;font-size:1.1rem">1</div>
<span style="font-size:0.88rem"><strong>La tecnología sin pedagogía no transforma.</strong> No basta tener herramientas — necesitas integración profunda de tecnología Y pedagogía para cerrar la brecha de uso.</span>
</div>

<div style="display:flex;align-items:flex-start;gap:14px;margin-bottom:10px">
<div style="min-width:40px;height:40px;background:var(--c-teal);color:#fff;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-weight:900;font-size:1.1rem">2</div>
<span style="font-size:0.88rem"><strong>Tu rol cambia, no desaparece.</strong> De transmisor a diseñador de experiencias. Lo que te hace insustituible: empatía, guía ética, creatividad.</span>
</div>

<div style="display:flex;align-items:flex-start;gap:14px;margin-bottom:10px">
<div style="min-width:40px;height:40px;background:var(--c-teal);color:#fff;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-weight:900;font-size:1.1rem">3</div>
<span style="font-size:0.88rem"><strong>La IA es tu aliada, no tu reemplazo.</strong> El marco HAR: humanos y sistemas inteligentes colaboran, cada uno aporta lo que el otro no puede.</span>
</div>

<div style="display:flex;align-items:flex-start;gap:14px;margin-bottom:10px">
<div style="min-width:40px;height:40px;background:var(--c-teal);color:#fff;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-weight:900;font-size:1.1rem">4</div>
<span style="font-size:0.88rem"><strong>Transforma tu práctica, no solo tus formatos.</strong> La diferencia entre digitalización y transformación digital es un cambio de identidad y propósito.</span>
</div>

<div style="display:flex;align-items:flex-start;gap:14px;margin-bottom:10px">
<div style="min-width:40px;height:40px;background:var(--c-teal);color:#fff;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-weight:900;font-size:1.1rem">5</div>
<span style="font-size:0.88rem"><strong>No estás solo/a.</strong> Comunidades de aprendizaje, colaboración institucional y planificación a largo plazo son los cimientos.</span>
</div>

</v-clicks>

</div>

---

<!-- SLIDE 19: CIERRE — CITA FINAL -->

<div class="bg-dark" style="position:absolute;inset:0;z-index:-1"></div>

<div style="display:grid;grid-template-columns:1.2fr 0.8fr;height:100%;align-items:center">
<div style="display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;color:#fff;padding:20px">

<div class="cita-grande" style="color:#fff;max-width:500px;font-size:1.15rem">
En la era de la inteligencia, la tecnología se encargará cada vez más de las tareas rutinarias. Pero la verdadera misión de la educación siempre será profundamente humana. El futuro de la educación no está en reemplazar docentes con máquinas, sino en construir una nueva alianza entre la inteligencia humana y la inteligencia artificial.
</div>

<div class="cita-autor" style="color:var(--c-yellow);opacity:1;margin-top:20px">
— Prof. Ronghuai Huang (黄荣怀)
</div>

<div style="margin-top:32px;font-family:var(--font-mono);font-size:0.7rem;color:#999">
Programa de Invierno · INFOTEC · China-América Latina · 2.ª Edición
</div>

</div>
<div style="display:flex;align-items:center;justify-content:center;padding:10px">
<img src="/img/teacher-ai-collab.png" style="max-height:320px;border-radius:8px;opacity:0.85" />
</div>
</div>

<div class="watermark" style="color:#fff">未来</div>

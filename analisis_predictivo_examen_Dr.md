# Análisis predictivo del examen del Dr.: perfil docente, patrones de pregunta y modelo de priorización

**Corpus:** "Intervenciones DR.pdf", 25 páginas con 4 grabaciones transcritas:

- 20/ago: ovario.
- 3/sep: endometrio 1.
- 10/sep: endometrio 2, que cierra con una evaluación rápida en el salón de cáncer cervicouterino (CaCu) y endometrio.
- 24/sep: testículo + CaCu, con instrucciones del examen.

**Examen:** parcial "el próximo jueves", de ovario, testículo, cuerpo uterino/endometrio y cervicouterino, con **preguntas abiertas clínicas, directas y concisas, "sin tanto rollo"**.

**Fuentes NCCN disponibles en el repositorio:**

- CaCu v2.2026: "CACUNCCN - convertido.pdf".
- Ovario: "ovarian222 - converted.pdf".
- Testículo: solo los apuntes `cancer_testicular_tratamiento_NCCN_2026*.md`, sin el PDF fuente en esta rama.
- **Endometrio/útero: no hay fuente NCCN en el repositorio.** Las preguntas de endometrio necesitan la guía NCCN de útero, o hay que avisar que se basan solo en lo dicho en clase.

---

## 1. Perfil del docente

| Rasgo | Evidencia textual | Implicación para el examen |
|---|---|---|
| Oncólogo clínico, no quirúrgico | "Nosotros los clínicos, los que no somos quirúrgicos"; 46 años, 20–22 años de práctica | Peso alto en terapia sistémica, farmacología, estado funcional, biomarcadores y algoritmo diagnóstico. La cirugía se pregunta como **concepto** (tipo de histerectomía, citorreducción óptima, orquiectomía inguinal), no como técnica fina. |
| Autoridad = la guía | "No son supuestos, lo que dice la guía son recomendaciones basadas en evidencia"; "Se me hace que no leyeron la guía"; "Revisen las letras chiquitas del primer o segundo algoritmo" | Premia la respuesta textual de la NCCN, incluidas las **notas al pie del algoritmo**. Castiga la opinión. |
| Base morfológica | "La embriología, la histología y la anatomía las van a seguir utilizando"; clasifica cada tumor desde los tejidos de origen (ovario: epitelio/germinal/estroma; útero: endometrio/miometrio/perimetrio; testículo: escroto/albugínea/túbulos/cremáster) | Pregunta recurrente: **"¿de qué tejido se origina? → clasificación histológica → la más frecuente"**. En CaCu: unión escamocolumnar → escamoso frente a adenocarcinoma. |
| "Lo más frecuente, no lo complicado" | "Tienen que pensar siempre en las cosas más frecuentes… lo complejo nos lo dejan a nosotros los oncólogos" | Pide el dato de primer orden: la histología más frecuente, el factor de riesgo principal, el fármaco eje. Rara vez la excepción rara. |
| Clínico de primer contacto (servicio social, México) | "Te llega en el servicio social una paciente de 30 años…"; NOM, GPC, Hidalgo; "no se pide todo el bloque de rutina" | Viñetas con **edad + síntoma + qué pides primero**. Valora la racionalidad en los estudios (qué sí y qué no). Mezcla la NOM/GPC con la NCCN (Papanicolaou por la NOM). |
| Absolutos y prohibiciones | "obligatoriamente", "todas, absolutamente todas", "NUNCA, NUNCA en la vida", "indicación absoluta", "no puede faltar" | Las frases con absolutos son **preguntas casi seguras**: colposcopía en lesión de alto grado (HSIL), nunca biopsia transescrotal, nunca radioterapia en no seminoma, el cisplatino no puede faltar en germinales, SOR en BRCA. |
| Farmacólogo | Mecanismo de acción y efectos adversos de paclitaxel (dos veces), etopósido, bleomicina, cisplatino (radiosensibilizador), carboplatino (fórmula de Calvert), Goldie-Coldman/Skipper | Por cada tumor espera **esquema + mecanismo + toxicidad limitante + porqué de la combinación o de la dosis**. |
| Biología molecular aplicada | BRCA→iPARP; Lynch/MMR→pembrolizumab/dostarlimab; TCGA; i(12p); TP53 17p; haploinsuficiencia | Patrón **alteración → para qué sirve (riesgo, pronóstico o fármaco)**. Distingue explícitamente "prueba genética ≠ biomarcador". |
| Corrige conceptos confundidos | Hemoglobina glicosilada frente a β-hCG; CA-125 frente a prueba genética; las tres clasificaciones citológicas (Bethesda/NIC/Papanicolaou) "que no deben confundirse" | Pregunta diferencias y equivalencias. Posible: "Diferencie…", "Equivalencia entre…". |
| Valoración funcional | ECOG/Karnofsky explicados en ovario y otra vez en endometrio, ligados a operar o no | Pregunta transversal casi segura: escala, rango, interpretación y consecuencia terapéutica. |
| Neo- frente a adyuvancia | Definición explícita + indicaciones (inoperable, invasión irresecable, metástasis, mal estado funcional) | Concepto general aplicable a cualquier tumor. En CaCu, la indicación de quimioterapia. |

**Errores o desfases del Dr. frente a la NCCN 2026** (responder con la NCCN; si cabe, nombrar el matiz):

- "Estadio IB → histerectomía radical tipo B". En la NCCN, la tipo B corresponde a IA1 con invasión del espacio linfovascular (LVSI+), IA2 o IB1 seleccionados. IB1–IIA1 → **tipo C1**.
- "Microinvasor: profundidad <3–5 mm y extensión <7 mm". La extensión horizontal (7 mm) se **eliminó en FIGO 2018**. IA1 ≤3 mm, IA2 >3–≤5 mm.
- "Borde positivo → resonancia magnética (RM) obligatoria". En la NCCN, con margen positivo: repetir el cono, o traquelectomía/histerectomía (tipo A si es displasia, tipo B si es carcinoma). La RM se recomienda para el estadio I tratado con cono, traquelectomía o histerectomía tipo A, y en general para IB1+.
- "Localmente avanzado = IIB, IIIA, IIIB, IVA". La NCCN incluye además **IB3 y IIA2** (quimiorradioterapia de categoría 1).
- "Indicación absoluta de braquiterapia: estadio IB". En la NCCN, la braquiterapia es componente **indispensable de toda radioterapia definitiva con cérvix intacto**. La braquiterapia sola aplica a IA1/IA2 inoperables.
- Ganglio centinela: el Dr. menciona azul de metileno. La NCCN describe colorante (verde de indocianina [ICG] superior a azul de isosulfán, ensayo FILM) o tecnecio-99m, inyectados en 2 o 4 puntos del cérvix, con mejor detección en tumores <2 cm y ultraestadificación.
- Serotipos de virus del papiloma humano (VPH): la NCCN solo nombra el **16 y el 18** como los más comunes. Los 31, 33, 45 (alto riesgo) y 6, 11 (bajo riesgo, condilomas) son conocimiento externo (†).
- Tamizaje y edad del Papanicolaou: la NCCN remite a la Sociedad Estadounidense de Colposcopía y Patología Cervical (ASCCP). La edad de inicio es dato de la NOM-014 (†), fuera de la NCCN.

---

## 2. Sintaxis de las preguntas

Frecuencia aproximada en el corpus, contando las preguntas formuladas a alumnos y las anunciadas para el examen (~45):

| Plantilla | Ejemplos literales | Peso |
|---|---|---|
| **"Mencione / Enumere / Dime N…"** (N = 3 o 5) | "Mencione 5 serotipos de VPH"; "Mencione 3 histologías"; "dime cinco neoplasias de Lynch"; "dame tres ejemplos de germinales"; "Describa de manera concisa cinco pruebas de inmunohistoquímica (IHQ)" | **~40%**: la dominante. N=3 para histologías y ejemplos; N=5 para factores de riesgo, serotipos, criterios y pruebas. |
| **"¿Cuál es el/la más frecuente / más importante…?"** | "Tumor maligno más frecuente en edad reproductiva"; "la mutación más frecuente en testículo"; "los dos factores de riesgo más importantes" | ~15% |
| **Viñeta clínica corta → decisión** | "Paciente de 19 años, masa pélvica, IOTA positivo, ¿qué biomarcador?"; "20 años, AFP 5,000 → histología"; "paciente de 30 años con sangrado uterino" | ~15%. Siempre con **edad** y un dato llave. |
| **"¿En quiénes está indicado…? / ¿Cuál es la indicación absoluta…?"** | Tamizaje con CA-125; pruebas genéticas; quimioterapia en CaCu; neoadyuvancia; quimioterapia sin histología en testículo | ~12% |
| **"¿Para qué sirve…?"** | BRCA, IOTA, ECOG/Karnofsky, sistema MMR | ~8% |
| **"¿Cuál es el mecanismo de acción / efecto adverso de…?"** | Paclitaxel, etopósido, bleomicina, cisplatino | ~6% |
| **"¿Qué diferencia hay entre…? / ¿Qué significa…?"** | Neoadyuvante frente a adyuvante; G1; i(12p); haploinsuficiencia; LVSI sustancial | ~4% |

**Rasgos formales:** frases cortas en imperativo, sin distractores, con número explícito de elementos. Espera listas, no ensayos. **Una buena respuesta de examen es una lista numerada con el dato duro (cifra, fármaco, dosis, estadio).**

---

## 3. Núcleo temático transversal

Bloques que aplica a **todos** los tumores; se espera la misma batería en CaCu:

1. Epidemiología mínima: el más frecuente por edad o grupo.
2. **Factores de riesgo** (los 5 y "los más importantes").
3. Genética/biología molecular y su utilidad.
4. **Histogénesis → clasificación histológica (3 ejemplos) → la más frecuente**.
5. Tamizaje: en quién sí y en quién no.
6. Abordaje diagnóstico paso a paso según la guía (interrogatorio/exploración → imagen → marcadores → biopsia).
7. Biomarcadores: cuál, para qué y en qué edad.
8. Estado funcional (ECOG/Karnofsky) → operable o no.
9. Estadificación (FIGO/TNM) en términos de temprano frente a avanzado.
10. **Tratamiento por estadio**: temprano = cirugía ± radioterapia; avanzado = multimodal.
11. Cirugía estándar y su nombre (tipo de histerectomía, citorreducción óptima, orquiectomía inguinal alta) + ganglio centinela (preguntado en **dos** tumores).
12. **Quimioterapia: esquema eje + mecanismo + toxicidad + porqué** (dosis en CaCu: cisplatino 40 mg/m² semanal).
13. Radioterapia: modalidades (externa frente a braquiterapia) e indicación.
14. Terapia blanco/inmunoterapia según biomarcador.
15. Preservación de la fertilidad: criterios (endometrio) y concepto (testículo, criopreservación).
16. Neoadyuvancia frente a adyuvancia.

---

## 4. Modelo de predicción

**Puntaje por tema:** P = 3·A + 2·R + 1.5·E + 1·T + 1·N

- **A (anuncio explícito):** 1 si el Dr. dijo "en el examen podría preguntar", "se los voy a preguntar", "pregunta de examen", o lo puso en la evaluación rápida o en la lista del examen.
- **R (repetición):** 1 si aparece en ≥2 sesiones o en ≥2 tumores (patrón transferible).
- **E (énfasis):** 1 si hay absolutos (obligatorio, nunca, absoluta, todas, no puede faltar) o corrección explícita de un error.
- **T (transferencia):** 1 si es la contraparte en CaCu de una pregunta hecha en otro tumor (por ejemplo, el mecanismo del paclitaxel en ovario → el mecanismo del cisplatino en CaCu).
- **N (centralidad NCCN):** 1 si es un nodo del algoritmo principal o una recomendación de categoría 1.

**Niveles:** ≥6 muy alta (≥80%); 4–5.5 alta (60–80%); 2.5–3.5 media (35–60%); <2.5 baja.

### 4.1 CaCu: temas puntuados

| Tema | A | R | E | T | N | P | Nivel |
|---|---|---|---|---|---|---|---|
| 5 serotipos de VPH (alto/bajo riesgo; 16 y 18 los más comunes) | 1 | 1 | 0 | 1 | 1 | 7 | Muy alta |
| 3 histologías (escamoso ~80%, adenocarcinoma ~20% [VPH-asociado frente a independiente], adenoescamoso, neuroendocrino de células pequeñas) | 1 | 1 | 0 | 1 | 1 | 7 | Muy alta |
| Indicación de quimioterapia / quimiorradioterapia (IB3–IVA; cisplatino 40 mg/m² semanal como radiosensibilizador; mecanismo) | 1 | 1 | 1 | 1 | 1 | 8.5 | Muy alta |
| Indicación de braquiterapia (todo cérvix intacto con radioterapia definitiva; sola en IA inoperable; refuerzo de cúpula si el margen vaginal es positivo) | 1 | 0 | 1 | 0 | 1 | 5.5 | Alta |
| 5 factores de riesgo (VPH persistente = principal; tabaquismo, paridad, anticonceptivos orales, inicio temprano de vida sexual, múltiples parejas, infecciones de transmisión sexual, inmunosupresión/VIH, autoinmunes) | 1 | 1 | 0 | 1 | 1 | 7 | Muy alta |
| 3 métodos de tamizaje (citología, prueba de VPH, co-prueba; inspección visual con ácido acético† [IVAA]) + edad por la NOM† | 1 | 1 | 0 | 1 | 0 | 6 | Muy alta (con dato fuera de la NCCN) |
| HSIL/NIC 3 → colposcopía obligatoria; equivalencias Bethesda/NIC/Papanicolaou | 0 | 0 | 1 | 0 | 0 | 1.5 → **ajuste +2** por clase dedicada | Alta |
| Cono: técnica (bisturí frío preferido), margen negativo (≥1 mm, sin HSIL ni invasión), cono como tratamiento definitivo en IA1 sin LVSI, conducta con margen positivo | 0 | 1 | 1 | 1 | 1 | 5.5 | Alta |
| Estadificación FIGO 2018 (temprano frente a localmente avanzado; IA1/IA2 por profundidad; IIIC por ganglios; imagen y patología permitidas) | 0 | 1 | 0 | 1 | 1 | 4 | Alta |
| Tipos de histerectomía A/B/C1 por estadio (trampa: el Dr. dijo IB→B) | 0 | 1 | 0 | 1 | 1 | 4 | Alta |
| Ganglio centinela (colorante/ICG/tecnecio-99m, 2 o 4 puntos, <2 cm, algoritmo de linfadenectomía específica por lado, ultraestadificación) | 0 | 1 | 0 | 1 | 1 | 4 | Alta |
| Preservación de la fertilidad (traquelectomía radical ≤2 cm; contraindicada en neuroendocrino de células pequeñas y adenocarcinoma gástrico) | 0 | 1 | 0 | 1 | 1 | 4 | Alta |
| Adyuvancia posoperatoria: criterios de Sedlis frente a factores de alto riesgo de Peters (ganglios, margen, parametrio) | 0 | 0 | 0 | 1 | 1 | 2 → +1 por ser algoritmo clave | Media-alta |
| Mecanismo y toxicidad del cisplatino (aductos/enlaces cruzados; nefrotoxicidad, ototoxicidad, neuropatía, emesis, hipomagnesemia) | 0 | 1 | 0 | 1 | 1 | 4 | Alta |
| Primera línea metastásica/recurrente (platino + paclitaxel ± bevacizumab + pembrolizumab si PD-L1 [CPS ≥1]) | 0 | 1 | 0 | 1 | 1 | 4 | Alta |
| Biomarcadores (PD-L1, MMR/MSI, TMB, HER2; p16 como sustituto de VPH) | 0 | 1 | 0 | 1 | 1 | 4 | Alta |
| Evaluación pretratamiento (biopsia/cono, RM pélvica, PET/TC desde IB1, VIH, cistoscopía/proctoscopía si hay sospecha) | 0 | 1 | 0 | 1 | 1 | 4 | Alta |
| Pembrolizumab + quimiorradioterapia (FIGO 2014 III–IVA) | 0 | 0 | 0 | 1 | 1 | 2 | Media |
| Neuroendocrino de células pequeñas (etopósido + platino; nunca preservación de la fertilidad) | 0 | 1 | 0 | 1 | 1 | 4 | Alta |
| Vigilancia (cada 3–6 meses × 2 años; citología de valor limitado) | 0 | 0 | 0 | 0 | 1 | 1 | Baja |
| Restricciones de dosis de radioterapia / órganos de riesgo | 0 | 0 | 0 | 0 | 0 | 0 | Baja |
| Embarazo | 0 | 0 | 0 | 0 | 1 | 1 | Baja |

### 4.2 Otros tumores: temas de nivel muy alto (para bancos futuros)

- **Ovario:**
  - IOTA ("seguro se los voy a preguntar");
  - tamizaje con CA-125 (solo en riesgo genético);
  - BRCA → SOR + iPARP;
  - biomarcadores por edad e histología (CA-125, AFP, β-hCG, DHL, inhibina B, HE4);
  - citorreducción óptima (<1 cm, ideal R0);
  - carboplatino/paclitaxel + mecanismo y efectos adversos;
  - BEP + mecanismo del etopósido + toxicidad de la bleomicina;
  - clasificación (epitelial/germinal/estroma) y la más frecuente por edad;
  - ECOG/Karnofsky.
- **Endometrio** (sin fuente NCCN en el repositorio):
  - los dos factores de riesgo principales (obesidad, estrógeno sin oposición);
  - histologías de alto riesgo;
  - Lynch (5 neoplasias; criterios de Ámsterdam/Bethesda);
  - ultrasonido >4 mm → biopsia;
  - 5 pruebas de IHQ (MLH1, MSH2, MSH6, PMS2, p53; receptores hormonales);
  - TCGA (4 grupos);
  - mutaciones de mal pronóstico;
  - criterios de preservación de la fertilidad (5);
  - grado FIGO (<5/5–50/>50% sólido);
  - neo- frente a adyuvante;
  - LVSI sustancial;
  - fórmula de Calvert;
  - pembrolizumab/dostarlimab en dMMR.
- **Testículo:**
  - i(12p);
  - factores de riesgo (criptorquidia);
  - algoritmo (ultrasonido Doppler, marcadores, TC; **nunca biopsia transescrotal**);
  - orquiectomía inguinal alta;
  - quimioterapia sin histología (masa masiva, compromiso vital, AFP >10,000 o β-hCG >50,000);
  - seminoma (AFP negativa; estadio I: vigilancia / carboplatino / radioterapia);
  - no seminoma (nunca radioterapia);
  - marcadores 3 semanas después de la orquiectomía;
  - linfadenectomía retroperitoneal (1–3 cm frente a >3 cm, eyaculación retrógrada);
  - BEP/EP y cisplatino indispensable;
  - IGCCCG;
  - síndrome de lisis tumoral (Cairo-Bishop, hiperhidratación);
  - criopreservación;
  - extragonadales (migración de células germinales).

---

## 5. Reglas de construcción del banco

1. Redactar con la sintaxis del Dr.: "Mencione N…", "¿Cuál es…?", "¿En quién está indicado…?", "¿Para qué sirve…?", viñeta con edad.
2. Respuesta modelo = lista numerada con el dato duro primero, y luego el desarrollo breve organizado (mecanismo, indicación, contraindicación, trampa) para que funcione como guía de estudio.
3. Cada respuesta indica el nivel de probabilidad y el origen (anuncio, repetición o transferencia).
4. Marcar con † lo que no está en la NCCN (NOM, serotipos 31/33/45/6/11, equivalencias citológicas clásicas).
5. Señalar las **discrepancias Dr.–NCCN** como "Ojo" dentro de la respuesta: el Dr. califica, pero el estudiante debe saber ambas.
6. Orden del banco = orden del núcleo transversal (sección 3), para que la lectura secuencial sea una guía completa del tumor.
7. Proporción sugerida por tumor: ~35% "Mencione N", ~20% viñetas clínicas, ~15% indicación, ~15% mecanismo/farmacología, ~15% "para qué sirve" / diferencias.

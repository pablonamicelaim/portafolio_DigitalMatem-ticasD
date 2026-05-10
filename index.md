
<p align="center">
  <img src="https://unl.edu.ec/sites/default/files/logogris%20copia.png" width="280" alt="Logo UNL"/>
</p>

# *Portafolio de Matemática Discreta* 
>## *Por: Pablo Isaias Namicela Maldonado*
---

## 🎯 Objetivo

>*Consolidar el aprendizaje de lógica proposicional mediante la elaboración de un portafolio que evidencie comprensión teórica, desarrollo de ejercicios y aplicación práctica.*

---

## 📂 Contenidos trabajados en la Unidad:

- Lógica proposicional
- Conectores lógicos
- Tablas de verdad
- Leyes proposicionales
- Reglas de inferencia

---

## 🧩 Contenido del Portafolio

---

### 1. 📖 Resumen Teórico

#### 📌 Definición de Proposición

Una *proposición* es un enunciado declarativo que puede ser *verdadero (V)* o *falso (F)*, pero no ambos al mismo tiempo.

> ✅ Ejemplo de proposición: "2 + 2 = 4" → Verdadero  
> ❌ No es proposición: "¿Cuánto es 2 + 2?" → Es una pregunta, no tiene valor de verdad.

---

#### 📌 Tipos de Proposiciones

| Tipo | Descripción | Ejemplo |
|------|-------------|---------|
| **Simple (atómica)** | No contiene conectores lógicos | "Estudio matemáticas" |
| **Compuesta (molecular)** | Une dos o más proposiciones con conectores | "Estudio y apruebo" |
| **Tautología** | Siempre es verdadera | `p ∨ ¬p` |
| **Contradicción** | Siempre es falsa | `p ∧ ¬p` |
| **Contingencia** | Puede ser V o F según los valores | `p → q` |

---

#### 📌 Conectores Lógicos

| Conector | Símbolo | Nombre | Descripción |
|----------|---------|--------|-------------|
| Conjunción | `∧` | Y (AND) | Verdadera solo si ambas son verdaderas |
| Disyunción | `∨` | O (OR) | Verdadera si al menos una es verdadera |
| Negación | `¬` | NO (NOT) | Invierte el valor de verdad |
| Condicional | `→` | Si...entonces | Falsa solo cuando p es V y q es F |
| Bicondicional | `↔` | Si y solo si | Verdadera cuando ambas tienen el mismo valor |

---

#### 📌 Tablas de Verdad

Una **tabla de verdad** muestra todos los posibles valores de una proposición compuesta.

**Tabla base para dos proposiciones (p, q):**

| p | q | p ∧ q | p ∨ q | ¬p | p → q | p ↔ q |
|---|---|-------|-------|----|-------|-------|
| V | V |   V   |   V   |  F |   V   |   V   |
| V | F |   F   |   V   |  F |   F   |   F   |
| F | V |   F   |   V   |  V |   V   |   F   |
| F | F |   F   |   F   |  V |   V   |   V   |

---

#### 📌 Principales Leyes Lógicas

| Ley | Expresión |
|-----|-----------|
| Doble negación | `¬(¬p) ≡ p` |
| De Morgan (conjunción) | `¬(p ∧ q) ≡ ¬p ∨ ¬q` |
| De Morgan (disyunción) | `¬(p ∨ q) ≡ ¬p ∧ ¬q` |
| Conmutativa | `p ∧ q ≡ q ∧ p` |
| Asociativa | `(p ∧ q) ∧ r ≡ p ∧ (q ∧ r)` |
| Distributiva | `p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)` |
| Identidad | `p ∧ V ≡ p` / `p ∨ F ≡ p` |
| Absorción | `p ∧ (p ∨ q) ≡ p` |
| Implicación | `p → q ≡ ¬p ∨ q` |

---

#### 📌 Reglas de Inferencia

| Regla | Forma | Descripción |
|-------|-------|-------------|
| Modus Ponens | `p, p→q ∴ q` | Si p es V y p→q es V, entonces q es V |
| Modus Tollens | `¬q, p→q ∴ ¬p` | Si q es F y p→q es V, entonces p es F |
| Silogismo Hipotético | `p→q, q→r ∴ p→r` | Encadenamiento de condicionales |
| Silogismo Disyuntivo | `p∨q, ¬p ∴ q` | Si una disyunción es V y una parte es F, la otra es V |
| Adición | `p ∴ p∨q` | De p se puede concluir p∨q |
| Simplificación | `p∧q ∴ p` | De una conjunción se puede extraer cualquier parte |

---

### 2. 📊 Ejercicios Resueltos

---

#### ✏️ Ejercicio 1 – Traducción de lenguaje natural a simbólico

**Definiciones:**
- `p` = "Llueve"
- `q` = "Salgo"
- `r` = "Estudio"
- `s` = "Apruebo"

| Enunciado en lenguaje natural | Forma simbólica |
|-------------------------------|-----------------|
| Si llueve, entonces no salgo | `p → ¬q` |
| Estudio o trabajo | `r ∨ s` |
| No es cierto que estoy cansado | `¬r` |
| Salgo si y solo si termino mis tareas | `q ↔ s` |
| Si llueve y no estudio, entonces no apruebo | `(p ∧ ¬r) → ¬s` |

---

#### ✏️ Ejercicio 2 – Construcción de tabla de verdad

**Proposición:** `p ∧ (q ∨ ¬p)`

**Procedimiento paso a paso:**

1. Identificar las variables: `p`, `q`
2. Calcular `¬p`
3. Calcular `q ∨ ¬p`
4. Calcular `p ∧ (q ∨ ¬p)`

| p | q | ¬p | q ∨ ¬p | p ∧ (q ∨ ¬p) |
|---|---|----|--------|--------------|
| V | V |  F |   V    |      V       |
| V | F |  F |   F    |      F       |
| F | V |  V |   V    |      F       |
| F | F |  V |   V    |      F       |

> **Conclusión:** Es una **contingencia** (hay valores V y F).

---

#### ✏️ Ejercicio 3 – Identificación: tautología, contradicción o contingencia

**Proposición:** `(p → q) ↔ (¬p ∨ q)`

**Procedimiento paso a paso:**

1. Calcular `p → q`
2. Calcular `¬p`
3. Calcular `¬p ∨ q`
4. Calcular `(p → q) ↔ (¬p ∨ q)`

| p | q | ¬p | p → q | ¬p ∨ q | (p→q) ↔ (¬p∨q) |
|---|---|----|-------|--------|----------------|
| V | V |  F |   V   |   V    |       **V**    |
| V | F |  F |   F   |   F    |       **V**    |
| F | V |  V |   V   |   V    |       **V**    |
| F | F |  V |   V   |   V    |       **V**    |

> **Conclusión:** Es una **tautología** ✅ — siempre verdadera. Confirma que `p → q ≡ ¬p ∨ q`.

---

#### ✏️ Ejercicio 4 – Aplicación de leyes proposicionales

**Simplificar:** `¬(p ∧ q) ∨ q`

**Procedimiento paso a paso:**

```
¬(p ∧ q) ∨ q
≡ (¬p ∨ ¬q) ∨ q        [Ley de De Morgan]
≡ ¬p ∨ (¬q ∨ q)        [Ley asociativa]
≡ ¬p ∨ V               [Ley del complemento: ¬q ∨ q = V]
≡ V                    [Ley de dominación: ¬p ∨ V = V]
```

> **Conclusión:** La proposición simplificada es **V** (tautología).

---

#### ✏️ Ejercicio 5 – Validación de argumento

**Argumento:**
```
Premisa 1: Si estudio, entonces apruebo.     (p → q)
Premisa 2: Estudio.                          (p)
─────────────────────────────────────────────────────
Conclusión: Apruebo.                         (q)
```

**Procedimiento — Modus Ponens:**

| Paso | Expresión | Justificación |
|------|-----------|---------------|
| 1 | `p → q` | Premisa 1 |
| 2 | `p` | Premisa 2 |
| 3 | `q` | Modus Ponens (1, 2) |

> **Conclusión:** El argumento es **válido** ✅.

---

### 3. 🧠 Ejercicio Aplicado — Caso Real

#### 🏥 Contexto: Sistema de acceso a un hospital

Un hospital tiene el siguiente sistema de seguridad:

> *"Si el paciente tiene cita y presenta su cédula, entonces puede ingresar. Si no puede ingresar, entonces debe esperar en recepción."*

**Paso 1 — Definir proposiciones:**

| Símbolo | Proposición |
|---------|-------------|
| `c` | El paciente tiene cita |
| `d` | El paciente presenta su cédula |
| `i` | El paciente puede ingresar |
| `e` | El paciente espera en recepción |

**Paso 2 — Expresión simbólica:**

```
Regla 1: (c ∧ d) → i
Regla 2: ¬i → e
```

**Paso 3 — Análisis con tabla de verdad (caso Regla 1):**

| c | d | c ∧ d | (c ∧ d) → i (cuando i = V) |
|---|---|-------|----------------------------|
| V | V |   V   |             V              |
| V | F |   F   |             V              |
| F | V |   F   |             V              |
| F | F |   F   |             V              |

**Paso 4 — Caso práctico:**

- El paciente **tiene cita** (c = V) y **presenta su cédula** (d = V)
- Por Regla 1: `(V ∧ V) → i` → `V → i` → `i = V`
- Puede **ingresar** ✅

- Si **no tuviera cita** (c = F):
- `(F ∧ V) → i` → `F → i` → `i` puede ser V o F (el sistema no garantiza acceso)
- Por Regla 2: si `¬i = V` → `e = V` → debe **esperar en recepción**

**Paso 5 — Conclusión:**

> La lógica proposicional permite modelar reglas de sistemas reales. En este caso, el acceso al hospital se puede verificar automáticamente evaluando las proposiciones `c`, `d` e `i`. Esto es la base de los sistemas de control de acceso en software.

---

### 4. 🔍 Reflexión Personal

<details>
<summary><b>¿Qué fue lo más difícil de entender?</b></summary>
  
<br>

El concepto que más tiempo me tomó entender fue el **condicional lógico** ($p \to q$). Intuitivamente, me parece contradictorio que una implicación pueda ser verdadera cuando la premisa es falsa, independientemente del consecuente. ¿Cómo puede ser verdad "si llueve, me mojo" cuando simplemente no llueve?
 
La clave para mí fue entenderlo no como una relación causal, sino como una **promesa**: la implicación solo se "rompe" si la premisa se cumple y la conclusión no. Si la premisa nunca ocurre, la "promesa" jamás fue puesta a prueba, por lo tanto sigue siendo válida. Una vez que mentalicé esa perspectiva, el condicional comenzó a tener sentido.
 
</details>

<details>
<summary><b>¿Qué tema comprendí mejor?</b></summary>

<br>

Las **tablas de verdad** fueron el tema más claro, ya que permiten visualizar sistemáticamente todos los posibles casos. Una vez entendida la estructura, construirlas se vuelve mecánico y predecible.
 
</details>

<details>
<summary><b>¿Cómo puedo aplicar la lógica en mi carrera?</b></summary>

<br>
  
La lógica proposicional tiene aplicaciones directas en:
 
- **Programación:** las estructuras `if`, `while`, `AND`, `OR`, `NOT` son exactamente conectores lógicos.
- **Bases de datos:** las consultas SQL usan condiciones lógicas (`WHERE`, `AND`, `OR`).
- **Diseño de sistemas:** modelar reglas de negocio y flujos de decisión.
- **Ciberseguridad:** validación de condiciones de acceso y permisos.
- **Inteligencia artificial:** sistemas expertos basados en reglas lógicas.

</details>

---

<div align="center">
  <sub>Pablo Namicela &nbsp;·&nbsp; Matemáticas Discretas &nbsp;·&nbsp; Universidad Nacional de Loja &nbsp;·&nbsp; 2026</sub>
</div>

---

<div align="center">
  <sub>Facultad de la Energía, las Industrias y los Recursos Naturales No Renovables &nbsp;·&nbsp; Loja, Ecuador &nbsp;·&nbsp; 2026</sub>
</div>



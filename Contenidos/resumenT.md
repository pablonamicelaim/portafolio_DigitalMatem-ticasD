<p align="center">
  <img src="https://unl.edu.ec/sites/default/files/logogris%20copia.png" width="280" alt="Logo UNL"/>
</p>
### 📌 Definición de Proposición

---

Una *proposición* es un enunciado declarativo que puede ser *verdadero (V)* o *falso (F)*, pero no ambos al mismo tiempo.

> ✅ Ejemplo de proposición: "2 + 2 = 4" → Verdadero  
> ❌ No es proposición: "¿Cuánto es 2 + 2?" → Es una pregunta, no tiene valor de verdad.

---

### 📌 Tipos de Proposiciones

| Tipo | Descripción | Ejemplo |
|------|-------------|---------|
| **Simple (atómica)** | No contiene conectores lógicos | "Estudio matemáticas" |
| **Compuesta (molecular)** | Une dos o más proposiciones con conectores | "Estudio y apruebo" |
| **Tautología** | Siempre es verdadera | `p ∨ ¬p` |
| **Contradicción** | Siempre es falsa | `p ∧ ¬p` |
| **Contingencia** | Puede ser V o F según los valores | `p → q` |

---

### 📌 Conectores Lógicos

| Conector | Símbolo | Nombre | Descripción |
|----------|---------|--------|-------------|
| Conjunción | `∧` | Y (AND) | Verdadera solo si ambas son verdaderas |
| Disyunción | `∨` | O (OR) | Verdadera si al menos una es verdadera |
| Negación | `¬` | NO (NOT) | Invierte el valor de verdad |
| Condicional | `→` | Si...entonces | Falsa solo cuando p es V y q es F |
| Bicondicional | `↔` | Si y solo si | Verdadera cuando ambas tienen el mismo valor |

---

### 📌 Tablas de Verdad

Una **tabla de verdad** muestra todos los posibles valores de una proposición compuesta.

**Tabla base para dos proposiciones (p, q):**

| p | q | p ∧ q | p ∨ q | ¬p | p → q | p ↔ q |
|---|---|-------|-------|----|-------|-------|
| V | V |   V   |   V   |  F |   V   |   V   |
| V | F |   F   |   V   |  F |   F   |   F   |
| F | V |   F   |   V   |  V |   V   |   F   |
| F | F |   F   |   F   |  V |   V   |   V   |

---

### 📌 Principales Leyes Lógicas

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

### 📌 Reglas de Inferencia

| Regla | Forma | Descripción |
|-------|-------|-------------|
| Modus Ponens | `p, p→q ∴ q` | Si p es V y p→q es V, entonces q es V |
| Modus Tollens | `¬q, p→q ∴ ¬p` | Si q es F y p→q es V, entonces p es F |
| Silogismo Hipotético | `p→q, q→r ∴ p→r` | Encadenamiento de condicionales |
| Silogismo Disyuntivo | `p∨q, ¬p ∴ q` | Si una disyunción es V y una parte es F, la otra es V |
| Adición | `p ∴ p∨q` | De p se puede concluir p∨q |
| Simplificación | `p∧q ∴ p` | De una conjunción se puede extraer cualquier parte |

---

### [*⬅️ Volver a Unidad 1*](../Unidad1.md)

<div align="center">
  <sub>Pablo Namicela &nbsp;·&nbsp; Matemáticas Discretas &nbsp;·&nbsp; Universidad Nacional de Loja &nbsp;·&nbsp; 2026</sub>
</div>

---

<div align="center">
  <sub>Facultad de la Energía, las Industrias y los Recursos Naturales No Renovables &nbsp;·&nbsp; Loja, Ecuador &nbsp;·&nbsp; 2026</sub>
</div>


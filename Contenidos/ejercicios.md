
### ✏️ Ejercicio 1 – Traducción de lenguaje natural a simbólico

---

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

### ✏️ Ejercicio 2 – Construcción de tabla de verdad

---

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

### ✏️ Ejercicio 3 – Identificación: tautología, contradicción o contingencia

---

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

### ✏️ Ejercicio 4 – Aplicación de leyes proposicionales

---

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

### ✏️ Ejercicio 5 – Validación de argumento

---

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

### [*⬅️ Volver a Unidad 1*](../Unidad1.md)

<div align="center">
  <sub>Pablo Namicela &nbsp;·&nbsp; Matemáticas Discretas &nbsp;·&nbsp; Universidad Nacional de Loja &nbsp;·&nbsp; 2026</sub>
</div>

---

<div align="center">
  <sub>Facultad de la Energía, las Industrias y los Recursos Naturales No Renovables &nbsp;·&nbsp; Loja, Ecuador &nbsp;·&nbsp; 2026</sub>
</div>

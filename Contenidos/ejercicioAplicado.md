
### 🏥 **Contexto:** Sistema de acceso a un hospital

*Un hospital tiene el siguiente sistema de seguridad:*

> *"Si el paciente tiene cita y presenta su cédula, entonces puede ingresar. Si no puede ingresar, entonces debe esperar en recepción."*

---

***Paso 1 — Definir proposiciones:***

---

| Símbolo | Proposición |
|---------|-------------|
| `c` | El paciente tiene cita |
| `d` | El paciente presenta su cédula |
| `i` | El paciente puede ingresar |
| `e` | El paciente espera en recepción |

---

***Paso 2 — Expresión simbólica:***

---

```
Regla 1: (c ∧ d) → i
Regla 2: ¬i → e
```

---

***Paso 3 — Análisis con tabla de verdad (caso Regla 1):***

---

| c | d | c ∧ d | (c ∧ d) → i (cuando i = V) |
|---|---|-------|----------------------------|
| V | V |   V   |             V              |
| V | F |   F   |             V              |
| F | V |   F   |             V              |
| F | F |   F   |             V              |

---

***Paso 4 — Caso práctico:***

---

- El paciente **tiene cita** (c = V) y **presenta su cédula** (d = V)
- Por Regla 1: `(V ∧ V) → i` → `V → i` → `i = V`
- Puede **ingresar** ✅

- Si **no tuviera cita** (c = F):
- `(F ∧ V) → i` → `F → i` → `i` puede ser V o F (el sistema no garantiza acceso)
- Por Regla 2: si `¬i = V` → `e = V` → debe **esperar en recepción**

---

***Paso 5 — Conclusión:***

---

> La lógica proposicional permite modelar reglas de sistemas reales. En este caso, el acceso al hospital se puede verificar automáticamente evaluando las proposiciones `c`, `d` e `i`. Esto es la base de los sistemas de control de acceso en software.

---

### [*⬅️ Volver a Unidad 1*](../Unidad1.md)

<div align="center">
  <sub>Pablo Namicela &nbsp;·&nbsp; Matemáticas Discretas &nbsp;·&nbsp; Universidad Nacional de Loja &nbsp;·&nbsp; 2026</sub>
</div>

---

<div align="center">
  <sub>Facultad de la Energía, las Industrias y los Recursos Naturales No Renovables &nbsp;·&nbsp; Loja, Ecuador &nbsp;·&nbsp; 2026</sub>
</div>

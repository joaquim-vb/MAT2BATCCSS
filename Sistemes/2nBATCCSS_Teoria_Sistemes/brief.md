# Brief — Sistemes d'equacions (2n BAT)

**Fitxer LaTeX:** `2nBATCCSS_Teoria_Sistemes.tex`
**Carpeta:** `Sistemes/2nBATCCSS_Teoria_Sistemes/`

**Última actualització:** 03/08/2026

---

## Context pedagògic (xat 25/07/2026)

- Tema **a continuació de Matrius**; examen **conjunt** matrius + sistemes.
- **Currículum oficial (BAT CCSS):** resolució de sistemes (fins a $3\times3$) i classificació **SCD / SCI / SI**. **No** entra discussió amb paràmetres.
- **Llibre:** temari més ampli (Gauss amb paràmetres, Rouché-Frobenius, Cramer, homogenis…).
- **Estratègia de classe:** les diapositives **inclouen tot**, però a l'aula el focus és:
  1. **Resolució i classificació** de sistemes
  2. **Discussió amb Gauss** (també **en funció d'un paràmetre**)
  3. Rouché-Frobenius: **possible**, no prioritari
  4. Cramer i generalitzacions: **rarament**

### Prioritat per secció

| Secció | Títol | Prioritat aula |
|--------|-------|----------------|
| 1 | Concepte i classificació | Alta (base) |
| 2 | Expressió matricial | Alta (enllaç amb matrius) |
| 3 | Mètode de Gauss (+ discussió / paràmetres) | **Màxima** |
| 4 | Rouché-Frobenius | Mitjana / opcional |
| 5 | Regla de Cramer | Baixa |
| 6 | Sistemes homogenis | Baixa / breu |

---

## Estructura

| Secció | Títol | Subseccions |
|--------|-------|-------------|
| 1 | Concepte i classificació | 1.1 Equacions · 1.2 Sistemes (+ recordatori $2\times2$) · 1.3 Classificació · 1.4 Escalonats |
| 2 | Expressió matricial | 2.1 $AX=B$ i $A^*$ · 2.2 Resolució amb $A^{-1}$ |
| 3 | Mètode de Gauss | 3.1 Transformacions · 3.2 Resolució · 3.3 Discussió · 3.4 Paràmetres |
| 4 | Rouché-Frobenius | 4.1 Enunciat · 4.2 Classificació amb rangs |
| 5 | Regla de Cramer | 5.1 Enunciat · 5.2 Generalització |
| 6 | Sistemes homogenis | 6.1 Definició i propietats |

Índex en **dues columnes**: seccions 1–3 | 4–6.

---

## Diapositives — Secció 1 (feta 25/07/2026)

### 1.1 Equacions lineals
Definició, coeficients / terme independent, què és lineal; exemple $2x_1-x_2+x_3-3x_4=6$ i comprovació $(3,0,0,0)$; nota: una equació amb més d'una incògnita → infinites solucions.

### 1.2 Sistemes d'equacions lineals
1. Definició general ($m$ equacions, $n$ incògnites) + solució + notació.
2. **Recordatori $2\times2$** (es pressuposen els mètodes): sistema $2x+y=5$, $x-y=1$ per reducció → $(2,1)$; cua cap a 3 incògnites.
3. Sistema $3\times3$: comprovar si $(1,0,-1)$ és solució (amb frase metodològica abans).

### 1.3 Classificació
Definicions SI / SCD / SCI; després tres exemples **$2\times2$** (SCD, SCI amb $\lambda$, SI) i resum final.

### 1.4 Sistemes escalonats
Definició + minipages escalonat / no escalonat; substitució enrere; exemple resolt → $(0,2,1)$.

---

## Diapositives — Secció 2 (feta 29/07/2026)

### 2.1 Expressió matricial
- $AX=B$ amb $A$, $X$, $B$ (dimensions).
- Matriu ampliada $A^*=(A|B)$; enllaç cap a Gauss.

### 2.2 Resolució amb la inversa
Condició ($A$ quadrada, $|A|\neq 0$); $X=A^{-1}B$. Exemple del llibre: enunciat+$A$,$B$ en minipages → invertible → cal $A^{-1}$ amb Gauss--Jordan (pas a pas) → $X=A^{-1}B$ → $(1,-3,-2)$.

---

## Diapositives — Secció 3 (feta 29/07/2026)

### 3.1 Transformacions elementals
Idea + tres operacions de fila; recordatori d'ordenar les incògnites.

### 3.2 Resolució (exemple del llibre)
Sistema → $A^*$ → zeros 1a columna → intercanvi + escalonar → $(1,0,-1)$.

### 3.3 Discussió
Criteris última fila (SCD / SCI / SI); exemple SCI + resolució en funció de $z=\lambda$; exemple SI.

### 3.4 Paràmetres
Gauss pas a pas amb $\lambda$; casos + resolució SCD ($z\to y\to x$); si $\lambda$ és a una columna es pot reordenar; si és a més d'una → Rouché--Frobenius (sense desenvolupar).

---

## Diapositives — Secció 4 (feta 03/08/2026)

### 4.1 Enunciat
Compatible $\Leftrightarrow$ $\operatorname{Rang}(A)=\operatorname{Rang}(A^*)$; recordatori de rang.

### 4.2 Classificació + exemples
Criteris SI / SCD / SCI; exemples SCD (nou), SCI i SI (els de la secció 3, enllaç amb Gauss); resum Gauss vs Rouché.

---

## Diapositives — Secció 5 (feta 03/08/2026)

### 5.1 Regla de Cramer
Enunciat + enllaç RF; exemple del llibre: $|A|=32$, $|A_x|=|A_y|=32$, $|A_z|=-32$ → $(1,1,-1)$.

### 5.2 Generalització
Discussió SCI amb rangs; Cramer $2\times2$ amb $z=\lambda$ → $x=1/5$, $y=(5\lambda+7)/5$.

---

## Diapositives — Secció 6 (feta 03/08/2026)

### 6.1 Sistemes homogenis
Definició, solució trivial, sempre compatible; SCD vs SCI; exemple SCI → $(-\lambda,-\lambda/3,\lambda)$.

---

## Convencions d'aquest tema

- Mateixa plantilla visual que Matrius (verd Margues, `caixadef`, overlays).
- **Abans de 3 incògnites:** sempre un recordatori breu $2\times2$ (resolució i/o classificació).
- Gauss: reutilitzar patrons de matriu ampliada / `\gaussop` / `\gjopfila`.
- Checklist overlays:
  - [x] Acumular passos (`\onslide`), no substituir
  - [x] Operacions de fila visibles al costat
  - [x] Classificació SCD / SCI / SI sempre amb la mateixa terminologia

---

## Pendent

- [x] Omplir secció 1 (concepte i classificació)
- [x] Omplir seccions 2 i 3 (expressió matricial + Gauss)
- [x] Omplir seccions 4–6 (Rouché, Cramer, homogenis)
- [ ] Activitats / fulls d'exercicis (carpeta `Sistemes/` quan toqui)

---

## Decisions de disseny (log del xat)

- **25/07/2026:** Carpeta nova `Sistemes/` al nivell de `Matrius/`; nomenclatura `2nBATCCSS_Teoria_Sistemes`. Esquelet amb 6 seccions; focus aula = Gauss + classificació/discussió (amb paràmetre).
- **25/07/2026:** Secció 1 omplerta. Recordatori $2\times2$ a 1.2; classificació 1.3 amb exemples $2\times2$.
- **29/07/2026:** Seccions 2 i 3 omplertes amb exemples del llibre (inversa, Gauss pas a pas, discussió SCI/SI, paràmetre $\lambda$).
- **03/08/2026:** Seccions 4–6: Rouché amb exemples enllaçats al Gauss de 3.3; Cramer (exemple llibre) + generalització; homogenis.

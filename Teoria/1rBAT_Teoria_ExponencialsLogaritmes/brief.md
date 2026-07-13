# Brief — Exponencials i logaritmes (1r BAT)

Document de referència per continuar/edició amb l'agent. Descriu el **contingut i l'ordre d'aparició** de cada diapositiva del fitxer `1rBAT_Teoria_ExponencialsLogaritmes.tex`.

**Última actualització:** juliol 2026 (estat del xat de conversió PPT → Beamer).

---

## Convencions del tema

- **Idioma:** català; usar \(D_f\), \(R_f\) (no «Rec(f)»); `\rightarrow` en lloc de «llavors» on calgui.
- **Colors:** verd Margues (`margueVerdFosc`, `margueVerdClar`, `margueVerdCaixa`).
- **Caixes:** `\caixatitol{...}` (fórmula tipus, centrada); `\caixadef[centrat]{...}` (propietats); `\caixadem` (demostració).
- **Solucions:** `\solucio{x = ...}` — tota l'expressió en verd i negreta (no caixa separada).
- **Factor comú:** `\fc{...}` ressalta el factor en verd (tipus 3).
- **Animacions:** `\only<n->` / `\item<n->`; en equacions, **primer exemple 1 sencer, després exemple 2** (columnes).
- **Font:** Fira Sans + `mathastext` (matemàtiques sans-serif).

---

## Estructura general

| Secció | Tema | Diapositives lògiques |
|--------|------|------------------------|
| — | Portada + índex | 2 |
| 1 | Recordatori de funcions | 1 |
| 2 | Funció exponencial | 5 |
| 3 | Equacions exponencials | 10 |
| 4 | Funció logarítmica | 8 |
| **Pendent** | Equacions logarítmiques + sistemes | — |

---

## Diapositives

### Portada
**Títol:** Exponencials i logaritmes · 1r BAT · logo institut.

### Índex
`\tableofcontents` automàtic.

---

### 1. Recordatori de funcions

**Layout:** text esquerra + gràfic dreta.

1. Definició de funció (variable independent → dependent, valor únic).
2. Es poden expressar com a gràfic, taula o expressió algebraica.
3. Gràfic: recta \(f(x)=3{,}8x\) (funció).
4. Gràfic: paràbola paramètrica **no** és funció (marca vermella ×).
5. «Exemples:»
6.–9. Exemple perímetre circumferència: \(f(x)=2\pi x\), variable dependent/independent.

---

### 2.1 Motivació funció exponencial

1. Problema insectes: cada dia cada individu té 2 descendents i mor.
2.–5. Taula dies 0–4: 1, 2, 4, 8, 16 insectes (animació cel·la a cel·la).
6.–7. Preguntes: població dia 5, 8, 25? Cal el dia anterior?
8. Caixa: \(\text{insectes}=2^{\text{dies}} \Rightarrow f(x)=2^x\).
9.–10. Altres situacions: virus, interessos, paper doblegat…

---

### 2.2 Funció exponencial

**Layout:** text esquerra + gràfic i dues taules dreta (posició fixa).

**Text (esquerra):**
1. Definició \(f(x)=a^x\), \(a\in\mathbb{R}^+\), \(a\neq 1\).
2. \(D_f=\mathbb{R}\).
3. \(R_f=\mathbb{R}^+\).
11. Si \(a>1\): \(a^x>1\) si \(x>0\), \(0<a^x<1\) si \(x<0\).
19. Si \(0<a<1\): cas simètric.
20. No talla l'eix \(x\) (\(a^x\neq 0\)).

**Gràfic + taules (dreta):**
4.–10. Taula i punts de \(f(x)=2^x\); corba blava \(f\).
13.–18. Taula i punts de \(g(x)=(1/2)^x\); corba vermella \(g\).

---

### 2.3 Propietats exponencial (I) — algebraiques

**Layout:** dues columnes (propietat | exemple).

1. \(D_f=\mathbb{R}\), \(R_f=\mathbb{R}^+\).
2.–3. \(a^x\cdot a^z=a^{x+z}\), \(a^x/a^z=a^{x-z}\) — ex. \(3^2\cdot 3^4=3^6\).
4.–5. \((a^x)^z=a^{xz}\) — ex. \((3^2)^4=3^8\).
6.–7. \((ab)^x\), \((a/b)^x\) — ex. \(3^5\cdot 4^5=12^5\).
8. \(a^0=1\) → totes passen per \((0,1)\).

---

### 2.3 Propietats exponencial (II) — creixement, límits, simetria

**Superior:** bullets esquerra + gràfic dreta.

1. \(a>1\) → **creixent** (\(x<z \Rightarrow a^x<a^z\)).
2.–3. Corbes \(f_1=2^x\), \(f_2=3^x\); límits si \(a>1\): \(x\to+\infty \Rightarrow +\infty\), \(x\to-\infty \Rightarrow 0\).
4. \(0<a<1\) → **decreixent**.
5.–6. Corbes \(f_3=(1/2)^x\), \(f_4=(1/3)^x\); límits si \(0<a<1\).
7. Simetria de \(a^x\) i \((1/a)^x\) respecte l'eix \(y\).

**Etiquetes gràfic:** fora de la zona de corbes (x o y fixos).

---

### 2.3 Propietats exponencial (III) — injectiva i exhaustiva

**Esquerra — injectiva:**
1. \(a^x=a^z \Rightarrow x=z\).
2. Ex.: \(2^x=2^3 \Rightarrow x=3\).
3.–6. Caixa demostració pas a pas (multiplicar per \(a^{-x}\), etc.).

**Dreta — exhaustiva:**
7.–10. \(y\in\mathbb{R}^+\) → \(\exists!\,x\) amb \(a^x=y\); exemples \(y=8\), \(y=16\).
7.–8. Gràfic \(f(x)=2^x\), recta \(y=8\), punt \((3,8)\).

---

### 3. Equacions exponencials (intro)

1. Exhaustivitat → cada \(y\) té única antiimatge.
2. Podem resoldre equacions exponencials.
3. Cinc tipus.
4.–8. Llista d'exemples (sense resoldre): \(5^x=625\), \(8^{2x+3}=4^{x/3}\), suma de potències, substitució, \(2^x=23\).

---

### 3 — Tipus 1: \(a^x=k\)

- Caixa tipus + **Estratègia:** expressar \(k\) com a potència de base \(a\).
- **Ex. 1** (esquerra, passos 2–4): \(5^x=625 \to 5^4 \to x=4\).
- **Ex. 2** (dreta, passos 5–7): \(4^x=64 \to 4^3 \to x=3\).

---

### 3 — Tipus 2: \(a^{f(x)}=b^{g(x)}\)

- **Estratègia:** mateixa base.
- **Ex. 1:** \(3^{x+1}=9 \to x=1\).
- **Ex. 2:** \(8^{2x+3}=4^{x/3} \to x=-27/16\).

---

### 3 — Tipus 3: suma de potències = \(k\)

- **Estratègia:** factor comú.
- **Diapo A — Ex. 1:** \(2^x+2^{x+1}=12\); separar \(2^{x+1}=2^x\cdot 2\); marcar \(\fc{2^x}\); \(x=2\).
- **Diapo B — Ex. 2:** \(3^{x-1}+3^x+3^{x+1}=39\); descomposició \(3^{x-1}=3^x/3\); factor comú; suma \(13/3\); passar factor; \(3^x=9\); \(x=2\).

---

### 3 — Tipus 4: substitució \(t=a^x\) (2n grau)

**Estratègia** (apareix abans de cada pas): (1) mateixa base → (2) \(t=a^x\) → (3) desfer canvi.

**Exemple 1:** \(4^x+6\cdot 2^{x+1}+32=0 \to t^2+12t+32=0 \to x_1=3\), \(x_2=2\).

**Exemple 2:** \(4^x-5\cdot 2^x+4=0 \to t^2-5t+4=0 \to x_1=2\), \(x_2=0\).

- \(t=2^x\) en **línia pròpia** (no «amb \(t\)» inline).
- Solucions en línies separades per \(x_1\), \(x_2\).

---

### 3 — Tipus 5: \(a^x=t\) (aproximat)

**Diapo A — Diagrama de flux** (pas a pas):
1. Provar \(x\) → 2. Calcular \(a^x\), comparar → 3. Massa gran/petit → 4. Precisió (defecte/excés) → 5. Tornar a provar (fletxa per l'esquerra, fora de les caixes).

**Diapo B — Exemple \(2^x=23\):**
- Esquerra: \(2^1\), \(2^2\), \(2^4<23\), \(2^5>23\); després \(2^{4{,}51}\), \(2^{4{,}52}\), \(2^{4{,}53}\); defecte \(x=4{,}52\), excés \(x=4{,}53\).
- Dreta: recta \(16\)—\(23\)—\(32\) (\(4<x<5\)); zoom \(4{,}51\)–\(4{,}53\).

---

### 4. La funció logarítmica

**Layout:** esquerra text + dreta gràfic i exemple.

**Esquerra:**
1. Com resolem \(2^x=8\)?
2. Logaritme = inversa de l'exponencial.
3. \(a^x=b \Rightarrow x=\log_a b\).
4. Caixa: «A quin nombre he d'elevar \(a\) per obtenir \(b\)?»
7. \(f(x)=a^x \Rightarrow f^{-1}(x)=\log_a x\).
8. Simetria respecte \(y=x\).

**Dreta:**
2. Corba \(f(x)=2^x\) (sense punts).
6. Corba \(f^{-1}(x)=\log_2 x\).
7. Recta \(y=x\).
5.–7. **Exemple pas a pas:** \(2^x=128 \to x=\log_2 128 \to x=7\).

---

### 4.1 Propietats dels logaritmes (I)

**Capçalera:** \(f(x)=\log_a x\)

**Bullets:** \(D_f=\mathbb{R}^+\), \(R_f=\mathbb{R}\); \(a\neq 1\); contínua; simetria \(\log_a x\) / \(\log_{1/a} x\); \(\log_a a=1\), \(\log_a 1=0\); punt \((1,0)\).

**Gràfic (pas 4):** \(\log_2 x\) (blau) i \(\log_{1/2} x\) (lila); punt \((1,0)\).

---

### 4.1 Propietats dels logaritmes (II)

**Layout:** 2 columnes; caixa verda centrada + exemples en bullets sota.

| Esquerra | Dreta |
|----------|-------|
| \(a^{\log_a x}=x\) → \(2^{\log_2 8}=8\) | |
| \(\log_a(xz)=\log_a x+\log_a z\) → \(\log_a(3b)\), \(\log_a 6\) | \(\log_a(x/z)=\ldots\) → dos exemples |
| | \(\log_a(x^p)=p\log_a x\) → \(\log_a(x^2)\), \(2\log_a x=\log_a(x^2)\) |

---

### 4.1 Propietats dels logaritmes (III)

**Bullets:** creixent si \(a>1\); decreixent si \(0<a<1\).

**Gràfic:** \(f_3=\log_2 x\), \(f_4=\log_8 x\) (creixents); \(f_1=\log_{1/2} x\), \(f_2=\log_{1/8} x\) (decreixents). Etiquetes a \((3,\pm 2{,}5)\) aprox.

**Límits (baix):**
- \(a>1\): \(x\to 0^+ \Rightarrow -\infty\), \(x\to+\infty \Rightarrow +\infty\).
- \(0<a<1\): casos oposats.

*(Comparació entre bases eliminada per claredat.)*

---

### 4.2 Bases més utilitzades

1. Exponencials: \(e^x\), \(10^x\).
2. Bases log: \(e\), \(10\).
3.–5. \(\ln x\), \(\log x\) (tecles calculadora).
6. Gràfic \(\ln x\) (vermell discontinu) vs \(\log x\) (gris).

---

### 4.3 Canvi de base

**Diapo A — Derivació:**
1. \(b^x=m \Leftrightarrow x=\log_b m\).
2. Aplicar \(\log_a\) → \(x=\frac{\log_a m}{\log_a b}\).
3. Fórmula: \(\log_b m=\frac{\log_a m}{\log_a b}\).

**Diapo B — Exemples:**
1. Calculadores sense \(\log_a\) arbitrari → \(\log_3 5=\frac{\log 5}{\log 3}\approx 1{,}465\).
2. Equacions: \(2^x=23 \to x=\frac{\log 23}{\log 2}\approx 4{,}52\).

---

## Pendent (no implementat)

- **5. Equacions logarítmiques** (tipus i estratègies, estil secció 3).
- **6. Sistemes d'equacions exponencials i logarítmiques** (o secció equivalent del PPT original).

---

## Notes de disseny (decisions del xat)

- Preferència per flux **vertical** i passos progressius (no cadenes horitzontals llargues).
- Equacions tipus 4: estratègia **abans** del pas corresponent (no simultani).
- Gràfics log/exponencial intro: **sense punts** quan n'hi ha prou amb les corbes (diapo 4); la 2.2 manté punts per construir taules.
- Evitar desbordament al peu: dividir diapositives denses (tipus 3 ex.2, canvi de base, etc.).
- Tipus 4: exemples han de ser de **2n grau** en \(t\) (no reduïbles només a factor comú).

---

## Fitxers relacionats

- `1rBAT_Teoria_ExponencialsLogaritmes.tex` — font
- `LogoInstitut.png` — logo portada/peu
- `Teoria/_template/beamer-teoria-template.tex` — plantilla
- `.cursor/rules/teoria-beamer.mdc` — regles Cursor per nous temes

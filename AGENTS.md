# MAT2BATCCSS — instruccions de projecte

## Abast i publicació

Aquest repositori conté material docent. El contingut que es pretén publicar és teoria i activitats resoltes; no afegeixis, no preparis per a commit ni pugis exàmens, solucions d'exàmens, proves o esborranys sense una ordre explícita de l'usuari.

- No facis `git add`, commits ni `push` tret que l'usuari ho demani explícitament.
- No eliminis fitxers generats ni canviïs `.gitignore` automàticament. Si cal definir la política de publicació, proposa primer els patrons i l'abast.
- No modifiquis les regles de Cursor (`.cursor/`) si no se't demana; són documentació de compatibilitat.

## Flux de treball LaTeX

- Treballa en blocs petits (normalment 1--3 diapositives o una sub-secció). Abans d'editar una presentació de teoria, llegeix el seu `brief.md` si existeix.
- El contingut docent i les explicacions han de ser en català. Si falta informació de les captures del llibre, pregunta o deixa explícita la decisió; no inventis contingut curricular.
- Compila el document objectiu amb `latexmk -pdf -interaction=nonstopmode -file-line-error` després de cada bloc lògic i abans de lliurar-lo. No cal compilar després de canvis purament microscòpics.
- Revisa els errors de compilació i els avisos de maquetació rellevants, especialment `Overfull \\vbox` i `Overfull \\hbox`. Si una diapositiva és massa densa, proposa dividir-la abans d'encongir la tipografia.
- No modifiquis altres temes ni plantilles compartides tret que l'usuari ho hagi inclòs a la tasca.

## Presentacions de teoria Beamer

- Per a fitxers de teoria Beamer, segueix la plantilla i les convencions de `Plantilles/TeoriaBeamer` quan siguin accessibles.
- Mantén Beamer 16:9, el logo només a la portada i animacions acumulatives (`n->`) per defecte. No facis desaparèixer contingut sense consultar-ho.
- Reutilitza macros i patrons existents; actualitza el `brief.md` en acabar una secció gran si l'usuari no indica el contrari.

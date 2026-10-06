# TempoPilot – prezentační web

**Čeho se repozitář týká:** veřejně hostovaný prezentační web osobního projektu **TempoPilot** – Windows aplikace, která zaznamenává práci na PC a práci s AI a pomáhá z ní udělat výkaz. Web popisuje, co aplikace umí, jak funguje, jak chrání soukromí, ukazuje snímky s ukázkovými daty a popisy změn.

Repozitář obsahuje **jen hotovou stránku** (`index.html`, vše v jednom souboru) a později i `version.json` pro automatické aktualizace aplikace. Web je veřejný, ale mimo vyhledávače (`noindex`). Zdrojový kód webu i aplikace je v soukromém repozitáři; stažení aplikace vyžaduje pozvánku do něj.

## Důležité adresy

| Co | Adresa |
|---|---|
| Web (GitHub Pages, veřejný, mimo vyhledávače) | https://mhudakcz.github.io/TempoPilot/ |
| Tento repozitář (veřejný, hotový web) | https://github.com/mhudakcz/TempoPilot |
| Zdrojový kód aplikace a webu (soukromý) | https://github.com/mhudakcz/TempoPilot-app |

## Aktualizace

Web se sestavuje ve zdrojovém repozitáři (`scripts/build-site.py`, postup v `site/README.md`); výsledný `index.html` se nahraje sem a GitHub Pages se přestaví samy.

# Projecte intermodular 2n DAM Semipresencial

## WIREFRAMES es troben a `img/wireframes`

Aquest projecte utilitza: 

Metodologia **AGILE** https://agilemanifesto.org/iso/ca/principles.html

**Trello** per organitzar el treball i els sprints https://trello.com/b/SO1R63oZ/projecte-intermodular  

**Draw.io** i **Figma** per a crear els wireframes `img/wireframes`

Modeladge Base de Dades amb **dbdiagram.io**

# STACK
Frontend:
- HTML + CSS + JS
- BOOTSTRAP

Framework aplicació escritori
- Electron

Backend:
- Node.js
- Express
- Supabase / Neon (Allotjament servidor al nuvol)

Base de dades:
- Postgres

# JUSTIFICACIÓ DE STACK
Amb **html**, **css** i **javascript** es pot crear ràpidament un interficie gràfica que pot ser aprofitada tant per a pàgina web simple, aplicació d'escritori i amb uns quants ajustaments, una app d'android. Bootstrap és utilitzat per a facilitar el  disseny i estilització dels diferents components d'aquesta interficie, a més, facilita la creació de botons, dropdowns i demés menús necessaris.

Amb **Electron** s'aconsegueix empaquetar tota la aplicació en un executable i *look and feel* de una aplicació d'escritori.

El backend amb **node.js** i **express** és una forma senzilla de crear el backend per a gestionar la entrada i eixida de dades i la connexió amb la base de dades, a més de certa coherència amb els llenguatges del frontend. Permet crear un servidor http fàcilment i una separació que facilitaria la portabilitat a altres plataformes.

Serveis com **Supabase** o **Neon** permeten la gestió de la base de dades Postgres a més. Els free tiers son suficients per a mostrar el funcionament d'aquest projecte.

Com a base de dades s'utilitza **Postgres** per familiaritat i integració amb els serveis que ja s'utilitzen.
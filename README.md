# 🧠 Projecte de Modelatge de Bases de Dades

Aquest projecte conté una sèrie d'exercicis dissenyats per practicar el modelatge de bases de dades relacionals a partir de requeriments reals. Està dividit en tres nivells de dificultat, amb escenaris inspirats en negocis i plataformes digitals com una òptica, un servei de menjar a domicili i una versió simplificada de YouTube.

---

## 📁 Nivell 1 – Òptica “Cul d’Ampolla”

### 📝 Descripció

Una òptica necessita informatitzar la gestió dels seus clients/es i les vendes d'ulleres. L’objectiu és dissenyar un model de base de dades que permeti emmagatzemar i consultar informació sobre:

- **Proveïdors**: nom, adreça (carrer, número, pis, porta, ciutat, codi postal, país), telèfon, fax, NIF.
- **Ulleres**: marca, graduació de cada vidre, tipus de muntura (flotant, pasta, metàl·lica), colors, preu.
- **Clients/es**: nom, adreça postal, telèfon, email, data de registre i qui els ha recomanat.
- **Empleats/des**: responsable de cada venda.
- **Vendes**: dia i hora de la venda.

### 📌 Exercicis

- **Exercici 1**: Modelatge de la base de dades des del punt de vista del client.
- **Exercici 2**: Modelatge de la base de dades des del punt de vista de les ulleres.

---

## 🍕 Nivell 2 – Comandes de Menjar a Domicili

### 📝 Descripció

Modelatge d'una base de dades per a una plataforma de comandes de menjar a domicili amb els següents requeriments:

- **Clients/es**: identificador, nom, cognoms, adreça, codi postal, localitat, província, telèfon.
- **Comandes**: identificador, data/hora, tipus (repartiment o recollida), quantitat per producte, preu total, nota addicional.
- **Productes**: pizzes, hamburgueses, begudes amb nom, descripció, imatge i preu. Les pizzes poden tenir categories variables.
- **Botigues**: identificador, adreça, codi postal, localitat, província.
- **Empleats/des**: identificador, nom, cognoms, NIF, telèfon, rol (cuiner/a o repartidor/a). Es guarda qui reparteix cada comanda i quan ho fa.

### 📌 Exercici

- **Exercici 1**: Disseny complet del model relacional per gestionar el servei de comandes.

---

## 📺 Nivell 3 – Mini YouTube

### 📝 Descripció

Modelatge d'una base de dades per a una versió reduïda de YouTube amb els següents elements:

- **Usuaris/àries**: email, contrasenya, nom d’usuari, data de naixement, sexe, país, codi postal.
- **Vídeos**: títol, descripció, mida, arxiu, durada, thumbnail, reproduccions, likes/dislikes, estat (públic, ocult, privat), etiquetes, data/hora de publicació, autor.
- **Canals**: nom, descripció, data de creació.
- **Subscripcions**: relacions entre usuaris/es i canals.
- **Playlists**: nom, data de creació, estat (públic o privat), vídeos afegits.
- **Comentaris**: text, data/hora i usuari/ària relacionat.

### 📌 Exercici

- **Exercici 1**: Disseny complet de la base de dades per suportar funcionalitats bàsiques de la plataforma.

---

## 🛠️ Eines Recomanades

- Eines de modelatge E/R: `dbdiagram.io`, `Draw.io`, `MySQL Workbench`, etc.
- SQL per a creació d’esquemes.
- Documentació i anàlisi de requeriments reals.

---

## 🎯 Objectiu

Consolidar coneixements sobre:

- Normalització i eficiència de les dades.
- Identificació d'entitats i relacions.
- Disseny de bases de dades escalables i funcionals.

---

## 📄 Llicència

Aquest projecte està distribuït sota la llicència MIT. Pots fer-lo servir, modificar-lo i compartir-lo lliurement.


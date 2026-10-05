Ciao, sono Andrea Flaiani
Sono uno studente magistrale in Ingegneria Informatica all' Università Politecnica delle Marche, con un forte interesse verso gli ambienti Data in generale e il mondo dell'AI 
come del Machine Learning. 

Di seguito ecco alcuni dei progetti universitari a cui ho lavorato:
### [Anomaly Detection su dati biometrici (VitalDB)](https://github.com/callmefl/anomaly-detection-vitaldb)
Pipeline a layer Bronze/Silver/Gold su dati biometrici da VitalDB: ingestione in Parquet, seconda fase di cleaning, e storage su MongoDB Time Series Collections con gestione artigianale dei metadati in ottica data-lakehouse governance. Infine, analisi multilivello di Anomaly Detection (regole cliniche + ML non supervisionato: Isolation Forest, Autoencoder) con API REST e dashboard web come output visivo
governance, modello finale di rilevamento anomalie.

**Stack:** Python, MongoDB, PyTorch, scikit-learn, FastAPI, Apache Parquet, pandas, Docker

### [Zero Trust Architecture](https://github.com/callmefl/Advanced-Cybersecurity-for-IT-Project)
Infrastruttura di rete Zero Trust dockerizzata con microsegmentazione in quattro zone, mTLS e attestazione hardware (TPM). Le richieste sono validate in tempo reale da Envoy (PEP) e Open Policy Agent (PDP) sulla base di una tupla contestuale a 7 dimensioni. Il rischio comportamentale è calcolato da un modello Gradient Boosting su Splunk MLTK, mentre Snort e Splunk SIEM monitorano la rete. Validato su 14 scenari di attacco e accesso.

**Stack:** Docker, Envoy Proxy, Open Policy Agent, Splunk (MLTK), Snort, nftables, MongoDB, Python

### [Predictive Process Monitoring con DGCNN](https://github.com/callmefl/DGCNN_active_prefixes_BIG_DATA_Project)
Predizione della prossima attività in processi aziendali a partire da event log .xes. I log sono convertiti in grafi con riparazione del rumore (insertion/deletion repair), e i casi paralleli sono collegati in Super-Grafi con nodo globale per dare contesto al modello. Una Deep Graph Convolutional Neural Network con SAGEConv e SortAggregation esegue la classificazione multiclasse, valutata con Accuracy e F1-Score.

**Stack:**  Python, PyTorch, PyTorch Geometric (PyG), Process Mining (XES), PM4Py, NetworkX, Matplotlib

### [Project Management & Business Intelligence](https://github.com/callmefl/Project-Management-Business-Intelligence)
Due progetti complementari.
⚡ Il primo è un Project Management Plan integrale (standard PMI/PMBOK) per una rete logistica a guida autonoma con droni ad Ancona, con schedulazione CPM a 22 mesi su Microsoft Project, analisi probabilistica dei rischi e piano finanziario
⚡Il secondo è una pipeline multi-piattaforma per la Sports Analytics applicata su dati FC24 strutturata per supportare tre stakeholder decisionali: lo Staff tecnico su Qlik Sense (analisi tattica, gestione dello spogliatoio e calci piazzati), la Direzione sportiva
  & Scouting su Power BI (valutazione patrimoniale della rosa, sostenibilità ingaggi e recruiting predittivo con algoritmi di Machine Learning ), e il C-Level su Tableau (benchmark macro-economico delle top 5 leghe europee e analisi sul Gender Pay Gap).

**Stack:** Microsoft Power BI, Tableau Public, Qlik Sense, Microsoft Project, Python

### [Sistema di gestione del ristorante Emilia](https://github.com/callmefl/Ingegneria-del-Software)
Software con applicativo desktop per la gestione del Ristorante Emilia (Portonovo): prenotazioni con codice univoco, assegnazione automatica dei tavoli con compattamento dinamico, gestione delle comande e dei conti per cameriere e amministratore. Progettato con una suite completa di diagrammi UML (analisi, progettazione, deployment).

**Stack:**  Python, PyQT, UML


<!--
**callmefl/callmefl** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Guide devis générique, partie 1 (en-tête et sections 1 à 6), version sourcée

> date_redaction : 2026-11-20 ; statut : synthese-sourcee


> **Ce guide est une synthèse de pages publiques lues entre le 2026-11-19 et le 2026-11-20. Ce n'est ni un avis juridique, ni un avis fiscal.** Les règles changent, plusieurs dispositifs sont suspendus ou échus, et beaucoup de règles de détail (dépenses éligibles, sous-traitance) ne sont **pas publiées**. Avant d'engager un client, faire confirmer par écrit auprès du financeur concerné.
>
> **Aucun appel n'a encore été passé** (Bpifrance, DREETS, comptable, régions) : le fichier de réponses est vide. Toutes les questions de la section 12 restent donc **à confirmer**. Aucune étiquette `[CONFIRMÉ PAR BPIFRANCE]` n'existe à ce jour.

**Légende de fiabilité utilisée partout dans ce guide**
- **[ÉCRIT]** : écrit sur une page officielle lue (la note source est indiquée).
- **[DÉDUIT]** : conclusion tirée des pages, non écrite telle quelle. À confirmer.
- **[NON PUBLIÉ]** : la page lue ne le dit pas. Ne pas le promettre au client.
- **[RECOMMANDATION]** : choix de prudence de ce guide, pas une règle du financeur.
- **[CONFIRMÉ PAR BPIFRANCE, date]** : réservé aux réponses reçues (aucune à ce jour).

---

## 1. Le principe : qui touche l'aide, qui paie le prestataire

Dans presque tous les dispositifs, **l'aide va au client** (l'entreprise bénéficiaire), pas au prestataire. [1] Le client paie le prestataire, puis se fait rembourser tout ou partie. Trois circuits à ne pas confondre :

| Circuit | Qui paie le prestataire | Exemples | Ce que ça change pour le devis |
|---|---|---|---|
| **A. Subvention au client** | Le client, qui est ensuite aidé (taux de 25 à 70 % selon le dispositif) [2][3] | Subvention Innovation, Bourse French Tech, aides régionales de conseil (dont PM'up et Innov'up en Île-de-France) | Le prestataire émet un devis classique au client. Le client dépose sa demande. |
| **B. Prestation commandée par le financeur ou son réseau** | Le financeur (Bpifrance, une Région ou un opérateur) paie l'expert ; le client règle sa quote-part [4] | Diag Data IA, missions de conseil Bpifrance, Pack IA (Île-de-France, experts du réseau Hub France IA / IMT-Teralab) [5][6] | **Le prestataire ne facture pas le client.** [7] Il faut être expert agréé / habilité, **à titre individuel** pour Bpifrance. [8] |
| **C. Paiement direct** | Le client, sans aide | Formation par un organisme sans Qualiopi [9] | Devis normal, sans mention « finançable ». [10] |

Source : (voir table).

---

## 2. Quelle prestation, quel canal ?

| Prestation | Canal le plus réaliste | Statut | Notes sources |
|---|---|---|---|
| **Développement IA** (IA locale, agents) dans un **projet d'innovation** | **Subvention Innovation** ou **Bourse French Tech** (circuit A). En Île-de-France : **Innov'up** (prestations externes d'un projet RDI) | **[ÉCRIT]** : l'aide finance « les dépenses de R&D internes et externes ». **[NON PUBLIÉ]** : liste précise des dépenses externes, plafond de sous-traitance, « la condition » du plafond [11][12] | (voir table) |
| **Développement IA** hors cadre R&D | Pas de canal clair trouvé. Piste IDF : PM'up en investissement immatériel, **[DÉDUIT]**, à confirmer [13] | **[NON PUBLIÉ]** [14] | (voir table) |
| **Conseil** (stratégie IA/data/SI), **choix du consultant sans référencement publié** | Aides régionales de conseil : Normandie, Pays de la Loire, Centre-Val de Loire, Nouvelle-Aquitaine, **Île-de-France (PM'up)** | **[ÉCRIT]** pour les taux et plafonds (voir section 7). L'absence de référencement est **[DÉDUIT]** (aucune exigence trouvée sur les pages) [15] | (voir table) |
| **Conseil**, région qui **exige un référencement** | Grand Est (Data/IA), Hauts-de-France (Booster Transformation) | **[ÉCRIT]** : prestataire référencé requis (Grand Est : « Sélectionnez un prestataire référencé »). [16][17][18] Procédure « fast track » : **[ÉCRIT]** dans le règlement d'intervention PDF de juillet 2025 (absente de la page web) [19] | (voir table) |
| **Diagnostics et missions de conseil Bpifrance** (Diag Data IA, Choix de l'approche IA…) | Circuit B : **agrément individuel d'expert** | **[ÉCRIT]** : « Bpifrance ne délivre pas d'agrément pour des cabinets… mais exclusivement pour des personnes » [20] | (voir table) |
| **Formation** | Paiement direct du client pour un organisme sans Qualiopi ; OPCO, CPF après Qualiopi [21] | Paiement sur fonds propres avec NDA sans Qualiopi : **[ÉCRIT]** par l'OPCO EP (FAQ) [9], **[NON PUBLIÉ]** sur une page DREETS [22] ; blocage des fonds publics sans Qualiopi **[ÉCRIT]** [23]. FNE-Formation : ne plus le présenter comme mobilisable en 2026 [24][25] | (voir table) |

**À retenir** : la valeur d'un prestataire en conseil, développement IA et formation se joue surtout sur deux terrains : (1) du **développement IA dans un projet d'innovation** financé par une subvention du client, (2) [26] du **conseil** financé par une aide régionale à libre choix du prestataire. Les diagnostics Bpifrance sont un canal d'apport d'affaires et de crédibilité pour un expert agréé, pas un circuit de facturation pour une société. [27] **Île-de-France** : PM'up pour le conseil, Innov'up pour le développement IA, sans référencement publié ; [28][29] aucune aide régionale trouvée pour la formation. [30]

---

## 3. Qui peut être le client ? (conditions publiées)

| Dispositif | Conditions du client | Source |
|---|---|---|
| Subvention Innovation / Bourse French Tech | « PME au sens de la Définition Européenne ». [31][32] Projet d'innovation avec « risques technologiques élevés » [33] | (voir table) |
| Diag Data IA | PME ou ETI de 10 à 2 000 ETP, au moins 1 000 000 € de chiffre d'affaires, plus d'un an d'existence [34][35][36] | (voir table) |
| Mission « Choix de l'approche IA » | PME avec au moins 250 k€ de CA, 3 ans d'existence, 10 salariés ; ou ETI de moins de 2 000 salariés [37][38][39][40] | (voir table) |
| Missions Systèmes d'information, Transformation digitale, Cybersécurité | Au moins 5 M€ de CA et 10 salariés, 3 ans d'existence (PME indépendante) ou ETI (la source écrit « au minimum ») [41][42][43][44][45][46] | (voir table) |
| Accélérateur IA | PME ou ETI de plus de 8 M€ de CA, plus de 50 salariés, 3 ans d'existence [47][48][49] | (voir table) |
| PM'up (Île-de-France) | PME de 5 salariés ou plus [50] | (voir table) |
| Innov'up (Île-de-France) | TPE à ETI, hors entreprise individuelle [51][52] | (voir table) |
| TP'up (Île-de-France) | TPE de 1 à 9 salariés [53] | (voir table) |
| Aides régionales de conseil | Souvent PME de la région, parfois secteur limité (ex. Grand Est : production, logistique, BTP) [54] | (voir table) |

**[DÉDUIT]** : les très petites entreprises sont exclues de la plupart des offres Bpifrance de conseil. [55] Pour elles, les aides régionales sont la voie réaliste (en Île-de-France, TP'up cite le conseil, mais son taux n'est pas publié [56][57]).

---

## 4. La règle d'or du calendrier

**[ÉCRIT]** sur les pages de la Subvention Innovation, de sa version Créative, de la Bourse French Tech et de la Bourse French Tech Émergence : « **Aucune dépense engagée antérieurement à la date de dépôt de la demande d'aide ne peut être retenue.** » [58][59][60][61] (voir table).

**[ÉCRIT]** côté régional : dépôt « avant le démarrage du projet » (Normandie) [62], « avant engagement des dépenses » (Pays de la Loire) [63]. Grand Est : la page indique que la **signature du devis est postérieure au dépôt** [64][65] (la formule « devis non signé » est un résumé de la note, à citer avec prudence). **Île-de-France, PM'up** : dossier avant démarrage, et un **devis signé avant le dépôt rend la dépense inéligible** [66][67] (règlement d'intervention CP2026-303 du 10/11/2026) [68]. **Île-de-France, Innov'up** : toute dépense avant le dépôt rend le projet inéligible [69] (règlement de 2021, validité à vérifier) [70]. Voir (voir table).

### Séquence recommandée **[RECOMMANDATION]** [71]
1. **Cadrer le besoin** avec le client (gratuitement ou en phase de proposition non engageante).
2. **Établir un devis non signé**, daté, avec durée de validité, en vue du dépôt.
3. Le **client dépose sa demande** d'aide (c'est lui le demandeur) et joint le devis non signé.
4. **Ne rien signer, ne rien démarrer, ne rien facturer** tant que la règle du dispositif n'est pas confirmée par écrit. Par défaut, attendre **l'accord écrit** du financeur.
5. Une fois l'accord reçu : signature du devis, démarrage, facturation selon l'échéancier.

> **Pourquoi attendre l'accord et pas seulement le dépôt ?** Pour la Subvention Innovation, la règle écrite protège les dépenses **postérieures au dépôt**. [58] Cela peut laisser entendre qu'on peut démarrer après le dépôt, **mais l'aide n'est pas garantie** : si elle est refusée, le client supporte seul la dépense. [72] Ce risque doit être dit au client. Certaines régions fixent aussi des règles plus strictes (Hauts-de-France : mission « après arrêté »). [73]
> **[NON PUBLIÉ]** (question 4, **à confirmer**) : ce que Bpifrance considère comme « dépense engagée » (devis signé ? acompte versé ? premier jour de travail ?). [74] **Question à poser avant le premier devis.**

---

## 5. Anatomie d'un devis finançable

### Principes
- **Un devis par lot, pas un forfait opaque.** Les financeurs vérifient des dépenses « acquittées » sur état récapitulatif [75] ((voir table)).
- **Décrire des livrables et des résultats, pas un outil.** Pour un dossier d'innovation, ce qui compte est le verrou technologique et le livrable, pas la marque du logiciel.
- **Séparer les prestations de nature différente** : cadrage / conseil, développement, formation, accompagnement. Elles n'ont pas le même financeur ni la même TVA. [76][77]
- **Afficher le tarif journalier.** Certaines aides plafonnent l'assiette par jour (Normandie : 50 % maximum, sur une base de **1 000 € HT par jour de consultance**) [78][79] : un tarif journalier supérieur n'augmente pas l'aide [80]. Voir (voir table).
- **Prix de marché, jours réellement nécessaires.** Les financeurs contrôlent les dépenses acquittées. [75] Un devis gonflé pour « consommer l'enveloppe » expose le client et le prestataire.
- **HT pour la plupart des aides lues, mais pas toutes.** **PL2I (Pays de la Loire) se calcule sur le TTC** (« 70 % du coût TTC de la prestation » [81] ; (voir table), relu en ligne par l'audit). Dans ce cas la TVA entre dans l'assiette, donc le statut TVA du prestataire compte. Vérifier la base (HT ou TTC) du dispositif visé.
- **Île-de-France, PM'up** : la mission de conseil doit être **ponctuelle, avec un livrable, d'au plus 12 mois, sans rémunération variable**, par un tiers indépendant sans lien d'intérêt avec le client [82][83][84][85] ((voir table)). Une rémunération au succès est donc à proscrire pour ce dispositif. [86]

### Modèle de structure **[RECOMMANDATION]** [87]

```
DEVIS n° ___ — [client] — [date] — valable ___ mois
Établi en vue d'une demande d'aide déposée par le client. Il ne vaut pas
engagement avant [accord écrit du financeur / date convenue].

CONTEXTE ET OBJECTIF (3 à 5 lignes, en termes de résultat attendu)

LOT 1 — Cadrage / diagnostic            (livrables : ___)   __ j × ___ € HT = ___ € HT
LOT 2 — Développement / mise en œuvre   (livrables : ___)   __ j × ___ € HT = ___ € HT
LOT 3 — Formation (action de formation) (programme annexé)   __ h / __ j × ___ = ___ € HT
LOT 4 — Suivi / transfert de compétences (livrables : ___)  __ j × ___ € HT = ___ € HT

Sous-traitance éventuelle : lot(s) concerné(s), nature, part du total.
Total HT / TVA / Total TTC
Échéancier de paiement : voir section 8.
Mentions : n° SIRET, n° de déclaration d'activité sur le lot formation. [88]
Clause : l'obtention de l'aide n'est pas garantie ; le client reste redevable du prix.
```

### Ce que le dossier du client demande souvent sur le prestataire
**[ÉCRIT]** (Normandie) : le dossier « devra notamment détailler la proposition du prestataire conseil comportant : les objectifs de sa mission, sa méthodologie, les livrables, les ressources mises à disposition (CV & références), planning ». [89] Prévoir donc, pour chaque devis :
- une **note de mission** (objectif, méthode, livrables, planning) ;
- les **CV et références** des intervenants ;
- le détail des jours par personne.

Pour un prestataire récemment créé, **les références personnelles des intervenants** et les missions précédentes comptent ici. [90] À préparer.

---

## 6. Sous-traitance : recours à des intervenants indépendants

### La chaîne
Client (bénéficiaire) → **prestataire** (facture le client) → **intervenants indépendants** (facturent le prestataire). Trois statuts d'indépendants courants : micro-entreprise, société, portage.

### Ce qui est établi
| Sujet | Ce que disent les pages | Statut |
|---|---|---|
| Sous-traitance de R&D dans une subvention innovation | Dépenses « externes » éligibles ; **sous-traitance de second rang non traitée** [11][91] | **[NON PUBLIÉ]** |
| Innov'up (Île-de-France) | Prestations externes et recherche sous-traitée citées ; règle sur le second rang non lue [92][93] | **[ÉCRIT]** (principe) / **[NON PUBLIÉ]** (second rang) |
| Diagnostics Bpifrance (Diag Data IA…) | L'agrément est individuel, « chaque candidat d'un même bureau d'études ou cabinet de conseil doit postuler pour chaque offre », le consultant réalise le Diag « de bout en bout » [94][95] | **[ÉCRIT]** |
| Formation CPF | Sous-traitant certifié Qualiopi, sauf micro-entrepreneur sous **77 700 € HT** de CA ; le sous-traitant ne sous-traite pas lui-même (« cascade ») [96][97][98] | **[ÉCRIT]** (CPF seulement) |
| Formation, NDA et sous-traitant | Code du travail L6351-1 : celui qui **réalise** l'action déclare son activité. Règle précise pour un sous-traitant non lue [99][100] | **[ÉCRIT]** (principe) / **[NON PUBLIÉ]** (détail) |
| Formation hors CPF | Règle non lue [101] | **[NON PUBLIÉ]** |

Sources : (voir table).

### Pièces à collecter auprès de chaque sous-traitant **[RECOMMANDATION]**
- Contrat de sous-traitance **écrit**, daté **avant** la prestation. [102]
- SIRET et justificatif d'existence (Kbis, avis de situation).
- **À vérifier avec un expert-comptable : attestation de vigilance URSSAF** (obligation du donneur d'ordre au-delà d'un certain montant ; seuil et conditions non vérifiés dans le coffre) [103].
- Pour un indépendant en portage : la société de portage facture, pas l'individu. Prévoir le circuit.
- Traçabilité des paiements (virements identifiables), car l'aide se règle sur dépenses **acquittées**.

### Point bloquant à clarifier avant de promettre
**Un client peut-il inclure dans sa demande une prestation que le prestataire sous-traite à un indépendant ?** Non publié. Question n° 1 pour Bpifrance [91] (voir section 12), **à confirmer** : aucune réponse reçue.

---

## Affirmations et sources
| N° | Affirmation | Étiquette | Extrait | URL | Note |
|---|---|---|---|---|---|
| 1 | L'aide va au client (le bénéficiaire), pas au prestataire, dans presque tous les dispositifs | [DÉDUIT] | — | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 2 | Innov'up : taux de 25 % à 70 % | [ÉCRIT] | « compris entre 25% et 70% » | https://www.iledefrance.fr/aides-et-appels-a-projets/innovup | idf-innovup |
| 3 | Subvention Innovation : taux jusqu'à 50 %, jusqu'à 70 % selon catégorie | [ÉCRIT] | « Cette aide peut couvrir jusqu'à 50 % des dépenses éligibles et selon la catégorie de l'entreprise, jusqu'à 70 %. » | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 4 | Reste à charge 6 000 € HT après subvention de 40 % | [ÉCRIT] | « est de 6 000€ HT après subvention de 40% » | https://www.bpifrance.fr/catalogue-offres/diag-data-ia | diag-data-ia |
| 5 | Pack IA : experts choisis par les pilotes du programme | [ÉCRIT] | « les pilotes (Hub France IA, IMT-Teralab) ont sélectionné le réseau d'experts » (lecture reformulée) | https://www.packia.fr | idf-pack-ia |
| 6 | Pack IA : 50 % Région, coût maximum pour l'entreprise 18 500 € | [ÉCRIT] | « Région : 50 % ; coût maximum pour l'entreprise 18 500 € » (lecture reformulée) | https://www.packia.fr | idf-pack-ia |
| 7 | Circuit B : le prestataire ne facture pas le client | [DÉDUIT] | — | aucune | —|
| 8 | Agrément délivré exclusivement à des personnes, pas à des cabinets | [ÉCRIT] | « exclusivement pour des personnes » | https://taleez.com/apply/expert-diag-data-ia-bpifrance-diagnostics | taleez-expert-diag-data-ia |
| 9 | Paiement sur fonds propres : la certification Qualiopi n'est pas exigée (FAQ OPCO EP) | [ÉCRIT] | « en fonds propres uniquement, la certification n'est pas exigée » (lecture reformulée) | https://www.opcoep.fr/question-formation/anticiper-les-evolutions-et-les-transitions-former-et-developper-les-competences-de-mes-salaries/connaitre-les-modalites-de-formation-et-gerer-les-inscriptions-en-formation/l-0 | s02-paiement-direct-sans-qualiopi |
| 10 | Ne pas écrire « finançable OPCO/CPF/FNE » dans les devis | [RECOMMANDATION] | — | https://www.opco-atlas.fr/entreprise/plan-dev-competences.html | opco-prise-en-charge |
| 11 | Subvention Innovation finance les dépenses de R&D internes et externes | [ÉCRIT] | « financer en partie, les dépenses de R&D internes et externes liées à votre projet d'innovation » | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 12 | Liste des dépenses externes éligibles, plafond de sous-traitance, contenu de « sous condition » | [NON PUBLIÉ] | — | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 13 | PM'up : dév IA possible en investissement immatériel, à confirmer | [DÉDUIT] | — | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 14 | Développement IA : hors cadre R&D, non publié | [NON PUBLIÉ] | — | aucune | GUIDE_DEVIS_BPI |
| 15 | Aides régionales de conseil à libre choix : l'absence d'exigence de référencement est déduite des pages | [DÉDUIT] | — | https://adnormandie.fr/wp-content/uploads/2025/11/REGLEMENT-IMP-CONSEIL.pdf | normandie |
| 16 | Grand Est : sélection d'un prestataire référencé par la Région | [ÉCRIT] | « Sélectionnez un prestataire référencé » | https://www.grandest.fr/vos-aides-regionales/module-numerique-data-ia/ | grand-est |
| 17 | Grand Est : seul le recours aux prestataires référencés permet l'aide | [ÉCRIT] | « Seul le recours aux prestataires référencés permet à l'entreprise de bénéficier de l'aide régionale. » | https://www.grandest.fr/vos-aides-regionales/module-numerique-data-ia/ | grand-est |
| 18 | Hauts-de-France BTR3 : choix à partir d'une liste de consultants référencés | [ÉCRIT] | « à partir d'une liste de consultants référencés » | https://guide-aides.hautsdefrance.fr/dispositif1045 | hauts-de-france |
| 19 | Grand Est : procédure « fast track » écrite dans le règlement PDF de juillet 2025, absente de la page web | [ÉCRIT] | « Les modalités et conditions de référencement seront strictement identiques à celles des opérateurs » | https://www.grandest.fr/wp-content/uploads/2025/07/reglement-module-numerique-data-ia.pdf | grand-est |
| 20 | Pas d'agrément pour des cabinets, exclusivement pour des personnes | [ÉCRIT] | « Bpifrance ne délivre pas d'agrément pour des cabinets de conseil ou bureau d'études mais exclusivement pour des personnes. » | https://taleez.com/apply/expert-diag-data-ia-bpifrance-diagnostics | taleez-expert-diag-data-ia |
| 21 | CPF : NDA actif et Qualiopi pour le type d'action | [ÉCRIT] | « Être certifié Qualiopi pour le type d'action » | https://of.moncompteformation.gouv.fr/espace-public/aide/comment-etre-reference-sur-mon-compte-formation | cpf-organisme |
| 22 | Paiement direct sans Qualiopi : aucune page DREETS sur le sujet | [NON PUBLIÉ] | — | https://normandie.dreets.gouv.fr/La-certification-qualite-des-OF-QUALIOPI | s02-paiement-direct-sans-qualiopi |
| 23 | Qualiopi exigé pour accéder aux fonds publics ou mutualisés (DREETS) | [ÉCRIT] | « Qualiopi requis pour accéder aux fonds publics ou mutualisés » (lecture reformulée) | https://normandie.dreets.gouv.fr/La-certification-qualite-des-OF-QUALIOPI | s02-paiement-direct-sans-qualiopi |
| 24 | FNE-Formation : plus possible de déposer des demandes au titre de l'édition 2024 | [ÉCRIT] | « Il n'est plus possible de déposer des demandes de prise en charge au titre du FNE-Formation 2024 » (lecture reformulée) | https://www.akto.fr/fne-formation-tout-savoir-dispositif-specificites-region/ | s02-fne-formation-2026 |
| 25 | FNE-Formation 2026 : aucune source officielle ne confirme une ouverture | [NON PUBLIÉ] | — | https://www.akto.fr/fne-formation-tout-savoir-dispositif-specificites-region/ | s02-fne-formation-2026 |
| 26 | Valeur d'un prestataire : développement IA dans un projet d'innovation et conseil à libre choix | [DÉDUIT] | — | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 27 | Conseil vendable seulement via habilitation ou agrément individuel | [DÉDUIT] | — | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-choix-de-lapproche-ia | mission-de-conseil-choix-de-lapproche-ia |
| 28 | Dév IA : Innov'up si projet RDI, PM'up à confirmer | [DÉDUIT] | — | https://www.iledefrance.fr/aides-et-appels-a-projets/innovup | idf-innovup |
| 29 | PM'up : prestataire référencé/qualifié non publié | [NON PUBLIÉ] | — | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 30 | Formation : aucune aide régionale de formation continue des salariés repérée | [NON PUBLIÉ] | — | https://www.iledefrance.fr/aides-et-appels-a-projets | idf-autres-aides |
| 31 | Subvention Innovation : profil PME au sens de la définition européenne | [ÉCRIT] | « PME au sens de la Définition Européenne, » | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 32 | Bourse French Tech : profil PME au sens de la définition européenne | [ÉCRIT] | « PME au sens de la Définition Européenne, » | https://www.bpifrance.fr/catalogue-offres/bourse-french-tech | bourse-french-tech |
| 33 | Subvention Innovation : projet à risques technologiques élevés | [ÉCRIT] | « Vous souhaitez amorcer un projet d'innovation technologique ou Nouvelle Génération avec des risques technologiques élevés » | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 34 | PME ou ETI de 10 à 2 000 ETP indépendante | [ÉCRIT] | « PME ou ETI de 10 à 2 000 ETP indépendante » | https://www.bpifrance.fr/catalogue-offres/diag-data-ia | diag-data-ia |
| 35 | Chiffre d'affaires d'au moins 1 000 000 € sur 12 mois | [ÉCRIT] | « Réalisant au minimum 1 000 000€ de chiffre d'affaires sur un bilan de 12 mois » | https://www.bpifrance.fr/catalogue-offres/diag-data-ia | diag-data-ia |
| 36 | Ancienneté de plus d'un an | [ÉCRIT] | « Ayant plus de 1 an d'existence » | https://www.bpifrance.fr/catalogue-offres/diag-data-ia | diag-data-ia |
| 37 | Choix de l'approche IA : CA minimal | [ÉCRIT] | « Réalisant au minimum 250k€ de chiffre d’affaires sur un bilan de 12 mois » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-choix-de-lapproche-ia | mission-de-conseil-choix-de-lapproche-ia |
| 38 | Choix de l'approche IA : ancienneté minimale 3 ans | [ÉCRIT] | « Ayant minimum 3 ans d’existence » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-choix-de-lapproche-ia | mission-de-conseil-choix-de-lapproche-ia |
| 39 | Choix de l'approche IA : au moins 10 salariés | [ÉCRIT] | « Employant au minimum 10 salariés » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-choix-de-lapproche-ia | mission-de-conseil-choix-de-lapproche-ia |
| 40 | Choix de l'approche IA : ETI indépendante de moins de 2 000 salariés | [ÉCRIT] | « ETI indépendante de moins de 2000 salariés » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-choix-de-lapproche-ia | mission-de-conseil-choix-de-lapproche-ia |
| 41 | Systèmes d'information : CA minimal | [ÉCRIT] | « Réalisant au minimum 5 M€ de chiffre d’affaires sur un bilan de 12 mois » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-systemes-dinformation | mission-de-conseil-systemes-dinformation |
| 42 | Systèmes d'information : ancienneté minimale 3 ans | [ÉCRIT] | « Ayant minimum 3 ans d’existence » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-systemes-dinformation | mission-de-conseil-systemes-dinformation |
| 43 | Systèmes d'information : au moins 10 salariés | [ÉCRIT] | « Employant au minimum 10 salariés » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-systemes-dinformation | mission-de-conseil-systemes-dinformation |
| 44 | Systèmes d'information : ETI indépendante | [ÉCRIT] | « ETI indépendante » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-systemes-dinformation | mission-de-conseil-systemes-dinformation |
| 45 | Transformation digitale : CA minimal | [ÉCRIT] | « Réalisant au minimum 5 M€ de chiffre d’affaires sur un bilan de 12 mois » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-transformation-digitale | mission-de-conseil-transformation-digitale |
| 46 | Mission Cybersécurité : CA minimal | [ÉCRIT] | « Réalisant au minimum 5 M€ de chiffre d’affaires sur un bilan de 12 mois » | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-cybersecurite | mission-de-conseil-cybersecurite |
| 47 | Accélérateur IA : CA supérieur à 8 M€ | [ÉCRIT] | « Réalisant un chiffre d'affaires supérieur à 8M€ » | https://www.bpifrance.fr/catalogue-offres/accelerateur-ia | accelerateur-ia |
| 48 | Accélérateur IA : plus de 50 collaborateurs | [ÉCRIT] | « Plus de 50 collaborateurs » | https://www.bpifrance.fr/catalogue-offres/accelerateur-ia | accelerateur-ia |
| 49 | Accélérateur IA : au moins 3 ans d'existence | [ÉCRIT] | « Au moins 3 ans d'existence » | https://www.bpifrance.fr/catalogue-offres/accelerateur-ia | accelerateur-ia |
| 50 | PM'up : PME d'au moins 5 salariés avec un établissement en IDF | [ÉCRIT] | « comptant au moins 5 salariés et ayant au moins un établissement en Île-de-France » | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 51 | Innov'up : entreprises de moins de 5000 salariés, quelle que soit la forme juridique | [ÉCRIT] | « les entreprises, quelle que soit leur forme juridique (y compris les associations ayant une activité économique), de moins de 5000 salariés » | https://www.iledefrance.fr/aides-et-appels-a-projets/innovup | idf-innovup |
| 52 | Innov'up : entreprises individuelles non éligibles | [ÉCRIT] | « Les entreprises individuelles ne sont pas éligibles. » (lecture reformulée) | https://www.iledefrance.fr/aides-et-appels-a-projets/innovup | idf-innovup |
| 53 | TP'up : TPE de 1 à moins de 10 salariés | [ÉCRIT] | « Employant de 1 à moins de 10 salariés » (lecture reformulée) | https://www.iledefrance.fr/aides-et-appels-a-projets/tpup | idf-autres-aides |
| 54 | Grand Est : activité de production, de logistique ou BTP | [ÉCRIT] | « activité de production, de logistique ou appartenant au secteur du BTP » | https://www.grandest.fr/vos-aides-regionales/module-numerique-data-ia/ | grand-est |
| 55 | Les très petites entreprises sont exclues de la plupart des offres Bpifrance de conseil | [DÉDUIT] | — | https://www.bpifrance.fr/catalogue-offres/mission-de-conseil-choix-de-lapproche-ia | mission-de-conseil-choix-de-lapproche-ia |
| 56 | TP'up cite les prestations de conseil parmi les dépenses | [ÉCRIT] | « Prestations de conseil » (lecture reformulée) | https://www.iledefrance.fr/aides-et-appels-a-projets | idf-autres-aides |
| 57 | TP'up : taux non publié | [NON PUBLIÉ] | — | https://www.iledefrance.fr/aides-et-appels-a-projets/tpup | idf-autres-aides |
| 58 | Aucune dépense engagée avant le dépôt (Subvention Innovation) | [ÉCRIT] | « Attention : Aucune dépense engagée antérieurement à la date de dépôt de la demande d'aide ne peut être retenue. » | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 59 | Aucune dépense engagée avant le dépôt (Bourse French Tech) | [ÉCRIT] | « Attention : Aucune dépense engagée antérieurement à la date de dépôt de la demande d'aide ne peut être retenue. » | https://www.bpifrance.fr/catalogue-offres/bourse-french-tech | bourse-french-tech |
| 60 | Aucune dépense engagée avant le dépôt (Innovation Créative) | [ÉCRIT] | « Attention : Aucune dépense engagée antérieurement à la date de dépôt de la demande d'aide ne peut être retenue. » | https://www.bpifrance.fr/catalogue-offres/subvention-innovation-innovation-creative | subvention-innovation-innovation-creative |
| 61 | Aucune dépense engagée avant le dépôt (Émergence) | [ÉCRIT] | « Attention : Aucune dépense engagée antérieurement à la date de dépôt de la demande d'aide ne peut être retenue. » | https://www.bpifrance.fr/catalogue-offres/bourse-french-tech-emergence | bourse-french-tech-emergence |
| 62 | Normandie : dépôt avant le démarrage du projet | [ÉCRIT] | « en tout état de cause avant le démarrage du projet » | https://adnormandie.fr/reglement-des-aides/ | normandie |
| 63 | Pays de la Loire Conseil : dépôt avant l'engagement des dépenses | [ÉCRIT] | « avant l'engagement des dépenses » | https://www.paysdelaloire.fr/conseil | pays-de-la-loire |
| 64 | Grand Est : demande avec devis non signé d'un prestataire référencé | [ÉCRIT] | « La demande doit comprendre le devis non signé établi par l'un des prestataires référencés par la Région Grand Est. » | https://www.grandest.fr/wp-content/uploads/2025/07/reglement-module-numerique-data-ia.pdf | grand-est |
| 65 | Grand Est : demande avant le démarrage de la prestation | [ÉCRIT] | « avant le démarrage de la prestation » | https://www.grandest.fr/vos-aides-regionales/module-numerique-data-ia/ | grand-est |
| 66 | PM'up : dossier déposé avant le démarrage du projet | [ÉCRIT] | « Le dossier de candidature doit être déposé avant le démarrage du projet. » | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 67 | PM'up : devis signé avant dépôt = inéligible | [ÉCRIT] | « Les dépenses ne doivent pas avoir été engagées avant le dépôt de la candidature (ex. devis signé, acompte sur commande, réservation de salon,…) » | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 68 | PM'up : règlement d'intervention CP2026-303 du 10/11/2026 | [ÉCRIT] | « règlement d'intervention (CP2026-303 du 10/11/2026) » | https://mesdemarches.iledefrance.fr/document-collect/cridfprd/root/public?objectId=ef42f5d6-4bae-48df-9df8-c3c2b44f13ba | idf-pmup |
| 69 | Innov'up : toute dépense avant dépôt rend le projet inéligible | [ÉCRIT] | « Toute dépense réalisée avant le dépôt de la demande d'aide rend le projet inéligible au présent dispositif. » | https://www.iledefrance.fr/aides-et-appels-a-projets/innovup | idf-innovup |
| 70 | Innov'up : règlement lu datant de septembre 2021, validité à confirmer | [ÉCRIT] | « le règlement lu est celui de septembre 2021 » (lecture reformulée) | https://www.iledefrance.fr/aides-et-appels-a-projets/innovup | idf-innovup |
| 71 | Séquence et choix de prudence du guide (devis non signé, attendre l'accord écrit) | [RECOMMANDATION] | — | aucune | — |
| 72 | Si l'aide est refusée après démarrage, le client supporte seul la dépense | [DÉDUIT] | — | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 73 | HDF BTR3 : la mission peut commencer après réception de l'arrêté | [ÉCRIT] | « La mission peut commencer après réception de l'arrêté » | https://guide-aides.hautsdefrance.fr/dispositif1045 | hauts-de-france |
| 74 | Définition d'une « dépense engagée » non publiée | [NON PUBLIÉ] | — | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 75 | Solde de l'aide sur état récapitulatif des dépenses acquittées | [ÉCRIT] | « le solde à l'achèvement des travaux après fourniture à Bpifrance d'un rapport de fin de programme et un état récapitulatif des dépenses acquittées » | https://www.bpifrance.fr/catalogue-offres/bourse-french-tech | bourse-french-tech |
| 76 | TVA formation : exonération pour l'organisme titulaire d'une attestation | [ÉCRIT] | « titulaire d'une attestation délivrée par l'autorité administrative compétente » | https://entreprendre.service-public.gouv.fr/vosdroits/F32231 | tva-formation-professionnelle |
| 77 | Sans exonération, les autres prestations sont soumises à la TVA à 20 % | [ÉCRIT] | « Les autres prestations sont soumises à la TVA à 20 % » | https://entreprendre.service-public.gouv.fr/vosdroits/F32231 | tva-formation-professionnelle |
| 78 | Normandie Impulsion Conseil : 50 % maximum du coût HT | [ÉCRIT] | « fixé à 50% maximum du coût HT des dépenses éligibles » | https://adnormandie.fr/wp-content/uploads/2025/11/REGLEMENT-IMP-CONSEIL.pdf | normandie |
| 79 | Normandie : base de 1 000 € HT maximum par jour de consultance | [ÉCRIT] | « sur la base de 1 000 € HT maximum/jour de consultance » | https://adnormandie.fr/wp-content/uploads/2025/11/REGLEMENT-IMP-CONSEIL.pdf | normandie |
| 80 | Un tarif journalier supérieur à la base Normandie n'augmente pas l'aide (assiette plafonnée à 1 000 € HT/jour) | [DÉDUIT] | « Le client doit rester sous le plafond de 1 000 € HT/jour pour l'assiette. » | https://adnormandie.fr/wp-content/uploads/2025/11/REGLEMENT-IMP-CONSEIL.pdf | normandie |
| 81 | PL2I : 70 % du coût TTC de la prestation | [ÉCRIT] | « La subvention PL2I représente 70 % du coût TTC de la prestation » | https://www.paysdelaloire.fr/les-aides/pays-de-la-loire-initiative-innovation-pl2i | pays-de-la-loire |
| 82 | PM'up : le conseil donne lieu à un livrable | [ÉCRIT] | « Ils donnent lieu à la réalisation d'un livrable » | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 83 | PM'up : mission de conseil de 12 mois maximum | [ÉCRIT] | « mission de 12 mois maximum » | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 84 | PM'up : pas de rémunération variable | [ÉCRIT] | « pas de rémunération variable » | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 85 | PM'up : dépenses auprès d'un tiers aux conditions du marché, sans contrôle de l'acquéreur sur le vendeur | [ÉCRIT] | « sans que l'acquéreur soit en position d'exercer un contrôle sur le vendeur, ou vice-versa » | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 86 | PM'up : une rémunération au succès est à proscrire | [DÉDUIT] | — | https://www.iledefrance.fr/aides-et-appels-a-projets/pmup | idf-pmup |
| 87 | Modèle de structure de devis du guide | [RECOMMANDATION] | — | aucune | — |
| 88 | Le prestataire doit disposer d'un numéro de déclaration d'activité (NDA) | [ÉCRIT] | « le prestataire de formation choisi doit disposer d'un numéro de déclaration d'activité » (lecture reformulée) | https://www.opcoep.fr/question-formation/anticiper-les-evolutions-et-les-transitions-former-et-developper-les-competences-de-mes-salaries/connaitre-les-modalites-de-formation-et-gerer-les-inscriptions-en-formation/l-0 | s02-paiement-direct-sans-qualiopi |
| 89 | Normandie : le dossier détaille objectifs, méthode, livrables, CV et références, planning | [ÉCRIT] | « les objectifs de sa mission, sa méthodologie, les livrables, les ressources mises à disposition (CV & références), planning » | https://adnormandie.fr/wp-content/uploads/2025/11/REGLEMENT-IMP-CONSEIL.pdf | normandie |
| 90 | Les références des intervenants comptent pour une société de 2026 | [DÉDUIT] | — | aucune | GUIDE_DEVIS_BPI |
| 91 | Qui peut réaliser les dépenses externes (agrément, sous-traitance, indépendance) | [NON PUBLIÉ] | — | https://www.bpifrance.fr/catalogue-offres/subvention-innovation | subvention-innovation |
| 92 | Innov'up : prestations externes d'un projet RDI financées | [ÉCRIT] | « Les frais de personnel ou le coût de prestations externes liées à la réalisation du projet » | https://www.iledefrance.fr/aides-et-appels-a-projets/innovup | idf-innovup |
| 93 | Innov'up : règle sur la sous-traitance de second rang non lue | [NON PUBLIÉ] | — | https://www.iledefrance.fr/aides-et-appels-a-projets/innovup | idf-innovup |
| 94 | Agrément intuitu personae, chaque candidat postule pour chaque offre | [ÉCRIT] | « chaque candidat d’un même bureau d’études ou cabinet de conseil doit postuler pour chaque offre » | https://www.bpifrance.fr/devenez-expert-agree-sur-les-diagnostics-bpifrance | devenez-expert-agree-diagnostics |
| 95 | Le consultant réalise le Diag de bout en bout | [ÉCRIT] | « Il est de la responsabilité du consultant de réaliser le Diag de bout en bout » | https://taleez.com/apply/expert-diag-data-ia-bpifrance-diagnostics | taleez-expert-diag-data-ia |
| 96 | Sous-traitance CPF : sous-traitant certifié Qualiopi (sauf exception) | [ÉCRIT] | « Être certifié Qualiopi (sauf exception) » | https://of.moncompteformation.gouv.fr/espace-public/aide/quelles-sont-les-regles-du-recours-la-sous-traitance | sous-traitance-formation |
| 97 | Exception micro-social : chiffre d'affaires annuel inférieur à 77 700 € HT | [ÉCRIT] | « un chiffre d'affaires annuel inférieur à 77 700 € (hors taxes) » | https://of.moncompteformation.gouv.fr/espace-public/aide/quelles-sont-les-regles-du-recours-la-sous-traitance | sous-traitance-formation |
| 98 | Pas de sous-traitance en cascade | [ÉCRIT] | « pas de sous-traitance en cascade » | https://of.moncompteformation.gouv.fr/espace-public/aide/quelles-sont-les-regles-du-recours-la-sous-traitance | sous-traitance-formation |
| 99 | L6351-1 : celui qui réalise l'action déclare son activité | [ÉCRIT] | « Toute personne qui réalise des actions prévues à l'article L. 6313-1 » (lecture reformulée) | https://code.travail.gouv.fr/code-du-travail/l6351-1 | s02-nda-sous-traitance-formation |
| 100 | NDA : règle précise pour un sous-traitant non lue | [NON PUBLIÉ] | — | https://code.travail.gouv.fr/code-du-travail/l6351-1 | s02-nda-sous-traitance-formation |
| 101 | Hors CPF, aucune règle de sous-traitance lue | [NON PUBLIÉ] | — | https://of.moncompteformation.gouv.fr/espace-public/aide/quelles-sont-les-regles-du-recours-la-sous-traitance | sous-traitance-formation |
| 102 | Pièces à collecter auprès des sous-traitants (contrat écrit, SIRET, portage, traçabilité des paiements) | [RECOMMANDATION] | — | aucune | — |
| 103 | Attestation de vigilance URSSAF : seuil et conditions non vérifiés | [NON VÉRIFIÉ] | — | aucune | — |

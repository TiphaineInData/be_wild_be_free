---
title: Wild Data Hub
description: ' '
layout: default
---

## Introduction et Contexte

![header](header.jpg)
{: .text-center}

Bienvenue dans **Wild Data Hub** : une vraie aventure dans le monde de la donnée ! Pendant les prochaines semaines, vous allez construire **de A à Z votre propre application d'analyse de données**, de la collecte jusqu'à la restitution devant un public.

Le plus cool ? **C'est vous qui choisissez votre sujet et vos sources de données.** Que vous soyez branché·e business, industrie, finance, sport, environnement, médias sociaux, musique, cinéma, jeux vidéo… ou tout autre domaine qui vous passionne, vous orienterez le projet dans cette direction.

L'idée est simple : **vous êtes libres sur le QUOI, on vous guide sur le COMMENT.** Tout le monde suivra le même fil rouge — collecter, transformer, stocker, analyser, modéliser, visualiser, restituer — pour pouvoir avancer ensemble et s'entraider. Vous êtes des **Data Analysts** maintenant : vous savez de quoi on parle. 🚀

> **À retenir dès le départ :** ce projet est aussi votre support de **certification (RNCP38616, option Data Analyse)**. La gestion de projet et le Machine Learning n'y sont pas des options : ils sont **au cœur** de ce que le jury évaluera.

## Objectifs Pédagogiques

- Collecter des données à partir de **sources variées** (APIs REST, web scraping, fichiers, Open Data).
- Nettoyer, explorer et préparer les données avec **Python (pandas)**.
- Concevoir un **pipeline de transformation moderne (ELT) avec dbt** et le **fiabiliser** (tests, modèles incrémentaux).
- Stocker et **modéliser les données dans BigQuery** pour l'analyse (schéma en étoile / OLAP).
- Construire des **tableaux de bord décisionnels accessibles** (Power BI ou Looker Studio).
- Entraîner et évaluer un **modèle de Machine Learning** (scikit-learn).
- Exposer le tout dans une **application Streamlit**.
- Mener le projet en **méthodologie Agile**, en intégrant **veille, éthique, RGPD, AI Act, impacts environnementaux et sociétaux**.

## Organisation

Le projet se déroule sur **7 semaines actives**, suivies de **2 semaines de préparation à la certification**, en mode **itératif et collaboratif (Agile)**.

- **Groupes de 3 à 4.**
- **Sujet libre**, choisi par le groupe. Deux pistes vous sont proposées plus bas **si vous n'avez vraiment aucune idée** — mais ce ne sont que des idées d'API : à vous de creuser et de définir votre angle.
- **Outils de suivi** : un espace **Notion ou Trello d'équipe** (backlog, kanban, cahier des charges, registre des risques, planning) **+ une page perso par membre** (votre code, votre dashboard, votre ML, votre journal de décisions).

![architecture](assets/image/architecture.svg)
{: .text-center}

## Travailler en équipe : collectif ET individuel

C'est la règle d'or du projet, alors lisez-la deux fois :

- **En amont, c'est collectif.** L'équipe construit **ensemble l'infrastructure partagée** : collecte, pipeline, base de données.
- **En aval, c'est individuel.** À partir de la base commune, **chaque membre tient sa propre « tranche verticale »** : ses requêtes et son analyse exploratoire, **son dashboard BI**, **son modèle de ML** (vous pouvez même choisir des ML différents !), **sa page Streamlit**.

Pourquoi ? Parce que la certification **évalue chacun·e individuellement**. On ne laisse donc pas la personne la plus à l'aise tout faire : chacun·e doit pouvoir présenter et défendre sa partie devant le jury.

## Déroulé semaine par semaine

Vous avez **7 semaines de production** (S13 → S19), puis **2 semaines de préparation à la certification** (S20-S21). Voici ce que vous devez produire chaque semaine — côté projet et côté gestion de projet.

| Semaine | Sur le projet (ce que vous produisez) | Gestion de projet |
|---|---|---|
| **S13** · 3-7 août | Choix du sujet ; cadrage : problématique, objectifs et premiers KPIs, sources candidates | Constitution de l'équipe, kanban, premier backlog |
| 10-14 août | — *(fermé)* | — |
| 17-21 août | — *(fermé)* | — |
| **S14** · 24-28 août | Sujet validé ; exploration des données (EDA) ; **script de collecte → données brutes envoyées dans BigQuery (raw)** | Ouverture du cahier des charges (sources, backlog) ; premiers risques (RGPD, biais du sujet) |
| **S15** · 31 août-4 sept | **Transformation dbt** (staging → marts) ; modèles incrémentaux (hash, partition / clustering) ; les **deux marts** (étoile pour la BI + table de features pour le ML) | Cahier des charges enrichi (archi, choix d'outils justifiés par la veille) ; backlog affiné |
| **S16** · 7-11 sept | Finalisation + **automatisation du pipeline** (GitHub Actions) ; démarrage du **dashboard BI** | Risques techniques / environnementaux / sociétaux + positionnement **AI Act** ; revue de mi-projet |
| **S17** · 14-18 sept | Nettoyage du code ; **dashboard BI** (un par personne), accessible | Pilotage (kanban, points d'étape) |
| **S18** · 21-25 sept | **Modèle de Machine Learning** (un par personne) + **application Streamlit** + hébergement du code | Pilotage |
| **S19** · 28 sept-2 oct | Prépa démo ; **documentation** (schéma OLAP) ; **soutenance** | Synthèse finale des risques (mitigation, audit) ; recommandations |
| **S20** · 5-9 oct | Revue des livrables, **soutenance blanche** | Bilan et ajustements |
| **S21** · 11-15 oct | Préparation finale à la certification | — |

> 💡 **L'« IA » de ce projet, c'est le Machine Learning, et il est obligatoire.** Il s'agit de **ML classique avec scikit-learn** (régression / classification / clustering). Les fonctionnalités à base de LLM (Gemini & co.) restent un **bonus facultatif**.

> 🧰 **Culture perso / bonus (non exigé)** : si votre groupe est à l'aise, vous pouvez explorer **Docker** (conteneurisation), **Prefect** (orchestration avancée) et l'**hébergement sur GCP**. À ne tenter qu'une fois le pipeline de base solide.

## Les cours en parallèle

Vous ne serez jamais lâché·es seul·es face à la technique : les cours arrivent **au fil de l'avancement** du projet — notamment GCP / BigQuery, la gestion de projet Agile, dbt, GitHub Actions, Power BI / Looker, Streamlit, le Machine Learning, ainsi qu'une étape **documentation** (avec le schéma OLAP de votre base). Docker et Prefect sont abordés en **culture perso**.

## Missions et Livrables Attendus

**Livrables collectifs (équipe)**

- Cahier des charges + backlog (Notion / Trello).
- Registre des risques (éthique, RGPD, environnement, société).
- Scripts de collecte + **pipeline ELT** (script Python → BigQuery + dbt) automatisé.
- Documentation technique + **schéma OLAP** (modèle en étoile) de la base.

**Livrables individuels (chaque membre)**

- Vos scripts de collecte / extraction.
- Votre analyse exploratoire (stats descriptives, valeurs anormales traitées).
- **Votre dashboard BI** (Power BI ou Looker, accessible WCAG).
- **Votre modèle de ML** (scikit-learn) + évaluation par métriques.
- **Votre application Streamlit** exposant le modèle.
- Votre page perso (journal de contributions et de décisions).
- Votre participation à la soutenance.

## Méthodologie & bonnes pratiques

- Avancez en **Agile** : backlog, user stories, kanban, points d'étape réguliers.
- **Documentez** au fur et à mesure (code, choix techniques, schéma de base).
- Pratiquez une **veille** : chaque choix d'outil doit s'appuyer sur une source crédible.
- Tenez un **registre des risques** vivant : biais, RGPD, **AI Act** (où se situe votre projet sur l'échelle de risque ?), impact environnemental (sobriété numérique) et sociétal.
- Utilisez **Git** (versioning, branches, pull requests) dès le début.
- Soignez l'**accessibilité** de vos rendus (couleur, taille de texte — critères WCAG).

## Pas d'idée de sujet ? Deux pistes (juste des idées d'API)

⚠️ **Ce ne sont que des points de départ.** Les APIs ci-dessous n'ont **pas été testées** : à vous de vérifier qu'elles fonctionnent, de définir votre problématique et de vous casser la tête sur l'angle. Vous restez libres de partir sur tout autre sujet.

**Piste A — WildSearchFood** *(analyse et recherche de restaurants)*
Idées de données : API Yelp (quota gratuit limité) + sources Open Data. Exemples d'analyses : notes moyennes, prix vs qualité, nuages de mots sur les avis, cartographie. ML possible : topic modeling sur les descriptions, analyse des avis.

**Piste B — WildFindJob** *(analyse du marché de l'emploi dans la data)*
Idées de données : APIs d'offres d'emploi + web scraping. Exemples d'analyses : tendances des offres, compétences les plus demandées, géographie de l'emploi. ML possible : recommandation d'offres, détection de tendances.

## Ressources

- [Liste non-exhaustive d'idées d'APIs](https://docs.google.com/document/d/1HZcOZ60cGACjA56UJY5l-vTVvXdguJNhL4woeXBPtJo/edit?usp=sharing)
- [dbt — documentation](https://docs.getdbt.com/)
- [Streamlit](https://www.youtube.com/@CodingIsFun/playlists)
- [scikit-learn — guide utilisateur](https://scikit-learn.org/stable/user_guide.html)

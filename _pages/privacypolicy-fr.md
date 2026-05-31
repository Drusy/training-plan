---
layout: post
title: Politique de confidentialité
permalink: /fr/privacy/
lang: fr
---

# {{ site.app_name }}
# Politique de confidentialité

## À propos

{{ site.app_name }} est une application iOS qui aide les athlètes à gérer leurs compétitions à venir et à générer des plans d'entraînement personnalisés grâce à l'IA. Elle prend en charge la course à pied, le cyclisme, la natation et le triathlon.

## Données utilisées

{{ site.app_name }} peut accéder aux données suivantes pour fournir ses fonctionnalités principales :

- Données de profil sportif (discipline, niveau, poids optionnel)
- Données de compétitions (dates, distances, objectifs)
- Données de plan d'entraînement et de séances (programme, suivi de complétion)
- Connexion optionnelle à Strava (uniquement si activée par l'utilisateur)
- Notifications locales optionnelles (uniquement si autorisées par l'utilisateur)

## Stockage des données

Toutes les données de compétitions, plans et profil sont stockées localement sur votre appareil.  
Nous n'exploitons pas de serveurs et ne collectons pas vos données personnelles.

Lorsque vous choisissez Claude (Anthropic) ou GPT-4o (OpenAI) pour générer un plan, votre profil et vos objectifs sont envoyés à l'API du fournisseur concerné. Cela est couvert par leurs politiques de confidentialité respectives :

- [Politique de confidentialité Anthropic](https://www.anthropic.com/privacy)
- [Politique de confidentialité OpenAI](https://openai.com/privacy)

Nous ne vendons pas de données personnelles.

## Autorisations

Selon les fonctionnalités activées, l'application peut demander :

- Autorisation de notifications (rappels quotidiens d'entraînement et alertes de séances)
- Accès Internet (pour la génération de plans IA et la synchronisation Strava optionnelle)

## Services tiers

**API Strava** (optionnelle, uniquement si l'utilisateur se connecte) :  
[https://developers.strava.com](https://developers.strava.com)

**API Claude d'Anthropic** (optionnelle, uniquement si sélectionnée par l'utilisateur) :  
[https://www.anthropic.com](https://www.anthropic.com)

**API OpenAI** (optionnelle, uniquement si sélectionnée par l'utilisateur) :  
[https://openai.com](https://openai.com)

**Firebase Crashlytics** (stabilité de l'application et diagnostic des crashs)

## Ressources

Cette application utilise des ressources UI système Apple (SF Symbols).  
Les assets de marques tierces (ex. : bouton Strava) sont utilisés selon leurs règles de marque.

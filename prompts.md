prompts.md

# Journal des Prompts — Projet Site Vitrine PulseArena

**Formation :** Master 2 STAPS — Management des Événements et des Loisirs Sportifs (Université Paris Nanterre)  
**Outil utilisé :** Gemini (LLM)  
**Cadre d'utilisation :** Assistant de conception par étapes (cadrage stratégique, architecture HTML5/CSS3, élaboration du questionnaire de conversion et vérification de cohérence).

---

## Étape 1 — Cadrage du projet et feuille de style globale (`style.css`)
* **Prompt / Demande :** Conception d'une identité visuelle sobre, dynamique et responsive en CSS3 pour PulseArena (organisation de tournois sportifs et team building en Île-de-France), avec variables de couleurs, grilles adaptatives et navigation cohérente.
* **Vérification & ajustements effectués :** Contrôle du contraste des couleurs, de la lisibilité sur écran ordinateur et smartphone, et ajustement du cadrage des images dans les cartes (`object-fit: cover` et classes `.photo-haut` / `.photo-bas`).

## Étape 2 — Structure de la page d'accueil (`index.html`)
* **Prompt / Demande :** Création de la page d'accueil présentant la proposition de valeur de PulseArena, ses 3 atouts principaux et des appels à l'action visibles vers les offres et le formulaire de devis.
* **Vérification & ajustements effectués :** Vérification de la hiérarchie sémantique (`<header>`, `<main>`, `<section>`, `<footer>`) et de la cohérence du menu de navigation.

## Étape 3 — Présentation des prestations et tarifs (`offres.html`)
* **Prompt / Demande :** Rédaction de la page des offres détaillant les 3 formules (Tournoi Entreprise & CSE, Olympiades Team Building, Pack Association & Loisir), un tableau comparatif des tarifs/délais, les horaires et la zone d'intervention en Île-de-France (Ouest parisien).
* **Vérification & ajustements effectués :** Adaptation des zones géographiques aux réalités locales (Suresnes, Nanterre, La Défense, Yvelines) et contrôle des boutons de conversion.

## Étape 4 — Crédibilité, retours clients et FAQ (`a-propos.html`)
* **Prompt / Demande :** Création de la page À propos intégrant la méthodologie d'organisation en 4 étapes, des témoignages clients et une FAQ interactive sans JavaScript (`<details>` / `<summary>`).
* **Vérification & ajustements effectués :** Test d'ouverture/fermeture des questions fréquentes dans le navigateur et relecture des engagements inclusifs.

## Étape 5 — Fiche marketing complète et pilotage (`informations.html`)
* **Prompt / Demande :** Structuration des 8 rubriques marketing exigées : présentation du projet, personas, objectifs SMART, typologie des leads (chauds/tièdes/froids), pipeline de conversion chiffré, tableau de 8 KPI (formules, cibles, outils, fréquences), calendrier éditorial sur 3 mois et cadre RGPD.
* **Vérification & ajustements effectués :** Contrôle de la cohérence mathématique entre le volume mensuel de visiteurs (500/mois) et les taux de passage du pipeline.

## Étape 6 — Questionnaire de qualification et page de contact (`formulaire.html` + Google Forms)
* **Prompt / Demande :** Conception d'un questionnaire Google Forms sur mesure en 11 questions (identification, format, effectif, zone, échéance, budget, canal d'acquisition, consentement RGPD) et intégration du lien sur la page `formulaire.html`.
* **Vérification & ajustements effectués :** Désactivation des restrictions de connexion universitaire dans Google Forms, liaison des réponses à une feuille Google Sheets de suivi et test en navigation privée.

## Étape 7 — Crédits visuels et mentions légales (`credits.html`)
* **Prompt / Demande :** Création de la page recensant les 5 visuels libres de droits du dossier `images/`, les mentions légales du cadre pédagogique et la note de transparence sur l'usage de l'IA.
* **Vérification & ajustements effectués :** Vérification de la correspondance exacte entre les noms de fichiers déclarés dans le tableau et les images présentes dans `images/`.
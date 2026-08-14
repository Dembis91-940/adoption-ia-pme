# Politique de données et IA — [Nom de l’entreprise]

> **Objet :** définir ce que l’entreprise confie aux outils d’IA, ce qu’elle ne leur confie jamais, et les réflexes de protection des données (RGPD).
> **Version :** 1.0 — Date : [date] — Validée par : [direction]

## La règle fondatrice

> **On ne confie à une IA que ce qu’on accepterait de publier.**

Une donnée donnée à un outil d’IA peut être stockée, analysée ou réutilisée hors de notre contrôle. Le réflexe : **classer avant d’injecter.**

## Les 3 catégories de données

| Catégorie | Exemples | Traitement |
|---|---|---|
| **Publiques** | Appels d’offres publics, contenu marketing, documentation générale | Utilisation libre, avec validation humaine des sorties |
| **Internes** | Procédures, plans, données commerciales non confidentielles | Utilisation possible sur compte professionnel sécurisé, anonymisation si possible |
| **Sensibles / personnelles** | Données clients, données de santé, salaires, coordonnées personnelles, secrets industriels, données financières précises | **Jamais** dans un outil d’IA public. Anonymisation, outil conforme (UE + contrat), ou traitement 100 % humain |

## Ce qui est INTERDIT (liste non exhaustive)

- ❌ Injecter une **liste brute** de clients, prospects ou salariés dans un outil d’IA
- ❌ Coller un **contrat**, une **facture**, un **dossier médical** ou un **tableau de paie** dans une conversation d’IA
- ❌ Utiliser un **compte personnel** d’outil d’IA pour des données de l’entreprise
- ❌ Utiliser un outil d’IA **non inscrit au registre** pour des données internes ou sensibles
- ❌ Envoyer des données personnelles vers un outil hébergé **hors UE** sans garantie contractuelle

## Les 5 réflexes de protection

1. **Anonymiser avant d’injecter.** Noms → initiales. Montants → ordres de grandeur. Données de santé → catégories générales.
2. **Vérifier la localisation.** UE = zone de confiance. Hors UE = vérifier les garanties avant tout usage.
3. **Compte professionnel obligatoire.** Le compte d’entreprise garantit que nos données ne servent pas à entraîner les modèles.
4. **Jamais de liste brute.** Un fichier complet ne se copie jamais dans une conversation d’IA.
5. **Classer en 5 secondes.** Publique / interne / sensible : chaque collaborateur doit savoir classer avant d’agir.

## Que faire en cas de doute ?

| Situation | Action |
|---|---|
| Je ne sais pas si une donnée est sensible | Je ne l’injecte pas. Je demande au responsable |
| L’outil n’est pas dans le registre | Je ne l’utilise pas. Je dépose une demande (48 h) |
| Une donnée sensible a été injectée par erreur | Je le signale immédiatement (fiche-incident-ia.md) |
| Un client demande des comptes sur ses données | Je transmets au responsable — registre + politique en main |

## En cas de violation de données (RGPD)

1. **Arrêter** immédiatement l’usage concerné.
2. **Documenter** : fiche-incident-ia.md (quoi, quand, quel outil, quelles données).
3. **Évaluer** le risque pour les personnes concernées.
4. **Notifier** : si le risque est réel, notification à la CNIL sous 72 h et information des personnes.
5. **Corriger** : mise à jour du registre, de la politique, formation si nécessaire.

## Engagement

Je reconnais avoir lu la politique de données et m’engage à appliquer le classement publique / interne / sensible avant toute utilisation d’un outil d’IA.

| Nom | Fonction | Date | Signature |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

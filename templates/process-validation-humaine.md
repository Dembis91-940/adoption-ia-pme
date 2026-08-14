# Processus de validation humaine

> **Objectif :** garantir qu’aucune sortie d’IA à impact (client, chiffre, publication, contrat) n’est diffusée sans validation par un humain responsable.
> **Règle d’or :** pas de validation, pas de diffusion. Jamais.

## Les 4 garde-fous

1. **Responsabilité nominative** — chaque sortie à impact a un humain nommé responsable de sa validation.
2. **Séparation des tâches** — celui qui génère ne valide pas seul : double regard pour les contenus à risque.
3. **Traçabilité systématique** — chaque production est tracée (outil, date, prompt, validateur, décision).
4. **Seuil de risque adapté** — plus l’impact est grand, plus le contrôle est lourd.

## Le circuit de validation

```
Génération IA
      │
      ▼
┌─────────────────┐
│ Niveau FAIBLE   │  Brouillon interne, brainstorming
│ Validation      │  → Lecture + correction par l’auteur
│ par l’auteur    │  → Diffusion libre
└─────────────────┘
      │
      ▼
┌─────────────────┐
│ Niveau MOYEN    │  Email client, réseau social, rapport interne
│ Relecture       │  → Auteur : vérifie + corrige
│ responsable     │  → Responsable : relit et valide
│                 │  → Diffusion après validation
└─────────────────┘
      │
      ▼
┌─────────────────┐
│ Niveau ÉLEVÉ    │  Devis, chiffres, juridique, communication officielle
│ Double          │  → Auteur : vérifie + corrige
│ validation      │  → Responsable : valide
│                 │  → Vérification INDÉPENDANTE des faits et chiffres
│                 │  → Diffusion après double validation
└─────────────────┘
```

## Les 4 points de contrôle avant diffusion

À appliquer par le validateur sur **toute** sortie d’IA :

- [ ] **Faits** : les informations sont-elles vraies ? vérifiées ?
- [ ] **Chiffres** : les calculs, montants, dates sont-ils exacts ?
- [ ] **Cohérence** : le contenu correspond-il au contexte, à la demande, à l’entreprise ?
- [ ] **Ton** : le ton est-il approprié (client, public, interne) ?

## Le circuit d’approbation d’un NOUVEL usage

```
1. Demande (collaborateur)
   Outil + usage prévu + données + fréquence
        │
        ▼
2. Analyse de risque (responsable IA)
   Grille analyse-risque.md — RGPD, localisation, impact
        │
        ▼
3. Décision (sous 48 h ouvrées)
   Autorisé │ Autorisé avec conditions │ Refusé (motif)
        │
        ▼
4. Enregistrement au registre (registre-usages-ia.md)
   Sans enregistrement, l’usage n’existe pas
        │
        ▼
5. Communication à l’équipe
   « Ceci est autorisé, de cette façon, avec cette validation »
```

## Règles d’or

- **Une seule porte d’entrée** pour les outils d’IA : le processus. Pas de contournement « pour dépanner ».
- **Délai garanti : 48 h ouvrées.** Un processus lent sera contourné ; un processus rapide sera respecté.
- **Compte professionnel obligatoire.** L’usage de comptes personnels pour du travail est interdit (données hors de contrôle).
- **Revalidation semestrielle** des usages autorisés (outil toujours conforme ? toujours utilisé ?).

## Engagement

Je, soussigné(e) [nom], [fonction], m’engage à appliquer ce processus de validation humaine pour toute production d’IA dans l’entreprise.

Signature : _______________ Date : _______________

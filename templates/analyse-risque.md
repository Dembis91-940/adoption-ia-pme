# Analyse de risque d’un usage IA

> **Objectif :** évaluer un usage d’IA (nouveau ou existant) avant décision : autorisé, autorisé avec conditions, ou refusé.
> **À utiliser avec :** process-validation-humaine.md (le circuit) et registre-usages-ia.md (l’enregistrement).
> **Délai de réponse garanti : 48 h ouvrées.**

## Fiche d’analyse — [Usage / Outil évalué]

| Champ | Réponse |
|---|---|
| Date de l’analyse | |
| Analysé par | |
| Demandeur | |
| Outil évalué (nom, version) | |
| Usage prévu (tâche) | |
| Fréquence prévue | |
| Équipe(s) concernée(s) | |

## 1. Données impliquées

| Question | Réponse |
|---|---|
| Quelles données sont injectées dans l’outil ? | |
| Catégorie : publiques / internes / sensibles ? | |
| Des données personnelles (RGPD) ? | Oui / Non — lesquelles ? |
| L’outil est-il hébergé dans l’UE ? | Oui / Non — où ? |
| Compte professionnel avec garanties de confidentialité ? | Oui / Non |
| Les données servent-elles à entraîner le modèle ? | Oui / Non / Inconnu — vérifié ? |

## 2. Impact en cas d’erreur

| Question | Réponse |
|---|---|
| La sortie touche-t-elle un client ? | Oui / Non |
| Contient-elle des chiffres ou des montants ? | Oui / Non |
| Est-elle diffusée publiquement ? | Oui / Non |
| A-t-elle un aspect juridique ou contractuel ? | Oui / Non |
| Impact estimé d’une erreur non détectée | Faible / Moyen / Élevé — détail : |

## 3. Niveau de risque retenu

| Niveau | Critère | Contrôle requis |
|---|---|---|
| ☐ **Faible** | Aucune donnée sensible, aucun impact externe | Validation par l’auteur |
| ☐ **Moyen** | Impact externe limité (email, réseau social) ou données internes | Validation auteur + responsable |
| ☐ **Élevé** | Données sensibles, chiffres, juridique, communication officielle | Double validation + vérification indépendante |

**Risque retenu :** ☐ Faible ☐ Moyen ☐ Élevé

## 4. Décision

- ☐ **Autorisé** — enregistrer au registre avec niveau de risque et validateur.
- ☐ **Autorisé avec conditions** — conditions : *[ex. : pas de données clients, double validation obligatoire, anonymisation requise]*
- ☐ **Refusé** — motif : *[ex. : données hébergées hors UE sans garantie, compte gratuit, usage non nécessaire]*

## 5. Alternatives en cas de refus

| Alternative | Conformité | Coût |
|---|---|---|
| *Ex. : outil équivalent hébergé en UE, compte pro* | *Oui* | *29 €/mois* |
| *Ex. : traitement manuel avec modèle de fiche interne* | *Oui* | *0 €* |

## 6. Décision communiquée au demandeur le : [date] — par : [nom]

> **Après décision :** l’usage autorisé doit être ajouté au registre (registre-usages-ia.md) et communiqué à l’équipe. Sans enregistrement, l’usage n’existe pas.

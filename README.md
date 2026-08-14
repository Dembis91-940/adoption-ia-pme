# Adoption IA sans risque pour PME — Formation + Templates

> **« L’erreur IA de PwC a coûté des millions. Votre PME ne la fera pas. »**
> Formation niveau expert + 10 templates prêts à l’emploi : le cadre d’adoption de l’IA en 3 semaines, sans risque juridique ni réputationnel.

## Le concept

Le cas PwC 2026 est un cas d’école : des millions de pertes parce que des productions IA ont été diffusées **sans validation humaine**. Le problème n’est pas la technologie — c’est l’absence de processus. Les PME qui adoptent l’IA (ChatGPT, Claude, Copilot…) sans cadre reproduisent le même mécanisme à leur échelle.

**La promesse :** en 3 semaines, chaque usage d’IA dans votre PME est recensé, validé par un humain, traçable — et vos données sensibles sont protégées.

## Business model

| Élément | Détail |
|---|---|
| **Cible** | Dirigeants et gérants de PME (5 à 250 salariés) dont les équipes utilisent déjà l’IA sans cadre |
| **Problème** | L’IA génère des erreurs avec assurance ; sans validation humaine, une seule erreur diffusée coûte un client, un marché, ou des milliers d’euros (cas PwC) |
| **Solution** | Formation complète (7 modules, leçons denses + exemples réels + exercices + checklist) + 10 templates de gouvernance prêts à l’emploi |
| **Prix** | Formation 37 € · Formation + 10 templates 57 € · Pack Entreprise 97 € (avec session de cadrage 45 min) |
| **Marge** | ~95 % (produit digital, livraison par email, EmailJS gratuit) |
| **Canal** | SEO (« adopter l’IA en entreprise sans risque », « erreur PwC IA »), LinkedIn (dirigeants PME), bouche-à-oreille, partenariats experts-comptables / CCI |

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | Landing 3D immersive (Three.js, parallaxe, fond #070b14 cyan/violet) : hero « L’erreur IA de PwC a coûté des millions. Votre PME ne la fera pas. », le cas PwC décortiqué (carte 3D inclinable), le cadre en 3 semaines, 3 offres avec prix, formulaire de commande EmailJS |
| `formation-adoption-ia-pme.md` | **LA formation** niveau expert : promesse mesurable, 7 modules (cas PwC décortiqué, 4 garde-fous de validation humaine, registre des usages IA, processus d’approbation, gestion des données sensibles, formation des équipes, audit continu) — chaque module : leçon dense + exemple réel + exercice, checklist finale sur 3 semaines |
| `templates/` | 10 templates prêts à l’emploi (voir tableau ci-dessous) |
| `chatbot.js` + `chatbot-config.js` | Chatbot FAQ + capture de leads (EmailJS) : cas PwC, prix, fonctionnement, garantie |
| `README.md` | Ce fichier |

## Les 10 templates

| Template | Usage |
|---|---|
| `templates/registre-usages-ia.md` | La colonne vertébrale : tous les usages IA, risques, validateurs, statuts |
| `templates/process-validation-humaine.md` | Le circuit de validation (4 garde-fous) et d’approbation des nouveaux usages |
| `templates/charte-ia-pme.md` | Les règles signées par chaque collaborateur |
| `templates/analyse-risque.md` | La grille pour évaluer chaque usage avant décision (48 h) |
| `templates/plan-formation-equipe.md` | Le plan de formation sur 3 sessions (5 h) + suivi des présences |
| `templates/check-ia-avant-publication.md` | Les 4 points de contrôle (faits, chiffres, cohérence, ton) avant diffusion |
| `templates/politique-donnees.md` | Le classement publique / interne / sensible + réflexes RGPD |
| `templates/comite-ia.md` | La gouvernance : rôles, rythme des réunions, 5 indicateurs |
| `templates/audit-mensuel.md` | La grille de contrôle mensuel (registre, garde-fous, incidents, outils) |
| `templates/fiche-incident-ia.md` | Le circuit de signalement et de traitement des incidents |

## Zéro simulateur — preuves

- **Page 3D immersive réelle** : scène WebGL Three.js (1800 particules, icosaèdres wireframe, anneaux orbitaux, parallaxe souris, scroll en profondeur, carte 3D inclinable) — testée navigateur : WebGL OK, zéro erreur JavaScript.
- **Formulaire EmailJS réel** : service `service_cy1ytdb`, template `template_xpo58cv`, clé publique `8Pui4ZEqxW2jRVF7h` — chaque commande envoie `{site, name, email, question}` vers la boîte mail d’El mouskito, qui livre la formation et encaisse (virement ou message privé).
- **Chatbot réel** : FAQ préprogrammée sur le produit (cas PwC, prix, fonctionnement, données, garantie) + capture de leads EmailJS + stockage local des leads.
- **Contenu expert** : la formation et les 10 templates forment un système cohérent — chaque template référence les autres, chaque module de la formation renvoie aux templates correspondants.

## Déploiement (GitHub Pages — non fait, à la demande)

```bash
cd ~/Documents/livrables/adoption-ia-pme
git init && git add -A && git commit -m "Adoption IA sans risque pour PME"
gh repo create Dembis91-940/adoption-ia-pme --public --source=. --push
gh api repos/Dembis91-940/adoption-ia-pme/pages -X POST -f "source[branch]=main" -f "source[path]=/"
```

## Prochaines étapes

1. Stripe live pour le paiement en ligne (virement/DM en attendant)
2. Livraison automatisée de la formation par email (fichier attaché) après paiement
3. Témoignages réels des premières PME formées
4. SEO : article « le cas PwC 2026 : pourquoi l’IA échoue sans validation humaine » + page d’exemples de registres
5. Version atelier présentiel (demi-journée en entreprise) pour le Pack Entreprise

# Politique de confidentialité — Gentilé

_Dernière mise à jour : {{DATE_DE_PUBLICATION, ex. 12 mai 2026}}_

La présente politique décrit comment l'application **Gentilé** (« l'application »),
publiée par **{{NOM_DE_L_ÉDITEUR}}** (« nous »), traite vos données lorsque
vous utilisez l'application sur un appareil Android via le Google Play Store.

L'application est conçue pour fonctionner **sans compte utilisateur, sans
inscription et sans serveur d'éditeur**. La quasi-totalité des données restent
sur votre appareil.

---

## 1. Données traitées localement (sur votre appareil)

| Donnée | Finalité | Stockage | Durée |
|---|---|---|---|
| Historique des scores (mode de jeu, score, date, noms des joueurs en multi, manches jouées) | Afficher la page « Scores » et calculer vos statistiques | Base Room locale (`score_history`) | Jusqu'à effacement via le bouton « Effacer l'historique » ou désinstallation de l'app |
| Configuration de partie (mode, nombre de manches, joueurs, zone) | Lancer la partie depuis l'écran de setup | Mémoire vive uniquement | Effacée à la fin de la session |
| Compteur de parties terminées | Cadencer l'affichage des pubs interstitielles | SharedPreferences (`ads_prefs`) | Jusqu'à désinstallation |
| Position GPS approximative ou précise | Recentrer la carte sur votre position, uniquement si vous activez le bouton « Me localiser » | Mémoire vive uniquement | Effacée dès que la fonctionnalité est désactivée ou l'app fermée |

**Aucune de ces données n'est transmise à nos serveurs** (nous n'en avons pas).

---

## 2. Données traitées par des tiers

L'application appelle plusieurs services tiers pour afficher des contenus.
Chacun applique sa propre politique de confidentialité.

### 2.1. Google Mobile Ads (AdMob)
- **Éditeur** : Google Ireland Ltd / Google LLC
- **Données collectées** : identifiant publicitaire Android (AAID), informations
  techniques sur l'appareil (modèle, OS, langue), interactions avec les
  publicités, localisation approximative (dérivée de l'IP) pour le ciblage.
- **Finalité** : afficher une publicité interstitielle entre les parties.
- **Politique** : https://policies.google.com/technologies/ads
- **Consentement RGPD** : si vous êtes en France/UE, une bannière de
  consentement Google UMP s'affiche au premier lancement et vous permet
  d'accepter ou refuser les cookies/identifiants publicitaires.

### 2.2. Fondation Wikimedia (Wikipédia, Wikimedia Commons, Wikidata)
- **Éditeur** : Wikimedia Foundation, Inc.
- **Données échangées** : votre adresse IP et un user-agent identifiant
  l'application, lors du chargement de photos et de fiches Wikipédia.
- **Finalité** : afficher les galeries photo (monuments, musées, communes) et
  les informations associées.
- **Politique** : https://foundation.wikimedia.org/wiki/Privacy_policy

### 2.3. Fournisseur de tuiles cartographiques (CARTO / OpenFreeMap)
- **Données échangées** : votre adresse IP, les coordonnées des tuiles
  demandées (= zone que vous regardez sur la carte).
- **Finalité** : afficher le fond de carte.
- **Politique CARTO** : https://carto.com/privacy/

---

## 3. Permissions Android demandées

| Permission | Pourquoi |
|---|---|
| `INTERNET` | Charger les photos Wikimedia, les tuiles cartographiques et les publicités AdMob |
| `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` | Uniquement si vous activez le bouton « Me localiser » dans l'écran Explorer. La position n'est utilisée que localement pour recentrer la carte. |

Aucune autre permission sensible (caméra, micro, contacts, stockage…) n'est
demandée.

---

## 4. Données accessibles depuis l'application sans collecte

L'application affiche des données publiques issues de sources ouvertes,
**lues à la demande** et **non agrégées avec vos données personnelles** :
- `data.gouv.fr` (Licence Ouverte Etalab 2.0) — gentilés, monuments
  historiques, musées de France, maisons des illustres, patrimoine européen,
  jardins remarquables, architecture contemporaine, spectacle vivant, parcs
  naturels régionaux, parcs nationaux ;
- `github.com/gregoiredavid/france-geojson` (MIT, données IGN sous Licence
  Ouverte) — contours administratifs régions / départements / communes ;
- Photos Wikimedia (CC BY-SA, CC BY, domaine public) avec mention obligatoire
  de l'auteur et de la licence dans chaque carrousel.

---

## 5. Vos droits (RGPD)

L'application ne créant pas de profil utilisateur côté éditeur, vos droits
RGPD s'exercent ainsi :

- **Droit à l'effacement** : bouton « Effacer l'historique » dans l'écran
  Scores, ou désinstallation de l'application (efface tout, y compris le
  compteur de parties).
- **Droit d'accès / rectification** : toutes les données sont visibles dans
  l'écran Scores ; vous pouvez les modifier indirectement en effaçant et en
  rejouant.
- **Données AdMob** : pour exercer vos droits sur les données collectées par
  Google, consultez le tableau de bord de votre compte Google et la
  [politique vie privée Google](https://policies.google.com/privacy).
- **Réclamation** : vous pouvez déposer une plainte auprès de la
  [CNIL](https://www.cnil.fr/fr/plaintes).

---

## 6. Mineurs

L'application ne demande pas d'inscription, ne crée pas de profil et ne
collecte aucune donnée d'identification. Les publicités diffusées par AdMob
sont, par contrat, conformes aux règles applicables aux audiences générales ;
si vous estimez que l'application est utilisée par un mineur, refusez le
consentement AdMob au premier lancement pour désactiver le ciblage
publicitaire.

---

## 7. Transferts hors UE

Nous ne transférons pas de données hors UE — nous n'en collectons pas. Les
tiers (Google, Wikimedia, CARTO) peuvent héberger leurs serveurs hors UE ;
chacun applique ses propres clauses de transfert (clauses contractuelles
types européennes).

---

## 8. Modifications de cette politique

Nous pouvons mettre à jour cette politique pour refléter des évolutions
techniques ou réglementaires. La date de dernière mise à jour, en haut de ce
document, permet de suivre les changements. Les versions précédentes sont
consultables dans l'historique git du dépôt
{{URL_DU_REPO_GITHUB, optionnel}}.

---

## 9. Contact

Pour toute question relative à cette politique ou à vos données :

**{{NOM_DE_L_ÉDITEUR}}**
{{ADRESSE_POSTALE, optionnel pour un particulier}}
Email : **{{EMAIL_DE_CONTACT}}**

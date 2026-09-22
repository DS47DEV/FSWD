# FSWD Digital — site vitrine

Site statique sans dépendances, prêt à déployer sur Netlify.

## Publication
1. Personnaliser les textes, prix et mentions légales avant publication.
2. Créer un compte Netlify, choisir « Add new project » puis le déploiement manuel (« Deploy manually » ou « Netlify Drop »).
3. Glisser-déposer le dossier `fswd-site` décompressé (pas le ZIP) dans la zone de déploiement.
4. Dans les paramètres du site, choisir un sous-domaine `*.netlify.app` disponible.
5. Activer/vérifier la détection du formulaire `contact` dans Netlify Forms, puis effectuer un test réel de réception et de notification.

Le formulaire ne fonctionne pas comme une boîte e-mail autonome en ouvrant simplement index.html localement : Netlify doit analyser le HTML au déploiement. Vérifier les limites du forfait gratuit avant usage. Aucun nom de domaine n'est réservé automatiquement.

## À compléter
- Mentions légales et politique de confidentialité adaptée à la collecte des demandes.
- Coordonnées et informations d'entreprise une fois disponibles.
- Portfolio avec projets réels et visuels autorisés.
- CGV et devis adaptés avant la première prestation.


## V2 — Portfolio
- Navigation Portfolio et section Maison Sora (projet concept fictif).
- Correction de W3 START en FSWD START.
- Déployer tous les fichiers à la racine du dépôt GitHub `fswd-digital`, puis pousser sur `main` pour déclencher Netlify.
- Le formulaire Netlify Forms doit être testé après déploiement.


## V3 — Portfolio
Ajout du projet « Les Trésors de Madagascar » dans la section Portfolio, avec un lien vers https://les-tresors-de-madagascar.netlify.app/. Maison Sora et les autres sections sont conservées.

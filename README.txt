
# Smart QR — Auto-enregistrement + Retour du numéro (FR + Darija)

## Ce que tu veux
- 1) Quand quelqu'un scanne: **ton contact se sauvegarde** facilement.
- 2) Tu veux **recevoir automatiquement son numéro**.

## La réalité technique (important)
Les navigateurs et systèmes (iOS/Android) **n'autorisent pas** un site à lire **le numéro du visiteur** automatiquement (confidentialité). Donc on utilise des **actions explicites** du visiteur :
- Bouton **WhatsApp** avec **message pré-rempli** -> la personne t'envoie son numéro en 1 clic.
- Bouton **SMS** pré-rempli -> idem via SMS.
- **Formulaire** simple pour déposer son numéro (Google Forms / Tally / Formspree).

## Ce pack contient
- `index.html` : page principale. Paramètre `?auto=1` pour **déclencher le téléchargement du VCF** automatiquement.
- `contact.vcf` : ta carte vCard.
- `sms.html` : lien SMS profond (deep link) pré-rempli.
- `form.html` : page d’exemple avec un Google Form **à remplacer** par le tien.
- Design sombre, boutons clairs, responsive.

## Configuration
Ouvre les fichiers et remplace :
- Anouar
- +212694216714 (ex: +212612345678)
- anouar19topo@gmail.com
- -
- Topographie

## Déploiement rapide
- **GitHub Pages** : upload, puis Settings → Pages.
- **Netlify** : glisse-dépose le dossier, lien instantané.
- **Vercel** : import du repo, déploiement auto.

## QR code
- Si tu veux que le **contact s'enregistre direct**: crée un QR vers `https://tonsite/.../index.html?auto=1`.
- Sinon QR vers la page simple, l’utilisateur clique sur “Sauvegarder mon contact”.

---

## Darija (ملخّص)
- N9dro nkhalli l-wa7ed **y-sauvgardi** contact dyalek b VCF otomatikiyan (b `?auto=1`).
- **Ma n9dr-ch** njib nmr dial li scanner men QR bla ma howa y-sifto (privacy). 
- 3tina **WhatsApp** w **SMS** b risala m3ammra bach ysift lik **ra9mo** b klik wa7ed.
- Ila bghiti tsajjel les numéros f liste, sta3mel **form** (Google Forms / Tally / Formspree).

Bssa7a! ✨

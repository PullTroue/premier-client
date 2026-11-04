# Premier Client — page de vente

Site statique : un seul fichier, `index.html`, sans dépendance ni étape de build
(seules les polices viennent de Google Fonts).

## Activer le paiement
1. Crée un Payment Link à 59 € sur stripe.com.
2. Ouvre `index.html`, repère `var CHECKOUT_URL = "";` en bas du fichier
   et colle ton lien entre les guillemets.
3. Les deux boutons d'achat ouvrent alors la page de paiement Stripe.

## Mettre en ligne
Glisse le dossier sur Netlify Drop, Vercel, Cloudflare Pages ou GitHub Pages.

## À compléter avant de vendre
- Conditions de vente et mentions légales (statut, SIRET).
- Politique de remboursement (14 jours indiqués dans la FAQ : à confirmer).
- Le contenu des 5 modules.

# Gestion Commerciale Pro — React V1

Application de démonstration développée avec React 19, TypeScript, Vite, Recharts et Lucide.

## Démarrage

Prérequis : Node.js 20+ et connexion Internet pour installer les dépendances.

```bash
npm install
npm run dev
```

Ouvrez l'adresse locale affichée par Vite (habituellement http://localhost:5173).

## Fonctionnalités de cette V1

- Tableau de bord, indicateurs et graphiques de démonstration
- Gestion des clients et produits / services (ajout, recherche, export CSV)
- Création de devis et factures simples (une ligne par document)
- Conversion devis → facture, impression / enregistrement PDF via le navigateur
- Encaissements partiels, suivi du solde et rapports CSV
- Paramètres entreprise, thème clair / sombre, interface responsive
- Données de démonstration persistées localement dans le navigateur (localStorage)

## Limites importantes

- Aucun serveur ni authentification. Les données ne sont pas partagées entre ordinateurs.
- Ne pas utiliser avec de vraies données personnelles ou commerciales sensibles.
- Numérotation et opérations non sécurisées pour un usage multi-utilisateur.
- Calcul de TVA, conformité des factures, avoirs et commandes non finalisés.
- Les graphiques historiques contiennent des valeurs fictives.
- Cette V1 est un prototype fonctionnel, pas un logiciel prêt pour la production.

## Étapes suivantes

Supabase/PostgreSQL, authentification, rôles/RLS, transactions serveur, lignes multiples de facture, TVA/HT/TTC, commandes, avoirs, audit et tests automatisés.

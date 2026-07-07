# Zaaka Furniture — Coming Soon Page

## Déploiement sur Vercel

### Option 1 — Vercel CLI (recommandé)
```bash
npm install -g vercel
cd zaaka_coming_soon
vercel
```

### Option 2 — Vercel Dashboard (sans terminal)
1. Aller sur vercel.com → "Add New Project"
2. "Import Git Repository" OU "Deploy from template"
3. Glisser-déposer le dossier `zaaka_coming_soon`
4. Cliquer "Deploy"

### Redirection nom de domaine
1. Dans Vercel → Settings → Domains
2. Ajouter ton domaine (ex: zaakaFurniture.com)
3. Chez ton registraire DNS, ajouter :
   - CNAME : www → cname.vercel-dns.com
   - A record : @ → 76.76.21.21

## Fichiers
- `index.html` — La page complète (tout en un seul fichier)
- `vercel.json` — Configuration Vercel

## Personnalisation rapide
Chercher dans index.html :
- `contracts@zaakaFurniture.com` → remplacer par vrai email
- `+234 (0) 90 2567 744` → vérifier le numéro
- `zaaka_furniture` → handle Instagram confirmé

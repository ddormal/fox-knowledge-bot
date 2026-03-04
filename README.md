# Fox Ventures Knowledge Bot

Chatbot interne basé sur le module CONNAISSANCE (Odoo Knowledge).

## Déploiement en 3 étapes

### 1. Importe ce repo sur GitHub
- Va sur github.com → **+** → **New repository** → nomme-le `fox-knowledge-bot`
- Upload tous ces fichiers (glisser-déposer)

### 2. Connecte à Vercel
- Va sur vercel.com → **Add New Project** → importe le repo
- Ajoute les **Environment Variables** :
  - `ANTHROPIC_API_KEY` = ta clé API (depuis console.anthropic.com)
  - `CHAT_PASSWORD` = le mot de passe pour tes employés
- Clique **Deploy**

### 3. Partage le lien
- Vercel te donne une URL → partage-la avec tes équipes

## Mise à jour de la base de connaissances
Modifie `src/lib/knowledge-base.ts` → push → Vercel redéploie automatiquement.

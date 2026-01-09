# Deploy Instructions για MrKatharos Site

## Local Git Setup

```bash
cd /Users/makpap/CLEAN/mrkatharos-site
git init
git branch -M main
git add .
git commit -m "Initial MrKatharos static site"
```

## GitHub Repository

1. Δημιούργησε νέο repository στο https://github.com/new
   - Name: `mrkatharos-site`
   - Public/Private: όπως θέλεις
   - ΜΗΝ επιλέξεις README, .gitignore, ή license

2. Σύνδεσε και push:
```bash
git remote add origin https://github.com/YOUR_USERNAME/mrkatharos-site.git
git push -u origin main
```

## Vercel Deployment

1. Πήγαινε στο https://vercel.com/dashboard
2. Add New → Project
3. Import Git Repository → επίλεξε `mrkatharos-site`
4. Ρυθμίσεις:
   - Framework Preset: **Other**
   - Build Command: (άδειο)
   - Output Directory: (άδειο)
   - Root Directory: `./`
5. Deploy

## Future Updates

```bash
git add .
git commit -m "update message"
git push
```

Το Vercel κάνει auto-deploy σε κάθε push!


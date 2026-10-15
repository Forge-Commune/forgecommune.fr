# forgecommune.fr

Site internet de Forge Commune : une page de présentation statique (HTML +
CSS, sans dépendance ni étape de build).

| Fichier | Rôle |
|---|---|
| `index.html` | Page d'accueil : mission, fonctionnement, projets, principes, participer |
| `mentions-legales.html` | Mentions légales (à compléter une fois l'association déclarée) |
| `style.css` | Styles, thème clair et sombre automatique |
| `favicon.svg` | Icône (enclume stylisée) |
| `CNAME` | Domaine pour GitHub Pages |

## Voir le site en local

```sh
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

## Mise en ligne

Avec GitHub Pages : *Settings → Pages → Deploy from a branch → `main` / root*,
puis faire pointer le DNS de `forgecommune.fr` vers GitHub Pages. Le site
fonctionne aussi tel quel sur n'importe quel hébergement statique.

## À compléter

- [ ] Adresse `contact@forgecommune.fr` : à créer (ou remplacer)
- [ ] Description de rouages.net
- [ ] Mentions légales : siège, RNA, SIREN, directeur de publication, hébergeur
- [ ] Lien vers les statuts : le dépôt `Documents` doit être public pour que
      le lien fonctionne

# adamstra.github.io

Site du jeu **Yoté**, servi par GitHub Pages à la racine du domaine
`https://adamstra.github.io/`.

Ces fichiers sont **générés** depuis les sources du jeu, ils ne se modifient
pas ici :

```bash
cd ~/Godot/yote
python3 tools/make_site.py ~/Godot/adamstra.github.io
```

| Fichier | Pourquoi il existe |
| --- | --- |
| `confidentialite.html`, `privacy.html` | Google Play exige une **URL** de politique de confidentialité |
| `app-ads.txt` | AdMob le lit à la racine du domaine ; sans lui, une partie des annonceurs n'enchérit pas |
| `index.html` | page d'accueil |

Le dépôt doit s'appeler `adamstra.github.io` — et pas autre chose : c'est ce
qui fait servir `app-ads.txt` à la racine, là où AdMob le cherche.

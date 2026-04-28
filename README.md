# Plugin Osuny : centered layout

Ce plugin transforme les mises en page avec barre latérale (4 colonnes / 8 colonnes) en mises en pages centrées.


<img width="1440" height="789" alt="image" src="https://github.com/user-attachments/assets/88d3d5a2-5c6d-4516-9231-72e7771997f6" />


## Utilisation

D'abord, importer le plugin dans le site.

```bash
git submodule add git@github.com:osunyorg/osuny-plugin-centered-layout.git themes/osuny-plugin-centered-layout
```

Ensuite, ajouter le plugin comme un thème dans `config/_default/config.yaml`.

```yaml
theme: 
  - osuny
  - osuny-plugin-centered-layout
```

Enfin, importer le style dans `assets/sass/main.sass`.

```sass
@import "osuny-plugin-centered-layout/style"
```

## Exemples 

- https://www.encommuns.net/articles/2025-06-23-aux-origines-de-la-science-ouverte-retour-sur-les-institutions-qui-on-fait-de-la-science-un-commun/
- https://histoires.noesya.coop/john-et-la-chouette-venue-du-froid/

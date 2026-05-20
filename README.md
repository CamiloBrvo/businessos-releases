# BusinessOS — releases desktop

Dépôt **public** : uniquement les installateurs desktop.

Le code source BusinessOS est **privé** (accès restreint).

## Télécharger

→ **[Dernière release](https://github.com/CamiloBrvo/businessos-releases/releases/latest)**

| Plateforme | Fichier |
|------------|---------|
| **macOS** (Apple Silicon) | `BusinessOS_*_aarch64.dmg` |
| **Windows** (x64) | `BusinessOS_*_x64-setup.exe` |

## Autres fichiers sur la page release

| Fichier | Rôle |
|---------|------|
| `.tar.gz` + `.sig` + `latest.json` | Mise à jour **automatique** dans l'app installée |
| « Source code (zip) » | Généré par GitHub — contient **ce README uniquement**, pas le code BusinessOS |

## Mises à jour automatiques

L'app interroge :  
`https://github.com/CamiloBrvo/businessos-releases/releases/latest/download/latest.json`

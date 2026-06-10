# Open edX - Guide d'installation et de configuration

- LMS :  http://local.openedx.io
- Studio : http://studio.local.openedx.io

## Accès de test

### Administrateur
- Login : admin@example.com
- Mot de passe : 12345
## Installation

### Prérequis
Infrastructure : VPS
Système d'exploitation : Ubuntu Server 24.04 LTS
Conteneurisation : Docker
Outil de déploiement : Tutor 21.x

### Installation

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install docker.io -y
pip install "tutor[full]"
tutor config save
tutor local launch
```

## Documentation complète

Le guide détaillé est disponible dans :

`Guide_Installation_Open_edX.docx`

## Références

- Documentation Tutor : https://docs.tutor.edly.io/
- Documentation Open edX : https://docs.openedx.org/

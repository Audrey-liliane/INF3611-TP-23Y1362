# Rapport de Déploiement - INF3611
**Étudiant :** BITAK AUDREY LILIANE
**Matricule :** 23Y1362

## Détails du Déploiement
- **Application déployée :** Vault (HashiCorp)
- **Port HTTP assigné :** 5280
- **URL d'accès :** https://23Y1362.systeme-res30.app

## Configuration Docker
- **Réseau :** `vault_network` (driver bridge)
- **Volumes :** Utilisation de Bind Mounts sur `./vault_app`

## Reverse Proxy
- Configuration Nginx située dans `/etc/nginx/sites-available/23Y1362.conf`
- SSL géré via le certificat Wildcard de systeme-res30.app
# INF3611-TP-23Y1362

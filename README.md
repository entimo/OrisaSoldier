# Projet Proxmox - OrisaSoldier

## Objectif
Déployer automatiquement une VM Lubuntu sur Proxmox avec Ansible.

## Structure
- `playbook.yml` : Le code de création.
- `inventories/dev/` et `inventories/prd/` : Les IPs et mots de passe.

## Comment lancer ?
**Commande pour la DEV :**
```bash
ansible-playbook -i inventories/dev/hosts playbook.yml -k
```
*(Pour la prod, remplacer dev par prd. Taper le mot de passe SSH quand demandé).*

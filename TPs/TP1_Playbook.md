# TP PLaybook - inventaire

## Gestion de l'inventaire

- le serveur client de type debian doit faire parti d'un groupe de l'inventaire appelé web

## Creation d'un playbook

- Fichier yaml : tp1-web-playbook.yaml

- Nom de play
- Target : web

- Installe les packages : (module ??)
     - git
     - vim
     - apache2

- S'assurer que le service apache2 soit activé (enable) et démarré (module ??)

- Copie un fichier "static" (présent dans le projet ansible) vers /var/www/html (module ??)

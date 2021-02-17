# Applications des connaissance :

## Modules, Handlers, variables, conditionnals, loop

### Reprise du playbook bootstrap-playbook.yaml

- Déclarer des variables

- S'assurer que openssh server soit bien installé
  - Une task par type de distri : (conditionnals when )
    - module apt
    - module yum

- Modifier la configuration du serveur openssh (/etc/ssh/sshd_config): (module lineinfile) => loop pour 3 modif
    - Activer le LogLevel
    - Commenter la ligne X11Forwarding yes
    - une autre 

- SI modification du fichier sshd_config => reload du service ssh
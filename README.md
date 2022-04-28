# Rapport des travaux
Ce présent répo présente les playbooks  pour l'automatisation des tâches d'administration systeme au sein d'un entreprise lambda.
  Ses principales tâches sont la création des utilisateurs au seins de  différentes machines à distantes qui elles même cont classés en 2 groupe 
      - Le groupe Projetet le groupe test
      
Nous avons aussi la création des utilisateurs selon les groupes de machines (fichier inventaire) t les groupes utilisateurs
les utilisateurs ont des mots de passe que nous avons crypté à l'aide dansible-vault
le load balacing grâce au role Haproxy
le partitionnement et la création de disque

Pour finir nous avons aussi paramètrer une tâche qui se lance automatiquement à l'aide de crontab tâche qui met simplement à jour les paquets du système sur lesmachines du groupe test chaque h du matin et tous les jours


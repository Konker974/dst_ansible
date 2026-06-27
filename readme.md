Ce projet a pour but d'installer prestashop sur une machine et sa bdd mysql initialisée en amont sur une autre machine. N'oubliez pas de modifier la variable prestashop_domaine avant de le lancer

Commande pour lancer le playbook :  ansible-playbook -i inventory app.yaml --ask-vault-pass
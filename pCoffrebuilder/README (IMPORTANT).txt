# Dépendance 
- ESX (Sauf Legacy)
- Addoninventory
- Datastore 

# Soucis dépot d'arme 
Si vous avez un soucis concernent le dépôt d'arme (vous ne retrouvez pas votre arme dans la partie du coffre)
Cela veut dire qu'il vous manque le datastore de ce dernier, voici un modèle pour régler ce soucis :

INSERT INTO `datastore` (`name`, `label`, `shared`) VALUES
('police', 'LSPD', 1),

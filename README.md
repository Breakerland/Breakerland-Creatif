# Breakerland Creatif

Bienvenue sur le projet du serveur Creatif de Breakerland.

## Contribution
Vos contributions sont les bienvenues et doivent être approuvées par un administrateur. Si celle-ci est validée, elle est alors fusionné au projet et effective sur le serveur lors de son redémarrage quotidien.

## Obfuscation
Certaines données sont sensibles et ont donc été soit supprimé (plugins payants), soit obfusqué (identifiants BDD, Token).
Cependant tous les fichiers de configuration restent disponible à la modification et les variables obfusquées sont désobfusquées sur notre serveur en sécurité.

## Variables

### Propriétés serveur
Pour les identifiants du Bot Discord BreakerBot, veuillez utiliser les variables suivantes :
```bash
Server name: '$server_name_creatif'
Server address: '$server_address_creatif'
Server port: '$server_port_creatif'
Query port: '$query_port_creatif'
RCON port: '$rcon_port_creatif'
RCON password: '$rcon_password_creatif'
```

### Votifier
Pour les informations de connexion avec Votifier.
```bash
Votifier port: '$votifier_port'
```

### Dynmap
Pour les informations de connexion avec Dynmap.
```bash
Dynmap port: '$dynmap_port_creatif'
```

### Base de donnée
Il est préférable de favoriser l'utilisation de MySQL ou MariaDB lorsqu'il l'est possible.
Pour les informations de connexion, veuillez utiliser les variables suivantes :
```bash
Host: '$mysql_host'
Port: '$mysql_port'
```

Pour les identifiants de connexion pour les données spécifiques au serveur Creatif, veuillez utiliser les variables suivantes :
```bash
User: '$mysql_user_creatif'
Password: '$mysql_password_creatif'
Database: '$mysql_database_creatif'
```

Pour les identifiants de connexion pour les données communes à différents serveurs, veuillez utiliser les variables suivantes :
```bash
User: '$mysql_user_proxy'
Password: '$mysql_password_proxy'
Database: '$mysql_database_proxy'
```

### Bot Discord
Pour les identifiants du Bot Discord BreakerBot, veuillez utiliser les variables suivantes :
```bash
Invite: '$discord_invite'
General channel: '$discord_channel_general'
Console channel: '$discord_channel_console'
Token: '$discord_token'
```

### Dynmap
Pour les paramètre de la Map dynamique, veuillez utiliser les variables suivantes :
```bash
Host: '$dynmap_host_creatif'
Port: '$dynmap_port_creatif'
```
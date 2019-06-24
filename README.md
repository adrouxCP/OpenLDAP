# OpenLDAP + phpldapadmin

### Le docker-compose monte un conteneur pour le serveur LDAP et un conteneur pour phpldapadmin.
    PHPladapadmin se charge de l'administation du LDAP. Connexion en interface web =>
            url: http://127.0.0.1:8080
            Login DN: "cn=admin,dc=example,dc=org"
            Mot de passe : admin
           
### Peupler le LDAP
    Via PHPladpadmin, "import" le fichier ldap-test.ldif

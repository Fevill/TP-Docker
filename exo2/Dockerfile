# Exo2
FROM php:7.4-cli

WORKDIR /app

COPY src/hello.php /app

# Créer une image docker embarquant un interpréteur PHP
# Tager l'image exo2:1.0
# Le démarrage d'un container basé sur cette image devra afficher "Hello PHP" par interprétation d'un fichier hello.php (php hello.php)
CMD ["php","/app/hello.php"]
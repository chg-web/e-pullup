# epullup

Liste de fichiers améliorant la sécurité d'un serveur sous Debian

## Liste des fichiers


  * /etc/postfix/header_checks                                  : Fichier de détection spam, phishing, scam, virus se trouvant dans les headers pour postfix 
  * /etc/postfix/body_checks                                    : Fichier de détection spam, phishing, scam, virus se trouvant dans le corps de mail pour postfix 
  * /etc/postfix/mime_headers_checks                            : Fichier de détection spam, phishing, scam, virus pouvant se trouver dans des pièces jointes pour postfix 
  * /etc/postfix/sanitize.cf                                    : Fichier de filtre de nettoyage pour supprimer données sensibles dans les headers pour postfix 

## Minimum requis

Testé sous Debian Strech ou supérieur

## Installation

Il suffit de faire un copier/coller des fichiers nécessaires. Normalement les chemins des fichiers disponibles correspondent à la structure de dossiers sous Debian
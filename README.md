# Bbox Network Lab — ARC Raiders

Page statique pour comparer des mesures DNS-over-HTTPS et des temps de réponse HTTP depuis le navigateur.

## Hébergement
Cette page est destinée à GitHub Pages. Elle ne nécessite ni serveur ni secret.

## Limites techniques
- Un navigateur ne peut pas envoyer de ping ICMP classique ni mesurer correctement la perte de paquets ICMP.
- Les tests DNS utilisent DNS-over-HTTPS (DoH), pas les requêtes UDP DNS habituelles de la PS5.
- Les temps HTTPS ne sont pas le ping en jeu et ne mesurent pas directement le serveur ARC Raiders.
- Pour le diagnostic complet de la Bbox (ping ICMP, pertes et latence sous charge), utilisez le moteur Python local Windows préparé séparément.

## Activer GitHub Pages
Dans le dépôt : **Settings → Pages → Build and deployment → Deploy from a branch**, sélectionnez **main** et **/(root)**, puis Save. Le site sera publié à l'adresse affichée dans cette page de paramètres.

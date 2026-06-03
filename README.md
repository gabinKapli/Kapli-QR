l'url a mettre dans le component web embed via un template dans les colonnes : 
https://gabinkapli.github.io/Kapli-QR/

Comment ça fonctionne :

1) Le scanner s’ouvre dans un composant Web Embed Glide.
2) La caméra détecte un QR code.
3) Le texte contenu dans le QR code s’affiche pour confirmation.
4) Si l’utilisateur confirme, le texte scanné est envoyé au webhook Glide.
5) Glide reçoit cette valeur et peut ensuite lancer un workflow, par exemple rediriger l’utilisateur, enregistrer une donnée ou afficher une information.
6) Après l’envoi, le scanner reprend automatiquement.
7) Le lien du scanner contient le webhook Glide dans le paramètre endpoint, ce qui permet de choisir où envoyer le résultat du scan.

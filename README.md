Comment ca fonctionne :

1) Le scanner s'ouvre dans un composant Web Embed Glide.
2) La camera detecte un QR code.
3) Le QR code doit contenir l'URL de la fiche Glide a ouvrir.
4) Le lien detecte s'affiche pour confirmation.
5) Quand l'utilisateur clique sur "Ouvrir la fiche", le scanner ouvre l'URL au niveau de la page complete avec `_top`.
6) L'utilisateur sort donc du Web Embed et arrive directement sur la vraie fiche dans l'application Glide.

Important :

Le mode avec confirmation est conseille, car Glide affiche le scanner dans une iframe. Le clic utilisateur aide le navigateur a autoriser la sortie du Web Embed.

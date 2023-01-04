# Road map

On va créer un site internet qui permet au utilisateurs de s'authentifier et d'ajouter des posts.
 3 Pages:

# Page Accueil

Afficher tous les posts de tout les utilisateurs ordonnés par date. (les plus récents d'abord).
 
 - créer une page d'accueil ou va retrouver les post des utilisateurs 
 - et publier nos post 

 ## Page login

- Un formulaire pour s'inscrire DONE
- Script pour ajouter un user dans la base de données DONE

- formulaire de connection DONE
- script pour verifier si l'utilisateur a donné un email et password valide DONE
- Stocker les infos (id, email, avatar, role) quelque part: session DONE

- Mieux gerer les erreurs.

 # Profil: 
 
 Les informations de l'utilisateur (avatar, username, email, couverture), un formulaire pour créer un post.
 
 Afficher tous les posts de l'utilisateur:

 - Un post c'est un titre, une image optionnelle, contenu.

 - Pouvoir changer sa photo de profils 

 - Un script (/routes/uploadAvatar.php), enregistre l'image, et met a jour l'utilisateur dans la base de données

 - pouvoir modifier nos post 
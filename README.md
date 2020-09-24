C'est Une application de Clone Whatsapp avec flutter et Firebase dans la partie backend.

Dans cette application, on a les fonctionnalités suivantes : 

  1) S'authentifier avec son Compte google et vos données comme le prénom, le nom, l'image profil de votre compte google ... seront récupéré pour créer votre profil
  
  2) Modifier son profil avec les données par défaut inséré lors de l'authentification
  
  3) Voir la liste des utilisateurs inscrits
  
  4) Envoyer des messages a chaque utilisateur (texte, image et vidéo)
  
Dans firebase on a deux collections : User et Messages

Et chaque discution entre deux utilisateur est inserer dans un seul noeud pour ne pas permettre a un autre utilisateur de voir le message d'autrui.

Les plugins utiliges sont: 

  firebase_core
  
  firebase_auth
  
  google_sign_in
  
  cloud_firestore
  
  fluttertoast
  
  image_picker
  
  shared_preferences
  
  firebase_storage
  
  cached_network_image
  
  intl
  
  firebase_messaging
  
  flutter_local_notification
  
  photo_view
  
  video_player

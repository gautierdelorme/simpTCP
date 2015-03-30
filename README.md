# simpTCP
simpTCP (alternative TCP) by Bastien Micheau and Gautier Delorme - INSA Toulouse, FRANCE


I.Fait : 
- Création de PDU lancé depuis l'état closed active
- Création de PDU prend message
- Création de PDU qui compile
- Test d'affichage avec simptcp_create_pdu() qui semble fonctionner corectement.
   . Erreur sur seq_num, tracké jusqu'à le fonction d'insertion de seq_num (avec la fonction htons)

II. Reste à faire :
- debugger creation pdu
- Utiliser libc_send() de libc_socket pour envoyer

III. Commentaires : 
Passé longtemps pour compiler l'appel de la fonction de création du PDU.

Bastien Micheau et Gautier Delorme
     Tp2-Linux
    Mise en place d'un cluster de 2 nodes

![Capture d'écran 2025-02-11 081456](https://github.com/user-attachments/assets/66799b13-c622-4578-bf33-1aa23780ad48)


     Installaion reussi d'après vagrant up
![Capture d'écran 2025-01-29 233546](https://github.com/user-attachments/assets/6e8c0f40-7376-42c5-a1d1-fd90bdcb820b)

     Ouvrerture de la session SSH vers la VM (web et db)
![Capture d'écran 2025-01-29 235013](https://github.com/user-attachments/assets/cf6c013d-3c4b-4bad-a5eb-55555a6cb966)

     Vérification de versions après l'installation des différents outils dans le noeud web et db
![Capture d'écran 2025-01-29 235240](https://github.com/user-attachments/assets/fb9bea24-931e-46b3-8307-2e5828836582)
![Capture d'écran 2025-01-30 000036](https://github.com/user-attachments/assets/e0655aca-2d38-40b7-a5c8-21610aea4fe4)
![Capture d'écran 2025-01-30 012047](https://github.com/user-attachments/assets/b8d29c63-cff5-4852-b20c-2de277fbfd65)
![Capture d'écran 2025-01-30 015055](https://github.com/user-attachments/assets/6bca39c0-f705-41fe-b7ad-c36aa78a4191)


     Test de la connectivité pour les deux noeuds
![Capture d'écran 2025-01-30 000357](https://github.com/user-attachments/assets/63c5ff39-cc23-4dc2-8379-bee292ef71d8)

## Configuration MySQL situé à /etc/mysql/mysql.conf.d/mysql.cnf dans le noeud db
![Capture d'écran 2025-01-30 012904](https://github.com/user-attachments/assets/dce6e368-1ea5-4f8d-bc1c-2a649952118a)

     Test de connexion à MysQL dans la machine db
![Capture d'écran 2025-01-30 013026](https://github.com/user-attachments/assets/2a8000ec-9f72-47c1-9958-349fe9f31327)

     Test de la connectivité à la machine db avec IP: 192.168.0.11 dans la machine web
![Capture d'écran 2025-01-30 015350](https://github.com/user-attachments/assets/3e81f8af-4e6b-4e8a-b76c-41137150442c)

     Création de l'utilisateur web dans la machine db avec l'IP de la machine web: 192.168.0.12
<img width="462" alt="3H0813" src="https://github.com/user-attachments/assets/4f78e774-94f4-4bae-8e97-0a0e1e93a2a5" />
<img width="446" alt="3H1037" src="https://github.com/user-attachments/assets/7ea5edce-b873-494c-bd6a-015184ce5902" />


     Accord du privilège à l'utilisateur web_user
<img width="461" alt="3H0907" src="https://github.com/user-attachments/assets/58c76858-3065-4ec9-bf3c-f6e4a1591a7a" />

     Clonage du projet spring boot dans la machine web (https://github.com/ngorseck/admin-app)
<img width="641" alt="3H3508" src="https://github.com/user-attachments/assets/b8a6c2c1-8c98-4423-b954-38ccacc7f504" />

     Configuration des variables d'environnment dans machine web
![Capture d'écran 2025-01-30 022854](https://github.com/user-attachments/assets/4a69e858-3be4-440f-b277-04b2ef3d954f)

     Configuration dans l'application.yml de projet spring boot
![Capture d'écran 2025-01-30 024032](https://github.com/user-attachments/assets/37f839a9-c42a-4e23-a248-fb8528f2f407)

     Demarrage de l'application dans la machine web
![Capture d'écran 2025-01-30 024624](https://github.com/user-attachments/assets/c33110dc-c8e5-4cd7-882d-16bf94cd313b)

     NB: La base de données admin est créée automatiquement une fois l'application est demarrée depuis dans la machine web
![Capture d'écran 2025-01-30 040500](https://github.com/user-attachments/assets/ea1c3679-4cc3-4905-98b5-90535a3920b7)

     Quelques capture des requêtes
![Capture d'écran 2025-01-30 095855](https://github.com/user-attachments/assets/8cc0ebb6-9ea3-4d8f-93ff-ffdcd69cc912)
![Capture d'écran 2025-01-30 100220](https://github.com/user-attachments/assets/b88ecc7a-ca59-4663-b8fe-67776f87501f)
![Capture d'écran 2025-01-30 100330](https://github.com/user-attachments/assets/b3aa09f3-c780-4246-baba-c48e2ad2f5cc)



















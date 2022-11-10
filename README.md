# ESGI-3A-SI2 - Partiel CCNA - Céline OULMI <br>

 Jeudi 27 octobre 2022<br>

### ➔ Objectif
• Etude conceptuelle et mise en place d’un réseau avec élaboration d’un plan
d’adressage optimisé et d’un plan de sécurité fiable.

#### Scénario :
Vous participez dans une équipe réseau/sécurité à la mise en place d’un réseau pour DevOpsSecurity.
Vous devez concevoir ce réseau en IPv4 pour configuration des machines/hôtes et du routage OSPF
avec proposition d’un plan de sécurité.

Ce réseau est constitué de quatre agences connectées à un routeur au siège de la société situé à Paris.
Le siège de la société est connecté à son tour à un routeur de FAI par souci de centralisation.

Votre tâche consiste à créer un plan d’adressage afin d’accueillir le nombre d’hôtes requis et
de proposer votre plan de sécurité pour l’infrastructure.

#### Étape 1 : Proposez et concevez la topologie du réseau.

##### a. Équipements réseau :

1) Six routeurs :
```
Quatre routeurs d’agences
Un routeur de siège social
Un routeur de FAI distant
```
2) Des commutateurs de 24/48 ports prenant en charge des LAN :

##### b. LAN :

1) Deux LAN par routeur d’agence : - FAIT
```
(a) Deux LAN avec 500 hôtes
(b) Un LAN desservant 120 hôtes
(c) Un LAN avec 200 hôtes
(d) Deux LAN avec 80 hôtes
(e) Un LAN avec 60 hôtes
(f) Un LAN avec 30 hôtes
```

2) Un LAN à trois hôtes attribués au routeur de FAI pour la connectivité de serveur (DNS, Web
et protocole TFTP). - FAIT


#### Étape 2 : Concevoir le modèle d’adressage du réseau.
a. Proposer une adresse répondant aux spécifications répertoriées à l’Étape 1. - FAIT <br>
b. La connexion LAN du FAI utilise un numéro de réseau IPv4 différent pour indiquer une
connectivité Internet ou de télécommunication aux serveurs. - FAIT <br>
c. Utiliser VLSM (si possible) avec efficacité pour économiser les adresses et prévoir l’évolutivité. <br>
d. Proposer un plan d’adressage en justifiant.

#### Étape 3 : Représenter l’infrastructure avec Packet Tracer(avec configuration)
1) Documenter l’infras. - FAIT
2) Préciser le type de câblage et les équipements nécessaires utilisés.

#### Étape 4 : Proposer un plan de sécurité
1) Analyser les besoins en sécurité.
2) Proposer votre plan de sécurité (voir syllabus)

#### A déposer sur Myges le 24/11/22, le jour de la soutenance :
1. Le fichier PKT fonctionnel.
2. Le livrable d’au moins 10 pages.

#### Remarque : Attention au retard, vous serez pénalisés de 2 points/jour.

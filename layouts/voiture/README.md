# Voiture - Cartographie en roulant
Ce layout est fait pour une cartographie des éléments routiers.

## Note importantes
Impossible d'avoir des sous-dossiers d'icones par catégories :

OK  : 
    
    <button type="tag" label="···  Vitesse à 90  ···" icon="voiture_icons/France_road_sign_B14__90_.png"/>
NOK : 

    <button type="tag" label="···  Maxspid de 80  ···" icon="vitesse-icone/France_road_sign_B14__90_.png"/>

Lien pour la signalisation en France : [LIEN](https://wiki.openstreetmap.org/wiki/FR:Signalisation_routi%C3%A8re_en_France).

# Architecture
4 Catégories :
- **[Vitesse]** Vitesse
- **[Regulation]** Régulation trafic (feu, stop, cédez le passage)
- **[Rallentis]** Rallentissement (dos d'âne, chicane)
- **[Etat]** Etat de la route
# Vitesse en France
Les vitesses les plus fréquentes sont (ordre croissant) :
- 30km/h
- 50km/h
- 70km/h
- 80km/h
- 90km/h
- 110km/h
- 130km/h

Comment le cartographier (ex. 50km/h) ?
[Lien](https://wiki.openstreetmap.org/wiki/FR:Key:traffic_sign "Wiki OSM-FR").
   
    
https://wiki.openstreetmap.org/wiki/File:France_road_sign_B14_(90).svg
![France_road_sign_B14_(50)](https://github.com/Thibtib51/osmtracker_layouts/assets/50510871/1d1eb67e-532f-4650-871e-b2cbe08493b4)

Sur un way avec :

    maxspeed=50
    source:maxspeed=FR:sign

Sur un node à part du way avec :

    traffic_sign=FR:B14[50]
    direction=* (relatif au nord)
## Travail en cours
- [X] Téléchargement des panneaux B14
- [X] Les mettre en PNG et taille 500x500px
- [X] Renommer les fichiers avec "Vitesse_"
- [X] Ajout dans sous dossier "voiture_icons"

# Régulation de trafic en France
Les régulations de trafic en France sont :
- Feu tricolore de signalisation
- Stop
- Cédez le passage
- Passage piéton
## Travail en cours
- [X] Téléchargement des panneaux B14
- [X] Les mettre en PNG et taille 500x500px
- [X] Renommer les fichiers avec "Regul_"
- [X] Ajout dans sous dossier "voiture_icons"
# Rallentissement en France
Les rallentissement les plus fréquents sont :
- Dos d'âne
- ~~Coussin berlinois~~
- Chicane priorité avant
- Chicane priorité arrière
- ~~Chicane simple~~
## Travail en cours
- [X] Téléchargement des panneaux B14
- [X] Les mettre en PNG et taille 500x500px
- [X] Renommer les fichiers avec "Rallen_"
- [X] Ajout dans sous dossier "voiture_icons"
# État de la route
Voir Key:smoothness https://wiki.openstreetmap.org/wiki/Key:smoothness

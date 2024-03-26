## Voiture - Cartographie en roulant
Ce layout est fait pour une cartographie des éléments routiers.

## Architecture
4 Catégories :
- Vitesse
- Régulation trafic (feu, stop, cédez le passage)
- Rallentissement (dos d'âne, chicane)
- Etat de la route
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
https://wiki.openstreetmap.org/wiki/File:France_road_sign_B14_(90).svg
![France_road_sign_B14_(50)](https://github.com/Thibtib51/osmtracker_layouts/assets/50510871/1d1eb67e-532f-4650-871e-b2cbe08493b4)
Sur un way avec :

    maxspeed=50

Sur un node avec :

    traffic_sign=FR:B14[50]
    direction=*
# Régulation de trafic en France
Les régulations de trafic en France sont :
- Feu tricolore de signalisation
- Stop
- Cédez le passage
- Passage piéton
# Rallentissement en France
Les rallentissement les plus fréquents sont :
- Dos d'âne
- Coussin berlinois
- Chicane priorité avant
- Chicane priorité arrière
- Chicane simple
# État de la route
Voir Key:smoothness https://wiki.openstreetmap.org/wiki/Key:smoothness

# ballon
Veille pour ballon atmo. Objectif : altitude max pour mesure du vent (prise au vent / vitesse)

TODO
+ Conception (fonctionnement / prix)
  + Ballon
    - Calculs force https://www.deleze.name/marcel/physique/aerostat/helium/index.html
    - Surface matériau https://www.toutcalculer.com/geometrie/volume-surface-sphere.php
    - vide https://github.com/jclaveau/ballon/issues/3
    - composit https://www.youtube.com/watch?v=tUrGZMB4WHY
    
      https://www.epoxyresolutions.com/technologies/materiaux-composites-definitions/
      
      Masse volumique = 2 à 2,1 kg/dm3
Contrainte rupture traction sens longitudinal = 12 dN/mm²
Contrainte rupture traction sens circonférentiel = 70 dN/mm²
Contrainte rupture en flexion = 10 dN/mm²
Module d’élasticité sens circonférentiel = 3500 daN/mm²
Module d’élasticité en flexion = 1500 dN/mm²

      choix refort https://www.youtube.com/watch?v=ioj1YBm6bJY
      fibre de verre vs carbone vs kevlar https://www.youtube.com/watch?v=KHXVf0SaJpA
      sphere carbone / economie max d'epoxy https://www.youtube.com/watch?v=g7pziJ8tUSY https://www.youtube.com/watch?v=VodfQcrXpxc
      epoxy moussante https://www.sf-composites.com/ProductCard/RES2080MB%25252F4/resine-epoxy-moussant-2080-5kg
      
      mylar pas cher https://www.cdiscount.com/maison/decoration-accessoires/ballon-en-feuille-ballons-mylar-de-18-pouces-pour/f-117634605-vol6437913247163.html
      
      design chambre a vide http://edge.rit.edu/edge/P14651/public/Miscellaneous/Design%20rules%20for%20vacuum%20chambers.pdf
  + Nacelle
    - Altimetre https://forum.arduino.cc/index.php?topic=205097.0
    - GPS https://lecafedugeek.fr/arduino-creer-votre-propre-compteur-gps/
    - thermometre https://create.arduino.cc/projecthub/projects/tags/thermometer
    - Radio 
      https://fr.wikipedia.org/wiki/Ultra_haute_fr%C3%A9quence#Utilisations
      https://inductivetwig.com/products/hamshield-mini
    - Alimentation https://www.asca.com/cellule-solaire-souple-transparente/
  
  + Bonus ? https://makezine.com/projects/ionic-thruster/
    http://everything.explained.today/Ion_thruster/
+ Reglementation
  - https://forums.futura-sciences.com/astronautique/70616-ballon-sonde.html

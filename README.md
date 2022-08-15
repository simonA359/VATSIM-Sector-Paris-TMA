# VATSIM Sector Paris TMA

Fonds de carte pour De Gaulle APP et Orly APP. <br>
__Ne pas utiliser hors de la simulation sur VATSIM.__

# Installation Facile

+ Faire une sauvegarde du fichier secteur `.sct` (important)
+ Ouvrir le fichier secteur qui souhaite être modifié à l'aide d'un éditeur de texte
+ Se rendre dans le dossier `maps` sur Github puis ouvrir `GEO.txt` dans un premier temps
+ Copier le contenu du fichier en utilisant le bouton en haut à droite <img width="20" alt="image" src="https://user-images.githubusercontent.com/85018190/184549238-3668333f-da8c-4e2e-a3ea-853e3d884bcb.png">
+ Dans l'éditeur de texte, (CTRL+F) rechercher la section `[GEO]` puis placer le curseur de texte juste après le crochet droit `]`
+ Coller le contenu qui a été copié à partir de Github
+ S'assurer que le fichier orignal a déjà été sauvegardé
+ Enregistrer le fichier secteur modifié<br>
+ Faire de même pour les fichiers `ARTCC.txt`, `ARTCC LOW.txt` et `REGIONS.txt` avec le nom de la section qui leur correspond

# Cartes Disponibles

| **Config**  | LFPG_APP | LFPO_APP | LFPG_APP (+PO) |
| ------------- | ------------- | ------------- | ------------- |
| Ouest Lié  | Disponible  | Disponible | Adaptée à VATSIM |
| Est Lié  | Disponible  | Disponible | Adaptée à VATSIM |
| Ouest Inversé (PGW)  | Disponible | Peu de données | Adaptée à VATSIM |
| Est Inversé (PGE)  | Disponible | Aucune données | Adaptée à VATSIM |

# Eléments Euroscope

+ **GEO**<br><br>
	&nbsp;<ins>LE BOURGET</ins>
	+ LFPB Finale ILS **xx**
	
	&nbsp;<ins>CDG</ins>
	+ LFPG Contraintes Orly (**xx**)
	+ LFPG Contraintes Beauvais
	+ LFPG Delimitations **xx**
	+ LFPG Finale ILS **xxx**
	+ LFPG Point Merge KOLIV
	+ LFPG Restriction Survol Villepinte
	+ LFPG Trajectoires **xx**
	+ LFPG Zone Paris P 23
	
	&nbsp;<ins>TOUSSUS</ins>
	+ LFPN Finale ILS 25R
	+ LFPN Finale RNP 07L
	+ LFPN Finale VOR 07L
	
	&nbsp;<ins>ORLY</ins>
	+ LFPO Delimitations WL
	+ LFPO Finale ILS **xx**
	+ LFPO Limites EGA
	+ LFPO Trajectoires **xx**
	+ LFPO VPE Departs **07 / 24**
	+ LFPO VPE ILS **06 / 25**
	
	&nbsp;<ins>VILLACOUBLAY</ins>
	+ LFPV Finale ILS **xx**<br><br>

+ **REGIONS**
	+ LFPG VPE Departs **08 / 09 / 26 / 27**
	+ LFPG VPE ILS **08R / 09L / 26L / 27R**
	+ LFPO VPE Departs **07 / 24**
	+ LFPO VPE ILS **06 / 25**<br><br>

+ **ARTCC boundary**
	+ TMA LFPG TMA Paris (Toutes Config)
	+ TMA LFPG TMA Paris (Config **xx**)
	+ TMA LFPG Zone Beauvais
	+ TMA LFPO Delimitations WL
	+ TMA LFPO TMA Paris<br><br>

+ **ARTCC low boundary**
	+ Tower CTR LFPG CTR Paris<br>

# Captures d'écran

De Gaulle APP config EI :
![De Gaulle APP (EI)](https://user-images.githubusercontent.com/85018190/184678262-e7921820-a069-4054-b04a-d6d0aac46eaa.jpg)

De Gaulle APP config EL :
![De Gaulle APP (EL)](https://user-images.githubusercontent.com/85018190/184678278-3a95f852-e274-4d36-b554-3fe74266802c.jpg)

De Gaulle APP config WI :
![De Gaulle APP (WI)](https://user-images.githubusercontent.com/85018190/184678393-22726860-88b2-4372-8635-d22f870e5cf5.jpg)

De Gaulle APP config WL :
![De Gaulle APP (WL)](https://user-images.githubusercontent.com/85018190/184678414-777d5f06-1f7c-42f5-8979-8f4a34b3bfd4.jpg)

Orly APP config EI :
![Orly APP (EI)](https://user-images.githubusercontent.com/85018190/184678423-5f77cf17-7bce-45de-be88-4c1754a9ce89.jpg)

Orly APP config EL :
![Orly APP (EL)](https://user-images.githubusercontent.com/85018190/184678429-05d5a2af-ff7a-47fe-82f5-295fbfc50b8d.jpg)

Orly APP config WI :
![Orly APP (WI)](https://user-images.githubusercontent.com/85018190/184678436-36026714-90ac-4cfd-b692-c3dd4ca0e901.jpg)

Orly APP config WL :
![Orly APP (WL)](https://user-images.githubusercontent.com/85018190/184678446-a90da582-169c-40c4-b573-022a0aeed1fc.jpg)

# TODO

+ Finales Beauvais
+ Finales Orly ILS 02 & RNP 20

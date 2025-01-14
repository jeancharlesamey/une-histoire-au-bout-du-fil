# Boite à histoires "Socotel S63"

![image](https://user-images.githubusercontent.com/1282106/144014466-de22c6db-30d0-470b-b444-1885433b99f5.png)

(source : [x0r.fr](https://x0r.fr/blog/53) )

# Schema du circuit

![This is an image](./Breadboard_S63.png)

La masse de l'interrupteur de décrochage est partagée avec celle du cadran rotatif, un seul fil est donc nécessaire pour indiquer l'état (la masse est représentée sur le schéma mais on utilise ici les connexions déja présentes sur le circuit du téléphone).

# Matériel à rassembler
- Un [Arduino Nano](https://www.gotronic.fr/art-carte-arduino-nano-12422.htm) (mais vous pouvez utiliser d'autres modèles sans problème, selon votre boitier)
- Un [DFPlayer Mini](https://www.gotronic.fr/art-module-mp3-dfr0299-22404.htm)
- Une résistance de 1kΩ

# Code Arduino
On utilise ici deux bibliothèques non natives :
- [*DFRobotDFPlayerMini*](https://github.com/DFRobot/DFRobotDFPlayerMini) (installable via le gestionnaire de bibliothèques)
- [*RotaryDial*](https://github.com/markfickett/Rotary-Dial), (téléchargeable sur Github et installable au format ZIP)

Le [code source](./Boite_a_histoires_S63.ino) est abondamment commenté en français.

# Etiquette du cadran
Celle-ci est constituée d'un disque de 51mm de diamètre, et la police utilisée semble être du Univers Condensed Medium avec en 7.5pt un crénage de 46 (merci à [Jean-François Porchez](https://typofonderie.com) pour la suggestion de la police Univers)

![image](https://user-images.githubusercontent.com/1282106/144504833-abf780c6-383c-48c3-8791-4e733949bcb3.png)


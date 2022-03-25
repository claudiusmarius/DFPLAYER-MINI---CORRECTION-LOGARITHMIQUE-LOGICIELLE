# DFPLAYER-MINI---CORRECTION-LOGARITHMIQUE-LOGICIELLE
J'ai réalisé cette petite présentation conformément à ce que je vous avais annoncé dans la vidéo précédente :
BOITE A MUSIQUE - ARDUINO - DFPLAYER - MP3 : https://youtu.be/qnj8aLqI1N4
Il s'agit de faire une correction logicielle (logarithmique) pour adapter le signal de volume à la courbe de réponse de l'oreille humaine.
Première partie démonstrative de la possibilité de réalisation (tracé de la courbe)
Deuxième partie démonstrative par un montage sur breadboard pour comparaison avec ou sans correction
Troisième partie : présentation du code de la deuxième partie.
Les codes sont compatibles sur les MCU suivants :
Arduino UNO
Arduino NANO
Seeeduino XIAO
ATtiny84 et 85, ces 2MCU ne conviennent pas pour la première partie, car ils ne possèdent pas de liaison série pour communiquer avec le serial monitor
ESP32 pour la première partie, le code n'a pas été adapté pour la deuxième partie.

# arduino-l293-motor-speed-control
# Contrôle de Vitesse de Moteur DC avec Driver L293 et Arduino

Ce projet Arduino permet de contrôler la vitesse d'un moteur à courant continu (DC) en utilisant un driver L293. Le code Arduino utilise les broches PWM pour ajuster progressivement la vitesse du moteur, en accélérant d'abord de zéro à la vitesse maximale, puis en décélérant de la vitesse maximale à zéro. Le driver L293 permet de gérer la direction et la puissance du moteur.

## Composants nécessaires
- Arduino Uno (ou autre compatible)
- Driver de moteur L293D
- Moteur à courant continu (DC)
- Fils de connexion
- Source d'alimentation externe pour le moteur (si nécessaire)

## Connexions
- **EN** (Enable) du moteur connecté à la broche 9 de l'Arduino
- **IN1** du moteur connecté à la broche 11 de l'Arduino
- **IN2** du moteur connecté à la broche 12 de l'Arduino

## Fonctionnalités
- Contrôle de la vitesse du moteur à l'aide de la modulation de largeur d'impulsion (PWM)
- Accélération progressive du moteur de 0 à la vitesse maximale
- Décélération progressive du moteur de la vitesse maximale à 0
- Arrêt complet du moteur à l'état initial

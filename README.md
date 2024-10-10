# Projet de Bureau d'Études II : Relais d'Accessoires

Ce projet, réalisé dans le cadre du **Bureau d'Études II** à l'ENSAM Meknès (2022/2023), porte sur l'étude d'un relais d'accessoires pour un réacteur d'avion. L'objectif est de concevoir une solution cinématique qui permet de transmettre la puissance et la vitesse nécessaires au démarrage et au fonctionnement des accessoires d'un réacteur.

## Objectifs du Projet

L'objectif principal est de concevoir un **relais d'accessoires** capable d'assurer deux fonctions techniques majeures :
1. **Démarrage du réacteur** via un démarreur externe à air comprimé.
2. **Transmission de puissance** aux accessoires du réacteur (génératrice électrique et pompes hydrauliques).

### Contraintes
- **Sécurité** : Dimensionnement des sections à casser pour éviter les dégâts en cas de rupture d'arbre, avec un dispositif de maintien en place des pièces cassées.
- **Lubrification** : Carter sec, sans engrenages barbotant dans l'huile pour améliorer la durée de vie et le rendement.
- **Caractéristiques techniques** : Durée de vie des engrenages de 4000 heures, et des roulements de 2000 heures.
- **Température de fonctionnement** : -60°C à +125°C.
- **Matériaux** : Pignons en acier trempé, cémenté ou nitruré, carter en alliage léger.

## Étapes de Réalisation

### 1. Analyse du Cahier des Charges
- Identification des besoins du système de démarrage et de fonctionnement des accessoires.
- Contrainte de **légèreté** et de **rapidité** pour les avions de chasse.

### 2. Étude de la Cinématique
- **Architecture retenue** : Définir la position relative des axes du réacteur, démarreur et accessoires, avec une minimisation de l'encombrement.
- **Prédimensionnement des engrenages** : Calculs des dimensions des pignons avec une tolérance de ±1% pour respecter les vitesses de rotation.

### 3. Conception Mécanique
- **Débrayage automatique du démarreur** à un quart de la vitesse nominale du réacteur.
- **Sélection des matériaux** pour les pignons et le carter afin d'assurer robustesse et légèreté.
- **Vérification mécanique** : Calculs pour garantir la tenue des éléments critiques sous contrainte.

## Caractéristiques Techniques
| Composant     | Vitesse de Rotation | Sens de Rotation | Puissance Max |
| ------------- | ------------------- | ---------------- | ------------- |
| Réacteur      | 9000 tr/min          | +                |               |
| Génératrice   | 25750 tr/min         | -                | 45 kW         |
| Démarreur     | 19080 tr/min         | -                | 125 kW        |
| Pompe 1       | 3750 tr/min          | +                | 62 kW         |
| Pompe 2       | 5800 tr/min          | +                | 55 kW         |

## Dossier de Conception
Le dossier d'étude comprendra :
- **Schémas cinématiques** : Définissant la relation entre les composants.
- **Calculs mécaniques** : Dimensionnement des pignons et vérifications des vitesses et puissances.
- **Dessin technique** : Plans détaillés du relais d'accessoires et des composants internes.


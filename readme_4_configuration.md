# Configuration

## Audio
Si vous utilisez une carte Audio USB, il faut la configurer à 48Khz (et surtout pas 44khz)

## Réseau
Si vous utilisez un cable Ethernet (fortement conseillé), il faut couper le WIFI de l'ordinateur, et vérifier via un Browser que vous avez bien accès à Internet via le cable

## Jamulus

Une fois Jamulus lancé, il faut:
1. ouvrir la fenêtre "My Profile" et renseigner son nom 
1. ouvrir la fenêtre "settings" et 
    1. définir le buffer delay à 10.67
    1. placer le Jitter Buffer en Auto (ou bien monter les curseurs à la main un peu plus haut que la position atteinte en auto)
    1. Audio channels sur Mono
    1. Audio quality sur Normal
1. Quitter et redémarrer Jamulus, sinon le Buffer Delay pourrait ne pas être bien défini

Dans l'écran principal de Jamulus (Noir), mettre la Reverb à zero.

Ensuite lier Jamulus aux bonnes entrées et Sortie (la partie délicate):
1. Si une interface audio est utilisée, la sélectionner dans la liste
2. si on travaille avec le micro intégré, le choisir dans la liste

Sur PC, il peut être nécessaire de cliquer sur ASIO en bas à gauche de l'écran Settings, et choisir ses entrées et sorties.

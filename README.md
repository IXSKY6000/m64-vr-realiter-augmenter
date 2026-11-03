# Mario dans ma pièce — Quest 3 — v0.2.0

[Télécharger l’APK](https://github.com/IXSKY6000/m64-vr-realiter-augmenter/raw/refs/heads/apk-download-v0.2.0/MarioRoom-Quest3.apk)

Installation / mise à jour avec SideQuest ou `adb install -r MarioRoom-Quest3.apk`.
Même identifiant et même signature que la v0.1.0 : aucune désinstallation nécessaire.
[Instructions et commandes](INSTALLATION.txt).

- Mode officiel Meta MR sans limite (BOUNDARYLESS_APP).
- Plus de lancement automatique de la configuration de pièce.
- Déplacements, actions et animations avec le moteur libsm64 original à 30 Hz.
- Occlusion temps réel par la profondeur du Quest, mains incluses ; réglable au menu.
- 10 contrôles de simulation et comparaison de 150 ticks avec les appels C directs
  de libsm64 passés (positions, actions, animations, sommets).
- Signature, ARM64, contenu et alignement Android vérifiés.

Le mode sans limite et la profondeur réelle restent à vérifier sur un Quest 3 avec
Horizon OS à jour. Le système conserve le contrôle de ses écrans de configuration.
L’occlusion ne constitue pas une collision physique : pas de détection des coups
de pied réels. Aucun générateur de niveau, Goomba ou étoile ajouté dans cette version.

Ressources de Mario extraites de la ROM fournie par le propriétaire du dépôt ;
la ROM complète n’est pas distribuée. Mario et les ressources appartiennent à
Nintendo. Prototype personnel non affilié à Nintendo ou Meta.

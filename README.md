# Thronefall Archipelago — installation joueur

Serveur : `wss://archipelago.pozox.fr:443`

## Pour le joueur

1. Installez Archipelago 0.6.8.
2. Installez `thronefall.apworld` (double-clic ou copie dans `custom_worlds`). Redémarrez le Launcher Archipelago si besoin.
3. Copiez `ThronefallArchipelagoMetrics.dll` dans `BepInEx/plugins/ThronefallArchipelagoMetrics/`.
4. Dans le Launcher Archipelago, ouvrez **Thronefall Client**. Entrez l'adresse du serveur, puis votre nom de slot lorsqu'il le demande.
5. Lancez Thronefall.

Le client crée automatiquement un profil AP local portant le nom de slot défini par le YAML (par exemple `Alice`). Il est propre à cet ordinateur, se réinitialise lorsqu'une nouvelle seed est rejointe et ne modifie jamais la sauvegarde vanilla. Lancez le client avant le jeu afin qu'il choisisse ce profil.

Le mod affiche en haut à gauche les couronnes, checks, arme progressive et le niveau actuel des mobs. Les ennemis commencent à `+80 %` PV/dégâts ; chaque objet `Progressive Enemy Weakening` retire `10 %`, jusqu'à `-40 %`.

# All-of-World-of-Warcraft-Vanilla
Contient un lien vers le client World of Warcraft Vanilla, la realmlist de World of Mamene, la liste des bons addons, les configurations graphiques optimales, des textures HD, les guides pratiques et les explications pour monter son serveur.

## Le client World of Warcraft
1.  Télécharger le client du jeu en anglais est plus pratique pour la compatibilité avec les addons [ici](https://pydio.dedikam.com/public/b2c756)
2.  Renommer le dossier téléchargé par "World of Warcraft"
3.  Déplacer ce dossier dans votre dossier "Program Files (x86)" comme ceci "C:\Program Files (x86)\World of Warcraft"  

## Serveur
1.  Vous inscrire sur un serveur privé
2.  Télécharger la realmlist du serveur et remplacer celle déjà existante dans votre dossier de jeu : "C:\Program Files (x86)\World of Warcraft"

## Reshade : les effets spéciales
Pour rendre votre jeu plus beau avec des effets utiliser Reshade  : https://reshade.me/
Vous devez installer la librairie pour OpenGL et ensuite sélectionner les effets à installer. Perso j'utilise seulement trois effets suivant : 
- FakeHDR régler à 1 ou à 1,500 en fonction de votre config
- Lumasharpen
- Vibrance

## Configurations : les graphismes mamene
Optimisations des graphismes du jeu (à faire en dernier après la configuration des réglages in Game) :
*source : https://forum.nostalrius.org/viewtopic.php?f=32&t=1100

1.  Aller dans le dossier "WTF" de World of Warcraft  se trouvant ici "C:\Program Files (x86)\World of Warcraft\WTF" ou si le dossier n'éxiste pas, créer un raccourci de votre wow.exe et faite clique droit -> raccourci -> cible et rajouter un " -console" à la fin de la cible. Ensuite lancer le raccourci et passer votre clavier en ENG et appuyer sur la touche "²" de votre clavier située à gauche de "&" ou "1" en haut de votre clavier.
2.  Modifier le fichier "Config.wtf" avec ces infos ou utiliser la console et ajouter l'intégralité de ces lignes une par une et en une fois en étant connecté sur votre personnage  : 
    - anisotropic 16
    - baseMip 0
    - detailDoodadAlpha 100
    - DistCull 888
    - doodadAnim 1
    - farclip 777
    - ffx 1
    - ffxDeath 1
    - ffxGlow 1
    - ffxRectangle 1 
    - footstepBias 1.0
    - frillDensity 256
    - gxColorBits 24
    - gxDepthBits 24
    - horizonfarclip 2112
    - lod 0
    - lodDist 250
    - mapObjLightLOD 2
    - mapObjOverbright 1
    - mapShadows 1
    - MaxLights 4
    - maxLOD 3
    - nearClip 0.33
    - occlusion 1
    - particleDensity 1
    - pixelShaders 1
    - shadowLevel 0
    - showfootprints 1
    - showLowDetail 0
    - showShadow 1
    - showSimpleDoodads 0
    - SkyCloudLOD 1
    - SkySunGlare 1
    - SmallCull 0.01
    - specular 1
    - spellEffectLevel 2
    - texLodBias -1
    - textureLodDist 777
    - trilinear 1
    - unitDrawDist 300
    - waterLOD 0
    - waterParticulates 1
    - waterRipples 1
    - waterSpecular 1
    - waterWaves 1
    - weatherDensity 3
    - gxMultisample 8 (1 is no anti-alising, 2 is 2x, 4 is 4x, 8 is 8x)
    - gxMultisampleQuality 1
    - gxResolution <your monitor's native resolution> e.g. gxResolution 1920x1080
    - showCull (re-enter this command until the output in the console says "Terrain culling disabled")
    - Enter the command gxrestart to reinitialize the graphics engine and apply the changes.
3.  Maximum smoothness :
    - bspcache 1
    - gxTripleBuffer 1
    - gxVSync 1
    - M2UsePixelShaders 1
    - M2UseZFill 1
    - M2UseClipPlanes 1
    - M2UseThreads 1
    - M2UseShaders 1
    - M2BatchDoodads 1
    - gxFixLag 1 (fixes mouse lag at expense of frames per second)
    - timingModeOverride 1 (uses GetTickCount) 2 (uses RDTSC) 3 (uses QueryPerformanceCounter) 4 (uses timeGetTime). Experiment with which timing method gives you the smoothest gameplay. Set the value, then restart the game completely. Apparently RDTSC is the most precise timing method.
    - gxRefresh <your monitor's maximum refresh rate> e.g. gxRefresh 60 (for 60hz monitor)
    - M2Faster <CPU physical cores - 1> (Dual-core = 1, Tri-core = 2, Quad-core and above = 3)
    - Enter the command gxrestart to reinitialize the graphics engine and apply the changes.

## HD textures
- Source : http://model-changing.net/blogs/blog/65-release-improved-models-for-112/
- Normalement pas de problème majeur avec les textures HD simplement le jeu ne supporte pas les déconnexions et reconnexions rapides et vous pouvez avoir un message d'erreur de WoW.


## Addons
Les addons servent à modifier votre interface de WoW, pour cela allez dans votre dossier de jeu : "C:\Program Files (x86)\World of Warcraft\Interface\AddOns" et placer y les addons que vous aurez téléchargé :

- Je vous conseil l'interface de Frostadamus : https://www.youtube.com/watch?v=29S283Ak2iQ
- En All in one "pfui", complet mais pas très sexy dans le sens ou ça vient vraiment casser l'univers graphique de WoW, par contre y'a tous les addons et le mec qui les développe est un génie : https://shagu.org/
- Et sinon la liste des addons compatiblent Vanilla si vous êtes du genre full custom : https://legacy-wow.com/Vanilla-addons/

## Guides : HELP ! c'est ou ? c'est quoi ? c'est comment ?
- Le Guide du fast farmer chinois 1 to 60 en 4 jours mamene  : https://www.joanasworld.com/
- Les métiers dans WoW : https://forums.jeuxonline.info/showthread.php?t=443002
- Talent Calculator : https://classicdb.ch/?talent#L

## Serveur local
1.  Télécharger le serveur WoW Vanilla si le lien est mort c'est qu'il y a eu une MAJ dans ce cas référez-vous à la source : https://www.mediafire.com/file/ypud7vgvcppgads/Vanilla+bropack+v13.rar
2. Extraire là ou vous voulez, exemple de chez moi à la racine de mon disque SSD "C:"
3. Démarrer le serveur :
    1. Lancer le fichier batch "Start apache.bat"
    2. Lancer le fichier batch "Start MySQL.bat"
    3. Démarrage du monde "realmd.exe"
    4. Démarrage du serveur "mangosd.exe"

- Par défaut vous pouvez vous connectez au serveur avec ces identifiants : admin/admin
Ou vous pouvez vous créer un nouveau compte admin dans la console mangosd.exe comme ceci : 
account create <name> <password>
account set gmlevel <name> 6
- Il vous faudra ensuite changer la realmlist de votre jeu par : 127.0.0.1 pour vous connecter à votre serveur WoW Vanilla en local.
- Vous pouvez accéder à votre base de donner avec un logiciel de gestion de base comme HeidiSQL ou autre avec les identifiants suivants : root/root

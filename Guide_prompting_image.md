# Guide de Formation : L'Art de Prompter des Images

---

## Introduction : Le Réflexe Initial

> **« La première chose à faire quand on ouvre une conversation pour une image, c'est laisser cette conversation de côté et ouvrir un nouveau document pour planifier. »**

Pourquoi ce réflexe est-il crucial ? Parce que la barre de discussion d'une IA générative (Midjourney, DALL-E, Flux, Stable Diffusion, ChatGPT, etc.) vous pousse à l'impulsivité. Or, prompter à la volée, c'est laisser l'IA décider à votre place. Pour obtenir exactement ce que vous avez en tête, vous devez passer du rôle de *spectateur* à celui d'*architecte*.

---

## L'Analogie du Mouton de Minecraft

Pour comprendre comment fonctionne une IA génératrice d'images, imaginez que votre idée de départ est un **mouton dans Minecraft** que vous faites apparaître au milieu d'une immense plaine.

### Scénario 1 : Le Mouton en Liberté (Le Prompt Vague)
Si vous posez votre mouton dans un champ sans construire la moindre clôture autour de lui (ex. : vous tapez simplement *"Un guerrier dans une forêt"*), que va-t-il faire ? 
Il va s'engouffrer dans la première brèche et s'enfuir vers la **zone extérieure**. Dans le monde de l'IA, cette zone extérieure correspond au **bruit statistique moyen** : le contenu le plus standard, générique, lisse et basique que l'IA puisse fournir.

```text
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   ZONE EXTÉRIEURE : Contenu Générique, Basique, Lisse et Cliché (Défaut IA)
   
                         ^                       ^
                         |     (S'échappe !)     |
                    <----+---   [ 🐑 Mouton ]   ---+---->
                         |  (Idée sans barrière) |
                         v                       v
                         
   ZONE EXTÉRIEURE : Éclairage plat, Cadrage centré banal, Style aléatoire
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```

### Scénario 2 : Le Mouton Encadré (Le Prompt Maîtrisé)
Maintenant, imaginez que vous entouriez ce mouton de toutes les **barrières nécessaires**. Chaque barrière porte un nom : *Style, Éclairage, Type de plan, Décor, Objets, Position, Expression...* 

En construisant cet enclos, vous empêchez l'IA de fuir vers ses travers génériques. Le mouton (votre génération) est obligé de rester exactement à l'endroit précis où vous voulez qu'il soit.

```text
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   ZONE EXTÉRIEURE (Bruit statistique bloqué par vos barrières)
   
         +====================== [ 1. STYLE ] ======================+
         |                                                          |
   [ 6. ÉCLAIRAGE ]                                        [ 5. TYPE DE PLAN ]
         |                                                          |
         |                      [ 🐑 Mouton ]                       |
         |               (Votre image sur-mesure,                   |
   [ 4. DÉCOR ]             exactement là où                        [ 2. OBJETS ]
         |                  vous la voulez)                         |
         |                                                          |
   [ 7. COULEURS ]                                         [ 3. EXPRESSION ]
         |                                                          |
         +===================== [ 3. POSITION ] ====================+
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```

---

## La Hiérarchie de l'Attention : Le Poids et l'Ordre des Mots

Avant même de lister vos barrières, il faut comprendre une règle mécanique fondamentale des moteurs de génération d'images : **tous les mots d'un prompt n'ont pas la même valeur.**

Les modèles d'IA lisent votre texte de gauche à droite (ou de haut en bas) et accordent un **poids d'attention dégressif** aux informations. Ce qui est placé au tout début reçoit la majorité de la puissance de calcul et structure toute la toile de fond de l'image.

```text
  [ DÉBUT DU PROMPT ] =================================> [ FIN DU PROMPT ]
   Poids : MAXIMUM (Fondations)                           Poids : FAIBLE (Détails)
   Médium, Style, Sujet, Action                           Textures, Finitions, Exclusions
```

### Les 3 règles d'or de la hiérarchie :

1. **Les fondations en premier :** Si vous demandez *"Un chevalier en armure dans une forêt sombre, avec une épée rouillée, de la pluie, des feuilles mortes au sol, sous forme d'aquarelle minimaliste"*, l'IA aura déjà construit une image photoréaliste lourde dans sa "tête" avant même d'arriver au mot *"aquarelle"* tout à la fin. Le style et le sujet principal doivent toujours ouvrir la marche.
2. **Au sein d'une même catégorie, mettez l'élément majeur en tête :** Dans la section Décor, écrivez d'abord *"Cathédrale gothique en ruine"* avant de lister *"des bougies éteintes sur le sol et du lierre sur les colonnes"*.
3. **Évitez la dilution par le bavardage :** Des formules comme *"J'aimerais beaucoup que tu me dessines une très belle image qui représente..."* gaspillent le poids maximal du début de votre prompt sur des mots vides de sens visuel. Allez droit au but.

*(C'est exactement pour respecter cette mécanique d'attention que notre Checklist plus bas est numérotée dans cet ordre précis : du Médium jusqu'aux Finitions).*

---

## Prendre le Contrôle Absolu : Répertoire Exhaustif et Ressources

> **« Un prompting efficace passe par la spécification de tous les éléments sur lesquels on possède un CONTRÔLE. »**

Chaque mot que vous n'écrivez pas est une décision que vous déléguez à la machine. Vous trouverez ci-dessous l'inventaire complet des barrières à votre disposition, des listes de pistes pour vous inspirer, ainsi que des liens vers des guides visuels de référence.

---

### 1. Le Médium et le Style Artistique (Le "Comment")

C'est la barrière la plus structurante : elle définit la matière même de votre image.

*   **Photographie et Pellicules :** Photographie numérique (DSLR, 8k, ultra-réaliste), Photographie argentique (35mm, 120mm moyen format), Polaroid instantané, Daguerréotype (photo très ancienne sur plaque), Cyanotype (monochrome bleu), Photo infrarouge, Lomographie, Pellicules spécifiques (Kodak Portra 400 pour les portraits doux, Fujifilm Velvia pour les paysages saturés, Kodak Tri-X 400 pour le noir et blanc granuleux, CineStill 800T pour les ambiances nocturnes néon).
*   **Peinture et Beaux-Arts :** Peinture à l'huile (empâtement / impasto, coups de pinceau visibles), Aquarelle (humide sur humide, lavis transparent), Gouache (opaque et mat), Peinture acrylique, Fresque murale antique, Tempera, Peinture à l'encre de Chine (Sumi-e).
*   **Dessin et Illustration :** Croquis au crayon graphite (hachures, estompe), Dessin au fusain, Esquisse à l'encre et à la plume, Pastel sec ou gras, Craie sur tableau noir, Gravure sur bois (Linocut / Woodcut), Eau-forte (Etching), Illustration au feutre à alcool (style Copic), Bande dessinée franco-belge (Ligne claire), Comics américain (encrage lourd, trames demi-teintes), Manga (trames, lignes de vitesse), Roman graphique, Storyboard, Dessin technique (Blueprint), Enluminure médiévale.
*   **3D, Digital et Graphisme :** Rendu 3D (Octane Render, Unreal Engine 5, Blender, V-Ray, ZBrush), Low-poly (polygones visibles), Voxel Art (style cubique), Pixel Art (8-bit, 16-bit), Illustration vectorielle (Flat design, Corporate Memphis), Art isométrique, Collage numérique, Matte painting, Synthwave / Retrowave, Vaporwave.
*   **Artisanat, Volume et Matières :** Sculpture (marbre de Carrare, bronze patiné, bois flotté, argile / terre cuite, glace), Origami et Kirigami, Paper cut-out (découpage de papier en couches avec ombres portées), Stop-motion (pâte à modeler / Claymation style Aardman, feutrine), Vitrail (Stained glass), Mosaïque byzantine, Tapisserie et Broderie, Crochet (Amigurumi), Pyrogravure, Art en verre soufflé.
*   **Mouvements Artistiques et Esthétiques :** Renaissance, Baroque, Rococo, Romantisme, Impressionnisme, Pointillisme, Art Nouveau (style Alphonse Mucha), Art Déco, Cubisme, Surréalisme, Expressionnisme allemand, Pop Art, Brutalisme, Minimalisme, Cyberpunk, Steampunk, Solarpunk, Biopunk, Dieselpunk, Dark Fantasy, Ukiyo-e (estampe japonaise).

**Ressources et guides illustrés sur le web :**
*   [Midlibrary - Encyclopédie visuelle des styles et mouvements artistiques pour l'IA](https://midlibrary.io/)
*   [Google Arts & Culture - Explorer les mouvements artistiques en images](https://artsandculture.google.com/category/art-movement)
*   [Tate Museum - Glossaire illustré des termes et techniques artistiques](https://www.tate.org.uk/art/art-terms)

---

### 2. Le Sujet Principal et les Objets (Le "Qui" ou "Quoi")

Ne nommez pas simplement votre sujet : sculptez-le avec des adjectifs précis.

*   **Nature et Démographie (Humains) :** Âge précis (enfant de 8 ans, quarantenaire, vieillard centenaire), genre, ethnie, morphologie (athlétique, frêle, trapu, élancé, corpulent).
*   **Détails du visage et de la peau :** Taches de rousseur, rides d'expression profondes, cicatrices, grain de peau naturel (pores visibles), peau diaphane, peau burinée par le soleil, tatouages tribaux ou cybernétiques, maquillage (tribal, haute couture, clownesque, gouttes de sueur, cambouis).
*   **Coiffure et Pilosité :** Cheveux ébouriffés par le vent, tresses africaines, chignon strict, crâne rasé, cheveux blancs filasse, barbe drue de trois jours, moustache cirée.
*   **Garde-robe, Époque et Tissus :** Style vestimentaire (victorien, streetwear, haute couture, haillons post-apocalyptiques, armure de plates gothique, combinaison spatiale élimée).
*   **Matériaux et états de surface (Crucial pour les objets et vêtements) :** Cuir craquelé, velours côtelé, soie irisée, lin froissé, denim délavé, laine épaisse, latex brillant, métal brossé, acier rouillé, laiton oxydé (vert-de-gris), chrome réfléchissant, bois calciné, porcelaine fissurée (Kintsugi), verre dépoli, pierre moussue, plastique translucide.

**Ressources et guides illustrés sur le web :**
*   [Fashion History Timeline (FIT) - Guide visuel de l'histoire du costume par époque](https://fashionhistory.fitnyc.edu/)
*   [AmbientCG - Catalogue visuel de centaines de matériaux et textures physiques](https://ambientcg.com/)

---

### 3. L'Action, la Position et l'Expression (La "Vie")

Si vous ne précisez pas l'action, votre sujet posera de manière figée comme pour une photo de passeport.

*   **Positions Statiques :** Assis en tailleur, avachi dans un fauteuil, adossé nonchalamment contre un mur, debout les bras croisés, à genoux, recroquevillé en position fœtale, en garde (posture de combat), campé sur ses deux jambes, en lévitation, penché en avant.
*   **Actions Dynamiques :** En plein saut (figé en l'air), en train de sprinter, esquivant un coup, dansant avec grâce, tombant à la renverse, escaladant une paroi, lançant un objet, pointant du doigt vers l'objectif.
*   **Interactions fines :** Réparant un mécanisme minuscule, lisant un parchemin à la loupe, buvant une tasse fumante, serrant une épée à deux mains, caressant un animal, écrivant frénétiquement.
*   **Expressions Faciales :** Sourire serein, rire aux éclats, colère froide (mâchoire serrée, sourcils froncés), terreur pure (yeux écarquillés), mélancolie, regard vide et épuisé, concentration intense, surprise, dédain, malice (sourire en coin), pleurs.
*   **Direction du Regard :** Regardant droit dans l'objectif (contact visuel direct), regardant hors-champ (vers la gauche/droite), levant les yeux au ciel, regard baissé vers le sol, fixant un objet dans sa main, regardant par-dessus son épaule.

**Ressources et guides illustrés sur le web :**
*   [Pose Library - Guide illustré sur les lignes d'action et le dynamisme des postures](https://poselibrary.com/line-of-action-examples)
*   [Line of Action - Références photographiques de postures et d'expressions humaines](https://line-of-action.com/)

---

### 4. L'Environnement, le Décor et l'Époque (Le "Où" et "Quand")

Le décor raconte l'histoire de votre sujet sans avoir besoin de mots.

*   **Lieux Intérieurs :** Laboratoire clandestin, bibliothèque victorienne poussiéreuse, cockpit de vaisseau spatial, taverne médiévale enfumée, loft minimaliste en béton, serre botanique luxuriante, cathédrale gothique en ruine, atelier de mécanique encombré, station de métro abandonnée, cuisine de restaurant en plein coup de feu.
*   **Lieux Extérieurs :** Ruelle cyberpunk sous la pluie, forêt primaire brumeuse, désert de sel craquelé, toundra arctique, sommet montagneux escarpé, marché oriental bondé, plage de sable noir volcanique, marais putride, champ de bataille dévasté, jardin zen japonais, bidonville vertical.
*   **Styles Architecturaux :** Brutalisme (béton massif et géométrique), Gothique, Haussmannien, Art Déco, Architecture organique (courbes biomorphiques), Néo-futurisme, Architecture vernaculaire (bois, terre crue), Industriel (briques rouges et poutres métalliques rivetées).
*   **Époque / Temporalité :** Préhistoire, Antiquité gréco-romaine, Moyen Âge, Époque Édouardienne, Années folles (1920), Années 1950 (esthétique Diner américain), Années 1970 (tons orangés et motifs géométriques), Années 1980 (néons, salles d'arcade), Futur proche, Futur post-apocalyptique.
*   **Éléments de mise en scène (Props) :** *Premier plan (Foreground) :* feuillage flou, fumée, étincelles, barreaux de fenêtre. *Plan moyen (Midground) :* mobilier, outils, véhicules, végétation, débris. *Arrière-plan (Background) :* montagnes lointaines, ligne d'horizon urbaine (skyline), planètes dans le ciel, foule floue.

**Ressources et guides illustrés sur le web :**
*   [ArchDaily - Base de données photographique mondiale d'architecture et d'intérieurs](https://www.archdaily.com/)
*   [FilmGrab - La plus grande bibliothèque d'images de films pour étudier les décors et ambiances](https://film-grab.com/)

---

### 5. La Caméra, le Type de Plan et la Composition (L'Œil du Réalisateur)

C'est ici que vous choisissez où placer le spectateur par rapport à la scène.

*   **Échelle de Plans (Shot Sizes) :**
    *   *Extreme Wide Shot (EWS) / Plan très large :* Le décor domine totalement, le sujet est minuscule.
    *   *Wide Shot (WS) / Plan large (ou Plan d'ensemble) :* Le sujet est visible de la tête aux pieds, bien intégré dans son décor.
    *   *Full Shot (FS) / Plan pied :* Le sujet remplit le cadre de la tête aux pieds.
    *   *Medium Wide Shot (MWS) / Plan américain (Cowboy Shot) :* Cadré à mi-cuisses ou aux genoux.
    *   *Medium Shot (MS) / Plan moyen (Plan taille) :* Cadré à la ceinture, idéal pour le langage corporel et le visage.
    *   *Medium Close-Up (MCU) / Plan rapproché poitrine :* Cadré sous les épaules, met l'accent sur l'émotion tout en gardant un peu d'espace.
    *   *Close-Up (CU) / Gros plan :* Le visage (ou l'objet) remplit entièrement le cadre.
    *   *Extreme Close-Up (ECU) / Très gros plan (Insert) :* Détail infime (un œil, des lèvres, le mécanisme d'une montre).
*   **Angles de Prise de Vue (Camera Angles) :**
    *   *Eye-Level (Niveau des yeux) :* Angle neutre, naturel et immersif.
    *   *Low Angle (Contre-plongée) :* Caméra placée bas qui regarde vers le haut. Rend le sujet puissant, héroïque ou menaçant.
    *   *High Angle (Plongée) :* Caméra placée haut qui regarde vers le bas. Écrase le sujet, le rend vulnérable ou isolé.
    *   *Bird's-Eye View / Overhead Shot (Vue zénithale / Vue à 90° du dessus) :* Vue directement à la verticale, façon drone ou satellite.
    *   *Worm's-Eye View / Ground Level (Vue au ras du sol) :* Caméra posée à même le sol, regardant vers le ciel.
    *   *Dutch Angle / Dutch Tilt (Angle hollandais) :* Caméra inclinée sur le côté, crée un sentiment de malaise, de folie ou de chaos dynamique.
    *   *Over-the-Shoulder (OTS / Amorçage) :* Pris par-dessus l'épaule d'un personnage de dos.
    *   *Point of View (POV / Vue subjective) :* On voit à travers les yeux du personnage (ex: on voit ses mains au premier plan).
*   **Objectifs et Focales (Lenses) :**
    *   *Fisheye (8mm) :* Déformation sphérique extrême, ultra grand-angle.
    *   *Ultra Grand-Angle (14mm - 24mm) :* Élargit l'espace, exagère les perspectives, idéal pour l'architecture et les paysages épiques.
    *   *Standard (35mm - 50mm) :* Proche de la vision humaine, polyvalent et naturel.
    *   *Téléobjectif / Portrait (85mm - 135mm - 200mm) :* Compresse les perspectives (rapproche l'arrière-plan du sujet), détache magnifiquement le sujet du fond.
    *   *Objectif Macro :* Pour photographier l'infiniment petit (insectes, gouttes d'eau) avec un grossissement extrême.
    *   *Tilt-Shift :* Effet maquette / miniature.
*   **Profondeur de Champ et Mise au Point (Focus & Depth of Field) :**
    *   *Shallow Depth of Field (Faible profondeur de champ, f/1.4, Bokeh) :* Sujet net, arrière-plan très flou et crémeux.
    *   *Deep Focus (Grande profondeur de champ, f/22) :* Tout est parfaitement net, du brin d'herbe à 10 cm jusqu'aux montagnes à l'horizon.
    *   *Motion Blur (Flou de mouvement) :* Sujet net mais décor filé par la vitesse (ou inversement).
*   **Règles de Composition :** Règle des tiers (Rule of thirds), Symétrie parfaite et centrage (style Wes Anderson), Lignes de fuite (Leading lines), Cadre dans le cadre (Frame within a frame : vu à travers une serrure, une fenêtre, entre deux arbres), Espace négatif (beaucoup de vide autour du sujet), Spirale d'or.

**Ressources et guides illustrés sur le web :**
*   [StudioBinder - Le guide visuel ultime des tailles de plans (Shot Sizes) avec exemples de films](https://www.studiobinder.com/blog/ultimate-guide-to-camera-shots/)
*   [StudioBinder - Le guide illustré de tous les angles de caméra au cinéma](https://www.studiobinder.com/blog/types-of-camera-shot-angles-in-film/)
*   [Nikon Lens Simulator - Simulateur interactif pour visualiser l'effet des focales (14mm à 800mm)](https://imaging.nikon.com/lineup/lens/simulator/)

---

### 6. L'Éclairage et la Météo (L'Atmosphère)

La lumière est ce qui transforme une image plate en une œuvre cinématographique.

*   **Sources de Lumière Naturelle :** Lumière directe du soleil de midi (ombres dures et courtes), Ciel voilé / Nuageux (Overcast : lumière très douce, sans ombres marquées, comme une boîte à lumière géante), Clair de lune, Lumière des étoiles, Feu de camp, Lave en fusion, Bioluminescence (plantes ou créatures qui brillent dans le noir), Éclairs d'orage.
*   **Moments de la Journée :**
    *   *Aube (Dawn) :* Lumière fraîche, rosée et brumeuse.
    *   *Golden Hour (Heure dorée, juste avant le coucher du soleil) :* Lumière rasante, chaude, dorée et magique.
    *   *Blue Hour (Heure bleue, juste après le coucher du soleil) :* Atmosphère crépusculaire bleu profond et froide.
    *   *Nuit noire (Pitch black) :* Obscurité totale percée uniquement par des sources ponctuelles.
*   **Sources de Lumière Artificielle :** Enseignes au néon, Lampadaire urbain (lumière orange au sodium), Ampoule au tungstène suspendue, Tubes fluorescents blafards (style hôpital ou parking), Lueur d'un écran d'ordinateur/smartphone sur le visage, Bougie, Phares de voiture dans la brume, Projecteur de scène (Spotlight), Guirlandes lumineuses (Fairy lights), Laser.
*   **Techniques d'Éclairage (Cinéma et Studio) :**
    *   *Chiaroscuro (Clair-obscur) :* Contraste extrême entre les zones éclairées et les ténèbres profondes (style Le Caravage ou Film Noir).
    *   *Rembrandt Lighting :* Éclairage de portrait caractérisé par un petit triangle de lumière sur la joue ombragée.
    *   *Rim Lighting / Backlighting (Contre-jour / Éclairage de contour) :* La lumière vient de derrière le sujet, dessinant un halo lumineux autour de sa silhouette.
    *   *Silhouette :* Sujet totalement noir devant un fond très lumineux.
    *   *Volumetric Lighting / God Rays (Rayons volumétriques / Rayons crépusculaires) :* Faisceaux de lumière visibles traversant la poussière, la fumée ou le feuillage.
    *   *High-Key Lighting :* Image très lumineuse, blanche, presque sans ombres (optimiste, épuré).
    *   *Low-Key Lighting :* Image globalement très sombre, dominée par les ombres (mystérieux, dramatique).
    *   *Subsurface Scattering (Diffusion sous-cutanée) :* La lumière traverse une matière semi-translucide (comme le soleil à travers une oreille, de la cire, du jade ou des feuilles).
*   **Météo et Particules Atmosphériques :** Pluie battante, Bruine légère (sol mouillé réfléchissant), Brouillard épais (Fog / Mist), Tempête de neige (Blizzard), Tempête de sable, Poussière en suspension dans l'air, Fumée épaisse, Vapeur d'eau, Braises et étincelles volantes, Pétales de fleurs ou feuilles mortes portés par le vent.

**Ressources et guides illustrés sur le web :**
*   [StudioBinder - Guide illustré des techniques d'éclairage au cinéma](https://www.studiobinder.com/camera-shots/lighting/)
*   [Digital Photography School - Les 6 schémas d'éclairage de portrait illustrés](https://digital-photography-school.com/6-portrait-lighting-patterns-every-photographer-should-know/)

---

### 7. La Colorimétrie et l'Ambiance (L'Émotion)

Les couleurs dictent immédiatement l'émotion ressentie par le spectateur avant même qu'il n'analyse le sujet.

*   **Harmonies de Couleurs :**
    *   *Monochrome :* Déclinaisons d'une seule et même couleur.
    *   *Noir et Blanc :* Fort contraste, gris doux, ou noir et blanc argentique.
    *   *Bichromie (Duotone) :* Utilisation de deux couleurs uniquement.
    *   *Couleurs Complémentaires :* Deux couleurs opposées sur le cercle chromatique (ex: le célèbre *Teal and Orange* / Bleu canard et Orange très utilisé au cinéma, ou Rouge et Vert).
    *   *Couleurs Analogues :* Couleurs voisines sur le cercle (ex: Jaune, Orange et Rouge pour une chaleur intense).
    *   *Triadique :* Trois couleurs équidistantes (ex: Magenta, Jaune, Cyan).
*   **Saturation et Température :**
    *   *Couleurs Pastel :* Douces, délavées, lumineuses (ambiance onirique ou enfantine).
    *   *Couleurs Désaturées / Muted / Bleached (Terne, blanchi) :* Couleurs presque absentes, ambiance froide, réaliste, triste ou militaire (ex: *Il faut sauver le soldat Ryan*).
    *   *Couleurs Vibrantes / Hyper-saturées / Néon :* Couleurs qui explosent à l'écran, psychédéliques ou pop.
    *   *Tons Chauds (Warm tones) :* Dominante d'or, d'ambre, d'ocre, de rouge et de marron (nostalgie, confort ou chaleur étouffante).
    *   *Tons Froids (Cool tones) :* Dominante de bleu acier, cyan, gris ardoise, vert émeraude (solitude, technologie, hiver, clinique).
    *   *Sépia / Vintage :* Teinte brunâtre vieillie.

**Ressources et guides illustrés sur le web :**
*   [Adobe Color - Roue chromatique interactive pour tester les harmonies (Complémentaire, Triade, Analogue)](https://color.adobe.com/create/color-wheel)
*   [Coolors - Générateur visuel de palettes de couleurs pour trouver des noms de teintes précis](https://coolors.co/palettes/trending)
*   [StudioBinder - Comment utiliser la couleur au cinéma (Théorie des couleurs illustrée)](https://www.studiobinder.com/blog/how-to-use-color-in-film-50-examples-of-movie-color-palettes/)

---

### 8. Le Format, la Technique et les Exclusions (La Finition)

*   **Ratio d'Aspect (Format du cadre) :**
    *   *1:1 (Carré) :* Format équilibré, style pochette d'album ou Polaroid.
    *   *16:9 (Écran large standard) :* Format vidéo, télévision, présentation paysage.
    *   *21:9 ou 2.39:1 (Cinémascope / Anamorphique) :* Format cinéma ultra-large, très immersif.
    *   *9:16 (Vertical) :* Format smartphone, affiche verticale.
    *   *4:3 ou 3:2 (Photographie classique) :* Format des appareils photo traditionnels et anciens téléviseurs.
*   **Effets de Texture et de Capteur :** Grain de pellicule prononcé (Film grain), Aberration chromatique (léger décalage des couleurs sur les bords), Lens flare (reflets optiques de la lumière dans l'objectif), Vignetting (bords de l'image assombris), Poussières et rayures (effet vieux film), Papier aquarelle texturé (Cold pressed paper), Toile de lin brute.
*   **Éléments à Exclure (Le Prompt Négatif) :** Ce que vous interdisez formellement à l'IA d'inclure (ex: *pas de texte, pas de filigrane, pas de flou, pas de couleurs vives, pas de bâtiments modernes en arrière-plan, pas de personnages secondaires*).

---

## Une Image Vaut Plus de 1000 Mots ! (L'Usage des Références Visuelles)

Parfois, même avec le meilleur vocabulaire du monde, il est difficile de décrire une posture exacte, un angle de caméra très spécifique ou une tombée de lumière subtile. 

> **N'oubliez pas que vous pouvez fournir bien plus que des mots à une IA pour arriver au résultat désiré.**

N'hésitez jamais à joindre une image de référence en remplacement (ou en complément) d'une ou plusieurs sections de votre checklist. **Même si votre image de référence n'a aucun rapport avec votre sujet final et ne contient qu'un seul des aspects que vous appréciez**, vous pouvez dire à l'IA d'extraire uniquement cette brique !

```text
   [ IMAGE FOURNIE À L'IA ]                 [ RESTE DE LA CHECKLIST TEXTE ]
   Une photo de vacances de vous            1. Style : Peinture à l'huile baroque
   accoudé à une table sous un      +       2. Sujet : Un vieux pirate squelette
   parasol, prise en contre-plongée.        4. Décor : Cabine de galion englouti
   
   Instruction : "Utilise uniquement        --> L'IA fusionne la géométrie/lumière
   l'angle, la posture et l'éclairage           de votre photo avec l'univers de
   global de cette image."                      votre checklist !
```

### Exemples de remplacements hybrides très efficaces :

*   **Déléguer l'éclairage et la couleur :** Joignez l'affiche d'un film que vous adorez et écrivez dans les sections 6 et 7 de votre checklist : *"Utilise strictement l'éclairage global et la palette colorimétrique de l'image jointe"*, puis remplissez le reste de la checklist normalement.
*   **Déléguer la posture et le cadrage :** Prenez-vous en photo avec votre téléphone (même mal coiffé dans votre salon) pour mimer une position précise des mains ou une inclinaison de la tête, et indiquez : *"Utilise cette photo comme référence pour l'angle de prise de vue et la posture exacte du personnage"*.
*   **Déléguer le style graphique :** Fournissez une illustration ou une texture et indiquez dans la section 1 : *"Reproduis exactement le style de coup de pinceau et le grain de cette image de référence"*.

---

## La Checklist de Génération (À fournir directement à l'IA)

> **Règle d'or :** Ne rédigez plus de longs paragraphes littéraires. Copiez-collez directement cette checklist remplie dans votre IA génératrice d'images (accompagnée éventuellement d'une image de référence). La structure par catégories est comprise nativement par les modèles récents et garantit que vous n'oubliez aucune barrière autour de votre mouton.

```markdown
Génère une image en respectant strictement la fiche de spécifications suivante :

1. [MÉDIUM & STYLE] : 
2. [SUJET PRINCIPAL, OBJETS & MATÉRIAUX] : 
3. [ACTION, POSITION & EXPRESSION] : 
4. [ENVIRONNEMENT, DÉCOR & ÉPOQUE] : 
5. [TYPE DE PLAN, ANGLE & OBJECTIF] : 
6. [ÉCLAIRAGE & MÉTÉO] : 
7. [COULEURS & AMBIANCE] : 
8. [FORMAT, TEXTURES & EXCLUSIONS] : 
```

---

## Exemples Illustratifs : De l'Échec à la Maîtrise

### Exemple 1 : Le Portrait de Science-Fiction

**Le Mouton sans barrières (Ce qu'il ne faut plus faire) :**
> *"Une femme cyborg dans une ville du futur."*
*(Résultat : Une image générique vue 10 000 fois, personnage jeune et lisse de face, néons roses et bleus par défaut, aucun récit).*

**Le Mouton encadré (Ce que l'on envoie à l'IA) :**
```markdown
Génère une image en respectant strictement la fiche de spécifications suivante :

1. [MÉDIUM & STYLE] : Photographie cinématographique sur pellicule argentique 35mm (Kodak CineStill 800T), esthétique de science-fiction rétro-futuriste réaliste et brute.
2. [SUJET PRINCIPAL, OBJETS & MATÉRIAUX] : Une femme mécanicienne cyborg de 70 ans, visage ridé taché de cambouis, grain de peau naturel très détaillé. Elle possède un œil bionique mécanique en laiton usé et oxydé, et porte un lourd manteau en cuir marron rapiécé sur un bleu de travail taché d'huile.
3. [ACTION, POSITION & EXPRESSION] : Assise à son établi, penchée en avant. Elle répare une minuscule montre mécanique ancienne à l'aide d'une pince de précision. Expression calme, extrêmement concentrée, léger sourire en coin. Son regard est fixé sur la montre entre ses mains.
4. [ENVIRONNEMENT, DÉCOR & ÉPOQUE] : Intérieur d'un atelier d'horlogerie clandestin, étroit et encombré, dans les bas-fonds d'une mégapole industrielle. Premier plan : quelques outils flous posés sur la table. Arrière-plan : câbles électriques qui pendent du plafond, étagères métalliques remplies de pièces détachées et d'engrenages.
5. [TYPE DE PLAN, ANGLE & OBJECTIF] : Plan rapproché poitrine (Medium Close-Up), angle légèrement en contre-plongée (Low angle). Objectif 50mm à grande ouverture (f/1.4) créant une faible profondeur de champ et un flou d'arrière-plan prononcé (bokeh). Règle des tiers.
6. [ÉCLAIRAGE & MÉTÉO] : Éclairage dramatique en clair-obscur (Chiaroscuro). La seule source de lumière principale est une petite lampe d'architecte articulée diffusant une lumière chaude et directionnelle sur ses mains et son visage. Légère fumée d'encens flottant dans le faisceau lumineux.
7. [COULEURS & AMBIANCE] : Palette dominée par des tons chauds (ambre, or vieilli, marron cuir) contrastant avec des ombres profondes bleu nuit (harmonie complémentaire discrète). Atmosphère intime, nostalgique et studieuse.
8. [FORMAT, TEXTURES & EXCLUSIONS] : Format paysage cinéma 16:9. Grain de pellicule réaliste, poussières visibles dans la lumière. Exclusions : pas de néons roses ou violets, pas de plastique lisse, pas de texte.
```

---

### Exemple 2 : L'Illustration d'Objet Fantastique

**Le Mouton sans barrières (Ce qu'il ne faut plus faire) :**
> *"Une fiole de potion magique sur une table."*

**Le Mouton encadré (Ce que l'on envoie à l'IA) :**
```markdown
Génère une image en respectant strictement la fiche de spécifications suivante :

1. [MÉDIUM & STYLE] : Rendu 3D stylisé de haute qualité (Octane Render, Blender), direction artistique de jeu vidéo fantastique avec des textures peintes à la main (Hand-painted textures).
2. [SUJET PRINCIPAL, OBJETS & MATÉRIAUX] : Une fiole d'alchimiste en cristal épais taillé à facettes, comportant quelques micro-fissures. Bouchon en liège ancien scellé à la cire rouge et entouré de petites feuilles de lierre grimpant. À l'intérieur, un liquide épais tourbillonnant semblable à une nébuleuse spatiale.
3. [ACTION, POSITION & EXPRESSION] : La fiole lévite à quelques centimètres au-dessus de son support, légèrement inclinée (Dutch tilt sur l'objet). Quelques gouttelettes de lumière s'échappent du bouchon et flottent vers le haut.
4. [ENVIRONNEMENT, DÉCOR & ÉPOQUE] : Posée dans l'étude d'un apothicaire médiéval. Juste en dessous de la fiole se trouve un vieux grimoire ouvert aux pages jaunies couvertes de schémas géométriques, sur une table en bois de chêne massif. Autour : quelques cristaux bruts, un mortier en pierre et des pièces d'or éparpillées.
5. [TYPE DE PLAN, ANGLE & OBJECTIF] : Plan moyen centré sur l'objet, vue en plongée à 45 degrés (perspective isométrique). Objectif macro 85mm, arrière-plan doucement flouté.
6. [ÉCLAIRAGE & MÉTÉO] : Bioluminescence et diffusion sous-cutanée (Subsurface scattering) : le liquide à l'intérieur de la fiole est la source de lumière principale, projetant des reflets caustiques sur le livre ouvert. En complément, un rayon de lune froid (Rim light) vient de la fenêtre à gauche pour dessiner les contours du cristal.
7. [COULEURS & AMBIANCE] : Harmonie de couleurs triadique et saturée : violet cosmique, bleu nuit profond et touches d'or chaud. Ambiance mystique, merveilleuse et feutrée.
8. [FORMAT, TEXTURES & EXCLUSIONS] : Format carré 1:1. Textures de bois, de papier parchemin et de verre dépoli très marquées. Exclusions : pas de personnages, pas d'interface utilisateur, pas de rendu photoréaliste froid.
```

---

## Atelier Pratique : À Vous de Jouer !

Dans votre IA de conversation habituelle (même dans sa version gratuite) :

### Étape 1 : Le Mouton en Liberté (Le Témoin)
*   Créez une image basique à l'aide d'un simple prompt d'une phrase (ex: *"Un détective dans son bureau la nuit"*), ou reprenez l'image générée lors de votre précédent exercice.
*   Observez le résultat : notez tout ce que l'IA a choisi à votre place (l'âge du personnage, l'angle de la caméra, la couleur de la lumière, le style graphique).

### Étape 2 : L'Apport de la Référence Visuelle
*   Recréez cette image en gardant exactement le même prompt d'une phrase, mais en ajoutant cette fois **une image de référence** pour l'angle, la position du personnage et la lumière (vous pouvez utiliser une de vos propres photos ou toute photo trouvée sur Internet).
*   Ajoutez simplement cette consigne à votre prompt : 
    > *"J'aimerais utiliser cette image comme référence pour l'angle, la position du personnage et la lumière."*
*   Comparez la différence de mise en scène avec votre première image.

### Étape 3 : Le Contrôle Total par la Checklist
*   Recréez maintenant votre image en utilisant **la checklist complète en 8 points**.
*   *Astuce anti-page blanche :* Si vous n'êtes pas inspiré pour remplir chaque ligne vous-même, vous pouvez tout à fait demander à l'IA de texte de remplir la checklist vierge pour vous avant de lancer la génération d'image ! 
*   Mais **mettez-y un peu de vous** : imposez-lui une direction artistique ou une atmosphère précise qui vous plaît personnellement. 
    *   *Exemple de demande à faire à l'IA pour préparer votre checklist :* *"Remplis cette checklist de génération d'image pour mon sujet, mais je veux absolument une atmosphère de film d'horreur des années 80-90 (grain VHS, éclairage au néon blafard ou lampe de poche dans la brume, couleurs saturées façon Stephen King / John Carpenter)."*
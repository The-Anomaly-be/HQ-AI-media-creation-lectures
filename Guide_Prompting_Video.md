# Guide de Formation : L'Art de Réaliser des Vidéos par l'IA
### Passer de générateur de clips aléatoires au rôle de Réalisateur et Monteur

---

## Introduction : Le Réflexe du Réalisateur

> **« En vidéo IA, on ne génère jamais un film en un seul prompt : on tourne des plans de 3 à 5 secondes que l'on assemble. La première chose à faire n'est pas d'ouvrir le générateur vidéo, mais de créer son Storyboard et ses images clés (Keyframes). »**

Pourquoi ce changement de paradigme est-il vital ? Parce que les moteurs vidéo (Runway Gen-3, Luma Dream Machine, Kling, Sora, Veo, Pika, Hailuo...) ne comprennent pas la dramaturgie globale d'une scène longue. Si vous tentez de raconter trois actions consécutives dans un seul prompt en mode *Text-to-Video*, l'IA va paniquer : les visages vont fondre, les membres vont se démultiplier et le décor va muter (le fameux phénomène de *morphing* ou d'hallucination temporelle).

Pour dompter la vidéo IA, vous devez adopter la méthode du cinéma traditionnel : **séparer la direction artistique (l'image fixe) de la mise en mouvement (la vidéo), puis construire votre récit par le découpage et le montage.**

---

## L'Analogie du Mouton en Mouvement : Poser les Rails

Dans le guide sur l'image fixe, notre idée était un **mouton dans Minecraft** qu'il fallait entourer de 8 barrières pour l'empêcher de fuir vers le "bruit statistique moyen". 

En vidéo, le défi double : **votre mouton est désormais lancé à pleine vitesse dans le temps !**

### Scénario 1 : Le Mouton en Roue Libre (Le Prompt Text-to-Video Vague)
Si vous tapez simplement *"Un chevalier marche dans une forêt puis sort son épée"* directement dans un générateur vidéo sans point de départ ni d'arrivée :
*   **Seconde 1 :** Le chevalier apparaît dans un style générique.
*   **Seconde 3 :** En tournant la tête, son casque fusionne avec ses cheveux.
*   **Seconde 5 :** Il sort une épée qui sort littéralement de son bras et la forêt se transforme en château sans raison.
C'est la **dérive temporelle** : à chaque nouvelle image (24 fois par seconde), l'IA réinvente la suite par probabilité et s'éloigne de votre idée.

```text
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   DÉRIVE TEMPORELLE : Morphing, membres qui fondent, décor qui mute, physique absurde
   
                                      /---> [Seconde 3 : Visage déformé]
                                     /
   [Idée de départ] ---> (Seconde 1) -----> [Seconde 4 : Épée qui fond]
   (Sans rails)                      \
                                      \---> [Seconde 5 : Décor incohérent]
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```

### Scénario 2 : Le Mouton sur des Rails (First Frame, Last Frame & Mouvement Contrôlé)
Pour empêcher toute hallucination, le réalisateur IA pose des **rails stricts** :
1.  **La Gare de Départ (First Frame / Première Image) :** Vous fournissez une image fixe parfaite (générée avec votre checklist image). L'IA n'a plus à inventer le style, l'éclairage ou le visage.
2.  **La Gare d'Arrivée (Last Frame / Dernière Image) :** Vous fournissez l'image exacte de la fin du mouvement (3 à 5 secondes plus tard).
3.  **Les Rails de Caméra et de Rythme :** Votre prompt vidéo ne sert plus à décrire le décor (déjà présent dans l'image), mais **uniquement ce qui bouge** : le vecteur de la caméra, l'action unique du sujet et la physique de l'environnement.

```text
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   CONTRÔLE TEMPOREL ABSOLU (Zéro hallucination, continuité parfaite)
   
   +-------------------+      ================ RAILS ================      +-------------------+
   |   FIRST FRAME     | ===> [Mouvement Caméra : Travelling Avant]   ===> |    LAST FRAME     |
   |  (Image de début  |      [Action Unique : Lève le regard]             |  (Image de fin    |
   |   100% maîtrisée) |      [Physique : Pluie + Cape au vent]            |   100% maîtrisée) |
   +-------------------+      =======================================      +-------------------+
          (t = 0s)                     (Durée : 3 à 5 secondes)                   (t = 5s)
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```

---

## La Hiérarchie de l'Attention en Vidéo : Cinétique d'Abord !

Contrairement au prompt d'image où le style et les détails de texture occupent toute la place, **le moteur vidéo cherche avant tout des verbes d'action et des vecteurs spatiaux**.

> **Règle fondamentale :** Si vous utilisez une image de départ (*Image-to-Video*), ne gaspillez pas le début de votre prompt à re-décrire les vêtements ou les couleurs que l'IA voit déjà sur votre image ! Concentrez 80 % du poids des mots sur la dynamique.

```text
  [ DÉBUT DU PROMPT VIDÉO ] ======================> [ FIN DU PROMPT VIDÉO ]
   Poids : MAXIMUM (Cinétique)                       Poids : MOYEN/FAIBLE (Atmosphère)
   Mouvement de caméra + Action unique du sujet      Physique secondaire (vent, fumée), Vitesse
```

### Les 3 Règles d'Or du Prompt Vidéo :
1. **Un clip = Une seule intention de mouvement :** Ne demandez jamais *"Il court, puis s'arrête, puis boit une potion, puis regarde la caméra"*. C'est une séquence de 4 plans différents ! Demandez uniquement : *"Il s'arrête en haletant, les épaules qui se soulèvent"*.
2. **Séparez le mouvement de la caméra du mouvement du sujet :** Précisez toujours si c'est la caméra qui tourne autour du sujet immobile, ou si la caméra est fixe sur trépied pendant que le sujet traverse le cadre.
3. **Bannissez les négations en vidéo :** Les modèles vidéo gèrent très mal les mots comme *"sans bouger la tête"* (ils lisent *"bouger la tête"*). Préférez des formulations positives : *"Tête parfaitement immobile, regard fixe"*.

---

## Le Vocabulaire Technique Illustré du Réalisateur IA

Pour diriger votre caméra virtuelle et votre salle de montage, voici l'inventaire complet des outils cinématographiques compris par les IA vidéo, accompagnés de schémas spatiaux.

---

### 1. Les Mouvements de Caméra (Camera Movements)

Ne laissez jamais la caméra flotter au hasard. Choisissez un mouvement mécanique précis :

```text
  1. PAN (Panoramique horizontal)          2. TILT (Panoramique vertical)
     La caméra pivote sur son axe             La caméra pivote de haut en bas
     [Caméra Fixe] ===> (Regarde G -> D)      [Caméra Fixe] ===> (Regarde Bas -> Haut)

  3. DOLLY IN / PUSH IN (Travelling avant) 4. TRUCK / TRACKING (Travelling latéral)
     La caméra avance physiquement            La caméra roule parallèlement au sujet
     [Caméra] --------> [Sujet]               [Caméra] ===>        [Sujet] ===>

  5. ORBIT / ARC (Mouvement circulaire)    6. CRANE / JIB (Mouvement de grue)
     La caméra tourne autour du sujet         La caméra s'élève verticalement dans les airs
            /------>\                         [Caméra Haute]  ^
     [Caméra]  (Sujet)                                        | (Monte physiquement)
            \<------/                         [Caméra Basse]  |
```

*   **Fixed Camera / Static Shot / Locked-off Tripod (Plan fixe sur trépied) :** La caméra ne bouge pas d'un millimètre. Idéal pour la contemplation, les dialogues ou pour laisser le sujet traverser l'écran.
*   **Pan Left / Pan Right (Panoramique horizontal) :** La caméra reste sur place mais tourne la tête de gauche à droite (ex: pour suivre un véhicule ou révéler un paysage).
*   **Tilt Up / Tilt Down (Panoramique vertical) :** La caméra reste sur place mais s'incline du bas vers le haut (ex: partir des bottes d'un géant pour révéler son visage) ou du haut vers le bas.
*   **Dolly In / Push In (Travelling avant) :** La caméra avance physiquement vers le sujet. Crée une tension croissante, une intimité ou souligne une prise de conscience du personnage. *(Différent du Zoom : le Dolly modifie la perspective du décor !)*
*   **Dolly Out / Pull Back (Travelling arrière) :** La caméra recule physiquement loin du sujet. Révèle l'environnement, crée un sentiment d'abandon, de solitude ou de surprise.
*   **Truck Left / Truck Right / Lateral Tracking Shot (Travelling latéral) :** La caméra se déplace sur le côté à la même vitesse que le sujet qui marche ou court (vue de profil en mouvement).
*   **Follow Shot / Lead Shot (Travelling suivi ou précédé) :**
    *   *Follow Shot :* La caméra suit le personnage de dos pendant qu'il avance.
    *   *Lead Shot (Backward tracking) :* La caméra recule devant le personnage qui marche face à nous.
*   **Orbit / Arc Shot (Travelling circulaire 180° ou 360°) :** La caméra décrit un cercle autour du sujet central. Très épique, héroïque ou vertigineux.
*   **Crane Up / Crane Down / Pedestal (Mouvement de grue) :** La caméra monte ou descend verticalement dans l'espace (ex: s'élever au-dessus d'une foule à la fin d'une scène).
*   **Handheld Camera / Shaky Cam (Caméra à l'épaule) :** Léger tremblement organique humain (style documentaire) ou secousses intenses (scène de combat, chaos, survie).
*   **Steadicam Shot :** Mouvement fluide et flottant qui suit le sujet à travers des espaces complexes sans aucune secousse.
*   **FPV Drone Shot (Vol de drone immersif) :** Mouvement ultra-rapide, acrobatique, plongeant à travers des fenêtres, des canyons ou entre des obstacles.
*   **Dolly Zoom / Vertigo Effect (Transtrav / Effet Vertigo) :** La caméra recule pendant que l'objectif zoome en avant (le sujet garde la même taille mais le décor semble s'écraser ou s'étirer violemment derrière lui).
*   **Rack Focus / Pull Focus (Bascule de point) :** La caméra ne bouge pas, mais la netteté passe d'un objet flou au premier plan vers un personnage net en arrière-plan (ou inversement).

**Ressources visuelles de référence :**
*   [StudioBinder - Guide vidéo et illustré de tous les mouvements de caméra au cinéma](https://www.studiobinder.com/blog/different-types-of-camera-movements-in-film/)
*   [Eyecandy - Bibliothèque visuelle interactive de plans, mouvements et effets de caméra (GIFs)](https://eyecannndy.com/)

---

### 2. Cadrage Dynamique, Angles et Échelle de Plans en Mouvement

En vidéo, le cadrage et l'angle interagissent avec le déplacement du sujet :

*   **L'Espace de Regard et de Mouvement (Lead Room / Nose Room) :** Si votre personnage court vers la droite, cadrez-le sur le tiers gauche de votre image de départ (*First Frame*) pour lui laisser l'espace visuel dans lequel courir.
*   **Low Angle Tracking (Suivi en contre-plongée au ras du sol) :** Placer la caméra très bas en suivant les pas ou un personnage qui avance donne une puissance monumentale au mouvement.
*   **Overhead / Bird's-Eye Tracking (Suivi zénithal à 90°) :** Vue de dessus suivant un véhicule sur une route sinueuse ou un personnage dans un labyrinthe (géométrie pure).
*   **Over-the-Shoulder (OTS) Dynamique :** Commencer derrière l'épaule d'un personnage et avancer (*Push in*) pour dépasser son épaule et découvrir ce qu'il regarde.

---

### 3. Le Découpage en Plans (Shot Breakdown) : Raconter une Histoire

Un spectateur s'ennuie au bout de 4 secondes si le plan ne change pas, et l'IA perd en qualité au-delà de 5 secondes. La solution est le **découpage séquentiel**.

Pour raconter une scène de 15 secondes, vous allez générer **4 à 5 plans distincts** qui répondent à une grammaire universelle :

```text
   SÉQUENCE DE 15 SECONDES : "LA DÉCOUVERTE DE L'ARTEFACT"
   
   [PLAN 1 : 3.5s]         [PLAN 2 : 3.0s]         [PLAN 3 : 2.0s]         [PLAN 4 : 2.5s]         [PLAN 5 : 4.0s]
   ESTABLISHING SHOT       MEDIUM TRACKING         INSERT / ECU            REACTION SHOT           LOW ANGLE REVEAL
   Plan très large de      Plan américain,         Très gros plan sur      Gros plan visage,       Contre-plongée,
   la grotte, l'exploratrice elle marche avec      sa main qui effleure    ses yeux s'écarquillent le monolithe s'allume
   entre au loin.          sa torche (Travelling). la pierre gravée.       avec le reflet bleu.    derrière elle.
```

1.  **Plan 1 — L'Establishing Shot (Plan de situation / Plan général) :** Montre le lieu, l'ambiance, la météo et situe le personnage dans l'espace.
2.  **Plan 2 — Le Plan d'Action (Medium / Tracking Shot) :** Rapproche le spectateur du personnage en train d'agir ou de se déplacer.
3.  **Plan 3 — L'Insert / Cutaway (Très Gros Plan de détail) :** Montre un objet précis que le personnage manipule ou observe (une clé qui tourne, un compteur qui s'affole, une goutte de sang, un doigt sur une détente). *Astuce IA : Les plans d'insert sont très faciles à générer et masquent parfaitement les raccords entre deux plans du personnage !*
4.  **Plan 4 — Le Reaction Shot (Gros plan d'émotion) :** Cadré sur le visage et les yeux du personnage pour faire ressentir au spectateur ce qu'il vient de voir.
5.  **Plan 5 — Le Plan de Résolution ou de Relance (Payoff / Reveal) :** La conséquence de l'action, souvent accompagnée d'un mouvement de caméra ample (Dolly out ou Crane up).

---

### 4. Le Rythme, la Temporalité et la Cadence (Pacing & Speed)

Le rythme d'une vidéo IA se contrôle à deux niveaux : **à l'intérieur du plan** (vitesse de mouvement) et **entre les plans** (vitesse de montage).

#### A. Le Rythme Interne (Dans le Prompt IA) :
*   **Slow Motion / Ultra Slow-Mo (Ralenti extrême, 120fps, 1000fps Phantom Flex) :** Fige la poésie de l'instant. Idéal pour les éclaboussures d'eau, les étincelles, les cheveux au vent, une explosion ou un saut dramatique. *(Astuce : L'IA génère des mouvements beaucoup plus fluides et sans défauts lorsqu'on lui demande du Slow Motion !)*
*   **Real-time / Natural Pacing (Vitesse réelle, 24fps) :** Mouvement organique normal avec un flou de mouvement naturel (*180-degree shutter motion blur*).
*   **Fast-Paced / Hyperlapse / Timelapse (Accéléré) :** Les nuages défilent à toute vitesse, la foule devient des traînées lumineuses (*Light trails*), le soleil traverse le ciel en 3 secondes.
*   **Speed Ramp (Variation de vitesse) :** Le mouvement commence à vitesse réelle, puis passe brusquement au ralenti extrême au moment de l'impact.

#### B. Le Rythme Externe (Au Montage) :
```text
  RYTHME CONTEMPLATIF / DRAMATIQUE (Plans longs de 4 à 6 secondes)
  |================ Plan 1 (5s) ================|============= Plan 2 (4.5s) =============|
  
  RYTHME D'ACTION / BANDE-ANNONCE (Accélération progressive : Crescendo)
  |======== Plan 1 (3s) ========|==== Plan 2 (2s) ====|== P3 (1s) ==|=P4(0.5s)=|=P5(0.5s)=| [IMPACT NOIR]
```

---

### 5. Les Transitions : L'Art de Lier les Plans (En Montage ou via l'IA)

Comment passer élégamment du Plan A au Plan B ? Oubliez les transitions "PowerPoint" artificielles et utilisez les transitions du cinéma ou les ponts IA :

*   **Hard Cut (Coupe franche) :** 90 % du cinéma. On passe directement d'un plan à l'autre. Pour qu'elle soit invisible, utilisez le **Cut on Action (Raccord dans le mouvement)** : coupez le Plan 1 au moment exact où le personnage commence à ouvrir une porte (de dos), et démarrez le Plan 2 (de face) au milieu de cette même ouverture de porte.
*   **Match Cut (Raccord d'analogie visuelle ou de mouvement) :** La forme ou le mouvement de la fin du Plan A correspond exactement à la forme ou au mouvement du début du Plan B. *(Ex: Gros plan sur un œil rond qui s'ouvre $\rightarrow$ Coupe sur une planète ronde de la même taille au même endroit de l'écran).*
*   **Whip Pan Transition (Transition par panoramique filé) :** À la fin du Plan A, la caméra tourne brusquement vers la droite dans un flou de vitesse. Au début du Plan B, la caméra arrive depuis la gauche dans ce même flou de vitesse.
*   **Wipe / Obstacle Transition (Volet naturel par le premier plan) :** Un élément sombre passe devant l'objectif et bouche tout l'écran (un bus qui passe, le dos d'un passant, un tronc d'arbre), permettant de changer secrètement de plan.
*   **J-Cut et L-Cut (Transitions sonores — Le secret des pros !) :**
    *   *J-Cut :* On entend le son du Plan 2 (ex: le grondement d'un train) 1 ou 2 secondes *avant* que l'image du Plan 2 n'apparaisse.
    *   *L-Cut :* L'image passe au Plan 2, mais la voix ou la résonance du Plan 1 continue pendant encore 1 ou 2 secondes. **Cela gomme instantanément l'aspect "clips IA mis bout à bout" !**
*   **Le Pont Morphing maîtrisé (First-to-Last Frame Bridge) :** En donnant la dernière image du Plan A comme *First Frame* et la première image du Plan B comme *Last Frame* à l'IA, elle génère un plan-séquence impossible qui relie les deux scènes !

---

## Les Techniques Avancées de Production avec l'IA

C'est ici que se joue la différence entre l'amateur qui joue à la loterie avec l'IA et le créateur qui livre un film cohérent.

### 1. La Règle d'Or : Le Workflow "Image-First" (Image d'abord, Vidéo ensuite)
Ne tapez **jamais** votre prompt directement dans un outil vidéo si vous cherchez un résultat précis.
1.  Générez vos images fixes dans un générateur d'images (Midjourney, Flux, Nano Banana...) en utilisant la **Checklist Image en 8 points**. Cela coûte 10 fois moins cher, prend 10 secondes, et vous permet de valider le visage, le costume, l'éclairage et le cadrage.
2.  Une fois vos images parfaites validées, importez-les dans votre générateur vidéo en mode **Image-to-Video**.

### 2. Maîtriser le "First Frame / Last Frame" (Image de Début / Image de Fin)
La plupart des grands modèles actuels (Runway, Luma, Kling, Veo, Pika...) permettent de charger **deux images** pour un seul clip : le début (*Start Frame / Keyframe A*) et la fin (*End Frame / Keyframe B*).

```text
   ASTUCE DE PRO : CRÉER LE COUPLE [FIRST FRAME] + [LAST FRAME]
   
   Option A (Le Zoom / Dézoom parfait) :
   [First Frame] = Gros plan du personnage   --->   [Last Frame] = Plan large du même décor
   
   Option B (L'Édition d'image / Inpainting) :
   Prenez votre [First Frame] (ex: Porte fermée, épée au fourreau)
   Demandez à votre IA d'image : "Modifie cette image : ouvre la porte / lève l'épée"
   Vous obtenez une [Last Frame] avec 100% du même décor !
   L'IA vidéo n'a plus qu'à interpoler les 4 secondes entre les deux !
```

### 3. La Continuité d'un Clip à l'Autre (La Chaîne dePlans / Daisy-Chaining)
Comment faire un plan de 10 secondes ou garder exactement la même pose à la coupe ?
*   **Extraire la dernière frame :** Si votre clip de 5 secondes se termine à un moment génial, faites une capture haute définition de sa toute dernière image (ou utilisez la fonction *Extend from last frame*), et utilisez cette image comme **First Frame** du clip suivant.

### 4. Garder le Même Personnage et le Même Univers (Character & World Sheet)
Pour que votre héros ait exactement le même visage et les mêmes vêtements sur les 15 plans de votre court-métrage :
*   Avant de générer votre storyboard, créez une **Character Sheet (Planche de personnage)** : une image unique sur fond neutre montrant votre personnage de face, de profil, de dos et en gros plan visage.
*   Fournissez systématiquement cette planche comme **Image de Référence (Character Reference / Omni-Reference / Elements)** lors de la création de toutes vos *First Frames* de la séquence !

### 5. L'Utilisation de Vidéos de Référence (Video-to-Video / Motion Brush / Act-One)
Tout comme en image, un geste filmé au smartphone vaut 1000 mots :
*   **Act-One / Motion Reference :** Filmez votre propre visage avec votre téléphone pour jouer une émotion subtile (un soupir, un regard inquiet, une réplique) et transférez exactement ce jeu d'acteur sur l'image de votre personnage IA.
*   **Motion Brush (Pinceau de mouvement) :** Peignez directement sur votre image les zones qui doivent bouger (ex: tracez une flèche vers le haut sur la fumée, une flèche vers la gauche sur les nuages, et laissez les bâtiments verrouillés).

---

## La Checklist de Réalisation Vidéo (À fournir à l'IA)

> **Méthode :** Fournissez votre **First Frame** (et éventuellement votre **Last Frame**) à l'IA vidéo, puis copiez-collez cette fiche de direction de plan. Elle place immédiatement les vecteurs de mouvement en tête de prompt !

```markdown
Anime ce plan vidéo en respectant strictement la feuille de direction suivante :

1. [ANCRAGES VISUELS] : (Ex: De la First Frame fournie vers la Last Frame / Style cinématographique 35mm conservé)
2. [MOUVEMENT DE CAMÉRA] : (Ex: Travelling avant lent (Slow Dolly In) + léger mouvement d'épaule organique)
3. [ACTION UNIQUE DU SUJET] : (Ex: Le personnage tourne lentement la tête vers l'objectif et cligne des yeux)
4. [CADRAGE & ÉVOLUTION DU PLAN] : (Ex: Départ en Plan Américain évoluant vers un Gros Plan poitrine, bascule de point sur ses yeux)
5. [PHYSIQUE & DYNAMIQUE DU DÉCOR] : (Ex: Pluie battante oblique, cape en laine agitée par une rafale de vent vers la droite, braises qui montent)
6. [ÉCLAIRAGE DYNAMIQUE] : (Ex: Gyrophare bleu et rouge qui balaie son visage par intermittence dans l'obscurité)
7. [RYTHME & TEMPORALITÉ] : (Ex: Ralenti cinématographique fluide (Slow motion 60fps), flou de mouvement naturel)
8. [STABILITÉ & EXCLUSIONS] : (Ex: Visage et structure osseuse constants, pas de déformation des mains, pas de coupe brusque)
```

---

## Étude de Cas : Réaliser une Séquence de 3 Plans (De l'Échec à la Maîtrise)

### Ce qu'il ne faut JAMAIS faire (Le Prompt "Tout-en-un" sans images clés) :
> *"Un samouraï sous la pluie dégaine son katana, tranche une goutte d'eau au ralenti puis regarde la caméra d'un air menaçant."*
*(Résultat : Le katana apparaît tordu, le samouraï a trois bras pendant une seconde, la goutte d'eau n'est jamais visible et la caméra flotte sans but).*

### Ce que fait le Réalisateur IA (Découpage en 3 Clips de 4 secondes) :

#### Plan A — La Tension (3,5 secondes)
*   **Image fournie (First Frame) :** Plan américain en contre-plongée du samouraï immobile sous une pluie nocturne, main posée sur la garde du sabre.
```markdown
1. [ANCRAGES VISUELS] : Animation à partir de la First Frame fournie, esthétique cinéma 35mm sombre.
2. [MOUVEMENT DE CAMÉRA] : Travelling avant lent et implacable (Slow Push In) en contre-plongée.
3. [ACTION UNIQUE DU SUJET] : Le samouraï reste d'une immobilité de statue, seule sa poitrine se soulève dans une profonde inspiration et son pouce pousse légèrement la garde du katana d'un centimètre.
4. [CADRAGE & ÉVOLUTION DU PLAN] : Passe d'un Plan Américain à un Plan Rapproché Taille.
5. [PHYSIQUE & DYNAMIQUE DU DÉCOR] : Pluie lourde qui rebondit en gouttelettes sur son chapeau de paille et son armure mouillée, brume au sol qui glisse vers la gauche.
6. [ÉCLAIRAGE DYNAMIQUE] : Un éclair lointain illumine brièvement sa silhouette à contre-jour (Rim light) et fait briller le métal humide.
7. [RYTHME & TEMPORALITÉ] : Vitesse réelle (24fps) très posée, tension maximale.
8. [STABILITÉ & EXCLUSIONS] : Sabre parfaitement droit, armure rigide, aucun morphing.
```

#### Plan B — L'Insert Cinétique (2 secondes — Transition sur l'action)
*   **Images fournies :** *First Frame* = Très gros plan macro sur la lame qui sort du fourreau / *Last Frame* = La lame étincelante qui coupe une goutte de pluie en deux.
```markdown
1. [ANCRAGES VISUELS] : Transition fluide de la First Frame vers la Last Frame.
2. [MOUVEMENT DE CAMÉRA] : Caméra fixe macro verrouillée sur la trajectoire de la lame, très faible profondeur de champ (Bokeh f/1.4).
3. [ACTION UNIQUE DU SUJET] : L'acier poli du katana traverse le cadre en diagonale et fend une goutte d'eau en suspension.
4. [CADRAGE & ÉVOLUTION DU PLAN] : Très Gros Plan (Extreme Close-Up / Insert) centré sur le fil de l'épée.
5. [PHYSIQUE & DYNAMIQUE DU DÉCOR] : Onde de choc microscopique dispersant les gouttelettes d'eau en couronne autour de l'acier.
6. [ÉCLAIRAGE DYNAMIQUE] : Reflet spéculaire froid et tranchant qui court tout le long de la lame en mouvement.
7. [RYTHME & TEMPORALITÉ] : Ralenti extrême (Ultra Slow-Motion 1000fps), mouvement liquide et cristallin.
8. [STABILITÉ & EXCLUSIONS] : Lame géométriquement parfaite et rectiligne.
```

#### Plan C — La Résolution (4 secondes — Match Cut sur le regard)
*   **Image fournie (First Frame) :** Gros plan sur le visage du samouraï sous son chapeau, la lame arrêtée au premier plan flou devant son visage.
*   **Prompt :** *Dolly Out léger, il relève lentement le menton pour dévoiler ses yeux perçants face caméra pendant que la pluie s'écoule du bord de son chapeau au ralenti.*

---

## Atelier Pratique : Votre Première Mini-Séquence en 3 Étapes !

À réaliser avec votre IA de texte/image habituelle et le générateur vidéo de votre choix :

### Étape 1 : Concevoir son Découpage en 3 Plans (Le Storyboard Texte)
Choisissez une micro-scène simple de 10 secondes (ex: *"Un détective découvre un indice mystérieux sur son bureau"* ou *"Une astronaute ouvre le sas d'une planète inconnue"*).
*   Ne générez rien tout de suite ! Demandez d'abord à votre IA de texte de découper cette idée en **3 plans complémentaires** :
    1. Un **Plan d'ensemble ou moyen** avec un mouvement de caméra (ex: Travelling avant).
    2. Un **Très Gros Plan (Insert)** sur un objet ou une main en action.
    3. Un **Gros Plan d'émotion (Reaction Shot)** sur le visage.

### Étape 2 : Générer vos Images Clés (First Frames & Last Frames)
*   Utilisez la méthode du cours précédent (la Checklist Image) pour générer la **First Frame** de chacun de vos 3 plans en gardant exactement la même direction artistique.
*   *Défi Bonus :* Pour le Plan 2 (l'Insert), créez à la fois la **First Frame** (avant l'action, ex: boîte fermée) et la **Last Frame** (après l'action, ex: boîte ouverte avec une lueur dorée qui s'en échappe).

### Étape 3 : Rédiger les Checklists Vidéo et Animer !
*   Pour chacun de vos 3 plans, remplissez la **Checklist Vidéo en 8 points** (en vous aidant de l'IA si besoin) en imposant un rythme précis (ex: *Slow motion*, *Caméra épaule*, *Bascule de point*).
*   Lancez la génération de vos 3 petits clips de 4 secondes à partir de vos images clés.
*   Assemblez-les bout à bout (sur CapCut, Premiere, DaVinci ou Canva) en ajoutant une ambiance sonore continue (*L-Cut / J-Cut*) pour admirer la fluidité de votre séquence !
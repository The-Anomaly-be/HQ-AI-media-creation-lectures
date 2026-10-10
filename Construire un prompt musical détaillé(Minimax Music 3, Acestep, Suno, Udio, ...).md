**Construire un prompt musical détaillé**

Un prompt musical ne sert pas seulement à nommer un style. Il peut décrire une voix, un rythme, une palette sonore, une progression émotionnelle et la manière dont les instruments se répondent.

Le principe central de nos prompts est la **direction** : plutôt que d’énumérer ce que l’on veut entendre, on explique comment ces éléments doivent agir ensemble.

Compare ces deux formulations :

| *Soul, blues, jazz, drum’n’bass, piano, violon, trompette, voix féminine.* |
| :---- |

Et :

| Une voix féminine soul intime sur un groove trip-hop lent. Le piano installe une harmonie blues, le violon introduit un motif inachevé et la trompette lui répond. Dans la seconde moitié, les batteries passent en drum’n’bass tandis que les accords conservent leur rythme lent. |
| :---- |

La première décrit des ingrédients. La seconde propose une composition.

## 

## **1\. Avant de commencer : distinguer intention et contrôle**

Les prompts que nous devons écrire sont des briefs de composition très détaillés.

Leurs titres — `Global Metadata`, `Vocal Identity`, `Instrumental Identity`, etc. — organisent les instructions pour les rendre lisibles. Ce ne sont pas des commandes universelles ni une syntaxe obligatoire.

Il faut également distinguer :

* Ce que tu souhaites : une tonalité, un type de voix, une transition particulière.  
* Ce que tu décris : les mots employés pour transmettre cette intention.  
* Ce que le générateur produit réellement : une interprétation qu’il faut écouter et évaluer.

Une instruction précise n’est pas une garantie d’exécution exacte. Udio présente notamment ses balises comme des moyens de guider la création, pas comme une partition déterministe.

Dans cette leçon, les exemples sont donc des formulations de travail, pas des commandes dont le résultat serait assuré.

## 

## **2\. Global Metadata : définir l’identité générale**

Cette section répond à la question :

> Quel morceau est-ce que nous essayons de créer ?

Elle contient les choix qui doivent rester cohérents à l’échelle de toute la composition.

## **A. Les genres et leur hiérarchie**

Tu peux indiquer :

* Un genre principal.  
* Des influences secondaires.  
* Des styles réservés à certains passages.  
* Le rôle de chaque influence.

Dans notre cas, écrire « soul, blues, dub, drum’n’bass » ne précise pas lequel domine.

Une formulation plus utile serait :

> La soul définit la voix et l’émotion. Le blues colore les phrases mélodiques. Le trip-hop fournit le groove initial. Le dub organise le pont. La drum’n’bass intervient dans le climax instrumental.

Le mélange devient une répartition des fonctions plutôt qu’une accumulation.

## **B. Le tempo**

Le tempo décrit la vitesse de la pulsation, généralement en BPM : battements par minute.

Tu peux préciser :

* Un tempo principal.  
* Une sensation lente ou rapide.  
* Une accélération.  
* Un passage ressenti en half-time ou en double-time.

Exemple issu de notre première direction :

> Une pulsation à 86 BPM, avec une section de batteries en double-time à 172 BPM.

L’intention est de conserver une relation claire entre le passage lent et le passage rapide.

Pour un prompt plus accessible :

> Les batteries deviennent deux fois plus rapides dans le climax, mais les accords restent larges et espacés.

Cette formulation exprime aussi l’effet recherché : plus d’activité rythmique, sans accélérer tous les éléments.

## **C. La mesure et le groove**

Le tempo ne suffit pas à décrire le mouvement.

Tu peux ajouter :

* Une mesure : 4/4, 3/4, 6/8…  
* Un rythme droit ou balancé.  
* Du swing.  
* Des syncopes.  
* Une interprétation légèrement en retard sur le temps.  
* Un groove rigide, souple, brisé ou flottant.

Dans *Salt Bloom*, le début en 6/8 servait à produire un balancement circulaire. Dans *Velvet Teeth*, le swing rendait le rythme plus joueur et moins rectiligne.

Exemples :

> Un groove lent et balancé, avec des subdivisions ternaires et une caisse claire souple.

> Des batteries droites et nerveuses, contrastant avec une voix légèrement derrière le temps.

Le deuxième exemple ne décrit pas seulement deux éléments : il décrit leur relation.

## **D. La tonalité et les couleurs harmoniques**

Tu peux proposer :

* Une tonalité majeure ou mineure.  
* Un mode.  
* Des accords enrichis.  
* Des passages chromatiques.  
* Une harmonie stable ou ambiguë.  
* Une résolution claire ou suspendue.

Quelques traductions utiles :

| Terme | Ce que tu cherches à faire entendre |
| :---- | :---- |
| **Tonalité mineure** | Une couleur pouvant être sombre, tendue ou introspective selon le contexte |
| **Accords enrichis** | Des accords plus colorés, par exemple avec septièmes ou neuvièmes |
| **Chromatisme** | Des mouvements par demi-tons qui ajoutent du frottement |
| **Accords suspendus** | Une sensation d’attente harmonique |
| **Open fifths** | Des intervalles ouverts, avec moins d’information sur le caractère majeur ou mineur |
| **Unresolved ending** | Une fin qui ne donne pas une impression de clôture complète |

Tu n’es pas obligé de connaître une progression d’accords complète. Tu peux écrire :

> Une harmonie mineure, avec des accords ouverts et quelques éclaircies plus chaudes, sans résolution triomphante.

## **E. L’atmosphère et la trajectoire émotionnelle**

Distingue l’ambiance de départ de son évolution.

Une simple liste :

> Intime, sombre, intense.

Une trajectoire :

> Le morceau commence contenu, devient nerveux, laisse apparaître une fragilité centrale, puis se libère sans devenir euphorique.

Dans nos variations, cette trajectoire changeait profondément le morceau :

* Première version : confidence → tension → explosion → retour fragile.  
* *Velvet Teeth* : assurance joueuse → perte de contrôle → proximité sincère.  
* *Salt Bloom* : retenue → pression → ouverture → apaisement imparfait.

## **F. Les époques et références esthétiques**

« Années 1940, 1950, 1960 » peut rester très vague.

Précise ce que tu empruntes :

> L’intimité d’un petit ensemble jazz des années 1940, le grain d’amplificateur du blues des années 1950 et les réponses vocales de la soul des années 1960\.

Tu sélectionnes alors des caractéristiques, sans demander trois reconstitutions historiques simultanées.

## 

## **3\. Vocal Identity : diriger la voix**

Cette section répond à :

> Qui chante, avec quel timbre, quelle intention et quelle évolution ?

Le type de voix et son interprétation font partie des éléments que l’on peut décrire dans une direction musicale.udio+1

## **A. Le profil vocal**

Tu peux préciser :

* Voix féminine, masculine ou androgyne.  
* Voix solo, duo ou ensemble.  
* Registre grave, médium ou aigu.  
* Contralto, mezzo-soprano, soprano, ténor, etc.

Attention : la tessiture et le timbre ne sont pas la même chose. Une voix grave n’est pas automatiquement rauque, et une voix aiguë n’est pas nécessairement légère.

Nos deux dernières voix féminines étaient donc différentes :

> Contralto sombre, veloutée, avec un grave très présent.

Puis :

> Mezzo-soprano plus claire, avec un médium texturé et des notes hautes légèrement rugueuses.

## **B. Le timbre**

Tu peux demander une voix :

* Soufflée.  
* Sèche.  
* Granuleuse.  
* Chaude.  
* Métallique.  
* Claire.  
* Voilée.  
* Légèrement cassée.  
* Avec peu ou beaucoup de vibrato.

Exemple :

> Une voix féminine chaude et texturée, avec un léger grain lorsque l’intensité augmente.

C’est plus précis que :

> Une belle voix émotionnelle.

## **C. Le phrasé**

Le phrasé décrit la façon de faire vivre les mots dans le rythme :

* Entrées tardives.  
* Syllabes coupées.  
* Fins de phrases avalées.  
* Voyelles prolongées.  
* Débit parlé-chanté.  
* Phrases courtes séparées par du silence.  
* Placement devant ou derrière la batterie.

Exemple :

> Les couplets utilisent des phrases brèves et des fins de mots retenues. Le refrain ouvre les voyelles sans multiplier les ornements.

## **D. La progression de l’interprétation**

Ne décris pas uniquement une voix fixe.

> Au début, elle semble contrôler chaque mot. Dans le pont, elle abandonne cette assurance. Le refrain final reste doux, mais les phrases sont plus franches.

Cela donne une évolution à la performance elle-même.

## **E. Les voix secondaires**

Précise leur fonction :

* Doubler certaines phrases.  
* Répondre au chant principal.  
* Soutenir une note.  
* Ajouter une octave.  
* Créer un unisson imparfait.  
* N’apparaître qu’au climax.

Exemple :

> Une seconde voix féminine répond seulement aux deux dernières lignes du refrain, puis disparaît dans le pont.

## **F. La place de la voix dans le son**

Tu peux aussi indiquer :

> Voix proche, centrée et presque sèche dans les couplets ; plus distante et entourée d’échos dans le passage dub.

« Sèche » signifie ici avec peu de réverbération audible. Ce n’est pas la même chose qu’un timbre sec.

## 

## **4\. Instrumental Identity : donner un rôle aux instruments**

Cette section répond à :

> Que fait chaque instrument dans la composition ?

La liste des instruments est utile, mais leur rôle rend le prompt beaucoup plus informatif. L’instrumentation désigne justement les instruments employés dans un morceau.

## **A. Décrire le son**

Pour chaque instrument, précise si nécessaire :

* Sa matière sonore.  
* Son registre.  
* Sa technique de jeu.  
* Son niveau d’agressivité.  
* Ses effets caractéristiques.

Exemples :

> Piano droit feutré, attaques de marteaux audibles, notes graves très espacées.

> Violon proche, avec frottement d’archet, pizzicatos secs et longues notes tendues.

> Trompette ouverte, souffle audible et courtes chutes blues.

## **B. Décrire la fonction**

Un instrument peut :

* Porter la mélodie.  
* Installer les accords.  
* Soutenir le rythme.  
* Répondre à la voix.  
* Ajouter de la tension.  
* Relier deux sections.  
* Produire une texture.

Compare :

> Piano, violon, trompette.

Avec :

> Le piano soutient l’harmonie, le violon porte le motif principal et la trompette répond aux dernières notes du chant.

## **C. Décrire son évolution**

> Le violon commence en pizzicato, passe à des attaques d’archet répétées, puis développe une ligne longue au-dessus des batteries rapides.

Le même instrument peut donc produire plusieurs fonctions et plusieurs niveaux d’énergie.

## **D. Nommer un synthétiseur sans dépendre seulement de son nom**

Dans nos prompts, le Korg MS-20 était une référence sonore.

Pour rendre l’intention plus explicite :

> Un Korg MS-20 produisant une basse analogique résonante, nasale et légèrement instable, avec de courtes réponses saturées.

Le nom identifie une direction ; les adjectifs décrivent ce que tu veux réellement entendre.

## 

## **5\. Le motif : créer une identité reconnaissable**

Un motif est une courte idée musicale qui peut revenir et se transformer.

Dans nos prompts, nous avons utilisé :

* Une phrase descendante.  
* Une cellule syncopée de cinq notes.  
* Une quarte ascendante suivie d’une descente inachevée.

Tu peux préciser :

* Son contour : montant, descendant, circulaire.  
* Son rythme : régulier, syncopé, interrompu.  
* Son caractère : hésitant, insistant, chantant.  
* L’instrument qui l’introduit.  
* Les instruments qui le reprennent.  
* Le moment où il se complète.

Exemple :

> Une courte mélodie ascendante reste inachevée au début. La trompette la reprend dans l’interlude et le piano lui donne enfin une conclusion dans l’outro.

C’est un moyen de demander une unité musicale malgré les changements de style.

## 

## **6\. Production and Sonic Perspective : décrire la matière sonore**

Cette section répond à :

> Comment les sons doivent-ils être enregistrés, traités et placés ?

## **A. La texture**

Tu peux indiquer :

* Grain de bande.  
* Saturation douce.  
* Craquements de vinyle.  
* Souffle.  
* Distorsion.  
* Instabilité légère de hauteur.  
* Son propre, poussiéreux, brut ou poli.

Évite de confondre chaleur et manque de définition.

> Une texture analogique chaude, mais des attaques de batterie lisibles.

Cette phrase demande deux qualités compatibles, plutôt qu’un brouillard permanent.

## **B. L’espace**

Tu peux décrire :

* Une petite pièce.  
* Un espace ample.  
* Une voix proche.  
* Des instruments lointains.  
* Une image stéréo étroite ou large.  
* Des éléments centrés ou latéraux.

Exemple :

> Début étroit et proche ; ouverture progressive de la stéréo au refrain ; basse et voix principale maintenues au centre.

## **C. Les effets**

Précise où et quand ils interviennent :

> Le delay répète seulement la dernière syllabe de certaines phrases.

> La réverbération à ressort apparaît sur quelques accents de guitare.

C’est plus intentionnel que :

> Beaucoup de delay et de réverbération.

## **D. La dynamique**

La dynamique concerne les différences d’intensité.

Tu peux demander :

> Un pont réellement dépouillé pour que le retour des batteries paraisse plus grand sans rendre tout le morceau constamment fort.

Le contraste peut venir du volume, mais aussi du nombre d’instruments, de la largeur sonore ou de la densité rythmique.

## 

## **7\. Arrangement : construire le parcours**

L’arrangement précise ce qui se passe au fil du morceau : entrées, retraits, reprises, contrastes et transitions.

Les balises comme `[Verse]`, `[Chorus]`, `[Bridge]`, `[Intro]` et `[Outro]` correspondent à des fonctions structurelles courantes. Udio documente également des balises comme `[Build]`, `[Breakdown]`, `[Instrumental Break]` et `[Drop]`.

## **Les principales sections**

| Section | Fonction | Ce que tu peux indiquer |
| :---- | :---- | :---- |
| **Intro** | Installer l’identité | Instrument initial, présence de voix, arrivée du rythme |
| **Verse / couplet** | Développer le matériau | Densité, phrasé, accompagnement |
| **Pre-Chorus** | Préparer le refrain | Tension, changement de basse, montée vocale |
| **Chorus / refrain** | Affirmer une idée centrale | Hook, largeur, harmonies, contraste |
| **Post-Chorus** | Prolonger le refrain | Motif instrumental ou réponse vocale |
| **Interlude** | Ouvrir un espace entre sections | Dialogue instrumental, solo, changement de texture |
| **Bridge / pont** | Introduire un contraste | Nouvelle harmonie, retrait du rythme, autre perspective |
| **Breakdown** | Dépouiller le morceau | Instruments conservés et éléments retirés |
| **Build** | Accumuler de la tension | Densité croissante, répétitions, accélération perçue |
| **Drop** | Marquer une arrivée forte | Retour de basse, nouveau groove, bascule d’énergie |
| **Outro** | Organiser la sortie | Arrêt, dépouillement, résolution ou suspension |

Le « refrain » français correspond souvent au `Chorus`. La balise anglaise `Refrain` peut aussi désigner une courte phrase répétée plutôt qu’une section entière.

## **Décrire une section avec quatre questions**

Pour chaque partie :

1. Qu’est-ce qui entre ?  
2. Qu’est-ce qui sort ?  
3. Qu’est-ce qui change ?  
4. Quel effet cela produit-il ?

Exemple :

> Dans le pont, retirer la batterie et le piano. Conserver une basse espacée et la voix seule. Introduire quelques échos de trompette pour créer une sensation de distance.

## **Décrire les transitions**

La transition mérite sa propre instruction :

> Couper l’ensemble après le refrain et laisser une respiration nue avant le pont.

> Faire apparaître progressivement les subdivisions rapides avant l’entrée des breakbeats.

> Revenir au groove lent sans impact spectaculaire, en retirant simplement les batteries rapides.

Un changement devient plus convaincant lorsqu’il possède une préparation ou une conséquence.

## 

## **8\. Lyrics : séparer les paroles de leur interprétation**

Pour des paroles personnalisées, les sections peuvent être organisées avec des balises structurelles. Udio prévoit explicitement cet usage dans son éditeur de paroles.

Une organisation lisible :

| `[Verse]` `Texte chanté.` `[Chorus]` `Texte répété.` `[Instrumental Break]` `[Bridge]` `Texte contrastant.` `[Outro]` `Dernière phrase.` |
| :---- |

Les indications très détaillées que nous avons ajoutées, comme `[Verse — low, intimate, behind the beat]`, sont des descriptions créatives. Elles ne doivent pas être confondues avec une balise officiellement prise en charge dans tous les outils.

## **Ce que nos paroles cherchaient à faire**

Après ta correction, nous avons quitté le récit explicatif pour travailler :

* Les sensations physiques.  
* Les phrases interrompues.  
* Les sous-entendus.  
* Les mots courts.  
* Les répétitions transformées.  
* Les voyelles chantables.  
* Les silences.

Compare :

| *Je cache mes émotions parce que j’ai peur de me montrer vulnérable.* |
| :---- |

Avec notre approche :

| `I make it small.` `A little laugh.` `A little hum` `Behind my teeth.` |
| :---- |

La première formule explique. La seconde propose des gestes et laisse l’interprétation porter le reste.

## **Faire évoluer le sens sans raconter davantage**

Une phrase peut revenir avec un seul changement :

| `I like you almost.` |
| :---- |

Puis :

| `I don’t need almost.` |
| :---- |

Le refrain devient une progression émotionnelle, même sans scène narrative.

## 

## **9\. Construction Priorities : fixer les règles essentielles**

Cette section répond à :

> Qu’est-ce qui doit absolument rester cohérent ?

Exemples tirés de notre méthode :

* Ne pas faire jouer toutes les influences simultanément.  
* Garder la voix au centre de l’intention.  
* Transformer le motif plutôt que changer constamment de thème.  
* Réserver la distorsion aux moments qui en ont besoin.  
* Laisser de véritables espaces instrumentaux.  
* Construire le climax par contraste.  
* Éviter une conclusion automatiquement triomphante.

Pour les exclusions, formule aussi l’alternative souhaitée :

> Éviter un drop spectaculaire ; privilégier une bascule rythmique préparée par le violon.

> Éviter les cordes constamment présentes ; utiliser des interventions rares et physiques.

Cela rend la direction plus constructive qu’une longue liste d’interdictions.

## 

## **10\. Passer du brief détaillé au prompt utilisable**

Nos textes longs servent à concevoir le morceau. Pour l’utiliser dans un générateur, tu peux en extraire une version plus concentrée et répartir les instructions selon les champs disponibles.

## **Niveau 1 — Le noyau**

Garde cinq éléments :

1. Genre principal et influences.  
2. Voix.  
3. Groove.  
4. Instruments dominants.  
5. Évolution principale.

## **Niveau 2 — Les signatures**

Ajoute ce qui rend le morceau distinct :

* Un motif reconnaissable.  
* Un timbre inhabituel.  
* Une transition importante.  
* Une règle de production.  
* Une fin particulière.

## **Niveau 3 — Les détails locaux**

Place les indications propres à une section avec cette section, lorsque l’outil permet de la guider.

Voici une condensation de *Salt Bloom* :

| Soul-blues cinématographique avec voix féminine mezzo-soprano, chaleureuse et légèrement rugueuse. Début lent en 6/8, piano feutré, violon proche et basse analogique douce. Un motif de violon inachevé revient à la trompette puis au Korg MS-20. Couplets retenus, refrains progressivement ouverts, pont dub presque vide. La subdivision ternaire devient une pulsation rapide pour une section drum’n’bass, avec de brèves guitares indie-punk. Retour final dépouillé, voix plus libre, harmonie plus chaude mais sans résolution triomphante. Production tactile, saturation de bande discrète, vrais contrastes dynamiques. |
| :---- |

Cette version conserve le projet sans répéter toute la description.

## 

## **11\. Exercice : écrire ton propre prompt**

Complète ce canevas :

| `IDENTITÉ` `Le morceau est principalement…` `Les influences secondaires apportent…` `RYTHME ET HARMONIE` `La pulsation est…` `Le groove est…` `La couleur harmonique est…` `VOIX` `La voix possède…` `Dans les couplets, elle…` `Dans le refrain, elle…` `Les voix secondaires apparaissent…` `INSTRUMENTS` `L’instrument principal…` `La basse…` `La batterie…` `Les autres instruments répondent en…` `MOTIF` `L’idée musicale récurrente est…` `Elle se transforme en…` `PRODUCTION` `Le son est…` `L’espace évolue de… vers…` `Les effets interviennent sur…` `STRUCTURE` `Le début…` `La première ouverture…` `Le contraste central…` `Le point culminant…` `La sortie…` `PRIORITÉS` `Les trois éléments indispensables sont…` `Ce que je veux éviter…` |
| :---- |

Puis relis chaque ligne avec une question : « Est-ce que cela décrit quelque chose que je pourrais reconnaître à l’écoute ? »

« Un morceau exceptionnel » exprime ton ambition. « Un refrain dont la voix s’ouvre pendant que la basse descend, suivi d’un arrêt laissant une respiration seule » exprime une décision musicale. C’est cette traduction de l’intention en événements audibles qui donne sa valeur au prompt.

Prompts et paroles: 

(Les résultats obtenus avec ces prompts et paroles sont consultables sur Youtube:)

## **What remains**

##  **Prompt/Style**

Global Metadata:  
Cinematic psychedelic soul, smoky blues and noir jazz fused with trip-hop, dub, broken breakbeats, analog synthwave, raw indie-punk energy, and atmospheric drum’n’bass. A unified 86 BPM pulse, opening into a 172 BPM double-time drum’n’bass section without losing the underlying groove. D minor, with blues inflections, rich minor ninths, suspended chords, and brief luminous turns toward F major. A nocturnal journey from intimate vulnerability to restless momentum, ecstatic release, and a haunted, tender resolution. The atmosphere evokes a rain-soaked city, a nearly empty jazz club, and distant neon reflected through old glass. Vintage 1940s jazz-club intimacy, 1950s blues grit, and 1960s soul warmth form the emotional foundation; contemporary bass production and analog electronics gradually fracture that world.

Production:  
Warm, tactile, imperfect, but dynamically spacious. Dusty tape saturation, restrained vinyl crackle, subtle wow and flutter, close-miked acoustic details, spring reverb, and dark tape echoes. Preserve the grain of piano hammers, violin bow friction, trumpet breath, and vocal consonants. Narrow, almost monophonic opening gradually expands into a wide cinematic stereo field. Bass remains deep, centered, and controlled; drums become sharper and more physical as the arrangement develops. Lo-fi texture provides continuity without obscuring the instruments. Quiet passages feel genuinely exposed; climaxes feel larger through contrast, not constant loudness.

Vocal Details:  
An intimate, soulful lead voice with a smoky lower register, breathy vulnerability, and a restrained blues rasp. Verses alternate between close half-spoken confession and fluid melodic phrases, slightly behind the beat. Choruses open into longer, emotionally charged notes, with occasional cracked edges rather than polished perfection. Sparse vintage soul backing harmonies answer selected lines; never a continuous choir. During the indie-punk build, the lead becomes urgent and almost shouted for a few phrases, supported by rough unison doubles. Dub passages retain only isolated whispered words and fragments of humming, thrown into tape delay. Leave substantial instrumental space, especially during the first jazz interlude and the drum’n’bass release. Avoid relentless singing, excessive melisma, and glossy pop vocal processing.

Instrumental Identity:  
A slightly detuned upright piano carries the central motif: a short descending blues phrase that ends on an unresolved suspended note. That motif returns in different forms throughout the track—first on piano, then muted trumpet, bowed violin, and finally a filtered Korg MS-20 lead. Warm analog bass begins as a rounded, patient pulse and gradually acquires a growling resonant edge. The MS-20 supplies unstable drones, expressive filter sweeps, rough-edged melodic answers, and short bursts of controlled distortion. Muted trumpet contributes smoky jazz phrases and breathy sustained notes; violin moves from fragile solo lines to tense rhythmic bowing and soaring countermelodies. Tremolo blues guitar adds sparse bent notes, later transforming into abrasive indie-punk chords. Soft synthwave pads appear only when the harmonic space opens, creating a distant neon halo rather than dominating the arrangement.

Arrangement:

Intro — Intimate and unresolved:  
Begin with room tone, faint rain, tape hiss, and the mechanical sound of a piano key releasing. Solo upright piano introduces the descending motif with irregular pauses. A muted trumpet answers from the far background, followed by a thin violin harmonic. A low MS-20 drone slowly becomes audible beneath the final piano chord. No full beat yet; a single brushed snare pickup leads into the verse.

First Verse — Soul inside a broken groove:  
Introduce a slow trip-hop beat: deep soft kick, dry cracked snare, shuffled ghost notes, and lightly brushed cymbals. Rounded analog bass leaves deliberate gaps around the vocal. Piano chords remain sparse; tremolo guitar answers the ends of selected lines. Small breakbeat fragments flicker between phrases, hinting at a faster rhythmic world without taking over.

First Chorus — Warmth and widening:  
Open the stereo image. Add restrained soul harmonies, fuller piano voicings, a rising violin countermelody, and short trumpet responses. The drums become more syncopated while the bass remains unhurried. Let the chorus feel emotionally expansive, not maximal. End with an unexpected ensemble stop, leaving a vocal breath and a single decaying piano note.

Instrumental Interlude — Jazz slipping into dub:  
Trumpet and piano trade asymmetrical phrases over a stripped bass-and-rimshot groove. Send only the final note of each phrase into tape echo. Gradually remove the piano’s lower register and let the MS-20 answer the trumpet with a warped version of the main motif. Brief pockets of silence interrupt the echoes.

Second Verse — Friction and acceleration:  
Bring the vocal closer and more urgent. Replace brushed percussion with chopped breakbeats, tighter kicks, and sharper snare accents. Introduce palm-muted guitar, tense violin ostinatos, and a darker bass variation. Keep the first half restrained, then add rough guitar chords and short vocal doubles. Rhythmic density increases while the underlying pulse stays recognizable.

Bridge — Suspended dub space:  
Drop the full drums abruptly. Leave spacious sub bass, scattered rimshots, a distant piano chord, and whispered vocal fragments. Let spring-reverb splashes and tape echoes decay into near silence. Introduce sparse half-time dubstep-style bass responses with gritty MS-20 modulation—heavy, expressive, and separated by empty space, never a continuous wall of wobble. A rising violin note and a chopped snare pickup prepare the release.

Climax — Drum’n’bass with a soul:  
Unfold into 172 BPM rolling breaks over the same harmonic foundation. Combine crisp break edits, syncopated kick placement, warm sub bass, and a restrained distorted analog mid-bass layer. Violin carries the main motif in long sweeping phrases while trumpet delivers short, defiant accents. Piano punctuates the spaces between drum fills. Bring back the chorus vocal in brief soaring statements, followed by instrumental answers. Midway through, cut everything to voice and piano for two bars, then return with the fullest ensemble: rolling drums, raw indie-punk guitar, soul harmonies, and luminous synthwave pads.

Outro — The room returns:  
Let the fast breaks fall away, revealing the original slow groove beneath them. Remove guitar, backing voices, and synth pads one by one. The trumpet starts the central motif, but the piano quietly finishes it. End on a soft D minor ninth chord with a lingering suspended upper note, a fading violin harmonic, and the sound of the room. Allow the final tape echo to disappear naturally.

Construction Priorities:  
Build through transformation, subtraction, and contrast rather than stacking every genre at once. Give each instrument a distinct role and each transition a recognizable musical cause. Reintroduce the central motif with altered timbre, register, rhythm, or harmony so the track feels like one evolving composition. Avoid generic festival drops, constant risers, nonstop solos, and an overcrowded mix. Keep the emotional center human, imperfect, and soulful, even at maximum rhythmic intensity.

## **Paroles**

\[Intro — close, almost breathed\]

Mm…  
Not yet.  
Not all of me.

\[Verse 1 — low, loose phrasing\]

I go soft  
Where you go quiet.

A little shame,  
A little sweet.

You say my name  
Like nothing happened.

I lose my place.  
I lose the beat.

\[Pre-Chorus — held back\]

And that low, low feeling…  
There.

Don’t say it.  
Not if you don’t—

\[Chorus — soulful, open vowels\]

Oh, leave a little on me.  
Not enough to call it love.

Just the weight,  
Just the warmth—

Mm…  
I still lean into it.

Oh, leave a little on me.  
I won’t ask you what it was.

\[Instrumental — trumpet and piano, no lyrics\]

\[Verse 2 — intimate, slightly rougher\]

That almost.  
That mouth.

I know.  
I know.

I get mean  
When I need too much.

Then you go gentle—  
And I don’t know where to look.

\[Pre-Chorus — breath catching\]

There’s that low, low feeling…  
Again.

I could say it.  
You could let me.

Neither one.

\[Chorus — fuller, restrained harmonies\]

Oh, leave a little on me.  
Not enough to call it love.

Just the weight,  
Just the warmth—

Mm…  
I still lean into it.

Oh, leave a little on me.  
I won’t ask you what it was.

\[Dub Bridge — isolated phrases, long silences\]

No…  
Closer.

Not like that.

Like you—

Mm.

You know.

\[Build — raw, increasingly insistent\]

I want—  
No.

I need—  
No.

Come here.  
Come here.

Don’t make me  
Say it clean.

\[Instrumental Drop — rolling breaks, wordless vocal fragments\]

Ah—  
Oh, oh…

Mm—  
Ah…

\[Final Chorus — cracked, emotionally exposed\]

Oh, leave a little on me.  
I’ve been calling it enough.

Just the weight,  
Just the warmth—

\[Break — voice and piano\]

I said I wouldn’t ask.

\[Full Ensemble — lead and answering harmonies\]

But was it?  
Was it love?

Oh, leave a little on me.

A little—  
A little—

No.  
That’s not enough.

\[Outro — almost whispered\]

I go soft  
Where you go quiet.

Mm…

You know that.

You know.

**Under my tongue**

**Prompt/Style**  
Global Metadata

Cinematic alternative soul, dirty blues, broken jazz, dub-heavy trip-hop, angular breakbeat, analog synthwave, restrained dubstep, and a late surge of raw drum’n’bass with indie-punk friction. A slow 92 BPM foundation that periodically reveals its 184 BPM double-time potential. F-sharp minor, colored by minor sixths, chromatic blues passing tones, suspended ninths, and brief warm openings into A major. Seductive but unsettled: physical closeness, withheld words, a pulse that refuses to relax. Not a heartbreak ballad; an intimate push-and-pull between appetite, embarrassment, and surrender.

The emotional progression moves from dry, close tension to crooked rhythmic confidence, through a suspended dub passage, into a fast instrumental release, then returns to an altered version of the opening. Vintage 1940s small-combo jazz phrasing, 1950s amplifier grit, and 1960s soul call-and-response inhabit the same space as abrasive analog synthesis and modern broken drums. Avoid nostalgic pastiche: the old textures should feel alive, handled, and slightly dangerous.

Production and Sonic Perspective

Begin narrow, tactile, and almost uncomfortably close. Audible breaths, felted piano attacks, string friction, faint amplifier hum, and short room reflections. Use tape grain and occasional pitch instability rather than continuous loud vinyl crackle. Keep the first vocal unusually dry; let reverberation emerge as emotional distance increases.

Drums should alternate between soft-edged sampled grit and sharp live-room transients. Preserve silence around the kick and bass. Use selective distortion on parallel drum layers, not across the entire mix. Dub echoes travel across the stereo field, but the sub bass and lead vocal remain firmly centered. The biggest section gains scale through widened instrumentation and faster rhythmic movement, not a crushing master. Avoid a permanently muffled lo-fi sound: let trumpet brass, snare wire, and violin bow texture cut through when needed.

Vocal Details

A close, androgynous soul voice with a warm chest register, an occasionally frayed upper edge, and conversational phrasing that slips between melody and speech. The first verse sounds as though the singer is trying not to reveal how much a touch matters. Short phrases, swallowed endings, slight hesitation before emotionally exposed words.

The chorus uses an ascending melodic gesture followed by a low, descending answer. Stretch open vowels; keep consonants intimate and physical. A second voice appears only on selected words, sometimes answering, sometimes overlapping a fraction too late. No constant vocal doubling.

During the build, the lead becomes blunt and rhythmically insistent without turning into theatrical shouting. In the fast section, use only brief vocal hooks and breaths between instrumental phrases. The final return is quieter than the first chorus, but less guarded. Avoid ornamental runs that distract from the words.

Instrumental Identity

A felted upright piano introduces a clipped three-note figure followed by a low, slightly dissonant chord. This motif behaves like an interrupted sentence: it rarely completes until the final section.

A Korg MS-20 provides the principal analog bass voice: rounded and almost clean at first, then increasingly nasal, unstable, and harmonically rough. Separate the deepest sub layer from the more distorted midrange so the low end stays defined.

Violin begins with dry pizzicato responses, moves into close-miked double-stops, and eventually opens into long bowed lines above the fast drums. Trumpet starts unmuted, with breathy low notes and brief blues-inflected falls; use a mute only in the dub passage to create a smaller, more distant voice.

Electric guitar contributes clipped offbeat chords, amplifier tremolo, and occasional scraped strings. Save its raw indie-punk character for a short late eruption. A softly pulsing analog synth pad introduces the synthwave influence without imposing a separate retro-pop song on the arrangement.

Arrangement

\[Intro — exposed pulse\]

Start with two dry piano notes, a pause, then the unfinished three-note motif. Add a quiet foot-tap-like kick and a close vocal breath. Violin pizzicato answers from one side of the stereo image. The MS-20 bass enters before the full drums, making the silence feel charged rather than empty.

\[Verse 1 — restrained physical tension\]

Introduce a crooked trip-hop groove with a low kick, short rimshot, loose ghost snares, and sparse shuffled hats. The vocal occupies the foreground. Piano answers only after selected lines; guitar adds one clipped chord at a time. Keep trumpet absent until the final phrase, where a low brass note quietly changes the emotional color.

\[Chorus 1 — lift without explosion\]

Shift to a more mobile bass pattern and a wider snare sound. Bring in bowed violin, open piano voicings, and brief soul backing responses. The vocal melody rises while the bass descends, creating a sensation of reaching and being pulled back. Leave the final chorus phrase almost unsupported.

\[Post-Chorus — crooked instrumental hook\]

Trumpet repeats a transformed version of the piano motif over a syncopated breakbeat. Piano becomes percussive, guitar scratches against the groove, and the MS-20 answers with a short resonant growl. Make this section memorable enough to function as a second hook without vocals.

\[Verse 2 — more exposed, less polite\]

Remove the broad pads and return to a dry mix, but retain the busier drums. The singer sounds less composed. Add violin double-stops and occasional distorted bass tails between phrases. Midway through, strip the groove to kick, bass, and voice for four bars; reintroduce the breakbeat slightly before the next vocal entry.

\[Chorus 2 — interrupted release\]

Return with stronger backing responses and a rougher guitar texture. Let the arrangement approach its first real peak, then cut the final sustained vocal into a long tape echo. Do not resolve the harmony.

\[Dub Bridge — suspended contact\]

Keep a deep, widely spaced bass pulse, isolated rimshots, muted trumpet fragments, and harmonics from the violin. Piano disappears. The MS-20 produces slow filter movements and two or three short, heavy dubstep-style responses separated by silence. Whispered vocals remain close while their echoes recede. No predictable snare-roll riser.

\[Build — friction gathering\]

Introduce a short repeated vocal phrase, dry at first. Gradually add clipped guitar strokes, increasingly dense violin bowing, and sliced drum fragments that reveal the double-time feel. Briefly remove the bass just before the transition so its return has physical weight.

\[Fast Release — instrumental drum’n’bass\]

Open into 184 BPM rolling breaks over the original slow harmonic rhythm. Keep the bass phrasing spacious rather than matching every drum hit. Trumpet and violin trade contrasting statements: short, ragged brass phrases against sustained, aching strings. Let the piano motif finally complete once, then break it apart again.

Halfway through, introduce eight bars of abrasive indie-punk guitar and urgent vocal fragments. Remove the guitar before it dominates. Finish with an exposed drum fill, not a festival-style impact.

\[Final Chorus — quiet surrender\]

Return suddenly to the slow pulse. Retain only bass, soft snare, piano, and the lead voice for the first half. The backing singer now answers clearly instead of hiding in the mix. Violin and a faint analog pad enter for the final lines. The emotional release comes from a change in delivery, not another increase in volume.

\[Outro — unfinished, but warmer\]

The piano plays the complete motif without its usual interruption. A low trumpet note bends gently into the final harmony. Let the bass stop before the other instruments. End with a close vocal fragment, a small room reflection, and the mechanical release of the piano keys.

Construction Priorities

Use rhythmic displacement, sudden subtraction, and changing instrumental roles to create variety. Keep jazz phrasing conversational, blues texture physical, dub spacious, and the drum’n’bass release connected to the original groove. Never make every influence equally loud at once. Avoid generic rain ambience, cinematic trailer percussion, continuous bass wobble, ornamental string washes, and an oversized final chorus.

## **Paroles**

\[Intro — dry, close\]

Mm…

I had it.  
Right here.

Now look at me.

\[Verse 1 — low, hesitant\]

You get close.  
I get clever.

Something small,  
Something cruel.

Then your thumb  
Along my wrist—

There goes  
My little mouth.

\[Pre-Chorus — slightly lifted\]

All that nerve  
Until you look.

Then I’m—  
Then I’m—

\[Chorus — ascending, then falling\]

Under my tongue,  
Honey, it’s there.

Warm little word  
I won’t give air.

You lean in.  
I let you.

Oh—  
More than I meant to.

\[Post-Chorus — sparse backing responses\]

More than—  
Mm.

More than I meant.

\[Instrumental — trumpet, piano, broken drums\]

\[Verse 2 — rougher, more rhythmic\]

I like your hands.  
Hate that you know.

Say something stupid.  
Let me go cold.

No, not sweet.  
I can’t use sweet.

Not with your knee  
Still touching me.

\[Pre-Chorus — swallowed endings\]

I had a way  
To make this small.

Then you—  
Then you—

\[Chorus — fuller, overlapping responses\]

Under my tongue,  
Honey, it’s there.

Warm little word  
I won’t give air.

You lean in.  
I let you.

Oh—  
More than I meant to.

\[Dub Bridge — whispers, long gaps\]

Don’t move.

…No.

I didn’t say  
Move away.

Your hand.

There.

Leave it.

\[Build — dry, increasingly insistent\]

I said easy.  
I said slow.

I said things  
I don’t know.

A little nearer.  
A little—

Ah.

There goes my mouth.

\[Fast Release — instrumental, brief vocal fragments\]

Oh, you—  
You—

Mm, don’t.

Don’t stop.

\[Break — bass cuts, voice exposed\]

I don’t like  
How much.

\[Final Chorus — slow pulse, less guarded\]

Under my tongue,  
Honey, it’s there.

That little word—

You move my hair.

I lean in.  
You let me.

Oh—  
You let me.

\[Final Refrain — quiet call and response\]

More than I meant to.  
(More.)

More than I meant to.  
(Mm.)

I had something—

Never mind.

\[Outro — close, almost spoken\]

Stay like that.

Just—

Like that.

**Velvet Teeth**

**Prompt/Style**

Global Metadata

Female-led cinematic noir soul, crooked vintage jazz, electric blues, dubwise trip-hop, fractured breakbeat, analog synthwave, and volatile drum’n’bass, with brief flashes of dubstep weight and indie-punk abrasion. A 100 BPM foundation that opens into a 150 BPM fast-break passage through a deliberate metric transition: the original swung eighth-note triplets become the new straight eighth-note pulse. Make the change feel like the same body suddenly moving differently, not an unrelated track being introduced.

C minor, with blues thirds, diminished passing chords, minor-major seventh tension, and occasional warm E-flat major voicings. The mood is provocative, restless, amused, then unexpectedly vulnerable. Desire expressed through resistance, rhythmic confidence, and small failures of composure. No tragic romance narrative, no sentimental cinematic grandeur.

1940s small-band swing supplies the phrasing, 1950s electric blues supplies the bite, and 1960s female soul supplies the emotional authority. Contemporary drums, Korg MS-20 synthesis, deep dub space, and damaged synthwave textures destabilize that foundation. The result should feel intimate and unruly, elegant without behaving politely.

Female Vocal Identity

A distinctive female contralto with a dark, velvet-textured lower register, clear diction, a slightly grainy chest voice, and an agile upper register used sparingly. Mature, physically present, expressive without sounding theatrically seductive. No whispery delivery throughout, no sugary pop brightness, no exaggerated vintage impersonation.

Verses use rhythmically playful phrasing: short notes, delayed entrances, clipped consonants, and occasional low melodic slides. She sometimes lands ahead of the snare, sometimes lets a phrase drag behind it. A barely audible smile can sharpen one line; the next should sound unexpectedly sincere.

The main hook is compact and percussive rather than a long soaring chorus. Stretch only the last vowel of selected phrases. Let breath, slight rasp, and a momentary loss of vocal steadiness carry the emotional information.

A second female vocal layer occasionally answers in a dry lower harmony. During the vulnerable middle section, remove all doubles and effects: one woman, one microphone, audible distance changes as she leans away. The final refrain returns with greater rhythmic certainty but less emotional armor.

Use wordless chest-register hums, brief open-vowel cries, and occasional broken syllables as musical gestures. Avoid continuous ad-libs, decorative melisma, and a choir that fills every gap.

Production and Sonic Character

Open with a lively, narrow-band ensemble sound, then reveal the full low end after the first vocal entrance. The vintage texture should come from short room reflections, tape compression, amplifier grit, and slightly unstable pitch—not a blanket of crackle.

Piano attacks are woody and audible. Trumpet has real breath and occasional brassy edge. Violin remains close enough to hear bow pressure. Drums combine dry acoustic snare, chopped break fragments, shuffled hats, and occasional brushed pickups.

Use spring reverb as an accent, not a permanent wash. Tape delays should answer specific phrases and sometimes stop abruptly. Introduce stereo width selectively: a trumpet answer on one side, a violin scrape on the other, an unstable analog pad unfolding behind the chorus.

Keep sub bass centered and spacious. Reserve the heaviest distortion for short passages. Allow the middle section to become almost naked, making the subsequent rhythmic return feel physical without relying on excessive loudness.

Instrumental Identity

The central hook is a five-note syncopated figure with a repeated note and a descending chromatic tail. Introduce it on unmuted trumpet, transfer it to pizzicato violin, then reshape it into a snarling MS-20 phrase during the fast passage. Its rhythm remains recognizable even as its tone changes.

Upright piano uses clipped jazz voicings, blues grace notes, and occasional low-register accents. Instead of maintaining a constant harmonic bed, it interrupts, provokes, and answers the singer. In the middle section, it finally sustains full chords.

Bass alternates between a plucked, upright-like analog patch and a smooth deep sub tone. The Korg MS-20 adds nasal filter articulation, unstable sustained notes, and brief distorted replies. Keep the resonant bass gestures short enough to preserve the groove.

Violin begins percussively with pizzicato and short bowed attacks. Later, it develops a rough, singing melodic line rather than a glossy orchestral wash. Trumpet is bright and cheeky at first, muted and hesitant in the middle, then returns in short forceful bursts.

Electric guitar supplies dry blues stabs, muted rhythmic scratches, and a few sharply bent notes. Its indie-punk eruption should be brief, ragged, and rhythmically necessary. Synthwave enters through a low, pulsing analog arpeggio and a dim sustained pad, not through a dominant retro-pop lead.

Arrangement

\[Cold Open — already moving\]

Begin immediately with trumpet playing the five-note hook over handclaps, a short piano stab, and a dry shuffled snare. No ambient introduction. The singer enters before the phrase finishes, almost interrupting the band. After her first two lines, introduce the bass and widen the frequency range.

\[Verse 1 — crooked confidence\]

Establish the 100 BPM swung trip-hop groove. Use an economical kick pattern, snare ghost notes, and scattered break edits. Piano and voice trade short gestures; pizzicato violin occupies the vocal gaps. Keep the harmonic rhythm slow while the small instrumental details feel quick and impatient.

\[Hook 1 — compact and physical\]

Straighten selected drum accents without removing the underlying swing. Introduce a descending bass line, a low female response, and a short synth pulse. The lead hook is rhythmically simple enough to remember after one hearing. End with a clipped ensemble accent rather than a sustained chord.

\[Instrumental Turn — jazz with sharp elbows\]

Trumpet and violin trade the central figure, each altering its ending. Piano inserts blues chords between their phrases. Guitar adds scraped-string pickups. Let one unexpected extra beat extend the final turnaround before the verse returns.

\[Verse 2 — confidence beginning to slip\]

Reduce the brass and bring the female voice closer. Her phrasing becomes less teasing and more direct. Add darker piano inversions and a warmer bass tone. Halfway through, drop the snare for four bars, leaving kick, finger snaps, and a quiet violin note beneath the voice.

\[Hook 2 — stronger, then abruptly exposed\]

Return the full groove with rougher drum texture and a higher trumpet response. Add a single upper vocal harmony on the last hook line. Cut the ensemble before the expected final accent, leaving her last syllable dry and unprotected.

\[Middle Eight — the private voice\]

No beat for the opening four bars. Solo female voice and sustained upright piano, with an occasional muted trumpet breath between lines. No ornamental string swell. Let the singer abandon her earlier rhythmic confidence and leave unfinished phrases hanging.

A deep dub bass pulse then enters, followed by isolated rimshots and long, dark echoes. The MS-20 produces two heavy, slow bass responses with dubstep-like weight, each followed by empty space. Keep this passage intimate rather than spectacular.

\[Metric Turn — a new gait\]

Introduce brushed triplet subdivisions at the original tempo. Gradually replace them with clearer snare and hat articulations. Reinterpret that subdivision as straight eighth notes at 150 BPM. Let a violin pickup lead directly into the new fast pulse; avoid a conventional riser or countdown.

\[Fast Passage — restless release\]

Build rolling drum’n’bass breaks at 150 BPM while retaining broad, patient harmonic changes. The lead vocal appears only in short fragments; the instruments carry the movement. MS-20 bass plays a rough version of the central hook, violin stretches above it, and trumpet punctuates the spaces between break edits.

Introduce six to eight bars of raw indie-punk guitar, then remove it suddenly. Follow with a brief drums-and-voice exchange: one vocal phrase, one chopped break response, repeated twice. Keep the section lean, mobile, and slightly unpredictable.

\[Final Hook — back in the body\]

Return to the 100 BPM groove through an exposed triplet fill that restores the original subdivision. Do not make the final hook bigger than the fast passage. Use bass, drums, piano, and the woman’s voice; add only a few trumpet answers.

She now sings the hook with less attitude and more intention. The low backing voice disappears, leaving the lead to own the final words.

\[Outro — a grin with something underneath\]

Repeat the bass figure while the piano gradually changes its chord above it. Trumpet starts the hook but stops halfway. The singer delivers one final fragment slightly late, almost speaking. Finish with a dry kick, a short guitar scrape, and a piano chord whose upper note remains unresolved. No long cinematic fade.

Construction Priorities

Create contrast through swing versus straight phrasing, dry intimacy versus dub distance, and teasing confidence versus sudden emotional exposure. Keep the female lead central even during instrumental sections by letting instruments echo her phrasing. Give each genre a specific function rather than stacking them simultaneously. Avoid cabaret caricature, electro-swing clichés, relentless bass wobble, glossy string arrangements, and a triumphant final chorus.

## **Paroles**

\[Cold Open — low, amused\]

Mm.  
You like that?

I barely touched you.

\[Verse 1 — clipped, playful\]

All that slow talk.  
All that ease.

Then one little  
Catch in your breathing.

I bite back  
Something sweet.

Let it sit.  
Let it—

Mm.

\[Pre-Hook — leaning into the rhythm\]

I could be nice.  
I could behave.

But you keep looking  
At me that way.

\[Hook — compact, low, memorable\]

Say less.  
Come close.

I like you  
Almost—

Almost sure.  
Almost mine.

Don’t go gentle  
All the time.

\[Instrumental Turn — trumpet and violin, no lyrics\]

\[Verse 2 — closer, less playful\]

I wear that laugh  
A little loud.

You hear the thin bit  
Underneath.

Don’t be kind  
So suddenly.

I had my mouth  
Around a tease.

Now it won’t—  
Now it won’t—

\[Pre-Hook — small crack in the voice\]

You touch my face.  
I lose the line.

That wasn’t fair.

Do it twice.

\[Hook — stronger, low answering harmony\]

Say less.  
Come close.

I like you  
Almost—

Almost sure.  
Almost mine.

Don’t go gentle  
All the time.

\[Middle Eight — bare voice and piano\]

No, wait.

The other way.

Your palm…  
Not your fingers.

I know.  
I’m difficult.

Stay.

\[Dub Section — fragments, dark echoes\]

That little—

Mm.

Don’t laugh.

I felt it.

I felt—

\[Metric Build — rhythmic, increasingly breathless\]

Too near.  
Not near enough.

Too much.  
Not—

Your mouth.  
My nerve.

My nerve.  
Your—

\[Fast Passage — brief vocal hooks between instrumental phrases\]

Ah, there.  
There.

You got me—

No.  
Not yet.

\[Instrumental Release — rolling breaks, violin, MS-20\]

\[Break — female voice alone\]

I’m not teasing now.

\[Final Hook — grounded, no backing voice\]

Say less.  
Come close.

I don’t need  
Almost.

Put your hand  
Back into mine.

You can go gentle.

Take your time.

\[Outro — low, nearly spoken\]

Mm.

That’s different.

Don’t—

No.

Keep going.

**Salt Bloom**

**Prompt/Style**

Global Metadata

Female-led cinematic blues-soul, chamber jazz, asymmetrical trip-hop, dub, fractured breakbeat, analog synthwave, and emotionally charged drum’n’bass, with short bursts of indie-punk guitar and restrained dubstep bass design. Begin in a slow 6/8 feel at dotted-quarter \= 64 BPM. Each bar contains two broad pulses with three eighth notes inside each pulse. Later, reinterpret those eighth notes as a straight 192 BPM quarter-note pulse for the fast broken-beat passage. Preserve the recognizable melodic material across the transition so the acceleration feels like an unfolding of the original rhythm.

A minor, colored by Dorian sixths, blues inflections, open fifths, and occasional unresolved major sevenths. The principal harmonic movement circles around A minor, D major, and F major before discovering a warmer C major voicing near the end. Emotional character: withheld grief, stubborn vitality, a sudden opening, and an imperfect sense of release. Neither a conventional heartbreak ballad nor a victory anthem.

1940s chamber-jazz intimacy, 1950s slow-blues weight, and 1960s female soul intensity form the human foundation. Dub supplies negative space; trip-hop supplies weight; breakbeat and drum’n’bass expose the nervous energy beneath the slow surface. Analog synthwave appears as a horizon of sustained light rather than a retro-pop costume.

Female Vocal Identity

A female mezzo-soprano with a warm, textured middle register, a clear but slightly weathered upper register, and an audible shift between guarded speech-like singing and full-bodied sustained notes. The voice should feel unmistakably individual: a little air before some attacks, a small rasp when pressure increases, and occasional uneven vibrato at the end of an exposed phrase.

Unlike a smoky contralto performance, this lead has forward resonance and a raw, almost folk-like directness. Verses are close and unadorned. The first refrain stays controlled; later refrains open into longer vowels and a few urgent upper notes without turning into constant belting.

Use a single lead voice for most of the track. Introduce distant female unison layers only during the fast release, slightly misaligned like several versions of the same person trying to arrive together. No continuous harmony bed. One brief octave double can underline the emotional peak.

Wordless singing is important: low closed-mouth humming at the beginning, open “ah” vowels in the instrumental transition, and a final melodic fragment that remains unfinished. Avoid seductive whisper clichés, flawless pop smoothing, ornamental runs on every line, and theatrical sobbing.

Production and Sonic Perspective

Start with audible physical detail rather than environmental ambience: a violin bow catching the string, the felted attack of a piano note, a breath close to the microphone. Warm tape compression, faint amplifier noise, and slight pitch drift create age without muffling the entire track.

The opening has depth but little width. Piano sits close and slightly left; violin is dry and slightly right; the vocal remains centered. Trumpet begins far behind them and gradually approaches as the arrangement becomes more assertive.

Drums should retain rough acoustic edges. Combine a deep kick, brushed snare friction, loose toms, and chopped break transients. The fast passage becomes clearer and more sharply articulated, but not brighter everywhere at once.

Dub sends act as temporary absences: an instrument stops playing while its echo continues moving. Keep bass fundamentals centered, preserve space around the kick, and reserve strong MS-20 distortion for selected replies. The quietest section must genuinely feel smaller than everything around it.

Instrumental Identity

A solo violin introduces the principal motif: a rising fourth, a repeated upper note, then a descending phrase that stops before reaching its expected resting point. The melody initially feels caught on something. Piano later supplies the missing resolution; trumpet offers a rougher, more defiant version; the MS-20 fragments it into short rhythmic cells.

Felted upright piano provides open intervals, spare blues voicings, and occasional low notes separated by wide gaps. Let sustained chords emerge only when the voice becomes emotionally exposed.

The Korg MS-20 supplies a soft, breathing analog bass in the slow sections and a resonant, serrated mid-bass voice in the fast passage. Keep a separate restrained sub layer beneath the most distorted gestures.

Violin moves between long single-note bowing, tense tremolo, and short repeated figures. Avoid ornamental orchestral swells. Its physical bow pressure should mirror changes in vocal intensity.

Trumpet uses an open, slightly frayed tone, blues bends, and incomplete melodic answers. Electric guitar begins with sparse sliding notes and amplifier tremolo, then develops a brief raw indie-punk chord pattern. Slow analog pads and a simple sequenced pulse provide the synthwave dimension only after the first major transformation.

Arrangement

\[Prelude — a held breath\]

Begin with solo violin sustaining the upper note of the motif, then descending without resolving. A low female hum enters beneath it. Felted piano plays two widely spaced notes. No drums, no full bass line. Let the first lyric arrive before a stable harmonic center has fully formed.

\[Verse 1 — slow circular motion\]

Establish the 6/8 pulse with a deep kick on the first broad beat and a brushed snare gesture around the second. Avoid a rigid pattern; let the percussion breathe around the singer. Introduce a rounded analog bass and sparse piano intervals. Violin answers only twice, leaving the voice exposed.

\[Refrain 1 — withheld expansion\]

Bring in a short trumpet phrase and wider piano voicings. The singer lengthens her vowels but stays below her strongest register. Add one sustained guitar note with slow tremolo. End on a chord that feels suspended rather than climactic.

\[Instrumental Passage — blues in broken reflections\]

Piano and trumpet trade variations of the unfinished motif. Introduce quiet chopped percussion that suggests a straighter subdivision beneath the swaying meter. Violin pizzicato briefly replaces bowed strings. A tape echo repeats one trumpet note until its pitch begins to blur.

\[Verse 2 — pressure beneath the surface\]

Bring the voice closer and remove most reverb. The bass grows more mobile. Snare ghosts and low toms disturb the original rocking pattern. Guitar adds rough, isolated double-stops. Midway through, let the lead sing one line without piano or bass, then bring the ensemble back on an unexpected pickup.

\[Refrain 2 — first real opening\]

The singer reaches a brighter upper register. Violin now follows a countermelody rather than answering between lines. Add a dim analog pad and heavier drum accents. Let the last phrase repeat once with fewer words and greater physical intensity, then cut everything except the voice’s natural room decay.

\[Still Point — no rhythmic safety\]

Solo voice and piano. The piano finally completes the original violin motif, but the singer leaves her phrase unfinished. Keep the timing flexible. A faint trumpet breath appears after a long pause. No cinematic riser, no automatic string swell.

\[Dub Chamber — weight and distance\]

Reintroduce the bass as a widely spaced pulse. Use isolated rimshots, filtered guitar echoes, and two slow MS-20 bass gestures with dubstep-like mass. Violin harmonics hang above the empty space. Vocal fragments drift into delay, while the next live phrase remains dry and close.

\[Pulse Transformation — the hidden speed emerges\]

Make the original eighth-note subdivision increasingly explicit through violin repetitions, brushed percussion, and a restrained analog sequence. Reinterpret that subdivision as the quarter-note pulse of the 192 BPM section. The main motif remains broad while the drums become fast, creating continuity beneath the change in physical energy.

\[Fast Release — fierce, not triumphant\]

Rolling drum’n’bass breaks, controlled sub bass, fragmented MS-20 replies, and long vocal vowels rather than a dense new verse. Violin carries the melody above the drums; trumpet cuts across it with short rough accents.

Introduce a brief indie-punk guitar eruption midway through, with imperfect downstrokes and an audible amplifier edge. Let the female lead deliver two forceful lyric fragments, then retreat into wordless singing. Remove guitar before the section becomes a wall of sound.

\[Afterimage — changed ground\]

Strip away the fast breaks but do not immediately restore the original drum pattern. Leave a slow bass pulse, piano, and the lead voice. The earlier refrain returns with altered words and more relaxed timing. Introduce the warmer C major voicing without erasing the minor undertone.

\[Coda — movement without closure\]

The violin plays the motif once more, this time reaching its resting note. The voice holds a different note above it, preventing a neat emotional conclusion. Trumpet disappears first, then bass. Finish with piano resonance, a quiet female hum, and the sound of the bow lifting away from the string.

Construction Priorities

Build the track around a changing relationship to one melodic motif and one rhythmic subdivision. Contrast circular motion with forward motion, held breath with sustained voice, and isolated detail with collective force. Give the fast section enough space to develop instead of treating it as a short decorative drop. Keep the final release human and ambiguous. Avoid electro-swing gestures, constant noir imagery, festival impacts, generic empowerment phrasing, and an oversized closing chorus.

## **Paroles**

\[Prelude — low humming, then a bare phrase\]

Mm…

It comes up.  
I swallow.

Again.

\[Verse 1 — close, restrained\]

I make it small.  
A little laugh.

A little hum  
Behind my teeth.

You ask me twice.

I smooth my skirt.  
I say I’m tired.

It isn’t sleep.

\[Pre-Refrain — the phrase begins to open\]

There’s a sound  
I nearly make.

I feel it rise—  
I feel it—

\[Refrain — long vowels, restrained intensity\]

Oh, it sits so high.  
Oh, it goes so deep.

I can hold my mouth.  
I can’t hold the heat.

Let it come.  
Let it catch.

If I lose the note,  
Don’t give it back.

\[Instrumental — piano and trumpet, no lyrics\]

\[Verse 2 — firmer, with a rough edge\]

I’ve been good  
At sounding fine.

Even now—  
That little smile.

My heel keeps time.  
My hands stay flat.

Something in me  
Won’t sit like that.

\[Pre-Refrain — more exposed\]

Not a pretty sound.  
Not the one I meant.

A little higher—

Then it bends.

\[Refrain — brighter, less controlled\]

Oh, it sits so high.  
Oh, it goes so deep.

I can hold my mouth.  
I can’t hold the heat.

Let it come.  
Let it catch.

If I lose the note—

Let me lose it.

\[Still Point — voice and piano, free timing\]

No.

Don’t help me yet.

I’m so used to—  
I’m so—

Mm.

There.

That’s where.

\[Dub Chamber — isolated phrases, long gaps\]

Salt.

At the edge  
Of my mouth.

I thought—

No.

Let it out.

\[Pulse Transformation — repeating, gathering force\]

A little more air.

A little more—

Not softer.  
Not sweet.

Let it scrape.  
Let it breathe.

\[Fast Release — open vowels between lyric fragments\]

Ah—

I didn’t know  
I could sound like—

Ah—

That low.  
That wide.

Still me.  
Still mine.

\[Instrumental Release — rolling breaks, violin, trumpet\]

\[Afterimage — quiet, unguarded\]

Oh, it ran so high.  
Oh, it went so deep.

Now my mouth is dry.

Now I want to sing.

Nothing clean.  
Nothing fixed.

Just a little room  
For this.

\[Coda — almost spoken, then hummed\]

I’m tired now.

It isn’t sleep.

Mm…

Again.


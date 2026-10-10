# Building a Detailed Music Prompt

A music prompt does more than name a style. It can describe a voice, a rhythm, a sonic palette, an emotional progression, and the way instruments respond to one another.

The central principle behind our prompts is direction: rather than listing what we want to hear, we explain how those elements should work together.

Compare these two formulations:

> Soul, blues, jazz, drum’n’bass, piano, violin, trumpet, female vocals.

And:

> An intimate female soul voice over a slow trip-hop groove. The piano establishes blues-colored harmony, the violin introduces an unfinished motif, and the trumpet answers it. In the second half, the drums move into drum’n’bass while the chords retain their slow harmonic rhythm.

The first describes ingredients. The second proposes a composition.

## 1. Before You Begin: Distinguishing Intention from Control

The prompts we need to write are highly detailed composition briefs.

Their headings—`Global Metadata`, `Vocal Identity`, `Instrumental Identity`, and so on—organize the instructions to make them readable. They are not universal commands or mandatory syntax.

We also need to distinguish between:

- What you want: a key, a type of voice, a particular transition.
- What you describe: the words used to convey that intention.
- What the generator actually produces: an interpretation that you need to listen to and evaluate.

A precise instruction does not guarantee exact execution. Udio, for example, presents its tags as ways to guide creation, not as a deterministic score.

In this lesson, the examples are therefore working formulations, not commands with guaranteed results.

## 2. Global Metadata: Defining the Overall Identity

This section answers the question:

> What kind of track are we trying to create?

It contains the choices that should remain coherent across the entire composition.

### A. Genres and Their Hierarchy

You can specify:

- A main genre.
- Secondary influences.
- Styles reserved for particular passages.
- The role of each influence.

In our case, writing “soul, blues, dub, drum’n’bass” does not say which one dominates.

A more useful formulation would be:

> Soul defines the voice and the emotion. Blues colors the melodic phrases. Trip-hop provides the initial groove. Dub shapes the bridge. Drum’n’bass enters during the instrumental climax.

The blend becomes a distribution of functions rather than an accumulation.

### B. Tempo

Tempo describes the speed of the pulse, usually in BPM: beats per minute.

You can specify:

- A main tempo.
- A slow or fast feel.
- An acceleration.
- A passage perceived in half-time or double-time.

An example from our first musical direction:

> An 86 BPM pulse, with a double-time drum section at 172 BPM.

The intention is to maintain a clear relationship between the slow passage and the fast passage.

For a more accessible prompt:

> The drums become twice as fast during the climax, but the chords remain broad and spaced out.

This formulation also expresses the intended effect: more rhythmic activity without speeding up every element.

### C. Meter and Groove

Tempo alone is not enough to describe movement.

You can add:

- A time signature: 4/4, 3/4, 6/8…
- A straight or lilting rhythm.
- Swing.
- Syncopation.
- A performance placed slightly behind the beat.
- A rigid, loose, broken, or floating groove.

In *Salt Bloom*, the 6/8 opening was intended to create a circular sway. In *Velvet Teeth*, swing made the rhythm more playful and less straight.

Examples:

> A slow, swaying groove with ternary subdivisions and a relaxed snare.

> Straight, restless drums contrasting with a voice placed slightly behind the beat.

The second example does not simply describe two elements: it describes their relationship.

### D. Key and Harmonic Colors

You can suggest:

- A major or minor key.
- A mode.
- Extended chords.
- Chromatic passages.
- Stable or ambiguous harmony.
- A clear or suspended resolution.

Some useful explanations:

| Term | What you want the listener to hear |
| --- | --- |
| Minor key | A color that may feel dark, tense, or introspective, depending on the context |
| Extended chords | More colorful chords, for example with sevenths or ninths |
| Chromaticism | Semitone movements that introduce friction |
| Suspended chords | A sense of harmonic anticipation |
| Open fifths | Open intervals that provide less information about major or minor character |
| Unresolved ending | An ending that does not create a sense of complete closure |

You do not have to know an entire chord progression. You can write:

> Minor harmony with open voicings and a few warmer moments, without a triumphant resolution.

### E. Atmosphere and Emotional Trajectory

Distinguish the starting atmosphere from its evolution.

A simple list:

> Intimate, dark, intense.

A trajectory:

> The track begins restrained, becomes restless, reveals a central vulnerability, and then releases its tension without becoming euphoric.

In our variations, this trajectory profoundly changed the track:

- First version: intimate confession → tension → explosion → fragile return.
- *Velvet Teeth*: playful confidence → loss of control → sincere closeness.
- *Salt Bloom*: restraint → pressure → opening up → imperfect calm.

### F. Eras and Aesthetic References

“1940s, 1950s, 1960s” can remain very vague.

Specify what you are borrowing:

> The intimacy of a small 1940s jazz ensemble, the amplifier grit of 1950s blues, and the vocal responses of 1960s soul.

You are selecting characteristics rather than asking for three simultaneous historical recreations.

## 3. Vocal Identity: Directing the Voice

This section answers:

> Who is singing, with what timbre, intention, and progression?

The type of voice and its delivery are among the elements you can describe in a musical direction.

### A. Vocal Profile

You can specify:

- Female, male, or androgynous vocals.
- A solo voice, duet, or ensemble.
- A low, middle, or high register.
- Contralto, mezzo-soprano, soprano, tenor, and so on.

Be careful: tessitura and timbre are not the same thing. A low voice is not automatically raspy, and a high voice is not necessarily light.

Our last two female voices were therefore different:

> A dark, velvety contralto with a prominent lower register.

Then:

> A brighter mezzo-soprano with a textured middle register and slightly rough upper notes.

### B. Timbre

You can ask for a voice that is:

- Breathy.
- Dry in tone.
- Grainy.
- Warm.
- Metallic.
- Clear.
- Veiled.
- Slightly cracked.
- With little or plenty of vibrato.

Example:

> A warm, textured female voice with a slight rasp as the intensity increases.

This is more precise than:

> A beautiful, emotional voice.

### C. Phrasing

Phrasing describes how the words come alive within the rhythm:

- Late entrances.
- Clipped syllables.
- Swallowed phrase endings.
- Extended vowels.
- Half-spoken, half-sung delivery.
- Short phrases separated by silence.
- Placement ahead of or behind the drums.

Example:

> The verses use brief phrases and held-back word endings. The chorus opens the vowels without multiplying embellishments.

### D. Progression of the Performance

Do not describe only a fixed voice.

> At first, she seems to control every word. In the bridge, she abandons that confidence. The final chorus remains gentle, but the phrases are more direct.

This gives the performance itself an evolution.

### E. Supporting Voices

Specify their function:

- Double selected phrases.
- Answer the lead vocal.
- Sustain a note.
- Add an octave.
- Create imperfect unison.
- Appear only at the climax.

Example:

> A second female voice answers only the last two lines of the chorus, then disappears during the bridge.

### F. Placement of the Voice in the Sound

You can also specify:

> A close, centered, almost dry vocal in the verses; more distant and surrounded by echoes in the dub passage.

“Dry” here means with little audible reverberation. This is not the same thing as a dry vocal timbre.

## 4. Instrumental Identity: Giving Instruments a Role

This section answers:

> What does each instrument do within the composition?

A list of instruments is useful, but their roles make the prompt much more informative. Instrumentation refers to the instruments used in a track.

### A. Describing the Sound

For each instrument, specify as needed:

- Its sonic texture.
- Its register.
- Its playing technique.
- Its level of aggression.
- Its characteristic effects.

Examples:

> A felted upright piano with audible hammer attacks and widely spaced low notes.

> A close violin with bow friction, dry pizzicato, and long, tense notes.

> An open trumpet tone with audible breath and short blues falls.

### B. Describing the Function

An instrument can:

- Carry the melody.
- Establish the chords.
- Support the rhythm.
- Answer the voice.
- Add tension.
- Connect two sections.
- Produce a texture.

Compare:

> Piano, violin, trumpet.

With:

> The piano supports the harmony, the violin carries the main motif, and the trumpet answers the final notes of the vocal.

### C. Describing Its Evolution

> The violin begins with pizzicato, moves into repeated bow attacks, and then develops a long melodic line above the fast drums.

The same instrument can therefore serve several functions and several levels of energy.

### D. Naming a Synthesizer Without Relying Only on Its Name

In our prompts, the Korg MS-20 was a sonic reference.

To make the intention more explicit:

> A Korg MS-20 producing a resonant, nasal, slightly unstable analog bass with short saturated responses.

The name identifies a direction; the adjectives describe what you actually want to hear.

## 5. The Motif: Creating a Recognizable Identity

A motif is a short musical idea that can return and transform.

In our prompts, we used:

- A descending phrase.
- A syncopated five-note cell.
- A rising fourth followed by an unfinished descent.

You can specify:

- Its contour: rising, descending, circular.
- Its rhythm: regular, syncopated, interrupted.
- Its character: hesitant, insistent, songlike.
- The instrument that introduces it.
- The instruments that reprise it.
- The moment when it becomes complete.

Example:

> A short ascending melody remains unfinished at the beginning. The trumpet reprises it in the interlude, and the piano finally brings it to a conclusion in the outro.

This is a way to ask for musical unity despite changes in style.

## 6. Production and Sonic Perspective: Describing the Sonic Material

This section answers:

> How should the sounds be recorded, processed, and placed?

### A. Texture

You can specify:

- Tape grain.
- Gentle saturation.
- Vinyl crackle.
- Hiss.
- Distortion.
- Slight pitch instability.
- A clean, dusty, raw, or polished sound.

Avoid confusing warmth with a lack of definition.

> A warm analog texture, but clearly defined drum attacks.

This sentence asks for two compatible qualities rather than a permanent sonic fog.

### B. Space

You can describe:

- A small room.
- A spacious environment.
- A close voice.
- Distant instruments.
- A narrow or wide stereo image.
- Centered or side-positioned elements.

Example:

> A narrow, close opening; gradual stereo expansion in the chorus; bass and lead vocals kept in the center.

### C. Effects

Specify where and when they appear:

> The delay repeats only the final syllable of selected phrases.

> Spring reverb appears on a few guitar accents.

This is more intentional than:

> Lots of delay and reverb.

### D. Dynamics

Dynamics concern differences in intensity.

You can ask for:

> A genuinely stripped-down bridge so that the return of the drums feels larger without making the entire track constantly loud.

Contrast can come from volume, but also from the number of instruments, sonic width, or rhythmic density.

## 7. Arrangement: Building the Journey

The arrangement specifies what happens throughout the track: entrances, removals, reprises, contrasts, and transitions.

Tags such as `[Verse]`, `[Chorus]`, `[Bridge]`, `[Intro]`, and `[Outro]` correspond to common structural functions. Udio also documents tags such as `[Build]`, `[Breakdown]`, `[Instrumental Break]`, and `[Drop]`.

### The Main Sections

| Section | Function | What you can specify |
| --- | --- | --- |
| Intro | Establish the identity | Initial instrument, vocal presence, arrival of the rhythm |
| Verse | Develop the material | Density, phrasing, accompaniment |
| Pre-Chorus | Prepare the chorus | Tension, bass changes, rising vocal intensity |
| Chorus | Assert a central idea | Hook, width, harmonies, contrast |
| Post-Chorus | Extend the chorus | Instrumental motif or vocal response |
| Interlude | Open a space between sections | Instrumental dialogue, solo, texture change |
| Bridge | Introduce contrast | New harmony, removal of the beat, a different perspective |
| Breakdown | Strip the track down | Instruments retained and elements removed |
| Build | Accumulate tension | Increasing density, repetitions, perceived acceleration |
| Drop | Mark a strong arrival | Return of the bass, new groove, shift in energy |
| Outro | Organize the exit | Stop, gradual subtraction, resolution, or suspension |

The French word “refrain” often corresponds to `Chorus`. The English tag `Refrain` can also refer to a short repeated phrase rather than an entire section.

### Describing a Section with Four Questions

For each part:

1. What enters?
2. What leaves?
3. What changes?
4. What effect does it produce?

Example:

> During the bridge, remove the drums and piano. Keep a widely spaced bass and the voice alone. Introduce a few trumpet echoes to create a sense of distance.

### Describing Transitions

A transition deserves its own instruction:

> Cut the ensemble after the chorus and leave an exposed breath before the bridge.

> Gradually reveal the fast subdivisions before the breakbeats enter.

> Return to the slow groove without a spectacular impact, simply by removing the fast drums.

A change becomes more convincing when it has a preparation or a consequence.

## 8. Lyrics: Separating the Words from Their Delivery

For custom lyrics, sections can be organized using structural tags. Udio explicitly supports this use in its lyrics editor.

A readable layout:

```text
[Verse]
Sung text.

[Chorus]
Repeated text.

[Instrumental Break]

[Bridge]
Contrasting text.

[Outro]
Final phrase.
```

The highly detailed directions we added, such as `[Verse — low, intimate, behind the beat]`, are creative descriptions. They should not be confused with tags officially supported by every tool.

### What Our Lyrics Were Trying to Do

Following your feedback, we moved away from explanatory storytelling to work with:

- Physical sensations.
- Interrupted phrases.
- Implication and subtext.
- Short words.
- Repetitions that change.
- Singable vowels.
- Silences.

Compare:

> I hide my emotions because I am afraid to show vulnerability.

With our approach:

```text
I make it small.
A little laugh.

A little hum
Behind my teeth.
```

The first formulation explains. The second suggests gestures and lets the performance carry the rest.

### Developing Meaning Without Adding More Story

A phrase can return with just one change:

```text
I like you almost.
```

Then:

```text
I don’t need almost.
```

The chorus becomes an emotional progression, even without a narrative scene.

## 9. Construction Priorities: Setting the Essential Rules

This section answers:

> What absolutely needs to remain coherent?

Examples drawn from our method:

- Do not make every influence play simultaneously.
- Keep the voice at the center of the intention.
- Transform the motif rather than constantly changing themes.
- Reserve distortion for the moments that need it.
- Leave genuine instrumental spaces.
- Build the climax through contrast.
- Avoid an automatically triumphant conclusion.

For exclusions, also state the desired alternative:

> Avoid a spectacular drop; favor a rhythmic shift prepared by the violin.

> Avoid constantly present strings; use rare, physically expressive interventions.

This makes the direction more constructive than a long list of prohibitions.

## 10. Moving from a Detailed Brief to a Usable Prompt

Our long texts help us design the track. To use one in a generator, you can extract a more concentrated version and distribute the instructions across the available fields.

### Level 1 — The Core

Keep five elements:

1. Main genre and influences.
2. Voice.
3. Groove.
4. Dominant instruments.
5. Main progression.

### Level 2 — The Signatures

Add what makes the track distinctive:

- A recognizable motif.
- An unusual timbre.
- An important transition.
- A production rule.
- A particular ending.

### Level 3 — Local Details

Place section-specific directions with that section when the tool allows you to guide it.

Here is a condensed version of *Salt Bloom*:

> Cinematic soul-blues with a warm, slightly rough female mezzo-soprano. A slow 6/8 opening, felted piano, close violin, and soft analog bass. An unfinished violin motif returns on trumpet and then on the Korg MS-20. Restrained verses, progressively opening choruses, and an almost empty dub bridge. The ternary subdivision becomes a fast pulse for a drum’n’bass section with brief indie-punk guitar passages. A stripped-down final return, a freer voice, and warmer harmony without a triumphant resolution. Tactile production, subtle tape saturation, and genuine dynamic contrasts.

This version preserves the project without repeating the entire description.

## 11. Exercise: Write Your Own Prompt

Complete this framework:

```text
IDENTITY
The track is primarily…
The secondary influences contribute…

RHYTHM AND HARMONY
The pulse is…
The groove is…
The harmonic color is…

VOICE
The voice has…
In the verses, the singer…
In the chorus, the singer…
The supporting voices appear…

INSTRUMENTS
The main instrument…
The bass…
The drums…
The other instruments respond by…

MOTIF
The recurring musical idea is…
It transforms into…

PRODUCTION
The sound is…
The space evolves from… to…
The effects appear on…

STRUCTURE
The opening…
The first expansion…
The central contrast…
The climax…
The exit…

PRIORITIES
The three indispensable elements are…
What I want to avoid…
```

Then reread each line with one question: “Does this describe something I could recognize by listening?”

“An exceptional track” expresses your ambition. “A chorus in which the voice opens up while the bass descends, followed by a stop that leaves a single exposed breath” expresses a musical decision. Translating intention into audible events is what gives the prompt its value.

## Prompts and Lyrics

(The results obtained with these prompts and lyrics can be viewed on YouTube:)

## What remains

### Prompt/Style

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

### Lyrics

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

## Under my tongue

### Prompt/Style
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

### Lyrics

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

## Velvet Teeth

### Prompt/Style

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

### Lyrics

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

## Salt Bloom

### Prompt/Style

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

### Lyrics

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


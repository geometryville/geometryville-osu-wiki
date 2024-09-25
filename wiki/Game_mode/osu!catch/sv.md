# osu!catch

![Gameplay of osu!catch](/wiki/shared/catch-gameplay.jpg "osu!catch Interface")

osu!catch, tidigare känt som *Catch the Beat* eller *CtB*, är ett spelläge där spelaren kontrollerar en karaktär(fångaren) som fångar fallade frukter till musikens rytm.

## ![](/wiki/shared/mode/catch.png) Gameplay

### Låtväljaren

För att komma åt osu! spelläget, tryck `Ctrl`+`3` samtidigt.

Alternativt kan man klicka på `Mode` knappen och välja `osu!catch`.

### Grundläggande spelmekaniker

#### Spelfältet

![osu!catch playfield difference between CS2 and CS7](/wiki/shared/Catch_Playfield_27.jpg "osu!catch playfield difference based on CS")

Hur in/utzoomat spelfältet är beror på kartans CS (Cirkelstorlek) inställning. Lägre CS innebär mycket mer inzoomat och en mindre yta, medan högre CS innebär en mycket mer utzoomad och större yta.

Fångaren kan röra sig från vänster till höger och frukterna faller uppifrån neråt. Fångaren kan inte röra sig förbi spelfältets vänsta och högra gränser.

Alla frukter kommer att stanna kvar på tallriken tills kombon är färdig, varpå de studsar av tallriken. Timing och var på tallriken frukten faller spelar ingen roll; Antingen får man hösta möjliga poäng, eller så missar man.

#### Frukter

![Frukter](/wiki/shared/Catch_fruits.jpg "osu!catch fruits")

För att fånga dessa frukter måste spelaren se till att frukterna faller ner på tallriken istället för ovanför tallriken. Varje samlad frukt ger 300 poäng, en komboökning på 1, och behandlas som en 300 på score-skärmen.

#### Fruit trails

![Fruit trails](/wiki/shared/Catch_trails.jpg "osu!catch fruit trails")

A typical fruit trail will contains two fruits (start and end), droplets (slider path), juice drop (slider ticks), and more fruits for each reverse arrow points along with a reversed slider path. Droplet gives 10 points each and treated as 50 in result screen. Juice drop gives 30 points each, increment combo by 1, and treated as 100 in result screen.

Missing the juice drop will break the combo (as it is a slider tick), but missing the droplet will not break the combo. However, missed droplets will not be shown in the local result screen, but will be shown in the website's leaderboard as *Miss Droplet*, which notably affects accuracy (missed out the droplet, which is a 50) and score (10 points for each droplet missed).

#### Bananas

![Bananas](/wiki/shared/Catch_bananas.jpg "osu!catch bananas")

Here, large bananas will rain down and shrink down to catch size as it falls down to the plate (or not). Each collected bananas will give a static score of 1,100 regardless of mod and combo multiplier.

The bananas can be ignored with no health penalty. However, it can cost the extra points and health recovery from collecting the bananas. Notably, [Auto](/wiki/Gameplay/Game_modifier/Auto) mod will go above and beyond to catch *all* of the bananas without fail.

#### Hyperfruits

![Hyperfruits, and catcher hyperdashing from collecting previous hyperfruit](/wiki/shared/Catch_hyperfruits.jpg "osu!catch hyperfruits")

Hyperfruits are special fruits that will appear to help the catcher to catch the next fruit when normal dash is considered impossible to catch it in a strict timespan allocated. All hyperfruits have a signature red colour surrounding the hyperfruit itself by default.

Collecting the hyperfruit will make the catcher's dash upgraded to *hyperdash* (just fast enough to catch the next fruit), glows red, and leaves a temporary red *afterimage* at the collection point, until the next one fruit was caught or dropped, which the catcher will then be back to normal.

## Play Styles

*Refer to [Play Style page under osu!catch](/wiki/Gameplay/Play_style#osu!catch).*

## Controls

![Options keyboard section](/wiki/shared/Options_keyboard.jpg "Options Input icon, Keyboard section")

### Catcher control

- By default, the left `<-` (L) and right `->` (R) arrow keys to move the catcher.
- Press and hold the `leftShift` (D) key with one of the arrow keys will make the catcher *dash* in that direction at x2.0 speed (indicated with a **bright glow** from the catcher).
  - Alternatively, press and hold the Left Click (D) button on the mouse to trigger the dash.

The placement of in-game cursor does not matter when playing normally. If [Relax](/wiki/Gameplay/Game_modifier/Relax) mod was enabled, the control of the catcher will be the in-game cursor instead. However, the play unrankable when Relax mod was enabled (as it defeats the only challenge of osu!catch; fixed catcher speed and catcher plate control).

## Scoring

[Score in osu!catch](/wiki/Gameplay/Score/ScoreV1/osu!catch) is a weighted sum of multiple components of gameplay. It depends on the following:

- [Judgement](/wiki/Gameplay/Judgement) only provides fixed score values for each caught hit object and does not depend on hit accuracy.
- [Combo](/wiki/Gameplay/Combo_(score_multiplier)) is a score multiplier: clearing a hit object contributes more to the total score when combo is high and vice versa. In osu!catch, combo may be [broken](/wiki/Gameplay/Judgement/Combobreak) by missing a large fruit or a drop, which also decreases [health](/wiki/Gameplay/Health).
- [Accuracy](/wiki/Gameplay/Accuracy#osu!catch) shows how many objects were caught in total. Small droplets decrease accuracy when missed, but do not break combo.

After completing a beatmap, the score is assigned a [grade](/wiki/Gameplay/Grade#osu!catch), a short accuracy assessment in the form of a single letter. A golden or silver SS denotes 100% accuracy, and everything else, from S to D, depends on the amount of missed objects.

## Skinning

*Refer to [Skinning page of osu!catch](/wiki/Skinning/osu!catch) for full information.*

## Beatmapping

### osu! conversion notes

- Horizontal-axis placement determines the falling point of the fruits(hit circle) or fruit trails(slider).
- The appearance is based on the timing set to clear it, as usual.
- Speed of fruit trail is similar to slider ball speed.
- Spinner creates a banana rain.

**Note:** Hyperfruits are automatically generated.

## Trivia

### Gameplay

- [Auto](/wiki/Gameplay/Game_modifier/Auto) will *always* collect all the bananas.
- If `Hit-error` was enabled, it will always use `Colour`.
- The catcher can be moved around during any break.
- The catcher has a Miss animation, much like osu!taiko pippidon's Miss animation.
- The first default catcher was a chibified version of Ryuuta Ippongi (from [ouendan series](https://en.wikipedia.org/wiki/Osu!_Tatakae!_Ouendan)) until 2014, which was replaced by current catcher and mascot, [Yuzu](/wiki/Mascots#yuzu).
- When played by [Auto](/wiki/Gameplay/Game_modifier/Auto), the player name will be *salad!*.

### History

![osu!catch logo in the Special Modes](/wiki/shared/Ctb_logo.jpg "Catch the Beat logo in Special Mode")

- Until 10 April 2012 (2012-04-10), osu!catch maps could not be ranked or be included in ranked maps. However, this has now changed, and mappers may now make osu!catch-specific difficulties, provided they follow the guidelines. These guidelines are very much a work in progress, but as more osu!catch maps are ranked and feedback is given from their players, the guidelines will evolve to be as thorough and comprehensive as the osu! guidelines.
- The first ranked beatmap which contains at least one osu!catch difficulty is [Yousei Teikoku - Dare so Ka no Gekka (TV Size) (NatsumeRin), with the osu!catch guest difficulty mapped by Uran](https://osu.ppy.sh/beatmapsets/13676).
- The first ranked osu!catch-only beatmap is [Rita - Hajimari no Toki (Deif)](https://osu.ppy.sh/beatmapsets/91485).

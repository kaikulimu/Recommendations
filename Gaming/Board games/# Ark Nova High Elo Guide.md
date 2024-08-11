# Ark Nova High Elo Guide
> TODO Sort the sections
> TODO Sort the bullets in each section
> TODO `Africa` project more important than `Species Diversity` to prioritize(??); depends
> TODO: matches against 600 Elo+ players
    - 2024-01-03 https://boardgamearena.com/table?table=457672739 kaikulimu (133) vs monkeydo (163#)
    - 2024-01-21 https://boardgamearena.com/table?table=465214040 kaikulimu (125) vs Faerch (140#)
    - 2024-01-21 https://boardgamearena.com/table?table=465253147 kaikulimu (139#) vs Sageras0204 (134)
    - 2024-02-22 https://boardgamearena.com/table?table=478685954 nimoac (113#) vs kaikulimu (81)
    - 2024-03-03 https://boardgamearena.com/table?table=482460748 milo324 (116) vs kaikulimu (123#)
    - 2024-03-13 https://boardgamearena.com/table?table=486802373 kaikulimu (130#) vs Employee_427 (125)
    - 2024-05-10 https://boardgamearena.com/table?table=511080206 kaikulimu (131#)  vs human_light (112)
> TODO: My Immortal Game: https://boardgamearena.com/table?table=483168354 WuDiShaRenWang HK (129) vs kaikulimu (155#)
> Luckiest Cards Action Ever: https://boardgamearena.com/table?table=535869693 Move #78 kaikulimu (105) vs af145 (142#)
    - Draws into perfect sequence of Talented Communicator -> Wolf -> Savanna in one Cards 5 action
> Hall of Fall Emu: https://boardgamearena.com/table?table=504337132 Move #219 JDansp (17) vs Robin (56#)
> TODO: ???-point turn: https://boardgamearena.com/table?table=484894322 kaikulimu (136|5-project#) vs snp0 (136|4-project)
> TODO **Move of the Century!**: https://boardgamearena.com/table?table=522554724 Move #28 betacockroach (?) vs kaikulimu (?)
    - Verify: Sponsor 2 BR2 (+1X +$2) ~> BREAK (+$6) -> Assoc 4XX 2-rep Univ upgrade Build (+2rep) -> Build 5 [2, 1, pav, kiosk] cover rep and H or rep-draw, REP_5 upgrade Animals (+1H? +1rep +1ap -$10 +K$$1 +$$$1) -> Animals 5U Barn Owl + Tas Devil pouch 1 (-1H +2-rep 9ap -$23 +K$$2 +$$$6) -> Cards 5 (BR2 +1-2H) -> Sponsor 5 Spokesperson REP_8 worker (-1H +1rep) -> Assoc 4 PZoo ~> {Assoc Sponsor Cards Animals Build BR2 3-5H 0X 8-rep 11ap 0CP =-3pt $0 $$$16}

## Terminology
- PZoo = Partner Zoo
- Univ = University
- "unlock" = gaining a bonus from left hand size of map due to Assoc 5 project
- "cover" = cover a placement bonus on the map
- END = End of game 

#### Game State
Early Game: Until your opening strategy is executed (1st project, REP_8, pair of PZoos/Univs, sponsor upgrade for `Explorer`, etc.)
Mid Game: When you look for efficient plans after early game is completed
Late Game: When you start to calculate points to END

## TODO Statistics
- TODO: Statistics on drawing a certain type of card, or its chance of showing up in your hand/display

## Over-the-Board vs [BGA](https://boardgamearena.com/)
- Two more sponsor cards TODO

## End Analysis
- See details in "END analysis.xlsx"
- On average, a game ends at 150pt, composed of:
    - 60 pt from animals
    - 30 pt from sponsors + pav
    - 30 pt from projects
    - 30 pt from donations, endgame, rep track, map periperal, and fill map
- On average, **$1.8 = 1 pt**. If you amortize projects points onto animals (e.g. Birds 5 project makes each Bird worth 3 more pt):
    - We play 9 animals; each costs $19 for 11 pt, i.e. *$1.8 = 1 pt*
    - We play 6 sponsors; each giving > 6 pt
    - We support 3.5 projects; each giving 3.5 CP (10.5 pt)
- Income has diminighly return. Only a finite amount of "good money" has **$1.8 = 1 pt** ratio, limited by the number of projects you can support, as well as fill map.
    - Avoid playing animals that do not contribute to project and do not have high value by itself, to avoid spending "bad money"
- TODO
- TODO "Point by Turn", "Kiosks", "Cards Seen"

## Resource Efficiency
- **Diminishing Returns of Money**
- According to YouTube video ["How is Ark Nova balanced?"](https://www.youtube.com/watch?v=-OTo1C7-OpM) by "Strategy Advisor":
    - 1 appeal = 3 money
    - 1 reputation = 1 X = 1 rep-draw = 3 money
    - 1 CP = 8 money
    - Animals with requirements are better because requirements lead to discounts
- However, his "1 appeal = 3 money" breaks even with an average animal having 1 animal icon and 1 continent icon, which means you get 2 icons for free. Therefore, small animals are more cost-effective than large animals, especially in the early game where appeal is very important. Large animals usually have strong ability for late game and trading that much money for appeal is like a "free Determination", but is a waste of time for early game.
- Average of top 5 Arena players endgame: has $205, spent $186 for value, has 75 appeal and 25 CP
- "END analysis.xlsx" suggests *$1.8 = 1 pt*. Since appeal also generates income, **1 appeal = $1.8 + income_fraction**
    - See "income per next ap" section of "END analysis.xlsx" for estimation of *income_fraction*
- During early game, appeal is king. Pay attention to these watermarks:
    - 4 appeal or less:  +1 appeal == +1 income  => TODO Get 5 more game samples for "ap,CP by Round" in "END analysis.xlsx"
    - 16 appeal or less: +2 appeal == +1 income
    - 31 appeal or less: +3 appeal == +1 income
    - 55 appeal or less: +4 appeal == +1 income
- Hence, early appeal worth more than early CP, except for rushing CP_2/CP_5/CP_8
- Icon contributes to project => 1 icon = 3 point
- Icon matches PZoo           => 1 icon = $3 > 1 point
    - Discount is worth slightly more. For example, consider a animals costing $6 for 2ap. You rather have $3 discount than +1ap because $3 for 2ap is better than $6 for 3ap.
- "Mini Project" Sponsor cards (e.g. `Penguin Pool`) => 1 icon = 2 point
- Sponsors which give free appeal are excellent! 0 money = N appeal
- TODO Important to have 4-5 projects prepared, each is 0 money 6-15 points and free unlock map reward!
- To be efficient, synergize your animals to the maximum!
    - e.g.) https://boardgamearena.com/table?table=498183637: 
    - You already have 2 Predator icons, `Expert in Predators` and `Sponsorship: Lions`
    - `Wolf` is baseline $20 for 5 ap (4 ap + 1 ap from pack)
    - `Expert in Predator` gives $3 discount
    - Pack triggers for +2ap
    - `Sponsorship: Lions` gives +$3_income, so like $12 total
    - If you attribute it to Habitat 5, that's another +3pt
    - Conclusion: $17 for 7ap + 1CP? = 7-10pt && +$3_income
- Eyeballing it, I consider one X-token worth $3-4

#### Icons
- Bear > Bird > Herbivore > Predator > Reptile > Primate > Petting Zoo
- There are **no** Primates in Europe nor Australia
- Water > Rock because there are simply more water icons in game

#### Continents:
- Asia > America > Africa > Europe > Australia


## Action Sequencing
- **When in doubt, trust action sequencing.**
    - Often I would analysis different lines for two hours, and conclude that the better action sequence line is superior.
- **Key Insight** -- Doing stronger actions more times essentially translates to free Determination.
- Assoc and Animals are the strongest actions late game. Assoc and Sponsor are the strongest mid game.
- Sponsor is very strong early-mid game, can fall off a bit late game
- Cards essentially buffs other actions. Good early-mid game, often too slow late game; also depends on how good your hand is.
    - However, please prioritize Cards if display has an essential part of your combo
- Hence, Build is the weakest action

TODO Explain why you would do Cards before Assoc Round 1 when Australia PZoo has small chance of being stolen
- IMPORTANT: Before you do an obvious Action, think about if other actions would make more sense, esp. if you have X tokens
- TODO Explain "take actions at Strength 5, but here are the exceptions"
- You prefer to take a "priority action" more than once before break, so you can play it at a lower strength
    - e.g. Association 3 for PZoo when you have two workers
    - e.g. Sponsor 4 for sponsor card when you have two good sponsor cards to play
    - e.g. Animals 3 late game if you plan to do Animals twice
- TODO [Pat Schooley] You can play 2 sponsors before first break, but likely 1 Assoc and 1 animal, so prioritize Sponsor action

- *Observe*: It's natural to sequence Animals right behind Build

- Don't blindly sequence Cards before Animals in the early game. If you have upgraded Animals and 3-hand-size, you might want to play Animals 5U to use one card before Cards 5 drawing, in case oppo BREAK
    - e.g.) https://boardgamearena.com/14/arknova?table=539949404# Move #71: You want to play `Fur Seal` before drawing

#### X Token Usage
- Spend X token for "priority action" right before a Clever/Boost_down, because you want the Clever/Boost_down to boost "priority action" up by one
    - e.g.) Compare 
        1. Assoc 5X -> Animals Clever down Build
            - Better: You have less X token, but Assoc at 3 and Animals at 2
            - Clever is able to bump up Assoc action
        2. Animals Clever down Build -> Assoc
            - Worse:  You have one more X token, but Assoc at 1 and Animal at 3
        
- TODO X-back then double action is good
    - e.g.) Compare https://boardgamearena.com/table?table=520544496 Move #289
        1. X-Cards -> Assoc 8XXX Australia PZoo + Asia 5 -> Build 5 cover Clever?
            - TODO better?
            - TODO Double action is great
            - Caveat: real game is more complicated because you can Assoc 5 PZoo + 2rep later
        2. Asia 5X Asia 5 -> Build 5X cover Clever down Cards -> Assoc 3 Australia PZoo || Sponsor 5 BR 5
            - TODO worse?
            - Clever is able to bump up Assoc action
            - bad: You need to cover Clever

- Loss of sequencing due to Hypnosis or Constrcition can be solved by spending 2 Xs, except double Constriction which requires 4Xs

#### Transformative Property
- Let `A, B, C` be actions. Lower-strength action later on can transform sequencing change from `A behind B` to `A behind C`
    - e.g.) https://boardgamearena.com/table?table=511080206 Move #124:
    - You have {Animals Build Assoc Sponsor Cards}. You plan to do Assoc 3 PZoo twice. You are deciding between Assoc 3 and Cards 5.
    - Assoc 3 -> Cards -> Sponsor {Sponsor Cards Assoc Animals Build} -> Assoc 3 -> Build ~> {Build Assoc Sponsor Cards Animals}
    - Cards -> Assoc 3 -> Sponsor {Sponsor Assoc Cards Animals Build} -> Build -> Assoc 3 ~> {Assoc Build Sponsor Cards Animals}
    - You *transform* from "Assoc behind Cards" to "Assoc behind Build"
	
## Upgrade Order
- **For the same value, gaining in fewer turns is better.**
- According to "END analysis.xlsx", a winner ends the game with >= 150pt in <= 33 turns. Hence, aim for **> 4.5pt per turn**.

> Roughly from best to worse
1. Association
    - Upgrade **early!** => Rush donation to hit PZoo/Univ at CP_5 or CP_8 (Univ/PZoo are the best)
        - If you have no early project, can rush donation to hit CP_2
        - If you have an initial project with 3/4 CP, and Uniz/PZoo at 5-CP track reward
        - In addition, you will fill your Univ/PZoo slots faster => even more reason to upgrade Assoc
    - Upgrade => take 3rd/4th partner zoo for `partner zoo CP bonus` and/or `4th worker map CP bonus`
    - Upgrade => spend X tokens to double action (e.g. mid game Assoc 3+2, late game Assoc 3+5)
        - Assoc 3+2 is very efficient compared to simply Assoc 3, like if you took 2 Univs early on
    - Upgrade => cheap donations (2/5 spots are excellent; 7 spot is decent)
    - Upgrade => Late game monster
2. Sponsor
    - Upgrade => Play upgraded sponsors
    - Upgrade => Play high-value sponsor from display
    - Upgrade => Play multiple sponsors in one turn => free Determination
    - Upgrade => "Break 7 Gain 14" especially if you gain an upgrade before 1st break
3. Animals
    - Upgrade => Animals 5 gives 1 reputation
    - Upgrade => Play Level 2 animals
    - Upgrade => Animals 3 can play two animals, very deadly in the late game
4. Cards
    - Upgrade early => When your hand is really bad
    - Upgrade => Draw strong cards from display
    - Upgrade => To have more than 9 reputation
    - Recommended to move back for X token
5. Build 
    - Upgrade => Efficient building with kiosk/pavilion
        - It's only slight money/appeal advantage; not essential if something else is more urgent
    - Upgrade => Build about your map for flexibly and cover placements bonuses more easily
    - Upgrade => Bird Aviary
    - Recommended to move back for X token

- Focal point of each upgrade
    - Early game: Build, Sponsors
    - Mid game: Cards
    - Late game: Animals, Assoc


- *Sponsor vs Assoc*: If you have low income, upgrade Sponsors. If you have high income, upgrade Assoc
- If oppo upgrades Sponsors and do Sponsor 5 BR 5 +$10 a lot, counter via upgrade Assoc and donating a lot

- If you don't upgrade Build, your income is a lot lower, so upgrade Sponsor to compensate

- If you upgraded Sponsor and not Animals, consider skipping Cards upgrade since you won't have much rep
- If you upgraded Sponsor and have enough money, consider not upgrading Build

- *R1 Release*: Prefer to upgrade Sponsors and unlock Snap
	- Not preferred to upgrade Build because:
		1. You have low income, so unlikely to be able to do a full Build
		2. Since you freed up an empty enclosure, you don't need to Build as much
	- If no upgrade Build, then upgrading Sponsors is the best way for reliable income
		- Also, in R1 `Sponsor 5 BR 5 BREAK` is very sensible after release
    
- TODO **Pseudo-Upgrages**: unlock snap > unlock 2-size ~= unlock $5
- **Mad Enhancement**: Skip all PZoos, hence skipping Assoc upgrade, and instead focusing on doing many projects
    - Preferrable only if you can keep supporting projects efficiently with your Assoc actions
        - Hence, you need to be able to play many projects
    - Can be a desparate move if you have difficulty unlocking second worker
    - TODO At around 30 appeal, skipping upgrade to go for one more project is preferrable
    - TODO How much value does an upgraded action actually give you?
   

- TODO How to decide which to upgrade first???
- Default upgrade order: Build -> Animals -> Cards -> Association
    - If you upgrade Sponsor, then most likely give up Association
    - Reasons to upgrade differenly
        - Assoc early => Rush donation to hit PZoo/Univ CP track reward
        - Sponsor early => Gain early income when you low on money
        - Sponsor early => Big three sponsors: `Explorer`, `Talented Communicator`, `Science Lab`
        - Cards early => On Commercial Harbor
    - Reasons for non-standard give up:
        - Cards: if you have unlocked snapping map bonus *and* are high unlikely to reach more than 9 reputation
        - Build: if you have unlocked 2-size map bonus *and* will build 4/5 for large animal
            - Beware of having enough empty spaces. Rule of Thumb: Should upgrade Build if you played 2+ Sponsor enclosures
- Build-less upgrade order:  Sponsor -> Animals -> Cards -> Association
    - [dwarvintime] endorses
        - Masterclass game: https://boardgamearena.com/table?table=544611344 JDansp (137) vs Darcelmaw (154#)
    - If you can generate enough income w/o upgrading Build
    - Heavily relies on Sponsor 5 BR 5 for income
    - Consider this if at Round 2 your money is so low that you can't do a full Build
    
- *Number of Turns* statistics does not correlate 100% with how good you are
    - Sometimes stalling is the best move, e.g.) you waste one turn and oppo wastes two
    - If Sponsor N BR N occurs a lot, number of turns will be shorter
    - Gaining `Clever` is the recipe of most of the shortest games
        
TODO theory: don’t have inefficient turns, that’s why you Break 7 Gain 14 money       

TODO theory: Usually you need to support at least 4 projects to win 

- `Build 5 [2]` is better than `Build 2 [2]` because it pushes more actions up
        
TODO: to count which actions will come up next after a sequence of actions, say them out loud. (Reference the actual game) For example, the desired sequence is Sponsor 3 Side Entrance -> Build 2 -> Assoc 4 2-rep Univ -> Cards 5 -> Sponsor 4 Archaeologist -> Build 4 -> Animals 5
- Example game: ??? Move ???
- Say out loud “Sponsor, Build, Assoc, Cards”, and you know Sponsor will be strength 4 again, followed by Build at strength 4

- People like to do Cards in the last Round a lot, but it's really bad

## Association
*Project rankings*: 5CP base > release project > breeding > 2CP base

- Unlock Map Bonus Priority:
    - **Now not later.**: Whatever benefits you now is an extra good activation of the effect. Considering the total game is 5-6 rounds, one good activation is a big deal
1. Snapping
    - Unlock Snapping before Assoc worker *only* if you can break soon this round and gain another worker (or break soon again) by next round
    - Conjecture: Unlock only if you have something good to snap immediately
    - Effectively increases hand size by 1
2. Association Worker
    - You want to prolong the round
    - [JDansp] "Only good if you took PZoo -> Project to get 2nd PZoo in Round 2"
3. 2-size enclosure
	- `unlock 2-size -> X-Build` is better than `unlock $5 -> Build N [2]`
    - Gives lots of tempo if you have good setup
    - Good for rushing `Native Farm Animals`, `Native Seabirds` and `Native Lizards`
    - Take it over $5 if you have loads of excess money or if you are building a 4-size/5-size and still have enough money to play on that 2-size
    - Better if you can Clever/Boost down Build
    - If you plan to fill map
4. $5
    - When you do release as first project, unlock $5 first is good because you are very low on income
    - If you plan to Assoc donate

- General guidelines for unlock order
    - Unlock per-break bonuses or worker first if possible
    - Unlock whatever helps you the most right now

- Common ways to gain 2nd worker:
1. Rush 8 reputation
2. Unlock worker map bonus (via Assoc 5)
3. 3rd Partner Zoo (great for `Outdoor Areas`)
4. Play `Talented Communicator`
5. Play Full-throated animal
6. Have 2 CP 

- **Dangerous Game**: Completely skip PZoo or Univ is viable, only if you can ensure a long stream of projects to support
    - Skipping Univs will likely deny yourself REP_8 worker, unless you have other ways to gain rep, e.g.) upgraded Animals early and used it multiple times
    - If you only want an extra worker, you can take 3rd PZoo instead of 2 Univs

- Consider Univ block

- Try to rush 1-3 early projects at 2 CP, then focus on getting 4-5 CP projects
- Pay attention to synergy for early Release project, Breeding Program project, `Small Animals` project, `Research` project, and `Aquatic/Geological` project
- If you happen to do project at Round 1, consider gaining Snapping (map bonus) + Worker (CP track) or Worker (map bonus) + Upgrade Sponsor (CP track)

- Early PZoo fitting 2 animals is worth $6 already; pretty big deal tbh

- Look for opportunity to block Univ > block partner zoo
- For release projects, likelihood of having match Small > Large > Medium
    - TODO Math
    
- If you start with two Univs and get to 6-rep, consider upgrading Assoc to do Assoc 5 2-rep gain worker + PZoo
- [JDansp] Much more incentivized to rush Species 5 if you have a Bear in hand

- [JDansp] If you are at REP_6 while having only one worker, you can do `Assoc 5 unlock worker -> ... -> Assoc 4 2rep Univ REP_8 worker -> Assoc 3 PZoo`

- A larger size release is better than a smaller one in general, because you gain a larger empty enclosure back.
    
- Project Compatibility: The more conflicts, the more difficult to complete both projects in the same game
    - Herbivores 5 complements Africa 5
    - Predator Breeding complements Predator 5
    - Habitat 5 complements with Americas 5
    - Asia 5 conflitcs with Africa 5
    - Birds 5 conflitc with Reptiles 5
    - Release Europe conflicts with Europe 5
    - Australia 5 conflicts with Primates 5 (because there are no Primates in Australia)
	
## Sponsors
- Adapting from YouTube video  ["Ultimate Ark Nova Sponsor Cards Tierlist by JDansp"](https://www.youtube.com/watch?v=MoxaWdKL-kA), strongest sponsors are:
    - Overpowered: `Archaeologist` > `Federal Grants` > `Technology Institute` > `Side Entrance`
        - Personally I consider `Side Entrance` the strongest because it has 5 endpt and can be strong even in mid-late game 
    - Always nice: `Hydrologist`, `Geologist`, `Science Library`, `Zoo School`, `Expert in Asia`
    - Two appeal per icon is high value! `Aquarium` > `Penguin Pool` > `Meerkat Den` > `Cable Car` > `Baboon Rock`
    - Map shape abuser: `Native Farm Animals` > `Native Seabirds` > `Native Lizards`
    - Reasons to upgrade Sponsor: `Explorer` > `Talented Communication` > `Science Lab`
- TODO If you played Side Entrance, embrace large animals
- Around 12-16 total sizes from Sponsor enclosures will fill map; more and you run out of space easily
- When you have an income lead, consider BREAKing to widen the money gap, instead of delaying if oppo is able to spam Build to catch up on income
    - In that situation, oppo $$$1 is worth more than your $$$1
- [JDansp] With `Spokesperson`, you can take 2-rep Univ for REP_5 upgrade on Round 1, then take 2-Science Univ for REP_8 worker on Round 2
    - [Julie_1104] With `Spokesperson`, if you REP_5 upgrade Animals on Round 1 and are able to play "Animals 5U" twice, then you can also take 5-hand Univ for REP_8 worker on Round 2
- [JDansp] With `Zoo School`, on every map except Silver Lake, you can cover rep and take 2-rep Univ to do REP_5 upgrade Build before your first Build action => can be great!
- [JDansp] With `Release of Patents`, you can take 2-Science Univ then play it to gain CP_2 reward
- [JDansp] With `Waza Special Assignment`, small is usually better than large, because it's easier to play 2N small animals than N large animals
- [JDansp] Birds and Predators can easily draw into another Bird/Predator => `Ornithologist` and `Expert Pred` are better than its equivalents

#### When to Cause Break
Three primary factors:
- Money & income
- Association workers left & action position
- Number of cards in hand; pay attention to 5-hand-size Univ

- Triggering BREAK is fantastic early-mid game as you steal an X from oppo. Late game, not so good.
    e.g.) [dwarvintime] Early game, Break at 5, both players want to do Cards 5. If you do it second, you gain the X token
    - For early-mid game, only decline BREAK if it makes oppo have very bad actions, and they can't conveniently trigger BREAK
    - In Round 1/2, extra bit of money is huge

- TODO Also think about whether your opponent wants to cause break. Sometimes you can let them do it.
- Make oppo discard before draw can be worth to deny knowledge and disrupt synergy, even if they discard one less card
    - e.g.) https://boardgamearena.com/table?table=486802373 Move #26:
    - Oppo has 5 cards with hand size 3. `Eurasian Eagle-Owl` Perception 4 is about to be played
    - {4 choose 2} If we break now, he has to discard 2 within 4 unknown cards and 1 great card
    - {6 choose 3} If we break after he plays Eagle-Owl, he has to discard 3 within 6 unknown cards
    - Observe that if he discards before Eagle-Owl, he could have discarded cards that synergizes well with cards from Perception 4
    - Therefore, discarding before Eagle-Owl is better

#### `Side Entrance` Guide
- Usually build as "Main Entrance" to abuse income boost

## Cards
- TODO
- Card priority: **Near good > Future good**
- **Don't sabotage yourself** trying to deny your opponent. It's rarely worth it.
- **Believe in the Heart of the Cards**: Try to draw from deck as much as possible. Only Cards 5 snap if you really need to
    - Hence, unlock snapping is very strong
    - If you snap once, you might have too few cards in your hand that you need to snap again => Vicious cycle
- **Der Untergang**: Cards move down on display, e.g. when break happens or when you rep-draw. Remember to account for it.
- **Stargazing**: If a card on display is highly likely to still be yours, consider drawing one more card from deck instead of drawing it.
    - It does cost a bit of money => If income is high, stargazing is even better
- **Abundance Theory**: There is an abundance of good cards in the deck. If you are set for next actions, and are looking for animals, sponsors and projects for future, should draw from deck and take what you need.
    - You get to keep two cards instead of one!
    - **Take what you need; snap what you miss.**
    - e.g.) You want two animals, one sponsor, and one project for future
        - If you snap a project now, then you will still be missing two animals and one sponsor. Hence, you might be forced to snap again next round.
        - Instead, if you draw from deck and keep one animal and one sponsor, then you will only be missing one animal and one project.
- **Gemini**: When there are two cards on display creating a strong combo, consider snapping one and repu-draw the other
- **Blockers**: e.g.) If you have an Eagle, it's much less likely oppo also has an Eagle
- Don't be afraid of discarding cards. Discarding a card is worth ~2.5 money, but playing a more optimal card can easily outvalue 2.5 money
- When looking at cards on display, *also* consider what your opponent wants
- Which display cards do you pay attention to? Those that match with any of the projects. Don’t tunnel-vision on a single project
    - Projects cards are the rarest => worth snapping if it matters to you or your opponent
    - Also good synergies cards like `King Vulture`
- TODO don’t just think about what you want; deny important cards of your opponent! Even do Upgraded Cards 3 for this!
- Don't touch the display if you don't have to -- you might give your opponent miracle out!
- If you welcome a sponsor draw, Cards 5 draw 3 is a lot stronger. There are 66 sponsors in the BGA adaptation.
- Care: Release projects are more easily leeched than breeding programs
- Keeping Eagle early game has the benefit of more easily utilizing aviary

#### What to discard and what to keep
- **Combo Rarity**: Try to keep the rarest combo cards in your hand
- Let's use Duel Master's rarity system: *Common*, *Uncommon*, *Rare*, *Very Rare*, *Ultra Rare*
    - e.g.) https://boardgamearena.com/table?table=530224307 Move #82
        - If oppo does not BREAK, `American Bison` and Rhino is such as deadly combo that it's *Ultra Rare*.
        - This *Ultra Rare* combo might be so good that you won't be able to draw anything as good the entire game
        - Consider keeping `American Bison` instead of selling for $3, risking it getting discarded if oppo BREAK
        - You have a read that oppo is gonna play 3rd Petting before BREAK, so you should be safe
        - bad: $3 means a lot to you at that point
        - bad: You can still draw into other combos later in the game
        - bad: Possibilities of cards like `Owl Hut` showing up, then selling `American Bison` was correct

#### Card Draw Chances
- There are 128 animals + 64 sponsors + 2 BGA-only sponsors 20 non-base projects = 214 cards in the BGA deck
    - BGA-only sponsors are "Victory Column" and "Arcade"
- Number of cards per icon:
    - Any sponsor       66 sponsors               30.84% or 1/3.24
    - Bird:             25 animals, 4 sponsors    13.55% or 1/7.5
    - Herbivore:        25 animals, 4 sponsors  
    - Water:            23 animals, 6 sponsors
    - Predator:         25 animals, 3 sponsors    13.08% or 1/7.5
    - Reptile:          25 animals, 3 sponsors    
    - Rock:             19 animals, 5 sponsors    11.21% or 1/9
    - Primate:          18 animals, 4 sponsors    10.28% or 1/10
    - Non-base project: 20                         9.35% or 1/11
    - Petting Zoo:      10 animals                 4.67% or 1/21
    - Bear:              9 animals, 1 sponsors        
> See "ark_nova_draw_chance.xlsx" and "ark_nova_draw_chance.py" for calcuations
> TODO Update to the correct numbers
- Display replenish 2 cards chance to get:
    - Any sponsor                           52.17%
    - Bird, Herbivore, Predator, Reptile:  ~25.76%
    - Primate:                              20.22%
    - Petting Zoo, Bear:                     9.47%
- Draw 3 cards chance to get:
    - Any sponsor                           66.92%
    - Bird, Herbivore, Predator, Reptile:  ~36.03%  TODO Should be 37.50% at the start of the game, if the display and all your starting cards are not birds
    - Primate:                              28.74%
    - Petting Zoo, Bear:                    13.87%
- Draw 4 cards chance to get:
    - Any sponsor                           77.12%
    - Bird, Herbivore, Predator, Reptile:  ~44.88%
    - Primate:                              36.35%
    - Petting Zoo, Bear:                    18.05%
    
- *Lemma* -- Snapping a specific card > hope drawing it
    - Slight disadvantage: snapping gives oppo knowledge
- *Heuristic* -- draw icon chance increase per draw
    - Bird, Herbivore, Predator, Reptile:   12.00%, "Weight" = 1.125
    - Primate:                               9.00%, "Weight" = 1.5
    - Petting Zoo, Bear:                     4.50%, "Weight" = 3
> "Weight" refers to the difficulty of drawing a specific icon
- *Examples*:
    - If you already have one Petting Zoo, getting 2 more Petting Zoo has Weight 3 * 2 = 6
    - If you already have one Primate, getting 4 more Primates has Weight 1.5 * 4 = 6
    - If you have no Bird, getting 6 more Birds has Weight 1.125 * 6 = 6.75
    - *Aware* If opponent is fighting for the small icon, the Weight doubles
        - Therefore, easier to achieve secret Rhino project than a public project
- *Key Insight* -- Choose the goal with the lower Weight!

- TODO For Petting Zoos, it's very important that if you already have two Petting Zoos, there are only 8 left...

- TODO Draw changes for Continents? Reptile or Predator? Predator or Europe? Reptile or Predator or Europe? (taking inspiration from starting hand of https://boardgamearena.com/table?table=485980311)
    - TODO Prob (starting project highroll showing up on display?)
    - TODO Derive a easy formula please
    - TODO Have a list of chances, but then have some signature benchmarks. Can move the rest to Appendix section

- TODO Prob(Release/Breeding Program with matching animal in starting hand)
- TODO Probability(showing up before game end) == ??
    - TODO How many cards we draw in one game?
    
- TODO Prob(Display containing Primate suitable for Primate Breeding w/o Science icon): ~33%
- TODO Prob(Display containing Africa/Asia/Europe animal for Habitat 5 w/o PZoo): ~54.79%
    
- Prob(starting hand contains >= 1 Bird icon) = 68.81%
    - TODO Refactor "ark_nova_draw_chance.py" to validate calculation
    
- TODO When you fish for a project, Rhino counts as one

## Build
- During early build, feel free to leave some empty spaces
    - You can get to placement bonuses faster
    - Can highroll Native Farms or Zoo School, etc.
- Early build to cover buy sponsor is a very strong tempo move, usually worth the $ spent
- Kiosks are overrated; you only need 2-3 kiosks per game
	- As you get better at the game, you can END with fewer breaks => kiosks are less useful
- Try to build Bird Aviary and Reptile House near both rock and water
    - 11 Birds    can live in Aviary,        3 next to Rock, 1 next to Water (`Bald Eagle`)
        - All four 5-size birds w/o near water is a huge deal!
    - 25 Reptiles can live in Reptile House, 5 next to Rock, 9 next to Water (including all 4-size and 5-size reptiles)
- Bird Aviary > Reptile House
- When playing Side Entrance, you still want to have efficient actions. Try not to waste too much time doing Build 1
- At around 30 appeal, **do not** build kiosks anymore! Would rather have a 2-size enclosure just in case
- TODO Calculate the total estimated income for each kiosk
- When you fill map for 7 appeal, if you have 8 wasted spaces (= $16) it's still worth it
- If you're very unlikely to fill map, don't worry about leaving holes on your map
- If covering a placement bonus gives you very marginal benefits, save it for later
- [JDansp] If you have lots of spare money, can build a random 5-size to prepare for future
- **Prebuild**: Build an enclosure for the future, instead of X-Build or Build N [pav]
- [JDansp] Leave some empty spaces for good placement Sponsors like `Penguin Pool` or `Zoo School` if it's convenient
    - Leaves some border spaces in general for `Side Entrance`, `Native Farm Animals`, `Zoo School`, etc.
        - `Native Farm Animals` cover H draw paying off greatly vs betacockroach: https://boardgamearena.com/table?table=522554724 Move #148

#### `Archaeologist` Guide (original maps)
- Most powerful: Three PZoo on `Outdoor Areas`
- Spam rep on `Silver Lake`, `Ice Cream Parlors`, `Park Restaruant`
- Free Univ(s) on `Research Station`
- `Hollywood Hills` is the worst map for `Archaeologist`

#### Kiosk vs Pavilion
- TODO
- See "income per next ap" section of "END analysis.xlsx" for estimation of *income_fraction*

## Animals
- Always **double-check requirements** of Animals! So many games are lost due to a missed requirement...
- You only play 9.3 animals per game on average. Don't waste time on non-critical animals
- **One Distraction Rule (ODR)**: Generally, you can afford one distraction of ~3 animals (e.g. 3 Petting, 3 Herbs with `Meerkat Den`), and can still do one 2CP base project and one 5CP base project.
- Overpowered: `Sun Bear` > Rhinos ~= Eagles > `New Zealand Fur Seal` > Elephants > `Koala` (next to Rock: Round 1 +1rep +12ap)
    - But don't blindly keep Rhino! `American Bison` on a 5-CP America project board is better than a Rhino
    - If you plan to play `New Zealand Fur Seal`, **must** upgrade Animals while delay upgrading Build
    - Playing an Elephant before CP_10 is triggered is slightly better, because you have the option to discard both Elephant endgames
    - If you can can follow up with strong actions, Elephant is effectively free Determination, because you are gaining points roughly equal to two late game actions
    - `Sunbathing` is an excellent ability, often underrated
- High-requirement animals: `King Vulture`, `Siberian Tiger`, `Eurasian Brown Bear`, `Sumatran Tiger`, `Lion`, `American Bison`, `Giant Panda`, `Nile Crocodile`, `Galapagos Giant Tortoise`, `Proboscis Monkey`
    - Can give upwards of 6 free appeal, like `Giant Panda`
    - Think of it as gaining a free Determination for a 2-CP project, but you do lose map unlock bonus
        - Early game map unlock is better; late game free Determination is better
- High-value small animas: `Tasmanian Devil`, `Scarlet Macaw`
- Attack: Hypnosis (late game) > Pilfering (early game) > Constriction (late game on Association) > Venom (mid game)
    - Hypnosis on oppo Assoc 3 can be devastating, potentially stronger than Determination
- Petting Zoo animals are below average, unless there is `Species Diversity` project
- If you plan to play two animals, remember to play the Sunbathing one first
- TODO: Always pay attention to rock/water requirements, especially double
- Enhance Boost by sequencing your actions
    - e.g.) Doing Assoc right before Animals maximizes `Raccoon`'s "Boost: Association"
- On BGA, hover over animals to make sure you can meet all requirements.
- [dwarvintime] White Rhino allows you to skip upgrading Animals and still cross 100pt

## Opening Theory
- Don't always be afraid of opponent taking your desired Univ/PZoo. Should go for highest EV play
- **Income snowballs**: If you have low income, you might have to build less/worse kiosks
- If you need to play a 3-Rep requirement sponsor, such as `Penguin Pool`, two Univs can help you
    - 2-Rep Univ get you to 3-Rep, obviously
    - 5-hand Univ also works if you can build covering 1 Rep or play 1 Rep animal.
        - Replay example: https://boardgamearena.com/table?table=484430916 Julie (144#) vs kaikulimu (125)
- If you have Poach and Sunbathing, consider drawing cards before animals, but be **aware** of opponent causing break
    - `Koala` one of the best early game animal
- If you have multiple sponsors, try to play them all Round 1
- If you start with Cards at 5, and you are starting player, can be more greedy with starting hand keeps
- Typical line to punish slow opponents who used Cards: Assoc 4 5-hand Univ -> Cards 5 -> Sponsor 5 Break 5
- Sometimes it's advantageous to skip an early Build or Animals action because they are so weak
    
## Early Game
- **PISS on the early game**: project, income, sponsors, second worker
- **Win the game out of the opening** is the best way to play.
- If you have multiple sponsors, consider prolonging the round to play all sponsors
- In Round 1, okay to X-Assoc if you anticipate long round
- Ideally, you want to plan for REP_8 worker or non-base project or 5-CP-blocked base project as first goal. You want to leave 4/5-CP-unblocked base projects for late game.

#### Starting Hand
- TODO Watch video by NoWondersTV
- Keep cards in starting hand: **Near good > Future good**
- Try to keep multiple sponsors. The early you play it, the stronger it is.
- Keep at least one project if possible
    - If choose between two projects, Release Europe is less valuable if Europe 2 is a project slot
- Out of the 18 playable Birds in Round 1 without Science requirement, 7 of them requires a PZoo, 1 requires one Science, and 1 requires two Science => Bird Breeding is a much more logical keep
- A non-matching small animal can still be worth keeping. Else, you cannot stargaze
    - A form of **Near good**
    - Hence, keeping one Petting Zoo in starting hand is not bad
- **Hand Clogging**: Beware of clogging your hand whenever you keep "future good" cards, including `Native Animals` et al.
- Combo: 2-Science Univ into `Release of Patents` for instant CP_2 reward

#### How to read your opponent 
TODO (NoWondersTV video, pilfering monkey from PZoo, X-back Assoc/Build implies don’t want break, draw 3 means bad hand or don’t want anything display card or sunbathing (??)

## Mid Game
- TODO
- TODO Perma Break 5 Strategy

## Late Game
- Play **FAST!** in the late game. Skip any action that give you less than 6 average points...
    - Sponsor 7 Break 7 if you need to!
    - "Prioritize quick development. Sacrifice a few points if you have to."
- Think **consection actions!**. Do not waste a single turn
- TODO Consider how to maxmize all sponsor endgame bonuses, and compare with what your opponent can get
- TODO How to calculate how will the game end?
- Start calculating END when there are only two rounds left
- If you track your opponent's hand in turn-based game, calculate exactly what happens if he plays his animals
- *Rule of Six*: A less than 6 appeal action is usually too slow. The average point per turn in last 5 turns is ~10.5 pt.
    - Rush to END if you gonna have bad actions; can delay END if you still have other good actions.
    - Be concrete about oppo next actions before rushing to END. Sometimes they have will have no follow-up after a couple actions.
- In a race, do Animals 3 if you plan to do Animals twice
- It can be **overpowered** if you can do only Assoc and Animals actions
- Consider both opponent fast-crossing and stalling
- Europe PZoo is good to grab due to `Common European Adder`
- `Clever` can be excellent during late game
- Go for clarity if you are certain of the win, and don't greed
- Since endgame CPs are always multiples of 3pt, plus or minus 1-2ap can be meaningless
- TODO If you keep having good actions, can gamble oppo not having a long sequence of good actions. Try to speculate how many good actions oppo can do in a row
    - Useful in deciding whether to fast-play or slow-play

#### Number of Rounds before END
- See "END analysis.xlsx"
- A game usually has 5-6 rounds. If break is caused quickly in a round, then 6 rounds. Else, 5 rounds.
- Point, income at each break (assuming 5 breaks):
    - point: 0  10  30  60  100
    - income: 16  24  32  40  48
    - If there are 6 breaks, most likely the first two breaks combined lead to \{point = 0, income = 16\}
    - Sponsor X Break X generally lead to higher total number of breaks
- Hence, start thinking about END at around 60 appeal, or 50 appeal if you have two big projects

## Tips
- **Near Good, Open Future, Same for Deny** - learned from analyzing bsyragb's games.
- **Margin of victory is slim!** Analyze and play your best every move.
- **Be flexible!** Your plan should be adjustable to the cards showing up.
- **Protip**: Track how many actions you oppo will do before breaking
- **Take calculated risks!** Don't be afraid of exactly one card and make suboptimal play if oppo only has two cards in hand
- Strike a fine balance between playing around stuff too much or too little
- Always **track** your opponent's cards, even in the late game
- Be creative with Rep usages, e.g. `Zoo School` cover rep for Round 1 REP_5
- TODO How PZoo/Univ reward on CP track affect things (like early upgrade Assoc)
- Build 1 for kiosk/pavilion looks cute, but is *very* inefficient
- When Clever is good, it's very good. When Clever is bad, it's very bad.
- Usually, you play Side Entrance as "Main Entrance", where you build next to existing buildings in order to gain more income
- Beware of 41 CP and 113 appeal max limit
- Beware of Sunbathing if opponent suddenly draws lots of cards
- Think about what your opponent will likely do on their turn too, e.g. when considering who might cause break and discard cards
- Set an objective of next few turns so you don't forget what you want to achieve
- Before breaking, pay attention to Break income, esp. Snapping, Build 2, and `Science Lab`
- Denying oppo requires more thinking than optimizing self, therefore deny is better in longer time controls
- Do Pilfer/Venom check whenever you will end up with <$5, or even <$10 for `Japanese Macaque`
- Watching streams/replays from top players (e.g. JDansp) help a lot
- Your point toal = #ap + (#CP * 3) - 14 - min(#CP, 10)
    - e.g.) 38ap, 12CP => 38 + (12 * 3) - 14 - 10 = 50pt
- Don't just think about your hand! Think about cards on display as well.
- If very ahead, play safe. If very behind, gamble more.

## Map Guide
> Reference: ["#1 Ark Nova Player Map Ratings and Tips (JDansp /w Darcelmaw)"](https://www.youtube.com/watch?v=jCQwYeEdd7o)
> Every map has 42 empty spaces except Park Restaruant which has 43
1. Silver Lake
    - Geo 14, Hydro 22
    - Start near the lake
    - Archaeologist for reputation usually
    - Determination is the most overpowered map bonus during late game
        - Thus, save for it when unlocking map bonuses
    - `Free-Range New World Monkeys` very good on this map
2. Rescue Station
    - Geo 16, Hydro 20
    - Start near a digging spot
    - Build towards other digging spot, so you can dig ASAP if an important card shows up on display
    - Dig icons which match projects
    - Can dig large Herbivore for Flocking potential
3. Outdoor Areas
    - Geo 19, Hydro 15
    - Start near free partner zoo spot
    - `Archaeologist` is extremely overpowered, because you gain 3 partner zoos for free
    - Last water spot for `Hydrologist` is inconvenient
    - Cute play: Gain 3 partner zoos in Round 2 to gain 2nd worker
    - It's okay to cover one "Outdoor Areas" spot to play Aquarium on bottom right
    - Aviary is less valuable because you aleady have "Outdoor Areas"
    - Large animals requiring rock is weaker, because there is one spot to connect rock to "Outdoor Areas"
4. Research Station
    - Geo 20, Hydro 19
    - Start near free Univ spot
    - Or start near "Research Station"
    - Optimal play: Association 3 for partner zoo in Round 1, then build on free Univ spot in Round 2. Difficult for opponent to block Univ
    - Petting Zoo is better on starting hard for covering Univ spot
    - Can play `New Zealand Fur Seal` Round 1
5. Commercial Harbor
    - Geo 23, Hydro 21
    - Start near "Commercial Harbor"
	- Cards upgrade and unlock snap are insured at +$3
    - Consider upgrading Cards early to sell more cards => don't need kiosks that much => can skip upgrading Build
        - Should upgrade one of Build or Cards early, but perhaps not both. Sometimes top players upgrade Cards last even
    - Predators are very good on this map due to Sprint and Hunter abilities
    - Consider Cards 4 for efficient selling
6. Ice Cream Parlors
    - Geo 27, Hydro 11
        - `Hydrologist` is bad because water spaces are sacrce; and you want to leave water spaces open for late game
    - Start near the two rep spots is optimal. Then, you only need one extra rep to rush REP_8 worker with Upgraded Animals and double Univ
        - "Forced" Round 2 REP_8 worker: 2rep Univ and cover both reps REP_5 upgrade Animals -> Animals 5U -> 5-hand Univ -> Animals 5U REP_8 worker
        - Hence, Petting is good on this map
    - Else, start near a parlor spot
    - Rush complete ICP might not be worth it if you do not have any placement Sponsor to help
    - Incentivized to fill map for 7ap
    - Bad map for `Aquarium`
7. Hollywood Hills
    - Geo 15, Hydro 19
    - Start near 5 money/reputation/sponsor card spot
    - Upgrade Sponsors to obtain turbo Sponsors discount
    - Okay to upgrade Association if you have covered some sponsor card spots, but have not drawn an upgraded sponsor card
    - Cover H early is good for gaining knowledge
        - Due to tendency to hoard sponsors, 5-Hand Univ becomes more valuable
        - Also, sponsors are stronger early on, often worth a discard
8. Park Restaurant
    - Geo 25, Hydro 25
    - Start near "Park Restaurant"
    - Building spots are tight!
    - Can unlock Reptile House/Aviary to complete map
9. Geographical Zoo
    - Geo 13, Hydro 26
    - Start near whichever continent you plan to play animal next
    - Try to connect to the middle of the map quickly, so you gain access to all continents
    - Generally, gain 2 appeal is the best continent bonus; sometimes Clever can be crucial
10. Observation Tower
    - Geo 17, Hydro 15
    - Start near "Observation Tower"
    - Worse map because rock and water are highly separated => very inflexible

## Turn-Based Guide
- **It’s not about winning the game; it’s about making the best move.**
- **One Move at a Time**: Whenver oppo takes a turn, something might change your next move. So always reconsider.
- **Always think a few moves ahead. Do not play impulsively.**: You have made countless mistakes by playing too fast.
    - Especially when you are about to make a good move, you often forget to think about next moves, resulting in bad moves soon after.
    - [Emanuel Lasker] "When you see a good move, look for a better one."
- **Disguise** you actions by leaving Sponsors or Assoc at a high strength, if it doesn't hurt you
- Queue up for a turn-based game at ~7:00pm, to minimize time zone differences with players from Asia or Europe
- **Scouting**: Analyze oppo's game history beforehand to understand their play patterns
- Oppo multi-table 10+ games => distracted
- To find the best move, calculate candidate moves and compare
    - Evaluate with general principles before calculating deep, else you might lose the big picture
    - When faced with multiple complicated lines, go through them the same number of turns and observe the differences
- When calculating variations, do not forget that you can also cause the BREAK
- When calculating variations, use this template for action sequence, progress and money at end of line
    - e.g.) {Animals Assoc Sponsor Cards Build BR? ?H ?X ?rep ?ap ?CP =?pt $? K$$? $$$? BR:[snap, 2-size, 1CP]}
- Notes Template:
```
# Strategy
# Aware
# Synergies
# Display Interest
# Action
# Oppo Read
# Oppo Hand
# Oppo Knowledge
# Discard
- (Animals)
- (Sponsors)
- (Projects)
```
- **Simulation**: Assume you are gonna draw a certain representative card, and see how it plays out
- To avoid AP-ing too much, choose a decent line to calculate out then consider how to tune it
- Consider 2-3 lines of oppo each time to not get surprised. However, do not trust your read too much; even 600 Elo oppo surprises you from time to time.
- Beware of oppo nuts, but remember they often don't have it
- Oppo **Polarized Breaking**: When there are two polarizing lines to calculate, on whether oppo advances break or not, consolidate the commonalities and isolate the few different actions you will be taking
    - Often your own actions will be quite similar :)
- **Card Prophylaxis**: When deciding which cards to draw, if you are not gonna play them this round, you can simply consider which cards you need in your hand at the start of your next round
- Skim through CP_track, Assoc board, both player's board, REP_track and display before making a move
- Look for miracle plays utilizing placement bonuses
- Check which PZoos and Univs have already been taken this round
- Turns that take the longest time:
    - Starting hand selection
    - First action
    - right after each BREAK
    - when you need to draw/discard multiple cards
    - decide which to unlock with Assoc 5

## Player-Specific Reads
- JDansp
    - Thinks very high income is unnecessary

- Tsong Chen
    - Prefers having all four upgrades
    - Likes to upgrade Assoc

- dwarvintime
    - Loves unconventional play, such as unlock 2-size and skip Build upgrade
    - Favors `Sponsors -> Animals -> Cards -> Assoc` upgrade order
    
- human_light
    - Loves to unlock 2-size and skip Build upgrade
    
- Julie_1104
    - Will upgrade Assoc early to donate rush CP_2/CP_5
    - Prefers PZoo over Univs for discounts and project support
    - Focuses on animals which completes projects

- Aaron1021
    - Values income very highly => Spam kiosks, and loves Sponsor upgrade
    - Tries to fill map
    - Prefers Univ over PZoo
    - Loves upgrading Build

- Rayhaan2812 == Alay
    - Likes to keep cards for late game
    - Good at playing cards from display

- jppandas154
    - Upgrades [Animals, Build, Cards] 100%, Association 99%, Sponsors 1%
    - Values spamming sponsors in Round 1; thinks Sponsor is strongest action in Round 1
    - Multi-table 10+ games => distracted

- af145
    - Doesn't know too well which cards are the most powerful
        - e.g.) Prioritize `Medical Breakthrough` due to 4-Science requirement
    - Terraforming Mars mindset => Likes to keep good cards and large animals for lategame
    - Loves Univ start, esp. 5-hand Univ
    - Focuses on animals which completes projects
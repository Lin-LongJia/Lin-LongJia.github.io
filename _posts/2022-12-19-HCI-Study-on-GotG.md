---
title:  "Game Design and HCI Study on Marvel's Guardians of the Galaxy Game"
layout: post
categories: blog
---

![My project (3)](https://user-images.githubusercontent.com/29043325/208528633-2985b886-e688-4727-b861-04c79b54863d.png)

My deep analysis of game design choices that influenced the UI decision that hinders user experience and my interpretation how it should have been deigned



## Design Choices

Marvel's Guardian of the Galaxy(GotG) is a game that puts extra emphasis on its mechanic to incorporate team skills instead of supports for a main character. Unlike the most of the action games where the main character can unlock various combination of basic keys to generate satifying impact and blows to enemy, the core control for Star Lord in shoot bullets and break shield with its elemental weapon. The fundamental combat system is to break shield and use everyone's ability to clear out this wave of the enemy, and stall to repeate the process for the next wave of enemies. This is demostrated throughout its initial chapters by as the game hightlights what each character's first ability can offer. Especially opening the charter with Rocket and Groot, demostrating that Groot can do a area of effect(AoE) root and Rocket is able to do high AoE damage, it is very intutivive hat the game wants you to use these abilits as combo pieces. 
   
GotG also engages with the play by incorporating interactble dialogue during missions, this is very smart design choices as it fits Star Lord's charactistic very well, and also introduces mechanic where different response can result in different event outcomes. Reusing this to define the effect of the "Huddle" mechanics is very smart too.

These are the 2 core mechanic that I think it had to make the game stood out amongs the rest.

## The Problems
#### Lack of Identity
You probobaly know about the GotG if you played this game, whether from comic book or the movies

While the game did very well to show the chacter of the crew using dialogues and story it did not do a very good job a what their role is in combat.
Rather than constrain each character to be particularly good at a specfic thing, evey character has a abilities that are somewhat doing the same job as another character's ability. In general you can categorized a chacter to have an AoE ability, a Single target ability, a crowd control ability and their signature move. This not only washed out what makes each character unique in combat but also added a lot of option that is going to become overwhelming very quickly. 

I believe the develope do this because they wanted the player to explore diffent combination of abilities and express the chaotic battle sequence, however I found it to be less true, as I often just use the bread and butter combo such as Groot root + Rocket AoE Grenade, or having Garmora and Drax doing heavy single target damage to a big target. Or just use all the ability without really thinking when the boss enters the weak state. Notice that I have not mention Star Lord? Yes, I do often find myself not really using any of the Star Lord's ability because most of the game mechanics still relys on the Star Lord's gun, partularly the part to break enemies shied with elemental weapon. 

So the each of the side character can do little bit of everything, which redued their personal indentity in combat, what about out main character Star Lord? I think the development team complete miss the mark on Star Lord. The basic kit of Star Lord, like many hack and slash action games, a dodge/roll, a jump, and ways of combating. Star Lord's main way of combat is using R1 and R2 being the primary fire and elemental fire, and a meele button. The generic combat system is like any other action hack and slash game where you dodge attack to get bouns while maintaining your rates of attack, with Star Lord's primary ways of damage being range attack, I question the necessity of a meele attack button. The moment when you begain to feel like you are playing as Star Lord is when you uses his very first ability "Vantage Point." This bascially lets you hovers in air to do damages in a safer distance away from melee enemies. I would say this ability is what I would define some character differently from others, this ability essentally makes this character Star Lord. But locking behind cooldown and unnatural inputs makes this ability more forgetful more than anything else.

#### Ability UI
I spoke about the ability design and my view on why the developer do this. This not only created the identity problem but also cognitive load issue. The Cognitive Load theory suggest that there are limits to what a person can focus on given on a senerio of tasks. With the GotG giving each charater 4 abilites that is 20 abilities to worry about, with each abilties require at least 3 tacktile input to execute, there is a lot of stress to decide which character to call, and which ability to use. 

Here is a scenario of a typical combat loop. You hold down L2 and R2 to lock and shoot while moving using L3 as Star Lord. The most comfortable time to call for skills is when you are reloading, as this is when you are most vulnerable and free and there is a benefit of reducing your reload time if you press R2 when the reload bar is at green, so you have few frams to use abilites to maximize your output, but when you uses L1 to open up the charater menu, you have to make a decison on who to call...time lost, afterward you have to decide which ability to use with each character's skill has different order it is hard to track which is which in your mind...Time lost again. Then you will find yourself miss the window for the quick reload, which you also have to ensure you hold L2 to make sure the bouns shot hits a target. Therefore a lot times you ended up using your typical combinations bbecasue it requires less cognitive thinking to make sure you still get your reload bouns.

#### Control
There are some controlling issues that does not let me enjoy the game initially. One of the first unusual thing is Visor toggle, it is essentally a radar tools in many other games that reveal hints and highlight specific area for progression. Unlike many other game where it is a press and scan, it is a press on and press off. The decision is made to simualte Star Lord putting on the helmet to scan area and taking it off. Then I would questions why would the development team put some extra effort to have the scan mode more combat friendly, giving a better visual and offer combat assistance like hight target weakness auto aim mode, since Star Lord fights with his helmet on anyways.

The "Huddle" mechanics called by using L2 and R2 together can probably use different inputs, becasue L2 and R2 are purposful buttons during any combat, R2 lets you shot in elemental projectile and L2 opens up the team window for abilites, I found myself in may occasions trys to call a crew ability whying shotting ice bullets just to "Huddle Up" when I do not need it. 

## My Ideas
With these design flaws mentions above I will attempt to put my idea on it one by one.

#### Identity Crisis
To fix is fairly easy, you actually give each crew member an identity in combat. It is fairly easy to identify as it is stereotyically used to solve puzzles and as their initial ability. For groot, you make him a simply a crowd control guy, Rockey is the AoE person, where Gamora can be the person who can build up the enemy status bar, and Drax will deal heavy single target damage.

Rather than having 4 skills for each character, I think just one ability and one ultimate ability. We shall keep the current ultimate ability because they are true to their character, but moodifies the other 3 abilities into one using upgrade system to improve upon it. An excellent example is Groot, his inital ability should just be a short duration root for small enemies, with upgrate he will be able to root larger enemies, then add AoE potential to it, and finally add damaging component as the final upgrade. An example of Groots final upgrade is Groot is able to root large enemies in an AoE fashion before throwing them up and slaming them to the ground. 

Using an upgrade system we can make sure the ability can stay true to one identity and also show sens of progression

#### Ability UI
This is related to explaination above, if a chacter has 1 normal ability and 1 ultimate ability, it is much easier for player to make a quick decision, for example L2 -> D-Ppad Left -> Square is the sequence for normal ability and L2 -> D-Ppad Left -> Circle for ultimate. Keeping the input option binary reduces a lot of stress as personally I am doing the same combination of buttons anyways. 

If you want to keep the current design, the UI can have a quick fix by simply having an order in the way ability UI is displayed. You see, the durrent problem is every chacter's left ability is diffent in concept and goes the same as other abilities. What an ordered UI for abilits would be keeping the crowd control abilty for all character as the left ability, keep all the ultimate ability as the down ability etc... This way player will get a sense of pattern and familiarity with each character which will reduce the process time for player.

#### Control
At the current state playing Star Lord does not standout compare to any other character of the same genre. During most of the game play the primary button you press are L2, R1 and R2 which make sense as you are playing as a shooter, however I think there is a lot of oppotunites lost here.

As I mention before one of the mechanic that would identify your character as Star Lord is the hovering ability that was lock behind as an ability. I argue by incorporating this as a core combat loop is much btter than giving the palyer limited access to it. In my opinion the hoving ability should have its own decay bar called fuel energy where you can initialized it by releasing the jump button after holding it for some time, it will initialy give Star Lord a Hight boost, gradually falling down as fuel energy decays, he can gain hieght by pressing jump, dodge by pressing cirle at a cost of some fuel energies. They you can add more mechanic/upgrade invovels with hovering ability.

Also when you play on a PS4 controller I found it is super rare for you to ever need to press square or triangel, they do not serve a purpse in combat, well you can melee but it does not do much damage at all and you are usually at rage shooting anyway so I found those 2 button to be useless. Well in many of Star Lord's we see him using other tools beside his gun to do cool things like gravity grenade that pull things towards it, the development team can definitely add more tools to the player to make the character more Star Lord like. Another ideas for the button is to incorporated into team attacks, while the triangle is used as team attack mechanics and as a finisher, it is not consistence and you never know when you can use it. A great idea for this situation is using trigane as a quick time event to a follow up of an chacter's ability like how Noctis can do a sync attck after you selected a team member to use an ability in Final Fantasy XV. I think this would have created more bond to show teamwork and campion which was the key idea of the game.

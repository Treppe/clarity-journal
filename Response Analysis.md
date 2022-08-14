# Response Analysis
## Analyzing existing games  
Response | Game | Situation | Tools | Outcomes | Decision tree
--- | --- | --- | --- | --- | ---
**inactive emotional** | Psychonauts 2 | An interns teaming up with Ratz to complete the mission in casino | A player's attitude toward other interns | The game evokes in a player emotions of fun, surprise and fellowship | nan 
**proactive twitch** | Transistor | Player applied *functions* and movement in *Turn()* mode | *Functions*, *Turn()* | The game responses with a fast series of action animations and executions, which player thoughtfully directed a moment ago | nan
**reactive twitch** | The Witcher 3 | An enemy telegraphs its attack with animation | Parry, roll, dodge, traps, signs, ranged weapons | Player has a window of opportunity to utilize one of many combat tools they have and change the outcome of enemies attack | [link](DecisionTrees/DTree_TheWitcher3.png)  
**proactive choice** | 
**reactive  choice** | Middle-earth: Shadow of Mordor | The uruc's captain you are hunting is ambushed by another captain of the lower tier | The Nemesis system | Any decision player makes about resolving this situation will affect a power structure in uruc's army. The player is the one to choose how exactly it will change | [link](DecisionTrees/DTree_MiddleEarth.png) 
**proactive strategy** | Fallout: New Vegas | "Arizon Killer" quest (president Kimball assassination). Before president's arrival | Skills proficiency, NCR disguise, C-4, any other weapons | The Courier has a limited time (>1 hour of real time) to make some preparations for president's assassination. In this hour the player can set up a variety of traps for the arriving president: booby traps, presidents Vertibird flight system sabotage, strategize stealth kill and more | [link](DecisionTrees/DTree_FalloutNV.png)      
**reactive strategy** | Endless Legend | Global event: "Ententes and Alliances" | Alliance mechanic | When event starts player has a decision to make: build an alliance with another player and get an influence boost or ignore it and keep playing solo. Both these decision influence  the later player's strategy in a big way (see examples in decision tree) | [link](DecisionTrees/DTree_EndlessLegend.png)

## Premade scenario - Sniper
**Situation**
	- an FPS, a sniper atop a mountain far away is taking shots at you
- **Warning**
	- a laser beam flickering around you for a few seconds, then becomes solid and red right before the shoot is fired
- **How can your character respond to this situation?**
  ![](DecisionTrees/Sniper.png)

## Create your own mechanics
1. **Consider a ram** - create an attack that it could perform at combat
   - Headbutt 
2. **Twist it** - add a modifier to the creature
   - It's a [gorgon](https://www.dndbeyond.com/monsters/16908-gorgon) ram
3. **Update** your situation 
   - The ram stands on the back hooves and bleeps. The green gas emerges from its nose. It stands back on its four and a green circle of gas slowly grows around the ram. 
   - While ram performing this gas evaporating attack it also takes a defensive stance: taken damage is reduced
   - Player reduces its speed when touched by gas. If gas touches the player for more then 2 seconds it makes player *petrified* and they can't move until take any damage or the ram dies. Any damage taken while petrified is doubled 
4. **Create the player's decision tree**
  ![](DecisionTrees/Ram.png)
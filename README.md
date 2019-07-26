# Repubblica Romana

Repubblica Romana is an HPM Submod based around the events in Rome during the Liberal Revolution that swept through Europe. The Minister of the Interior, Pellegrino Rossi, was assassinated, causing the Pope to flee to neighboring Gaeta. In his absence, the government fell to liberal agitators who established the Roman Republic. This unrecognized government lasted for about a year until French soldiers were sent by Napoleon III to restore the papacy.

## Changelog:
### Version 0.1.1:
#### Mechanics -
* "Temporal Papacy" Mechanic added
	* From start of game, Papacy has the "Temporal Papacy" Country Modifier.
		* +0.01 Prestige
	* All starting provinces with majority Catholic pops get the "Temporal Papacy" Province Modifier
		* -0.1 Militancy
		* -0.1 Consciousness
#### Events -
* "Assassination of Pellegrino Rossi" modified
	* Added functionality of "Flight to Gaeta" Decision
	* Added second option to maintain Papal authority. No flavor added, yet.
* "Tuscan Revolution" modified
	* Cleanup Event added to convert Tuscany to a republic if the Republic wins the war in either Concedes or Defiant.
#### Decisions -
* "1836 Setup" Decision added
	* Gives the Papacy the Temporal Papacy modifiers where appropriate.
* "Flight to Gaeta" Decision removed
	* Integrated into the "Murder of Pellegrino Rossi" Event.
* "Seize Church Lands" Decision modified
	*Modifier now gives -10% Education Efficency, as well.
#### Miscellaneous -

### Version 0.1:
#### Events -
* "Murder of Pellegrino Rossi" Event added
	Kicks everything off
* "Tuscan Revolution" Chain added
	* "Tuscan Riots" Event added
	* "Tuscan Revolution" Event added
	* Three paths set up; Duke Flees, Duke Concedes, Duke Defiant.
		Flees - Duke Leopold flees and a liberal national assembly establishes a republic, petitioning for Republican statehood.
		Concedes - Duke Leopold caves to liberal demands and establishes a constitutional monarchy, petitioning for Republican vassalage. Republic can decline and instead elect to evict the Hapsburg
		Defiant - Duke Leopold denies the liberals and they petition the Republic to intervene.
* "Pope Flees Rome!" Event added
	* All European Great Power Catholics get the "Reinstall Papacy" Casus Belli
#### Decisions -
* "Flight to Gaeta" Decision added
	* Changes Papal States to the Roman Republic
	* Allows everything else to happen
* "Garibaldi's Legion" Decision added
	* Gives the "Garibaldi's Legion" modifier
		* +5% Organization Regain 
		* -5% Supply Consumption
	* Costs 10,000£
* "Seize Church Lands" Decision added
	* Gives the "Weakened Clergy" modifier
		* -5% Research Points
	* Gives 15,000£
#### Countries -
* Added Emilia and cores to Parma and Modena provinces
#### GFX - 
* Added Decision pictures for all decisions
* Added custom flags for Emilia
#### Casus Belli -
* Reinstate Papacy CB added
	* Is only given by event/cannot be fabricated
	* Puppetizes the Papal States and sends an event to return it too a theocratic government.
#### Miscellaneous -
* Removed various unneeded files for compatibilty with HPM
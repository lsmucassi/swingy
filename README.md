# swingy

A text-based RPG based on the gameplay and conditions described below. The program follows the Model-View-Controller architecture and allow switching between the console view and GUI view.

A player can have multiple heroes of different types. When the player starts the game he has 2 options: • Create a hero • Select a previously created hero.

In either case, the player can see the hero stats: • Hero name • Hero class • Level • Experience • Attack • Defense • Hit Points

Hero stats are affected by the hero level and artifacts. There are 3 types of artefacs: • Weapon - increases the attack • Armor - increases defense • Helm - increases hit points

After choosing a hero the actual game begins. The hero needs to navigate a square map with the size calculated by the formula (level-1)*5+10-(level%2). For example a hero of level 7 will be placed on a 39X39 map. The initial position of the hero is in the center of the map. He wins the game if he reaches on of the borders of the map

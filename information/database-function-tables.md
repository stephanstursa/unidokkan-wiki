---
Title: Database Function Tables
Sort: 2
---
#### Causality Types
| Causality ID | Name | Description | cau_val1 | cau_val2 | cau_val3 |
|:------------:|-------------------------------|--------------------------------------------------------|------------------------------------|---------------------|----------|
| 0 | isNoneRule | Nothing |  |  |  |
| 1 | isOverHpRate | HP is above percent | HP Percent |  |  |
| 2 | isUnderHpRate | HP is below percent | HP Percent |  |  |
| 3 | isOverEnergy | Ki is above a number | Ki Amount |  |  |
| 4 | isUnderEnergy | Ki is below a number | Ki Amount |  |  |
| 5 | isElapsedTurn | Battle has past turn number | Turn |  |  |
| 6 | isPartyRaceType | Checks if entire deck has a certain link skill | Link Skill ID |  |  |
| 7 | isEnemyRaceType | Checks if enemy has certain link skill | Link Skill ID |  |  |
| 8 | isOverFightingPower | Checks current attack and defense is over a number | Attack | Defense |  |
| 9 | isUnderFightingPower | Checks current attack and defense is under a number | Attack | Defense |  |
| 10 | isOverHpRateOverEnergy | HP is above percent, Ki is above number | HP Percent | Ki Amount |  |
| 11 | isOverHpRateUnderEnergy | HP is above percent, Ki is below number | HP Percent | Ki Amount |  |
| 12 | isUnderHpRateOverEnergy | HP is below percent, Ki is above number | HP Percent | Ki Amount |  |
| 13 | isUnderHpRateUnderEnergy | HP is below percent, Ki is below number | HP Percent | Ki Amount |  |
| 14 | isFirstAttack | Card is in first slot |  |  |  |
| 15 | isOverTargetNum | More than a number of enemies | Number of Enemies |  |  |
| 16 | isUnderTargetNum | Less than a number of enemies | Number of Enemies |  |  |
| 17 | isOverTargetHpRate | Enemy target HP above a percent | HP Percent |  |  |
| 18 | isUnderTargetHpRate | Enemy target HP below a percent | HP Percent |  |  |
| 19 | isAttackOrder | Checks card slot position | Slot (0, 1, 2) |  |  |
| 20 | isOverEnergyCondition | Ki is above percent | Ki Percent |  |  |
| 21 | isUnderEnergyCondition | Ki is below percent | Ki Percent |  |  |
| 22 | isPartyExistChara | Check if character is present in deck | Card Unique Info ID |  |  |
| 23 | isLinkNum | Check if at number of links or greater are active | Number of links |  |  |
| 24 | isHitDamaged | Activates upon being attacked |  |  |  |
| 25 | isTargetKill | Activates when target is killed |  |  |  |
| 26 | isOverHpRateEnableSpecial | HP is above percent, card has enough ki to super | HP Percent |  |  |
| 27 | isUnderHpRateEnableSpecial | HP is below percent, card has enough ki to super | HP Percent |  |  |
| 28 | isSlotElementType | Checks if any cards on rotation are a certain element | Element Type |  |  |
| 29 | isEnemyExistChara | Check if character is an enemy | Card Unique Info ID |  |  |
| 30 | isGuardSuccess | Check if card is guarding |  |  |  |
| 31 | isCombinationAttack | Activates if there are three enemy attacks |  |  |  |
| 32 | isChangeEnergyBallColor | Checks if there is a ki of a certain type on the board | Ki Type |  |  |
| 33 | isBetweenHpRate | Checks if card HP percent is between two numbers | HP Percent Lower | HP Percent Higher |  |
| 34 | isOverTeamCategoryNum | Check if category card is present | 0 for deck; 1 for enemy | Category ID | Unknown |
| 35 | hasAllElementBitpatternCards | Checks if deck has all types of an element bitset | Element Bitset |  |  |
| 36 | isOverHpRateAndElapsedTurn | HP is above percent, battle has past turn number | HP Percent | Turn |  |
| 37 | isUnderHpRateAndElapsedTurn | HP is below percent, battle has past turn number | HP Percent | Turn |  |
| 38 | isTargetEnemyCondition | Enemy has required status effects | Status Effect Flags (see footnote) | Unknown |  |
| 39 | isTargetElementTypeBitPattern | Check if enemy element matches element bitset | Element Bitset |  |  |
| 40 | isSpecialAttack | Activates if card has used a special attack |  |  |  |
| 41 | isOverTeamUniqueCardNum | Activates if deck has card with name | Unknown | Card Unique Info ID | Unknown |
| 42 | isEnergyBallGetNum | Activates if card gets more then specified Ki amount | Unknown | Ki Amount |  |

<br />

##### Causality #38 - isTargetEnemyCondition Status Flags

| Status Mask | Description |
|:-----------:|---------------------------|
| 1 | Unknown |
| 2 | Unknown |
| 4 | Unknown |
| 8 | Unknown |
| 16 | ATK Down |
| 32 | DEF Down |
| 64 | Unknown |
| 128 | Unknown |
| 256 | Efficacy Type 9 |
| 512 | Efficacy Type 47 |
| 1024 | Sealed (Efficacy Type 48) |
| 2048 | Efficacy Type 8 |
| 4096 | Unknown |
| 8192 | Efficacy Type 53 |
| 16384 | Efficacy Type 75 |
| 32768 | Efficacy Type 94 |
| 65536 | Efficacy Type 96 |
| 131072 | Unknown |
| 262144 | Unknown |
| 524288 | Efficacy Type 100 |
| 1048576 | Efficacy Type 101 |

<br /><br />

#### Calc Options
| Calc Option 	| Description        	|
|:-------------:|--------------------	|
| 0           	| Calc Plus          	|
| 1           	| Calc Minus         	|
| 2           	| Calc Percent Plus  	|
| 3           	| Calc Percent Minus 	|
| 4           	| Calc Equal         	|

<br /><br />

#### Efficacy Types
| Efficacy Type 	| Description                                               	|
|:---------------:	|-----------------------------------------------------------	|
| 1             	| Change Atk Param                                          	|
| 2             	| Change Def Param                                          	|
| 3             	| Change Atk Def Param                                      	|
| 4             	| Change Heal Hp                                            	|
| 5             	| Change Enegy Param                                        	|
| 8             	| Change Condition Delay                                    	|
| 9             	| Change Condition Stun                                     	|
| 11            	| Change Attack Order                                       	|
| 12            	| Change Pain Attack                                        	|
| 13            	| Change Resist Damage                                      	|
| 16            	| Change Element Type Atk                                   	|
| 17            	| Change Element Type Def                                   	|
| 18            	| Change Element Type Atk Def                               	|
| 19            	| Change Element Type Hp Param                              	|
| 20            	| Change Element Type Enegy Param                           	|
| 21            	| Change Recovery                                           	|
| 22            	| Change Condition Heal                                     	|
| 24            	| Change Guard Break                                        	|
| 26            	| Change Absorb Special Energy                              	|
| 27            	| Change Resist Special Damage                              	|
| 28            	| Change Absorb Deal Damage                                 	|
| 34            	| Change Dokkan Gauge Bonus                                 	|
| 35            	| Change Heal Bonus                                         	|
| 36            	| Change Special Bonus                                      	|
| 37            	| Change Energy Bonus                                       	|
| 38            	| Change Linkage Bonus                                      	|
| 39            	| Change Element Type Energy Bonus                          	|
| 40            	| Change Element Type Linkage Bonus                         	|
| 43            	| Change Hp Atk                                             	|
| 44            	| Change Element Type Hp Atk                                	|
| 46            	| Change Passive Probability Bonus                          	|
| 47            	| Change Condition Psychic                                  	|
| 48            	| Change Condition Astute                                   	|
| 50            	| Change Invalid Bad Condi                                  	|
| 51            	| Change Energy Ball Color                                  	|
| 52            	| Change Resurrection                                       	|
| 53            	| Change Condition Chance Time                              	|
| 54            	| Change Invalid Combination Attack Bonus                   	|
| 55            	| Change Target Def And Self Atk                            	|
| 56            	| Change Target Def And Self Def                            	|
| 57            	| Change Target Def And Self Energy                         	|
| 58            	| Change Energy Ball Heal                                   	|
| 59            	| Change Energy Ball Proportional Atk                       	|
| 60            	| Change Energy Ball Proportional Def                       	|
| 61            	| Change Energy Ball Proportional Atk Def                   	|
| 63            	| Change Special Energy Cost                                	|
| 64            	| Change Element Type Energy Ball Proportional Atk          	|
| 65            	| Change Element Type Energy Ball Proportional Def          	|
| 66            	| Change Element Type Energy Ball Proportional Atk Def      	|
| 67            	| Change Energy Ball Color Bitpattern                       	|
| 68            	| Change Energy Ball Proportional Bitpattern                	|
| 69            	| Change Energy Ball Color Specify Random                   	|
| 70            	| Change Energy Ball Color Specify Random Without Obstacles 	|
| 71            	| Change Hp Range Atk                                       	|
| 72            	| Change Hp Range Def                                       	|
| 73            	| Change Hp Range Atk Def                                   	|
| 74            	| Change Hp Range Ball Heal                                 	|
| 75            	| Change Condition Disable Swap                             	|
| 76            	| Change Condition Advantageous Atk Element                 	|
| 77            	| Change Reset Ball Color                                   	|
| 78            	| Change Condition Advantageous Def Element                 	|
| 80            	| Change Counter Attack                                     	|
| 81            	| Change Extra Attack                                       	|
| 82            	| Change Element Type Hp Atk Def                            	|
| 83            	| Change Element Type Energy Bitpattern                     	|
| 84            	| Change Suicide Attack                                     	|
| 85            	| Change Step Extra Attack                                  	|
| 86            	| Change Special Atk Rate                                   	|
| 87            	| Change Element Type Attack Coef                           	|
| 88            	| Change Element Type Defense Coef                          	|
| 89            	| Change Element Type Attack Defense Coef                   	|
| 90            	| Change Critical Attack                                    	|
| 91            	| Change Dodge                                              	|
| 92            	| Change Always Hit                                         	|
| 93            	| Change Element Type Bitpattern Hp                         	|
| 94            	| Change Invalidate Stun                                    	|
| 95            	| Change Dodge Counter Attack                               	|
| 96            	| Change Energy Ball Additional Point                       	|
| 97            	| Change Absorb Special                                     	|
| 98            	| Change Incremental Param                                  	|
| 99            	| Change Invalidate Status Down                             	|
| 100           	| Change Invalidate Astute                                  	|
| 101           	| Change Prediction                                         	|
| 102           	| Change Metamorphic Probability Count Limit                	|
| 104           	| Change HP Atk Def                                         	|
| 105           	| Replace Energy Ball                                       	|

<br /><br />

#### Target Types
| Target Type 	| Description                     	|
|:-------------:|---------------------------------	|
| 0           	| None                            	|
| 1           	| Self                            	|
| 2           	| Party All                       	|
| 3           	| Enemy                           	|
| 4           	| Enemy All                       	|
| 5           	| Self And Target                 	|
| 6           	| Party Race Type                 	|
| 7           	| Party Exist Chara               	|
| 8           	| Target Excepct                  	|
| 9           	| Target Party Enemy Attack Order 	|
| 10          	| Slot Attacker                   	|
| 11          	| Party Slot Random               	|
| 12          	| Party Cho                       	|
| 13          	| Party Goku                      	|
| 14          	| Enemy Cho                       	|
| 15          	| Enemy Goku                      	|

<br /><br />

#### Influence Types
| Influence Type 	| Description 	|
|:----------------:	|-------------	|
| 0              	| None        	|
| 1              	| Both Ends   	|
| 2              	| Left        	|
| 3              	| Right       	|
| 4              	| Jump Left   	|
| 5              	| Jump Right  	|

<br /><br />

#### Exec Timing
| Exec Timing | Description         |
|:-----------:|---------------------|
|      1      | Start Round         |
|      2      | Link Skills         |
|      3      | Your Turn           |
|      4      | Unknown             |
|      5      | Enemy Turn          |
|      6      | Unknown             |
|      7      | Unknown             |
|      8      | Battle Result Phase |
|      9      | End Round           |
|      10     | Unknown             |
|      11     | End of Puzzle Phase |

<br /><br />

#### Effect Pack Category
| Effect Pack Category | Animation Path |
|----------------------|-----------------------------------|
| 0 | comic_text/ja/%s/%s.lwf |
| 1 | ingame/battle/effect/%s/%s.lwf |
| 2 | ingame/sugoroku/effect/%s/%s.lwf |
| 3 | outgame/effect/%s/%s.lwf |
| 4 | ingame/battle/sp_effect/%s/%s.lwf |
| 5 | ingame/battle/sp_effect/%s/%s.lwf |
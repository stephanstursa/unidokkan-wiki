---
Title: Database Function Tables
Sort: 2
---
### Causality Types
| Causality ID | Description                   |
|:------------:|-------------------------------|
|       0      | isNoneRule                    |
|       1      | isOverHpRate                  |
|       2      | isUnderHpRate                 |
|       3      | isOverEnergy                  |
|       4      | isUnderEnergy                 |
|       5      | isElapsedTurn                 |
|       6      | isPartyRaceType               |
|       7      | isEnemyRaceType               |
|       8      | isOverFightingPower           |
|       9      | isUnderFightingPower          |
|      10      | isOverHpRateOverEnergy        |
|      11      | isOverHpRateUnderEnergy       |
|      12      | isUnderHpRateOverEnergy       |
|      13      | isUnderHpRateUnderEnergy      |
|      14      | isFirstAttack                 |
|      15      | isOverTargetNum               |
|      16      | isUnderTargetNum              |
|      17      | isOverTargetHpRate            |
|      18      | isUnderTargetHpRate           |
|      19      | isAttackOrder                 |
|      20      | isOverEnergyCondition         |
|      21      | isUnderEnergyCondition        |
|      22      | isPartyExistChara             |
|      23      | isLinkNum                     |
|      24      | isHitDamaged                  |
|      25      | isTargetKill                  |
|      26      | isOverHpRateEnableSpecial     |
|      27      | isUnderHpRateEnableSpecial    |
|      28      | isSlotElementType             |
|      29      | isEnemyExistChara             |
|      30      | isGuardSuccess                |
|      31      | isCombinationAttack           |
|      32      | isChangeEnergyBallColor       |
|      33      | isBetweenHpRate               |
|      34      | isOverTeamCategoryNum         |
|      35      | hasAllElementBitpatternCards  |
|      36      | isOverHpRateAndElapsedTurn    |
|      37      | isUnderHpRateAndElapsedTurn   |
|      38      | isTargetEnemyCondition        |
|      39      | isTargetElementTypeBitPattern |
|      40      | isSpecialAttack               |
|      41      | isOverTeamUniqueCardNum       |
|      42      | isEnergyBallGetNum            |

<br /><br />

### Calc Options
| Calc Option 	| Description        	|
|:-------------:|--------------------	|
| 0           	| Calc Plus          	|
| 1           	| Calc Minus         	|
| 2           	| Calc Percent Plus  	|
| 3           	| Calc Percent Minus 	|
| 4           	| Calc Equal         	|

<br /><br />

### Efficacy Types
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

### Target Types
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

### Influence Types
| Influence Type 	| Description 	|
|:----------------:	|-------------	|
| 0              	| None        	|
| 1              	| Both Ends   	|
| 2              	| Left        	|
| 3              	| Right       	|
| 4              	| Jump Left   	|
| 5              	| Jump Right  	|

<br /><br />

### Exec Timing
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
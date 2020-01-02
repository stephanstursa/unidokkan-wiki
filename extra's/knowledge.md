---
Title: Knowledge
Description: work in progress. Come back later
---
## **Custom Level**

in order to have a custom lvl like 420 all you have to do is add a new row in card_exps set lvl to desired lvl and set exp_type (to a random number above 999 or 4 trillion or a negative number) set exp_total to any number below 0 go to cards and set   exp_type to the number you set it to in card_exps table and set training_exp to the number you set it to in card_exps.exp_total and set lvl_max to the lvl amount you set it to in card_exps

By BunRum

------------------------
## **Super Attack Types**

`special_scripts.attack_attributes`

* 1 = **Ki based Super**

* 2 = **melee based super**


------------------------
## **Element Types**
Element id 

* 
0 = AGL

* 
1 =  TEQ

* 
2 = INT

* 
3 = STR

* 
4 = PHY

------------------------
#### **Super Type**

* 
10 = SUPER AGL

* 
11 = SUPER TEQ

* 
12 = SUPER INT

* 
13 = SUPER STR

* 
14 = SUPER PHY

------------------------
#### **Extreme Type**

* 
20 = EXTREME AGL

* 
21 = EXTREME TEQ

* 
22 = EXTREME INT

* 
23 = EXTREME STR

* 
24 = EXTREME PHY

------------------------
## **Leader Skills**


Is your dual leaderskill being dumb and doubling the effects? I'll teach you the EPIC way to do it

For Category + category:
This one will be easy for you PG users since most of the work is done for you

**Efficacy_type1** = 104

**Efficacy_type2** = 5

**Efficacy_type3** = 104

**Efficacy_type4** = 5

Go to sub_target_types
In the column **target_value** type in your category ID and pick a random one that fits that category ID (Pro tip, if it doesn't work, choose another one with the same category ID. It might work) and copy the **sub_target_type_set** of it into **sub_target_type_set1** and **sub_target_type_set2**
Grab another random (not the same) one and copy that **sub_target_type_set** ID into **sub_target_type_set3** and **sub_target_type_set4**

(The following steps are if you have not used PG to make your leaderskill)

------------------------
Eff1 = First category you chose

Eff1_value1 = HP

Eff1_value2 = ATK

Eff1_value3 = DEF

------------------------
Eff2 = ki

Eff2_value1 = [X Amount]

Eff2_value2 = 0

Eff2_value3 = 0

------------------------
Eff3 = Second category you chose

Eff3_value1 = HP

Eff3_value2 = ATK

Eff3_value3 = DEF

------------------------
Eff4 = ki

Eff4_value1 = [X Amount]

Eff4_value2 = 0

Eff4_value3 = 0


By Cake

------------------------
## **Category id's**

1 = 	Fusion

2 = 	Shadow Dragon Saga

3 = 	World Tournament

4 = 	Peppy Gals

5 = 	Hybrid Saiyans

6 = 	Universe Survival Saga

7 = 	Resurrected Warriors

8 = 	Realm of Gods

9 = 	Majin Buu Saga

10 = 	Potara

11 = 	Low-Class Warrior

12 = 	Super Saiyan 3

13 = 	Giant Form

14 = 	Planet Namek Saga

15 = 	Ginyu Force

16 = 	Movie Bosses

17 = 	Pure Saiyans

18 = 	Namekians

19 = 	Future Saga

20 = 	Full Power

21 = 	Androids

22 = 	Representatives of Universe 7

23 = 	Transformation Boost

24 = 	Wicked Bloodline

25 = 	Dragon Ball Seekers

26 = 	Time Travelers

27 = 	Universe 6

28 = 	Joined Forces

29 = 	Movie Heroes

30 = 	Goku's Family

31 = 	Vegeta's Family

32 = 	Artificial Life Forms

33 = 	Youth

34 = 	DB Saga

35 = 	Siblings' Bond

36 = 	Super Saiyans

37 = 	Worthy Rivals

38 = 	Androids/Cell Saga

39 = 	Kamehameha

40 = 	Bond of Master and Disciple

41 =    Conquest of Terror

42 =    DB Heroes 

43 =    Target: Goku

44 =    Otherworld Warriors

45 =    Super Saiyan 2

--------------------------
## **Link Skill id's**

1 = 	Best Buddies

2 = 	Courage

3 = 	The Students

4 = 	The Innocents

5 = 	Crane School

6 = 	Demon

7 = 	Demon Duo


8 = 	Brainiacs

9 = 	Golden Warrior

10 = 	Money Money Money

11 = 	Evil Autocrats

12 = 	Flee


13 = 	Telekinesis

14 = 	More Than Meets the Eye

15 = 	Hero

16 = 	Supreme Warrior

17 = 	Gentleman

18 = 	Brutal Beatdown

19 = 	Messenger from the Future

20 = 	World Tournament Reborn

21 = 	New


22 = 	Saiyan Warrior Race

23 = 	All in the Family

24 = 	Master and Pupil

25 = 	Respect

26 = 	Prodigies

27 = 	World Tournament Champion

28 = 	Metamorphosis

29 = 	Super Saiyan

30 = 	Experienced Fighters

31 = 	Twin Terrors

32 = 	Coward

33 = 	Attack of the Clones

34 = 	The Saiyan Lineage

35 = 	Android Assault

36 = 	Turtle School

37 = 	Rival Duo

38 = 	Mechanical Menaces

39 = 	Cold Judgment

40 = 	Royal Lineage

41 = 	The Ginyu Force

42 = 	Infighter

43 = 	Frieza's Minion

44 = 	Champion's Strength

45 = 	Z Fighters

46 = 	Dodon Ray


47 = 	Kamehameha

48 = 	Namekians

49 = 	Berserker

50 = 	Big Bad Bosses

51 = 	Frieza's Army

52 = 	Tough as Nails

53 = 	Speedy Retribution


54 = 	Tag Team of Terror

55 = 	RR Army

56 = 	Gaze of Respect

57 = 	Bombardment

58 = 	Over 9000

59 = 	Universe’s Most Malevolent


60 = 	Shocking Speed

61 = 	Family Ties

62 = 	Team Bardock

63 = 	Saiyan Pride

64 = 	Battlefield Diva

65 = 	Revival

66 = 	Dismal Future

67 = 	Organic Upgrade

68 = 	Resurrection 'F'

69 = 	Patrol

70 = 	Warrior Gods

71 = 	Super-God Combat

72 = 	New Frieza Army


73 = 	Loyalty

74 = 	Unbreakable Bond

75 = 	Galactic Visitor

76 = 	Master of Magic

77 = 	Majin Resurrection Plan


78 = 	God of Destruction

79 = 	Connoisseur

80 = 	Godly Power

81 = 	Energy Absorption

82 = 	Budding Warrior

83 = 	Majin

84 = 	Strength in Unity


85 = 	Strongest Clan in Space
86 = 	Thirst for Conquest

87 = 	The Hera Clan

88 = 	Galactic Warriors

89 = 	Over in a Flash

90 = 	The Incredible Adventure


91 = 	Coora's Underling

92 = 	Coora's Armored Squad

93 = 	Hero of Justice

94 = 	Signature Pose

95 = 	GT

96 = 	Infinite Regeneration

97 = 	Prepared for Battle

98 = 	Destroyer of the Universe
99 = 	Twin Fighters from Space

100 = 	Team Turles

101 = 	Fortuneteller Baba’s Fighter

102 = 	Guidance of the Dragon Balls

103 = 	Power Bestowed by God

104 = 	Hardened Grudge

105 = 	Auto Regeneration

106 = 	Fusion

107 = 	Deficit Boost

108 = 	Ultimate Lifeform

109 = 	Fierce Battle

110 = 	Infinite Energy

111 = 	Formidable Enemy


112 = 	Fused Fighter

113 = 	Fusion Failure

114 = 	Scientist

115 = 	Hatred of Saiyans

116 = 	Limit-Breaking Form

117 = 	The First Awakened

118 = 	Shattering the Limit

119 = 	Nightmare

120 = 	Fear and Faith

121 = 	Xenoverse

122 = 	Super Strike

123 = 	Transform

124 = 	Saiyan Roar

125 = 	Legendary Power

126 = 	Warriors of Universe 6 

127 = 	Shadow Dragons


128 = 	Penguin Village Adventure


129 = 	Otherworld Warriors
130 = 	Tournament of Power



1000 = 	Blazing Battle

1001 = 	Soul vs Soul

1002 = 	Golden Z-Fighter

1003 = 	Supreme Power

1004 = 	The Wall Standing Tall

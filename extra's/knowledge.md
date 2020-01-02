---
Title: Knowledge
Description: work in progress. Come back later
---
## **Custom Level**

in order to have a custom lvl like 420 all you have to do is add a new row in card_exps set lvl to desired lvl and set exp_type (to a random number above 999 or 4 trillion or a negative number) set exp_total to any number below 0 go to cards and set   exp_type to the number you set it to in card_exps table and set training_exp to the number you set it to in card_exps.exp_total and set lvl_max to the lvl amount you set it to in card_exps

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


# Rules of Miracle Duel

## How to win

+ This game requires pokers. When the game ends, the one has the biggest number wins, the one has the smallest loses.
	+ King is the biggest. Ace is the smallest.
	+ ♠️ spade > ♥️ heart > ♣️ club > ♦️ diamond (peach is bigger, black is bigger)


## In a duel, there are

### 2 roles:

+ The *Challenger* 
+ The *Challenged One*

### 3 steps:

1. **Attack**

  The *challenger* delivers a **speech** in few sentences. The maximum number of sentences he can use depends on his **magic points**. 

1. **Defend**
	
	  By summering the **speech** delivered by the *challenger*, the *challenged one* prevents himself from **injured**.

1. **Fightback**
	
	By correcting the mistakes or revising the sentences in the **speech**,
	  + the *challenged one* prevents himself from being **injured**, if he has more points than the *challenger*.
	  + the *challenged one* can get the *challenger* **injured**, if he has less points.

After the 3 steps above, the one has more **health points** wins the duel. The winner gets **healed** and chooses someone (include himself) to start next duel.

### By saying

+ **Health points**
  
  The number of points on one's poker card.

+ **Magic points**

  The number of points related to one's poker card:
    + 5 ≤ n ≤ 10, f(n) = n
    + A ≤ n ≤ 4, f(n) = 10 - n
    + J ≤ n ≤ K, f(n) = 10 - (n - 10)

+ **Injured** / **Healed**
  
  To keep the smaller / greater number between the current one and the one newly picked from top of the heap.

## Other rules

+ The earlier one joins the game, the greater initial health points he is going to have. 
+ If someone comes late, he gets the smallest points among all.
+ The host takes the red joker and starts the first duel. He doesn't lose.

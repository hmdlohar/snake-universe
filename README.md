Snake Universe Game is based on multiplayer concept. 
where every player have their own snake. their snake is roming in their own area. 
Universe mean whole universe. City,State,Country,Continant, Earch, Solar system, Galaxy....


Initially snake is put on current city masured using GPS/Internet Address. Snake starts moving from beginning. User can go in any direction within his city. User can Eat food which is placed around snake.
It is possible that other snake come and eat that food. 

Snake will die if he will conflict with it self OR Other snake OR Currenty Boundry.

Current Boundry is area where snake can rom. Boundery can increase as user's level icreases.

User will earn points when snake will eat food. this points is useful to increase user's level.

When snake will distroy following condition will be checked and disicionn will be taken.
	if(user have snake life ) the
		he can use that life to replace snake at that position.
	else
		snake will again start from initial position. 


Different snakes will have different colors. this color combinition can be choosen by user.


-==>> Problems with implemention. 
1. what happen if user's snake die and user have life to reborn it. how it will take place withing that area. This direct apperance can disturb other snake. 
		Solution: Newly born snake will be transparennt to other snakes for 5/10 seronds. In special case when user's snake is crossed by other snake then it can be transparent until he cross that orher snake.
		Snake can't eat anything in it's transparent condition. 

2. how to allow user to pause game. pausing may result in crossig two snakes each other. so user can have undesirable bennifit. 
		Solution: Current it make sense that do not allow user to pause. 

3. As long as game will be in 2D mode. so how to shhow user his area. should user see map of his area. but if area is bigger then how to adjuct map. 

4. Big universe generation problem. 



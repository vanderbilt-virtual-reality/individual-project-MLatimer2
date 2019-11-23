
# Bar Simulator README
**Playing Bar Simulator**

*Goal: Make a Martini*

	- Add an ice cube to your glass and pour your drink from the cocktail shaker.
*Tips & Tricks :*

	- Be careful about maneuvering around the area
	- If you move too fast, you can spill all of your drink and knock over things on the countertop
	- Covering the cocktail shaker with the lid may help in preventing unnecessary spillage.
*Bugs:*

	- I’ve noticed that maneuvering to grab ice cubes for your drink can result in loss of grabbing and moving controls.
	
**Discussion of Game**

*Inspiration:*

The project that I decided to make was a bartending simulation where you can create a shaken martini. 
When I was thinking about projects to make, I thought about problems in my life that could potentially 
be solved by virtual reality. One of the problems I’ve run into recently is experimenting with food. 
I really enjoy baking and cooking new types of food, but it is very easy to make a mistake that ruins
the whole dish and all of those ingredients goes to waste. Then I thought that virtual reality could 
be a potential solution that allows you to practice different cooking techniques or new recipes without
having to buy ingredients and potentially waste them. While obviously you miss the very important 
aspect of being able to taste the creations you make, but it still has the potential to help with 
different skills that you wouldn’t necessarily have to taste to measure. For example, the proper 
technique for whipping cream or simulating how different ratios of yeast affect the rising of bread. The
inspiration behind my project is to help with the practice that bartenders have to do in order to 
memorize different drink recipes as well as being able to pour accurate amounts of each or the ingredients
without needing measurement tools. Also mixing drinks seemed like the best start for this project as 
mixing the ingredients wouldn’t create something with a new shape and texture where I would have to 
simulate complicated interactions between the ingredients. In mixology, the main focus is memorization 
of recipes and creating the create ratio of ingredients, and with the ingredients mostly being liquid, 
its much easier to simulate the creation of the different drinks (changing color, volumes, glasses, etc.).

*VR as a solution:*

I think VR would be an adequate way to address this even noting it’s drawbacks. Very obviously, being able
to smell and taste your food is a crucial part of cooking, and the lack of these senses is a significant 
drawback to using virtual reality for this project (at least with current VR technology). Along with this, 
the issue of dexterity and realistic simulation in virtual reality could be an issue. With cooking, there 
is a multitude of ways that we interact with our food and ingredients, and it may be hard to accurately 
simulate that interaction along with the ingredients’ reaction to it. In terms of techniques, even in one 
recipe, you may need to crack eggs, whisk ingredients, knead dough, etc. For everything that happens to 
make a recipe correctly, there are numerous ways to make it incorrectly, and it is important to be able to 
simulate that. For example, if you bake your cookies too long or don’t add enough butter, you could end of
with very hard cookies. On the other hand, if you don’t cook them long enough or add to much liquid to the
dough, you could end up with soft cookies that don’t hold their shape. Both of these outcomes would be 
important to have when using VR to practice techniques and recipes. However, weighing that drawback against 
the food waste that can come with practicing food and drink related techniques can make this type of project
still valuable. Especially in today’s social climate, sustainability is very important to many people and 
is crucial to taking care of our planet and the creatures that live here. As a result, any tools or products
that can aid people in being more environmentally conscious are in high demand. I believe that having a way 
to virtually simulate making different recipes and practice these techniques without having to use and 
potentially waste a lot of food is a great example of this, and I think its benefits outweigh the fundamental
issue of lack of senses.

Although not a fundamental issue with using virtual reality for this solution, the ability of technology to simulate real life could also be an issue. What seems to be a simple task can turn into a very difficult one in VR, and to create a realistic game requires a lot of time and testing. This project is most definitely an example of this, especially with the addition of ‘realistic’ liquid into the simulation. There are a lot of complicated physics and calculation that go into creating realistic water in the game, and this created a lot of issues for my game. The particular solution I used for the liquid involved simulating individual particles that made up the ‘body’ of the liquid, and around 8000 particles were being used. Each particle had it own calculations of how it needs to interact with environment, which is a lot of calculations to be made in real time. While the solution looked pretty realistic while looking into the shaker, and the physics of it being poured into the martini glass was very nice, the particles creating the liquid could be very finnicky. Slight movements could cause the particles to explode out of the cup, which is an issue, but you could argue that it happens in real life as well. In general, it is hard to get VR to simulate life how you are used to interacting with it, and for my project it got to be very complicated.

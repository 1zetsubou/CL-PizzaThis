█▀▀ █   █▀▀█ █  █ █▀▀▄
█   █   █  █ █  █ █  █
▀▀▀ ▀▀▀ ▀▀▀▀  ▀▀▀ ▀▀▀
█▀▀▄ █▀▀ ▀█ █▀ █▀▀ █   █▀▀█ █▀▀█ █▀▄▀█ █▀▀ █▀▀▄ ▀▀█▀▀
█  █ █▀▀  █▄█  █▀▀ █   █  █ █  █ █ ▀ █ █▀▀ █  █   █
▀▀▀  ▀▀▀   ▀   ▀▀▀ ▀▀▀ ▀▀▀▀ █▀▀▀ ▀   ▀ ▀▀▀ ▀  ▀   ▀

█▀▀█  ▀  ▀▀█ ▀▀█ █▀▀█ ▀▀█▀▀ █  █  ▀  █▀▀
█  █ ▀█▀ ▄▀  ▄▀  █▄▄█   █   █▀▀█ ▀█▀ ▀▀█
█▀▀▀ ▀▀▀ ▀▀▀ ▀▀▀ ▀  ▀   ▀   ▀  ▀ ▀▀▀ ▀▀▀

Thank you for downloading the script please follow this steps before running the script:

1 - Add items:
go to "qb-core" then shared folder > items.lua and add this : 

	--Pizzeria
	['pmenu'] 	 			 		 = {['name'] = 'pmenu',							['label'] = 'Pizza This Menu',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pmenu.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Pizza This Menu'},
	['pwineglass'] 	 			 	 = {['name'] = 'pwineglass',					['label'] = 'Wine Glass',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pwineglass.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Wine Glass'},
	['pwhiskyglass'] 	 			 = {['name'] = 'pwhiskyglass',					['label'] = 'Whiskey Glass',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pwhiskyglass.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Whiskey Glass'},
	['pbeermug'] 	 			 	 = {['name'] = 'pbeermug',						['label'] = 'Beer Empty Mug',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pbeermug.png',		['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Beer Empty Mug'},
	['pbeermugfull'] 	 			 = {['name'] = 'pbeermugfull',					['label'] = 'Beer Mug',			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pbeermugfull.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Beer Mug'},
	['predwine'] 	 				 = {['name'] = 'predwine',						['label'] = 'Red Wine',			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'predwine.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Red Wine'},
	['pwhitewine'] 	 				 = {['name'] = 'pwhitewine',					['label'] = 'White Wine',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pwhitewine.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'White Wine'},
	['ppinkwine'] 	 				 = {['name'] = 'ppinkwine',						['label'] = 'Pink Wine',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppinkwine.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Pink Wine'},
	['pwhiskey'] 	 				 = {['name'] = 'pwhiskey',						['label'] = 'Whiskey',			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pwhiskey.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Whiskey'},
	['pdusche'] 	 				 = {['name'] = 'pdusche',						['label'] = 'Dusche Beer',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pdusche.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Dusche Beer'},
	['plogger'] 	 				 = {['name'] = 'plogger',						['label'] = 'Logger Beer',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'plogger.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Logger Beer'},
	['pam'] 	 			 		 = {['name'] = 'pam',							['label'] = 'AM Beer',			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pam.png',			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'AM Beer'},
	['pgoldsake'] 	 			 	 = {['name'] = 'pgoldsake',						['label'] = 'Gold Sake',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pgoldsake.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Gold Sake'},
	['prum'] 	 			 		 = {['name'] = 'prum',							['label'] = 'Rum',				['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'prum.png',			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Rum'},
	['pwhitewinebottle'] 	 		 = {['name'] = 'pwhitewinebottle',				['label'] = 'White Wine Bottle',['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pwhitewinebottle.png',['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'White Wine Bottle'},
	['pwhiskeybottle'] 	 			 = {['name'] = 'pwhiskeybottle',				['label'] = 'Whiskey Bottle',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pwhiskeybottle.png',['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Whiskey Bottle'},
	['pchampagne'] 	 			 	 = {['name'] = 'pchampagne',					['label'] = 'Champagne Bottle',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pchampagne.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Champagne Bottle'},
	['porange'] 	 		 		 = {['name'] = 'porange',						['label'] = 'Orange',			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'porange.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Orange'},
	['pbanana'] 	 			 	 = {['name'] = 'pbanana',						['label'] = 'Banana',			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pbanana.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Banana'},
	['papple'] 	 			 	 	 = {['name'] = 'papple',						['label'] = 'Apple',			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'papple.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Apple'},
	['pwatercup'] 	 			 	 = {['name'] = 'pwatercup',						['label'] = 'Water Cup',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pwatercup.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Water Cup'},
	['pdough'] 	 			 	 	 = {['name'] = 'pdough',						['label'] = 'Ready Pizza Dough',['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pdough.png',		['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Ready Pizza Dough'},
	['predwinebottle'] 	 			 = {['name'] = 'predwinebottle',				['label'] = ' Regular Red Wine Bottle',['weight'] = 1000,['type'] = 'item', 		['image'] = 'predwinebottle.png',['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Regular Red Wine'},
	['pcastellobrolio'] 	 		 = {['name'] = 'pcastellobrolio',				['label'] = 'Castello Brolio Red Wine',['weight'] = 1000,['type'] = 'item', 	['image'] = 'pcastellobrolio.png',['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Castello Brolio Red Wine'},
	['pgaryfarrel'] 	 			 = {['name'] = 'pgaryfarrel',					['label'] = 'Gary Garrel Red Wine',['weight'] = 1000, 	['type'] = 'item', 		['image'] = 'pgaryfarrel.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Gary Farrel Red Wine'},
	['prutherfordhill'] 	 		 = {['name'] = 'prutherfordhill',				['label'] = 'Rutherford Hill Red Wine',['weight'] = 1000,['type'] = 'item', 	['image'] = 'prutherfordhill.png',['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Rutherford Hill Red Wine'},
	['psparklingwine'] 	 			 = {['name'] = 'psparklingwine',				['label'] = 'Sparkling Wine',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'psparklingwine.png',['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Sparkling Wine'},
	['ppinkwinebottle'] 	 		 = {['name'] = 'ppinkwinebottle',				['label'] = 'Pink Wine Bottle',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppinkwinebottle.png',['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Pink Wine Bottle'},
	['ppizzaflour'] 	 		 	 = {['name'] = 'ppizzaflour',					['label'] = 'Pizza Flour',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppizzaflour.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Pizza Flour'},
	['pwater'] 	 		 		 	 = {['name'] = 'pwater',						['label'] = 'Water',			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pwater.png',		['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Water'},
	['psalt'] 	 		 			 = {['name'] = 'psalt',							['label'] = 'Salt',				['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'psalt.png',		['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Salt'},
	['poil'] 	 		 			 = {['name'] = 'poil',							['label'] = 'Oil',				['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'poil.png',			['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Oil'},
	['pbigdough'] 	 		 		 = {['name'] = 'pbigdough',						['label'] = 'Pizza Dough',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pbigdough.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Pizza Dough'},
	['pespressomacchiato'] 	     	 = {['name'] = 'pespressomacchiato', 			['label'] = 'Espresso Macchiato',['weight'] = 1000, 	['type'] = 'item', 		['image'] = 'pespressomacchiato.png',['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Espresso Macchiato'},
	['pcaramelfrappucino'] 	     	 = {['name'] = 'pcaramelfrappucino', 			['label'] = 'Caramel Frappucino',['weight'] = 1000, 	['type'] = 'item', 		['image'] = 'pcaramelfrappucino.png',['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Caramel Frappucino'},
	['pcoldbrewlatte'] 	     	 	 = {['name'] = 'pcoldbrewlatte', 				['label'] = 'Cold Brew Latte', 	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pcoldbrewlatte.png',['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Cold Brew Latte'},
	['pstrawberryvanillaoatlatte'] 	 = {['name'] = 'pstrawberryvanillaoatlatte',	['label'] = 'Strawberry Vanilla Oat Latte',['weight'] = 1000,['type'] = 'item', ['image'] = 'pstrawberryvanillaoatlatte.png',['unique'] = false,['useable'] = true, ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Strawberry Vanilla Oat Latte'},
	['pespressocoffeecup'] 	 		 = {['name'] = 'pespressocoffeecup',			['label'] = 'Espresso Coffee Cup',['weight'] = 1000, 	['type'] = 'item', 		['image'] = 'pespressocoffeecup.png',['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Espresso Coffee Cup'},
	['pmilk'] 	     		 		 = {['name'] = 'pmilk', 						['label'] = 'Milk', 			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pmilk.png', 		['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Milk'},
	['pcoffeebeans'] 	         	 = {['name'] = 'pcoffeebeans', 					['label'] = 'Coffee Beans', 	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pcoffeebeans.png', ['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Coffee Beans'},
	['pcream'] 	     		 		 = {['name'] = 'pcream', 						['label'] = 'Whipped Cream', 	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pcream.png', 		['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Whipped Cream'},
	['phighcoffeeglasscup'] 	     = {['name'] = 'phighcoffeeglasscup', 			['label'] = 'High Coffee Glass',['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'phighcoffeeglasscup.png',['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Empty High Coffee Glass'},
	['pcaramelsyrup'] 	     		 = {['name'] = 'pcaramelsyrup', 			    ['label'] = 'Caramel Syrup', 	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pcaramelsyrup.png',['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Caramel Syrup'},
	['pcoffeeglass'] 	     		 = {['name'] = 'pcoffeeglass', 					['label'] = 'Coffee Glass', 	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pcoffeeglass.png', ['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Empty Coffee Glass'},
	['pcocacola'] 	     		 	 = {['name'] = 'pcocacola', 					['label'] = 'Coca Cola', 		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pcocacola.png', 	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Coca Cola'},
	['psprite'] 	     		 	 = {['name'] = 'psprite', 						['label'] = 'Sprite', 			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'psprite.png', 		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Sprite'},
	['ppepper'] 	     		 	 = {['name'] = 'ppepper', 						['label'] = 'DR.Pepper', 		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppepper.png', 		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'DR.Pepper'},
	['ppizzabase'] 	     		 	 = {['name'] = 'ppizzabase', 					['label'] = 'Pizza Base', 		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppizzabase.png', 	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Pizza Base'},
	['ptomatosouce'] 	     		 = {['name'] = 'ptomatosouce', 					['label'] = 'Tomato Souce', 	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ptomatosouce.png', ['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Tomato Souce'},
	['pbasil'] 	     		 		 = {['name'] = 'pbasil', 						['label'] = 'Basil', 			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pbasil.png', 		['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Basil'},
	['pmozzarella'] 	     		 = {['name'] = 'pmozzarella', 					['label'] = 'Fresh Mozzarella', ['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pmozzarella.png', 	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Fresh Mozzarella'},
	['pmargharita'] 	 		 	 = {['name'] = 'pmargharita',					['label'] = 'Margharita Pizza',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pmargharita.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Margharita Pizza'},
	['pnapollitano'] 	 		 	 = {['name'] = 'pnapollitano',					['label'] = 'Napollitano Pizza',['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pnapollitano.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Napollitano Pizza'},
	['pmushroomspizza'] 	 		 = {['name'] = 'pmushroomspizza',				['label'] = 'Mushrooms Pizza',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pmushroomspizza.png',['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Mushrooms Pizza'},
	['pmushrooms'] 	 		 		 = {['name'] = 'pmushrooms',					['label'] = 'Mushrooms',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pmushrooms.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Mushrooms'},
	['pbutter'] 	 		 		 = {['name'] = 'pbutter',						['label'] = 'Butter',			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pbutter.png',		['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Butter'},
	['pseafood'] 	 		 		 = {['name'] = 'pseafood',						['label'] = 'Seafood Pizza',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pseafood.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Pizza Seafood'},
	['pseafoodmix'] 	 		 	 = {['name'] = 'pseafoodmix',					['label'] = 'Seafood Mix',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pseafoodmix.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Seafood Mix'},
	['pvegpizza'] 	 		 		 = {['name'] = 'pvegpizza',						['label'] = 'Vegetarian Pizza',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pvegpizza.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Vegetarian Pizza'},
	['pvegicheese'] 	 		 	 = {['name'] = 'pvegicheese',					['label'] = 'Vegetarian Cheese',['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pvegicheese.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Vegetarian Cheese'},
	['ptomatoes'] 	 		 	 	 = {['name'] = 'ptomatoes',						['label'] = 'Fresh Tomatoes',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ptomatoes.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Fresh Tomatoes'},
	['pmacncheese'] 	 		 	 = {['name'] = 'pmacncheese',					['label'] = 'Mac N Cheese',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pmacncheese.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Mac N Cheese'},
	['pelbowmacaroni'] 	 		 	 = {['name'] = 'pelbowmacaroni',				['label'] = 'Elbow Macaroni',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pelbowmacaroni.png',['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Elbow Macaroni'},
	['pcheddarcheese'] 	 		 	 = {['name'] = 'pcheddarcheese',				['label'] = 'Cheddar Cheese',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pcheddarcheese.png',['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Cheddar Cheese'},
	['pparmesancheese'] 	 		 = {['name'] = 'pparmesancheese',				['label'] = 'Parmesan Cheese',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pparmesancheese.png',['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Parmesan Cheese'},
	['pporkmeat'] 	 		 	     = {['name'] = 'pporkmeat',						['label'] = 'Pork Meat',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pporkmeat.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Pork Meat'},
	['pbbqporkmac'] 	 		 	 = {['name'] = 'pbbqporkmac',					['label'] = 'BBQ Pork Mac',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pbbqporkmac.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'BBQ Pork Mac N Cheese'},
	['pbbqsouce'] 	 		 	     = {['name'] = 'pbbqsouce',						['label'] = 'BBQ Souce',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pbbqsouce.png',	['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'BBQ Souce'},
	['pfresca'] 	 		 	 	 = {['name'] = 'pfresca',						['label'] = 'Pasta Fresca',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pfresca.png',		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Pasta Fresca'},
	['pregularpasta'] 	 		 	 = {['name'] = 'pregularpasta',					['label'] = 'Regular Pasta',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pregularpasta.png',['unique'] = false, 		['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Regular Pasta'},
	['pmargharitaslice'] 	 		 = {['name'] = 'pmargharitaslice',				['label'] = 'Margharita Slice',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppizzaslice.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Margharita Slice'},
	['pnapollitanoslice'] 	 		 = {['name'] = 'pnapollitanoslice',				['label'] = 'Napollitano Slice',['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppizzaslice.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Napollitano Slice'},
	['pmushroomspizzaslice'] 	 	 = {['name'] = 'pmushroomspizzaslice',			['label'] = 'Fungi slice',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppizzaslice.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Fungi Slice'},
	['pseafoodslice'] 	 		 	 = {['name'] = 'pseafoodslice',					['label'] = 'Seafood Slice',	['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppizzaslice.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Seafood Slice'},
	['pvegpizzaslice'] 	 		 	 = {['name'] = 'pvegpizzaslice',				['label'] = 'Vegi Slice',		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'ppizzaslice.png',	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Vegi Slice'},

2 - Add the job:
go to "qb-core" then shared folder > jobs.lua and at least under line 4 :

    ["pizzeria"] = {
        label = "Pizzeria",
        offDutyPay = false,
        defaultDuty = false,
        grades = {
            ['0'] = {
                name = 'Worker',
                payment = 30,
            },
            ['1'] = {
                name = 'Vice Boss',
                payment = 70,
            },
            ['2'] = {
                name = 'Boss',
                isboss = true,
                payment = 130,
            },
        }
    },

3 - Add images to inventory
here you have images folder copy the images inside that folder and put it inside "qb-inventory"

Have more questions / issues ? feel free to open a ticket in our discord server : https://discord.gg/kGPECGG27Q

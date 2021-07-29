# Feed the family: recipes, shopping and food delivery

<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. -->

Final project for the Building AI course

## Summary

The service plans a balanced menu for a given number of people and days, including food delivery services and keeping an eye on the given budget. It prepares a shopping list or adds groceries to the shopping cart in an online grocery store, and prepares orders for the food delivery service.

## Background

Planning, shopping and preparing full meals for the family at least once, often twice every day is a lot of work. For someone wanting (reasonably) healthy food for the growing children and not in the least interested in cooking, it is the single most arduous task of day-to-day life. I suspect the problem is common in many families – and in other households as well. Even if shopping and cooking itself isn't a problem, coming up with new ideas or some variation for meals isn't always easy  - especially, if there are restricting factors like a tight budget or strict dietary needs.

## How is it used?

The service would plan the next N meals, taking into account any dietary restrictions, number of family members, how much time can be spent on cooking, and meals proposed in the last two or three weeks. What makes it especially smart is that it also strives to keep under a given budget, while including food delivery as an option alongside with cooking. 

The service provides recipes for the cooking days, makes a shopping list and perhaps also adds the ingredients into a shopping basket of an online grocery store. For delivered meals, it can provide a list of what to order and from where or prepare the order for approval. 

In addition, there is an option to rate a proposed meal, and suggestions on how to adjust the meal a bit healthier or a bit more substantial (like replace cheese with tofu or add pulled oats to the soup).

In addition to the main target group, busy parents, the system would profit other users, as well. For example, users with a tight budget would get affordable suggestions for meals and perhaps more variation on their menu – easily. The increase in variation might be appreciated by users with strict dietary needs, as well. 

Making the menu for a longer period of time (e.g. a week) helps to minimize waste and reduce costs: if a package size is larger than what is needed for a meal, the service can plan to use the rest of the content another day. Vegetables that are in season are often also cheaper, which would direct the meals to be more environmentally friendly (or that could be another preference that could be added). Alongside everything else, the service makes sure that the nutrients of the proposed meals are in good balance.

## Data sources and AI methods

The data sources needed are:

| Data      | Source |
| ----------- | ----------- |
| Groceries, their prices and nutritional values | 	An online grocery store(s), such as K-ruoka or Foodie in Finland       |
| Recipes, preferably from several sources | Recipe libraries, for example the archive of the Chocochili blog |
| Delivered meals and their prices (and nutritional values, if available) | Food delivery service(s), like Foodora or Wolt |
| Information on nutrition of people of different ages | Ruokavirasto (Finnish food authority) has recommendations that could be used, but some expertise might be needed here from the developing party. |
| Information on special dietary needs | This might have to be left for each user to provide. The software could learn and make suggestions. |
| Information on alternative ingredients | The data set does not have to be very large, if it is only used to make the meals more healthy. But some expertise is needed for constructing the data. |
| Preferences of the user | Gathered by a questionnaire at the beginning, and by ratings as the service is used. |

The AI methods needed are at least:
*	A recommendation system
*	Learning the preferred-kind-of foods of the user
*	Optimising the balance between price, nutritional value, cooking time, variation and preferences

## Challenges

*	You'll probably still have to cook.
*	It is difficult to include all the possible special dietary needs and get it right, part of this perhaps has to be left to the user.
*	Replacements of ingredients might be difficult to get right.
*	The result is dependent on the data sources: if there are no suitable recipes available, the result won't be successfull.
*	The service will be limited on areas where delivery of food or groceries is not available. Recipes and a shopping list can still be provided.
*	With a very low budget, it might be difficult to find recipes online.
*	Special care should be taken when selecting the recipe libraries that all users are taken into account (very low budget, little time for cooking, allergies etc.) 
*	Extending a recipe is an interesting topic in itself, how to decide what to add or what could be left out?

## Acknowledgements

The K-ruoka online store provided some inspiration for this service.  



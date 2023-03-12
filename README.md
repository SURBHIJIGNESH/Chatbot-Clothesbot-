# Chatbot-Clothesbot-

Clothesbot is a user-interactive chatbot that accepts user input and helps in purchasing clothes by giving information regarding category, colour, company name, items, Material, payment method and Size. Clothesbot can assist you with all of this. You just have to ask queries and it will always recommend the best option for you with appropriate instructions. As there are many applications available for buying clothes, Users find something missing in it. Customers want to interact 24/7 so that they can properly purchase items as per their interest. And for that chatbot is very useful.

## Chatbot Functionality:

-	The chatbot helps us as a virtual assistant.
-	There are mainly two inbuilt intent namely fallback intent and welcome intent.
-	In welcome intent, customer says hello to bot and as a response bot specially gives information about the product. 
-	Fallback intent is useful when users change their mind for purchasing their product or cancel their order.
-	Another intent also can be created by using appropriate context, training phrases, actions and parameters and lastly responses.
-	In actions and parameters, entities are used which help users buying product according to their choice. Synonyms is also used as a entities. For example, if user want Small size shirt so instead of writing Small they just write S. bot understand synonyms.
-	In responses, bot response customer for their order.
-	Follow up intent can be created for order confirmation. For example, customer like the product then Yes and No follow up intent created for confirming the order.

## Approach:

-	The name of the chatbot is clothesbot(Fashion Shop)
-	Firstly, in a Welcome Intent, User can start typing hello and as an output, boat gives you the information regarding shop and a message about how bot can help you for buying clothes.
-	After that, In purchaseIntent, when customer ask about purchasing clothes, boat ask some question to users that they have any choices like colour preferences, company and many more. And then entities play a role.
-	There are 7 entities created namely Category, Colour, Company name, Items, Material, Payment method, and Size.
-	Six entities are used in purchase intent which help user which type of size, colour, and company they want to buy for their outfit. Bot use entities as per customer preferences.
-	Apart from this, Yes and No follow up intent are created for order confirmation. 
-	Second intent is about Special discount. When customer wand to order and say Yes then bot ask if users want anything.
-	As an answer customer says about discount and then special discount intent plays a role. After knowing the discount, another follow up intent Yes and No are created.
-	When customer says Yes, bot ask customer information like name and contact number and then billing follow up intent plays a role in which bot ask customer which payment method they want to use.  And then outfit order is completed.

## Chatbot link: https://bot.dialogflow.com/8b5af7ae-af9c-4959-8dd3-d7ff3c660da0


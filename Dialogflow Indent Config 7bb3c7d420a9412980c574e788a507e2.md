# Dialogflow Indent Config

Dialogflow indented configuration process setups :

**Intent 1: Default Greetings**

**Training Phrases:**
{ Hi, Hello, Hey }

**Responses:**
**Hello! Welcome to our dal franchise. How can I assist you today?**

**Intent 2: Default Exception Greetings**

**Training Phrases:**
Sorry
Excuse me

**Responses:**
**No problem! How can I assist you today?**

**Intent 3: Order Dal without Roti**

**Training Phrases:**
I would like to order dal without roti.

**Responses:**
**Sure! Which dal would you like to order? We have Dal Tadka Patiali, Trichy Mulagatawany Dal, Nellore Spicy Special Dal, Marathwada Special, and Serene Bengaluru Dal.**

**Intent 4: Order Dal with Roti**

**Training Phrases:**
I would like to order dal with roti.

**Responses:**
**Great! Which dal would you like to order with roti? We have Dal Tadka Patiali, Trichy Mulagatawany Dal, Nellore Spicy Special Dal, Marathwada Special, and Serene Bengaluru Dal.**

**Intent 5: Specify the Dal**

**Training Phrases:**
[User specifies the desired dal]

**Responses:**
**Noted! I have taken your order for [dal name]. Is there anything else you would like to add?**

**Intent 6: Enquire Status of Dal**

**Training Phrases:**
Can you check the status of my dal order?

**Responses:**
**Sure! May I know your order ID?**

**Intent 7: Handle Query on Shop History and Founders**

**Training Phrases:**
Can you provide some information about the shop's history and founders?

**Responses:**
**Our dal franchise was started by five creative and skilled individuals. Ms. Kulwinder Kaur specializes in Dal Tadka Patiali, Mr. Raman Subramanian is known for Trichy Mulagatawany Dal, Mr. Narasimha Reddygaru's specialty is Nellore Spicy Special Dal, Mr. Sayaji Gaekwadjee prepares Marathwada Special, and Mr. Byresamy Gowdaiah serves Serene Bengaluru Dal. Our founders take pride in offering authentic and delicious dals to our customers.**

**Extra Indent Command** 

**I would like to order whole masoor dal**
Noted! I have taken your order for whole masoor dal. Is there anything else you would like to add?

**I would like to order split orange Masoor dal**
Noted! I have taken your order for split orange Masoor dal. Is there anything else you would like to add?

**I would like to order whole green moong dal**
Noted! I have taken your order for whole green moong dal. Is there anything else you would like to add?

**I would like to order split green moong dal**
Noted! I have taken your order for split green moong dal. Is there anything else you would like to add?

**I would like to order whole black urad dal**
Noted! I have taken your order for whole black urad dal. Is there anything else you would like to add?

**I would like to order split black urad dal**
Noted! I have taken your order for split black urad dal . Is there anything else you would like to add?

**I would like to order whole white urad dal**
Noted! I have taken your order for whole white urad dal. Is there anything else you would like to add?

**I would like to order split white urad dal**
Noted! I have taken your order for split white urad dal. Is there anything else you would like to add?

**Note: In Dialogflow, you can configure the responses as text or use fulfillment to integrate with your backend systems for more dynamic responses.**

Remember to train your Dialogflow agent with these intents and provide enough training phrases for each intent to improve its recognition accuracy.
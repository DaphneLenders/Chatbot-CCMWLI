# Chatbot-CCMWLI
Our chatbot is a Shakespearian PoetryBot. It uses a database of Shakespeare poems to about love, nature and mythology to create poems on it self. This is done using Markov Chains. Next to that it can send funny Shakespeare memes to make you feel better. To have a conversation with the Chatbot the Python code should be run and a message should be sent to the bot. The bot can be found on Telegram by looking for "@WilliamShakeybot".

A conversation can be started with some casual small talk, by saying a greeting or asking how the PoetryBot is doing. We tried to personalize the bot by letting it cooperate information about the users first-name and the time a message is send in the conversation. Next to that we wanted to give the bot some 'character' by letting it talk in a Shakespearian language all the time. 
After some casual small-talk you can ask the bot to generate you a poem. It will ask you about what topic you want to hear a poem and generate one for you. PoetryBot will ask you to give your honest opinion about the poem he wrote. A sentiment analysis is conducted on this opinion, so that the bot can respond appropriately. 

You can also send the bot stickers and images, to which it will respond with a funny Shakespeare meme. If you do not want to send the bot a sticker you can also just ask him for a meme. 

If you are done talking to PoetryBot, just end the conversation by saying goodbye to him. He will send you a last farewell sonnet. 

## Example conversation with the PoetryBot
**Franka**: "Hello"

**PoetryBot**: "Good day to thee Franka! How dost thou, my friend?"

**Franka**: "Im fine, and how are you?"

**PoetryBot**: "Full many a glorious morning have I seen, 
            but never this happy have I been,  
            Seeing sunrises are my greatest pleasure, 
            my feelings of joy are beyond measure"
            
**PoetryBot**: "Or to answer the question thou askest: I'm doing most wondrous on this lovely morning"

**Franka**: "I dont know what to do, can you help me?"

**PoetryBot**: 

    "Ah, I see. Thee needeth my holp! Thither art a number of things I can do: 

    Thy can have some casual small talk with me, by giving me your greetings and asking how I art doing. 
    If thy want to heareth a poem, thee can simply command me to do so and I shall try to 
    write thee a poem about either love, nature or mythology. 

    I can also send thee memes if thou sendest me a sticker or if thy askest for memes. 
    I desire thee findeth them amusing. 

    If thou want to end the conversation, thou can sayest "farwell" or 
    "goodbye" and I will send thee a final farewell-sonnet. 

    Please forgiveth me if I do not understandeth everything"

**Franka**: "Can I hear a poem?"

**PoetryBot**: "I wilt writeth a poem special for thee"

**PoetryBot**: "do thee want to heareth a poem about love, about nature, or about the mythology?"

**Franka**: "about love"

**PoetryBot**: "Ah, I feel so very much inspired! I hope thee likest my poem about love"

**PoetryBot**: 

    "But let them do not glance thine eye i not be removed . 
     And made of the wrong that she is not kept , 
     And proved , 
     If between them love did except ? 
     If thou break , 
     Nor dare i desperate now crown themselves their rotten smoke ? 
     Take , 
     Where is my cloak ? 
     Such civil war shall be you have some mother . 
     Enjoyed no more rich in my good one more than hates known injury . 
     One on form another , 
     As proud livery . 
     Swelling on my black wires grow on to her false-speaking tongue : 
     For how shall not to thy lights flame to torture me young"
            
**PoetryBot**: "May I ask thee, my friend. Did you enjoyeth the poem?"

**Franka**: "I Loved it"

**PoetryBot**: "O Lord that lends me life, Lend me a heart replete with thankfulness! I am glad thou likest the sonnet. Does thee wanteth to hear another one about love, nature or mythology?"

**Franka**: "No thank you, but can you send me a funny meme?"

**Poetrybot**: "Alack, I do not understand what it is thy is saying Franka. I cry you mercy,  can thou say that again"

**Franka**: "meme?"

**Poetrybot**:

![alt text](https://ih1.redbubble.net/image.284655747.8213/poster%2C210x230%2Cf8f8f8-pad%2C210x230%2Cf8f8f8.lite-1.jpg "Lit into literature") 

**Franka**: "I have to go now, I see you later"

**PoetryBot**: 

    "Farewell! thou art too dear for my possessing,
    And like enough thou knowst thy estimate.
    The Charter of thy worth gives thee releasing;
    My bonds in thee are all determinate.
    For how do I hold thee but by thy granting,
    And for that riches where is my deserving?
    The cause of this fair gift in me is wanting,
    And so my patent back again is swerving.
    Thy self thou gav'st, thy own worth then not knowing,
    Or me, to whom thou gav'st it, else mistaking,
    So thy great gift, upon misprision growing,
    Comes home again, on better judgement making.
    Thus have I had thee as a dream doth flatter:
    In sleep a king, but waking no such matter."

## Things we tried that did not work
We tried to use glove to analyze messages of users, so that the bot can respond appropriately to these messages. An advantage of using glove would be, that the bot would be enabled to respond not only to given keywords (e.g. 'help') but also to words that are (according to the word2vec model) similar to those keywords (e.g. 'assistance', 'rescue', 'support'). However, this took too much computerpower and, as a consequence, the bot became too slow using glove. 

## Authors

* **All** - *Work on basic chatbot and find memes*
* **Daphne Lenders** - *Work on sentiment analysis and loading the dataset*
* **Justine Winkler** - *Work on sonnetizer and rime scheme*
* **Franka Buytenhuijs** - *Work on markov chains en glove*



We have created our first bot using dialogflow integrated with facebook.

Check out the link(https://dialogflow.com/)

Dialogflow (formerly Api.ai, Speaktoit) is a Google-owned developer of human–computer interaction technologies based on natural language conversations. The company is best known for creating the Assistant (by Speaktoit), a virtual buddy for Android, iOS, and Windows Phone smartphones that performs tasks and answers users' question in a natural language.[1] Speaktoit has also created a natural language processing engine that incorporates conversation context like dialogue history, location and user preferences.

![unnamed](https://user-images.githubusercontent.com/16176176/42135505-74c38b5c-7d69-11e8-944c-cfdfa5c40494.png)
![download 1](https://user-images.githubusercontent.com/16176176/42135569-3c094f26-7d6a-11e8-8397-cb165b3583d8.png)

Dialogflow is powered by google's machine learning which handles all NLP that our chatboot require.We did not write any code for our bot.We gave just proper intent and entity so that bot will understand and process accordingly.




An  # Intent (https://dialogflow.com/docs/intents) represents a mapping between what a user says and what action should be taken by your software.

Intent interfaces have the following sections:

1.Training Phrases
2.Action
3.Response
4.Contexts

[
![screenshot from 2018-07-01 21-55-22](https://user-images.githubusercontent.com/16374123/42136468-9f53e730-7d79-11e8-8086-e9482109d12a.png)
](url)

Here is an example of account lock intent.

![screenshot from 2018-07-01 22-08-29](https://user-images.githubusercontent.com/16374123/42136565-8c496190-7d7b-11e8-9a1c-13a27e11a746.png)
![screenshot from 2018-07-01 22-08-40](https://user-images.githubusercontent.com/16374123/42136570-9a830e8c-7d7b-11e8-909f-7d3afcbdd017.png)






# Entities  are powerful tools used for extracting parameter values from natural language inputs. Any important data you want to get from a user's request, will have a corresponding entity.

The entities used in a particular agent will depend on the parameter values that are expected to be returned as a result of the agent functioning. In other words, a developer does not need to create entities for every possible concept mentioned in the agent – only for those needed for actionable data.


There are 3 types of entities: system (defined by Dialogflow), developer (defined by a developer), and user (built for each individual end-user in every request) entities. Each of these can be classified as mapping (having reference values), enum (having no reference values), or composite (containing other entities with aliases and returning object type values) entities.

Check below example for entity

![screenshot from 2018-07-01 22-17-14](https://user-images.githubusercontent.com/16374123/42136628-e963caf4-7d7c-11e8-9147-4ba631e2051b.png)
![screenshot from 2018-07-01 22-18-49](https://user-images.githubusercontent.com/16374123/42136637-031c53da-7d7d-11e8-89fa-2d11cf69e50b.png)


There are total 14 integration dialogflow can have once built(https://dialogflow.com/docs/integrations).For our demo we have integrated with facebook and dialogflow web demo.

Give screenshot for both of them.

We have created a facebok page Innomindchatbot(https://www.facebook.com/InnomindChatbot-1851521798485031/?ref=bookmarks).For bot creation we needed a facebook developer account and then followed some steps (like token creation,validation,creation of webhook).It is now able to interact from my account.But it is not public available to other user because facebook does not allow to do so until the bot is reviewed by its team.

But it allows addition of test users to check the feature of its apps.We created a dummy account named Bruce Tyagi to test its features.Below is a link how it works.

Link in youtube

To check it in actio.please click below link

https://bot.dialogflow.com/deb99b0d-418e-40a2-8eb6-26bdd707322e

it works perfectly fine.




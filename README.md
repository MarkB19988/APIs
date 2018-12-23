# APIs

### What is an API?
An API in its simplest form, is an interface that allows programs to interact with each other. When implemented, an API essentially provides a set of rules and instructions that allow multiple programs to communicate. In order to ensure clear communication between the programs, APIs will usually specify how things such as routines and data structures should be defined.

APIs can differ depending on what function(s) they are tasked with performing.General APIs provide library functions for a programming language such as the Java API.  There are more specific APIs that provide more unique functions such as the Blizzard API. Language specific APIs can only be used in one specific language.

When implementing an API, you must be very careful only to expose what is necessary to ensure your application works as intended while keeping other parts of the application inaccessible. APIs have become very common on the internet as they allow for applications to communicate with each other and perform functions together without openly exposing the application.

### What is an SDK?
An SDK is a set of tools that can be used to develop software applications targeting a specific platform. SDKs include tools, libraries, documentation and sample code that would help a programmer to develop an application. A well know SDK is the Java SDK (JDK). This includes libraries, debugging facilities and other tools which can make writing programs much easier in Java. SDKs allow developers to write code and create programs much more efficiently since there is no need to look for components that are compatible with each other and all of them are placed into a single package that is easy to install.

### The Relationship Between APIs and SDKs
An API is an interface that allows programs to interact with each other, whereas a SDK is a set of tools that can be used to develop software applications for a specific platform. The simplest version of a SDK could be an API or a collection of APIs.This is because APIs are designed to provide specific functions and an SDK can combine APIs to have a large number of functions for the purpose of software development. However this is not true in reverse. An SDK can never be an API as it is the SDK that relies on the APIs.


### How Can The Online Game ‘Elite: Dangerous’ Be Improved Using An API?
Elite: Dangerous is a MMO spaceship simulator that tasks players with completing missions, delivering cargo, doing jobs for factions and a range of other things. I believe the functionality and quality of life could be vastly improved through the implementation of an API.

In Elite, the most prominent way to make money is through trading. Each station accepts different cargo depending on what the station was built for, e.g. Agriculture or Mining. However even though this information is known, the player is left without knowledge of what exactly in these categories the station is buying and selling and at what price. 

This would be the first improvement I believe integrating an API could make. An API that collects data on what cargo the player has on them, and then searches through all of the stations that are near the player to find a station that will buy what they are selling at the best price possible. The reverse could also be performed, finding stations that sell what a player is looking to buy at the lowest price possible. Introducing an API to perform these functionalities will provide a significant quality of life improvement by allowing the player to research and plan trade routes, making the act of trading much less luck based that it is currently.

Additionally, implementing an API that allows players to trade items that they own in game from a mobile device would be an excellent way to encourage player trading and communication. By implementing this API, you could being the community of the game close together and allow for player clans to be created that have the sole purpose of trading with other players, not just NPCs as the base game allows. Using the API to bring this functionality to a mobile or web application that could be accessed anywhere would be a great way to keep players interacting with the game.


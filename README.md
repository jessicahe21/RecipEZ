# RecipEZ - CPEN 321 Group Project

Team members: Harvir Dhaliwal, Ritchie Xia, Sandon Li, Jessica He

RecipEZ is a native Android mobile app that suggests recipes based on user selection of available ingredients with a Java frontend, JavaScript/Node.js backend, and MongoDB database. (Click the below image to watch our YouTube video!)

[![RecipEZ](https://github.com/jessicahe21/RecipEZ/assets/38922275/d94570e0-1ac1-406d-b462-9e51cd820b7a)](https://youtu.be/WgVdb-ZTIbo)

The problem that RecipEZ is aiming to solve is reducing food waste from household kitchens as well as teaching people how to cook using the ingredients that they have at home. The target audience for our product are young, busy people with occupied schedules that don’t have the luxury of time to plan out their meals intricately, often losing track of the food they have at home. RecipEZ helps people manage their fridge and kitchen pantry by notifying them when food is expiring and suggesting recipes to cook before their ingredients go bad. This allows users to learn different recipes and broaden their cooking repertoire while making sure food isn’t wasted!

The recipes that our app will display to the user are received via an HTTP request to an API. Since API calls are expensive, our app will optimize performance by caching recipes that users save (bookmark) in our database. Since users will often access their bookmark list, reducing overhead for accessing these recipes will provide an improvement in app performance. 

![Screenshot](https://github.com/jessicahe21/RecipEZ/assets/38922275/d750bfd2-12bc-4559-979f-5b8e568b01a8)

# My Flutter Journal

### What is this? 
Repository to organize knowledge I get regarding Flutter App development

### Starting point
I started by creating simple app in flutter, just to get a hang of widgets and basic ui layouts.
Thats when i created my first app. It's an 'Life Counter' for popular Trading Card Game: Magic the Gathering. 
[MTG life counter](https://github.com/Jan-Stepien/MTG-life-counter)

![alt text][gif]

[gif]: https://github.com/Jan-Stepien/MTG-life-counter/blob/main/github_assets/mtg_life_coutner.gif "Mtg life counter"

After i realised how cool the Flutter is i quickly jumped into the project creating Coffee Rating App. I've done some reading and with my experience in operating on streams in **Angular** i decided that Bloc is the thing i would like to implement.
As i started creating layout i realised that programming app is cool, but having it looking nicely is the go to.
Some more reading on the Flutter forums and i realised i dont have enough proffessional knowledge on coffee making or tasting that its gonna be hard for me to implement usefull rating app.
So i decided to move to Beer Rating, as it will make business decisions easier ( i love good sour or milkshake IPA ). After that i started implementing rating app. 
[App to be redesigned](https://github.com/Jan-Stepien/beer-team-scrap)

![alt text2][gif]

[gif]: https://github.com/Jan-Stepien/beer-team-scrap/blob/main/github_assets/ugly_beer_app.gif "Beer Team Scrap"


In effect i got an app where i can add a drink and kept the current selection on the **Bloc** ( i knew there is a bloc package to use, but i wanted to fully control the flow to learn more ). 
This was a moment to start using **Firebase Realtime Database**. Of all the reading i knew i can embed it pretty easly to my project so i dint have to spent more time learning node.js backend creation.
After few days, which i spent fighting with configuration of flutter version (after i upgraded...) i setup basic flow of reading and diplaying collection , while adding new item to database.

This was the moment when things got messy, i started implementing everything I found on instagram great idea boom right into project, splashscreen boom spending another day on it. Cool animations boom into project ended up in a huge mess... all the features started, project structure terrible, even naming of files got mystery... This brought me to the point where i need to write down specs and start working in organized way. So let's go.

### Baby steps - main app flow designing

First lets start with simple flow allowing us to use core functionality which is rate the beer! 
Quick youtube crash course of Figma and we are right in!


[Beer app figma project](https://www.figma.com/file/dW2sEj8mjibg5ZyoM04lgp/Beer-Team-App?node-id=0%3A1)


It ain't pretty, but not gonna spend more time on it. Will ask a friend of mine who is learning UI/UX designing, but will see if he finds some time for me.

With my mind setup how it will look like, time to code the basic flow. Lets jump right into it




[Lets keep it here to be able to check how to format this file](https://guides.github.com/features/mastering-markdown/)

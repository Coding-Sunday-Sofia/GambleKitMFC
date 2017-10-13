# Gamble Kit MFC - Static DLL
This is a C++ MFC applicaiton adapted from https://sourceforge.net/projects/gamblekit/
This code is meant to be run in Visual Studio. I compiled in Visual Studio 2015 Community edition.

#### YouTube Channel and Tutorials for this project
https://www.youtube.com/watch?v=QVhkd8VVrTo&list=PLyCwPGjh8kDzLA9Q4EhnLe0wixsovFcvD

The only files I edited are
- MainWindow.cpp 
- MainPage.h 
- MainPage.cpp 

Thanks to Scott Mayer for getting the DLL files working

## Description
GambleKit is a free open-source C++ object oriented library for quick and easy building of slot machine and gambling games with reels and GUI management.

It relies basically on declarative programming style, so the programmer needs simply to declare, for example at creation time, the basic layout and behavior of the game, and then leave the game flow, requiring as little additional intervention as possible.

The project is welcoming contributors and feedback is appreciated!
The next steps in development, by degree of priority follow documentation, more examples, slight code refinements and new features.

Please let me know if you are using the kit and what new features would you find most useful. You're welcome at the discussions or to post me your inquiries

## Features
* Object-oriented C++ kit with with declarative programming style which reduces the need of writing large amounts of code. The demo game in the screen shot above has all the displayed features working, made with about two pages of user code.
* Handles technical details such as graphics and sound effortlessly.
* Easy to make GUI - a button, animation, animated text and other entities can be created with a single line of code and automaticaly handled. Yet they can be highly customized while being declared, thanks to the many optional parameters
* Game is organized in pages, each of which is generally independent of the others by means of logic and appearance. This makes it easy to make many pages for different game screens, bonuses, menus
* Resource management takes care to load only necessary resources and share them between pages, so that no page logic and content has to take into consideration any other page.
* Highly structured reels model allows to define the rules of how the slots will play. A visual reel component provides the graphics representation of the slots, while its logic can be built out of different and customizable models for its wininng lines shape, symbols behaviour and coefficients, combinations generation and winnings analyzation.
* Extendable models for analyzation of winnings and potential winnings provide easy functionality for getting detailed information on a combination's actual and possible winnings - total win, winning of a particular line and its symbols, SCATTER and WILD winnings. The model also supports winnings symbol sequences, starting not only from the first reel, but from any
* Logical comparison between combinations. Sometimes quantitive analyzation is not enough. Different combinations might still hold partially or fully equivalent winnings regarding winning lines and winning symbols. Because of this, the kit can compare a combination against another to check if its winnings are fully or partially contained in the other one. One possible usage of such feature might be to very easily create a combination, which has different symbols than another one, but has equivalent winnings, or slightly greater, or slightly lesser, or ensure an entirely different winnings.
* Virtual file system, which can be used to store all the game data into one single file. Transition between using the virual file system and the physical file system is seamless. The virtual file system is useful for concealing the resources and for keeping them all in one file
* Bindings can handle many otherwise boring and irritating tasks, which keeps the code of the essential logic clean and simple
* Projects that use the kit are easily expanded and maintained, bacause a big part of the logic is created via declarations, which makes the code conventional and easier to follow even by someone unfamiliar with it

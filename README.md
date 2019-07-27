# Crystal Collector! (Repo - https://github.com/Carl-Lombardi/CrystalCollector) (Site - https://carl-lombardi.github.io/CrystalCollector/)
This is a simple Crystal Collector game whereas the user chooses a colored crystal which has a predetemined random value. The goal of the game is to not go over the target goal. 

## This site uses Javascript and JQuery 
The basic build of the site was HTML/Bootstrap with the use of Javascript to write the code of the game and the use of JQuery to manipulate the HTML. 

## Features
This app is a single page app with instructions, the game and a score keeping area which adds to the Wins or Losses depending on the user performance. 

## Code Example
The below code is for the wins/lose function. Basically, the below code shows what will happen when a user wins the game, or when a user loses. 

    function win () {
        totalwins++;
        $("#wins").text("Wins: " + totalwins++);
    }

    function lose () {
        totallosses++;
        $("#losses").text("Loss: " + totallosses++);
    }

## Installation 
No outside software is needed for installation. 

## How to Use
This is a pretty straight forward game with instructions on the page. 

## Issues and Solutions
The biggest issue that I ran into in creation of this app was making the app work as intended. 

## Credits
This app was created, written and developed by Carl Lombardi. 
# What I Learned In Week 10

## Grid Layout 
Allows to create a grid like layout with rows and columns.

`display: Grid` - makes children of an element to be displayed in grid. 

`grid-template-rows/columns` - used to create rows and columns respectively. 

`grid-row/column` - used to assign a child specific position a grid (i.e. grid-row: 1/2 - will change child's row position, where 1 is the beginning line and 2 is the ending line. grid-column: 1 / span 2 - span allows to make a children certain length)

## [Japanese Grid (Group)](https://github.com/hansCodeJam/japanese-grid-solution)
The goal of the exercise is to recreate goal image using grid layout. 

## [Japanese Grid Big](https://github.com/ignitikus/japanese-grid-big)
Expansion of japanese grid exercise. 

## [Holy Grid 1 & 2](https://github.com/ignitikus/holy-grid-template-areas) 
`grid-template-areas` - allows to create a map of a grid and assign names for certain areas in the grid. 

For example:

    grid-template-areas:
        "top top top"
        "mid mid mid"
        "bot bot bot"
    ;

## [Holy Responsive Grid](https://github.com/ignitikus/holy-responsive-grid)
@media and grid layout.


## JavaScript Object

Object is an array without indexes. 

For example:

    let person = {
        firstName: 'Keanu',
        lastName: 'Reeves',
        age: 55,
        eyeColor: 'Brown'
    }

firstName, lastName, age, eyeColor - properties of the variable `person`. 'Keanu', 'Reeves', 55, 'Brown' - values of those properties. 

Examples on how to access properties:

    person.firstName or person['firstName']


## Code Wars
### [Abbreviate a Two Word Name](https://www.codewars.com/kata/abbreviate-a-two-word-name/javascript) 
- Write a function to convert a name into initials. This kata strictly takes two words with one space in between them.
The output should be two capital letters with a dot separating them.

### [Player Contact Manager](https://www.codewars.com/kata/player-contact-manager/javascript) 
- You are the Dungeon Master for a public DnD game at your local comic shop and recently you've had some trouble keeping your players' info neat and organized so you've decided to write a bit of code to help keep them sorted! The goal of this code is to create an array of objects that stores a player's name and contact number from a given string.

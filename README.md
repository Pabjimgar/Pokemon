# Pokemon

In this notebook I am going to play around with a dataset extracted from Kaggle's user Alberto Barradas' account on Pokemon. The dataset can be found here. This Pokemon data set includes 721 Pokemon, including their number, name, first and second type, and basic stats: HP, Attack, Defense, Special Attack, Special Defense, and Speed.

This are the raw attributes that are used for calculating how much damage an attack will do in the games:

-__#__: ID for each pokemon

-__Name__: Name of each pokemon

-__Type 1__: Each pokemon has a type, this determines weakness/resistance to attacks

-__Type 2__: Some pokemon are dual type and have 2

-__Total__: sum of all stats that come after this, a general guide to how strong a pokemon is

-__HP__: hit points, or health, defines how much damage a pokemon can withstand before fainting

-__Attack__: the base modifier for normal attacks (eg. Scratch, Punch)

-__Defense__: the base damage resistance against normal attacks

-__SP Atk__: special attack, the base modifier for special attacks (e.g. fire blast, bubble beam)

-__SP Def__: the base damage resistance against special attacks

-__Speed__: determines which pokemon attacks first each round

-__Generation__: number of the generation (as an integer) each pokemon belongs to.

-__Legendary__: whether the pokemon is legendary or not as a boolean value.

## Table of contents

1.-Introduction

2.- Libraries

3.- Importing the data

4.- Pokemon attributes

5.- Legendary pokemon

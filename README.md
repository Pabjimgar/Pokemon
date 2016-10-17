# Pokemon

In this notebook I am going to play around with a dataset extracted from Kaggle's user Alberto Barradas' account on Pokemon. The dataset can be found here. This Pokemon data set includes 721 Pokemon, including their number, name, first and second type, and basic stats: HP, Attack, Defense, Special Attack, Special Defense, and Speed.

This are the raw attributes that are used for calculating how much damage an attack will do in the games:

-#: ID for each pokemon

-Name: Name of each pokemon

-Type 1: Each pokemon has a type, this determines weakness/resistance to attacks

-Type 2: Some pokemon are dual type and have 2

-Total: sum of all stats that come after this, a general guide to how strong a pokemon is

-HP: hit points, or health, defines how much damage a pokemon can withstand before fainting

-Attack: the base modifier for normal attacks (eg. Scratch, Punch)

-Defense: the base damage resistance against normal attacks

-SP Atk: special attack, the base modifier for special attacks (e.g. fire blast, bubble beam)

-SP Def: the base damage resistance against special attacks

-Speed: determines which pokemon attacks first each round

-Generation: number of the generation (as an integer) each pokemon belongs to.

-Legendary: whether the pokemon is legendary or not as a boolean value.

## Table of contents

1.-Introduction

2.- Libraries

3.- Importing the data

4.- Pokemon attributes

5.- Legendary pokemon

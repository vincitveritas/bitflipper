# bitflipper

The bitflipping programming langauge. Because at the end of the day, computers are just bit flippers.

## rough spec:

- every piece of data is just an array of bits
- functions are there to manipulate this string of bits (so quite function like)
- very strongly typed as in mostly defined lengths of the data that is to be manipulated
- hopefully no undefiend behavior (f.ex.: you can only add two 63 bit numbers together and write them into a 64 bit number, so you manually have to cut your original two 64 bit numbers into 63 biters, so when you add them you don't get an overflow, this langauge is trying to dodge undefiend behavior by not even allowing weird stuff)
- not necessarly focused on an easy syntax, this syntax is just an attempt at being somewhat "designed"
- should have low level access (directly to the memory)
- maybe have some sort of way of wireing in other code bits in other languages

## Thoughts and stuff

- code is probably written in UTF8 -> symbols can be manually or automatically converted into meaning

## todo

Start the project!
- make the rough spec
- build a bitflipper -> C translator
- test out

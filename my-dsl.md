# Language

<a href="http://scratch.mit.edu/">Scratch</a>


# Domain

Teaching programming to young children.


# Computational model

The language is literally built with blocks. A for-loop block, for example, could wrap around a set of blocks.
When the code is executed, an interpreter examines the sandbox for the start block. It then executes each set
of blocks that begins with the start block in parallel. At each step, it determines whether it needs to update
a variable, move a sprite, etc.


# DSL-ness

As Fowler noted, there are languages that could be general-purpose, but are not intended to be used as such,
making them DSLs. In that sense, Scratch is a DSL. It is indeed general-purpose, as it implements every feature
of a general-purpose language. However, it is incredibly slow, there is no quick way to add code aside from
placing blocks, etc. This language, as seen from the plethora of sprites and built-in animation code, is
intended for children to get used to the idea of coding and play around with basic concepts. In that sense,
it is a DSL.


# Internal or external?

It is an external DSL. It is built to make performing certain actions incredibly easy, such as animation.
To do this, it is built upon ActionScript, a language primarily used for web applications. Since the
language allows users to easily do what would be more difficult in raw ActionScript, this falls under
the external DSL category.

# Host language

ActionScript


# Benefits

This language is _fantastic_ at teaching students the basics of programming. Over the Summer, I worked
with Prof Dodds on building a curriculum around Scratch. The ease of creating tasks is only matched by
how easily students pick up how to make their own plays, songs, etc. 


# Drawbacks

The tradeoff of this language is how slow it is. Because it allows the users to place blocks anywhere and
execute multiple threads all at once, the execution can slow tremendously. The other drawback is that, while
it is easy to do simple projects, bigger, complex ones take much more time in simply moving blocks around.
There are games built out of Scratch (<a href="http://scratch.mit.edu/projects/10128407/">Paper Minecraft</a>
 for example), these are not what the language is designed for, leading to clunky code and laggy games.

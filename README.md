# Cast
A metadata driven tabletop RPG Rulebook Generator

## The Idea

Build a generator (like a static site generator) that reads Squad formats and components and generates a table top roleplaying book (or website)

Components are
Paragraphs, texts, images, tables, etc.

They may also have types like
* Rules
* Flavor
* Contexts
* Categories
* Prompts
* Worksheets
* Stats*

Formats are specify structured relationships between components
* These rules apply in this context
* This flavor describes these components
* These rules extend those rules
* The components (and their children) should be laid out like this

If stats are typed, we could include things like a roll20 site or app that could aid players in keeping track of stats. We could also include transformations to those stats in other components using the redux action reducer pattern.
* Int
  * Skill points
  * Hit points
  * Experience points
* Int range
  * like attributes from 1-18
* Boolean
  * Does or does not have ability X
  * Weapon profficiencies
* Enum
  * status effects

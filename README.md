# HPSpells
Repository containing dataset with spells from Harry Potter books. Contains list of all spells used in verbatim in the books. The only exception is _Avada Kedavra_, which was also searched in the books by the term "green light".

<ins>HPSpells.csv</ins> contains columns:
- Position: Position in the book, corresponding to the row number in [harry_potter_books.csv](https://github.com/gastonstat/harry-potter-data/blob/main/csv-data-file/harry_potter_books.csv)
- Book: Book number in the main series
- Chapter: Chapter number
- Spell: Spell used in the series
- Spell Type: Type of spell. Types were categorized using [Wizarding Home Spells List](https://wizardinghome.com/harry-potter-spells-list-a-z/)
- Effect: Spell effect
- Caster: The person who cast the spell
- Target: The person or animal targeted (objects are excluded)
- Location: Where spell was cast

<ins>Spell_Types_Game.csv</ins> contains the following spell type classifications based on game scenarios:
- Utility: Spells for everyday tasks, such as unlocking doors or creating light.
- Unforgivable Curse: Forbidden dark magic spells, including the Cruciatus Curse.
- Transfiguration: Spells that transform the form or appearance of objects or beings.
- Force: Spells that create physical movement, like pushing or pulling objects.
- Control: Spells that influence others' actions or thoughts.
- Protection: Spells that create shields or defend against attacks.
- Healing: Spells that cure injuries or ailments.
- Combat: Offensive spells used to harm or incapacitate opponents in battle.

Dataset was crafted using these sources:  
[1] [Harry Potter Lexicon](https://www.hp-lexicon.org/)  
[2] [Wizarding Home Spells List](https://wizardinghome.com/harry-potter-spells-list-a-z/)  
[3] [harry_potter_books.csv](https://github.com/gastonstat/harry-potter-data/blob/main/csv-data-file/harry_potter_books.csv)  
[4] [Harry Potter Wiki](https://harrypotter.fandom.com/wiki/Main_Page)  

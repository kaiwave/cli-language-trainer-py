# CLI Language Trainer
## Language grind flashcard project
I want to learn latin, but in principle this can be used for any language. (I can also use to practice my french).

It's basic flashcards which run in a basic CLI, there is no sophistication to this whatsoever. 

Potentially thinking of giving it a UI if I can be bothered, and may add more features later but nothing specific is planned...

Updates below (mostly so I can keep track of what I'm doing):

- **Patch 0.3**
- - added sentence mode, a way to practice translating full sentences, with hints available (shuffled answers). eg. ("i think therefore i am" with hints adds a line `Hint: sum ergo cogito`)
- - done in program, no need to put a dedicated hint inside ur own .csv file
- - added (optional) re-attempts for missed cards (until u get 100%), so u can practice ur weaknesses a bit better


- **Patch 0.2**
- - colors !! green for correct answers, red for incorrect. final % is colored red for <50%, yellow for 50%-85% and green for >85%
- - databases moved to `databases/`, and loading is now easier, only type the name of file. (`databases/` prefix and `.csv` extension not mandatory to enter anymore)
- - refactored basically everything out of main function to help w future expansion development and stuff


- **Patch 0.1**
- - added inline hint support, supposed to be for conjugation endings but can be for anything (eg. "amare" asks "Your answer: am", and u only need to put the ending)
- - add some `verb root-` before actual prompt (dash is important!!) 
- - see notation example in [default.csv](databases/default.csv) - (eg: "`am-amare 1st person singular present tense"`)

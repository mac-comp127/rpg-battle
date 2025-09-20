# Take-Home Activity: RPG Battle

## Self-Evaluation Rubric

# 🔴 Instructions

You can make a copy of this document and use the checkboxes below as you complete the self-evaluation of your solution.

# Correctness

Use the list below to evaluate the correctness of your solution. Cross off the items that your solution passes.

- [ ] The `GameCharacter` class mentions `Weapon` in four places:
  - [ ] an instance variable
  - [ ] a constructor parameter
  - [ ] a getter method
  - [ ] in the `attack` method, which calls `weapon.attack(…)`
- [ ] The `GameCharacter` class has no mentions of swords or fireballs anywhere:
  - [ ] not as part of the name of any instance variables
  - [ ] not in any parameters
  - [ ] not in the constructor or any of the methods
  - [ ] not in imports at the top
- [ ] The `GameCharacter` class no longer uses the `Random` class, and no longer has a `rand` instance variable. (This variable should move to `Sword`, the only class that needs it.)
- [ ] There is a `Weapon` interface with two methods: `getDescription` and `attack`.
- [ ] There are two classes named `Sword` and `Fireball`:
  - [ ] Both say implements `Weapon`.
  - [ ] Both have `getDescription` and `attack` methods.
  - [ ] Both have instance variables that do not have names that start with a “fireball” or “sword” prefix.
- [ ] `GameCharacterTest` says `new Fireball(15, 7)` on the line that creates the character `sally`, and `new Sword(5, 10)` on the line that creates `marvin`. The file has no other changes.
- [ ] The tests in `GameCharacterTest` all pass.
- [ ] The `Game` class successfully plays a game when you run it.

# Code Style

Use the list below to evaluate the adherence of your code to the [COMP127 Style Guide](https://f25.comp127.innig.net/resources/style-guide/). Cross off the items that your code satisfies.

- [ ] all classes are in packages
- [ ] package names start with a lowercase letter
- [ ] newly created Java files have a header comment with (a) author name, (b) brief description of class, and (c) acknowledgement, if appropriate
- [ ] identifier (variable and method) names are descriptive
- [ ] **variable** and **method** names are in lowerCamelCase (no CapitalizedNames,  names\_with\_underscores)
- [ ] **class** names are singular nouns
- [ ] **class** names are in UpperCamelCase
- [ ] all instance variables are **private**
- [ ] proper indentation:
  - [ ] opening curly braces (“{”) are at the end of the line
  - [ ] closing curly braces (“}”) are on their own line
  - [ ] the indentation of closing braces is the same as the indentation of the opening statements they match
  - [ ] lines are indented according to how deeply they are nested
- [ ] completed TODO comments are deleted
- [ ] extra blank lines are deleted
- [ ] unneeded commented lines of code are deleted
- [ ] print statements used for testing are deleted

# Reflection

Briefly reflect, in writing, on your experience solving this exercise. What did you miss?  What did you wish you did better?  What challenges did you face, and how did you overcome them?

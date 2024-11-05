# Welcome to the LLS Larpa Earhard Team
<sup>if you found this page without being in the TUM course, congrats. Nothing secret resides here, but nothing relevant either.</sup>
## Team Information
- please look at the ``Teams`` tab above and request to join your team
- You can ping other teams in issues with ``@``, e.g. ``@LarpaEarhart/aerodynamics``

## Coding Guidelines

- **Follow python style guidelines:** https://peps.python.org/pep-0008/
(Seriously, please at least skim over this, and read “Naming Conventions”)
- **All variables should have type hints.** https://mypy.readthedocs.io/en/stable/cheat_sheet_py3.html
This makes code more understandable and gives the autocomplete an easier time.
- **Functions should not have side effects** https://youtu.be/HlgG395PQWw
Do not modify data that your function does not return, e.g. by changing global variables. A function should do exactly what you expect of it by the name, nothing more.
- **Document which formulas you used in your function and where you found them.**
It is vital that we keep track of where formulas came from for citations, and that we have the standard form visible for formulas that had to be solved for a variable before being implemented.
- **Every piece of data only has a single source of truth.**
No matter what data, environment constant, airfoil polar, etc you have, it should only ever be defined in one spot. Do not hard-code variables. If you edit your code and you have to change the same number in two spots, something is wrong.
- **Every commit message must be understandable and useful**
Commit messages are what is used to later parse through when changes were made and where issues might have been introduced. Make them useful.
- Tip: Test your code and test it often. Testing every five lines is much faster than writing a hundred lines and debugging for five hours. Trust me.

## Neat Resources
- Indently - 5 good python habits, useful tricks to be aware of. https://youtu.be/I72uD8ED73U
- CodeAestetic - Naming Things in Code, very good general advice, the rest of the channel is grea too. https://youtu.be/-J3wNP6u5YU

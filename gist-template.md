# Title Password Validation RegEx

This document covers the indiviudal parts and components of this regex:
"​^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,}$/g"

## Summary
​
This regex makes sure a password equals 8 characters, upper case, lower case, numbers, letters, and special characters.
​
## Table of Contents
​
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)
​
## Regex Components
​

### Anchors
​Our first anchor is the ^. This tells our regex to begin at the start of a string. 
Our second one is the dollar sign. This tells our regex to stop at the end of a string.

### Quantifiers
​{8,} In our regex this symbol specifies that the password should 8 or more characters. 

### Grouping Constructs
​(?=.*[A-Z]) Our regex contains several of these grouping constructs. Each of them dictates which characters our passwords should have. 

### Bracket Expressions
​[A-Za-z\d@$!%*?&] Bracket expressions like this one specify exactly what character our regex is looking for. This particular one specifies that our regex should have uppercase, lower case, numbers, and symbols. 

### Character Classes
​[A-Z] Character classes tells regex to watch for a range of characters. This particular character class tells regex to watch for characters, upper case letters A-Z.

### The OR Operator
​This regex does not have an OR operator. 

### Flags
​Flags tell regex how far to search. The global or g flag tells regex to search the entire string.

### Character Escapes
​Character escapes are denoted by a \. They are used to make sure that regex doesnt read special characters as a part of the string. In this regex the lowercase d character representing 0-9 is escaped.

## Author
https://github.com/daniellecavallo

​
Danielle Cavallo: Guiding Lives, Empowering Futures

Danielle Cavallo is an accomplished individual with a diverse and impressive background, combining her expertise in finance, technology, and philanthropy to create a positive impact on the world. Born with a natural affinity for learning and a compassionate heart, Danielle's journey towards success began with a Bachelor's degree in Marketing from Caldwell University. Her dedication to academic excellence was recognized as she graduated with honors and was inducted into the prestigious Kappa Gamma Pi honor society.

The financial industry became Danielle's chosen path, where she devoted the last ten years to guiding clients towards better retirement and financial decisions. Her unique approach, grounded in empathy and a keen understanding of her clients' needs, has garnered her a reputation as a trusted and reliable advisor in the field.

But Danielle's interests didn't stop there. Driven by her passion for technology, she decided to expand her knowledge by pursuing studies in software engineering at Columbia University. With an unyielding thirst for knowledge, she aspires to delve into the world of cybersecurity, recognizing its vital role in safeguarding individuals and organizations in the digital age.

Beyond her professional accomplishments, Danielle is a woman of profound kindness and a strong sense of responsibility towards her community. She runs a non-profit organization dedicated to assisting the homeless, providing them with shelter, food, and opportunities to rebuild their lives. Her partnership with Great Harvest Bread Co in Nashville has further strengthened her mission to alleviate the hardships faced by the less fortunate.

Apart from her remarkable work, Danielle has diverse interests that keep her engaged and balanced. She is an avid enthusiast of Muay Thai, Pilates, and various sports, valuing the importance of physical well-being as much as intellectual growth. Her involvement in these activities also fosters camaraderie within her communities, where she is known for her friendly and approachable nature.

While Danielle has made a significant impact within the circles she belongs to, her dreams and aspirations extend beyond regional boundaries. Eager to make her presence known to the world, she remains committed to using her skills and knowledge to uplift lives, champion causes she believes in, and contribute to the betterment of society.

In summary, Danielle Cavallo is a remarkable individual whose journey is marked by determination, compassion, and an unwavering commitment to making a difference. As she continues to explore new horizons in both her professional and personal life, she remains an inspiring figure and a beacon of hope for those she touches with her positive influence.










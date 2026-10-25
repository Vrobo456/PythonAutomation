#Week 4

 -Character classes
 -Matching with the "dot" character

#Character classes
<img width="915" height="170" alt="image" src="https://github.com/user-attachments/assets/2b2f04d1-d286-425b-9573-9c6337174daf" />

#Using ranges in character classes
<img width="915" height="170" alt="image" src="https://github.com/user-attachments/assets/c512359c-64cb-4137-8fb5-6bc7ad248808" />

#Using [^] to negate character classes
<img width="915" height="170" alt="image" src="https://github.com/user-attachments/assets/7ed12808-df44-4754-ad51-9550cb28e131" />

#Using shorthand character classes
<img width="915" height="170" alt="image" src="https://github.com/user-attachments/assets/a02c324b-9e8a-41de-b31f-3ee0dea7404a" />

 -Table reference for using shorthand characters
 <img width="792" height="497" alt="image" src="https://github.com/user-attachments/assets/5e23ceb5-4f5f-4957-ac36-8f88f0717248" />

#Using "." to match characters
<img width="868" height="81" alt="image" src="https://github.com/user-attachments/assets/0b3d0df7-b210-4e4a-9b24-9719c39ea5c8" />


-You can make Character classes to match multiple letters or digits, plus you can use ranges inside the class e.g. [a-z]

-If you put "^" in front of the defined digits or letters in a character class, you negate that class. In other words everything that's not in that class is searched for

-The "." character takes everything that matches the characters that follow it and a character that's supposed to be in it's place e.g. ".ke" takes everything that matches "ke", plus a letter in it's place. ".ke" from "cake" would be "ake".

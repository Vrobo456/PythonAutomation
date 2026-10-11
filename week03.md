#Week 3
 - using '|' for alternative matching
 - finding all of the matches in a text

#Using pipe to match different suffixes to 'Cat' in a group
<img width="735" height="202" alt="image" src="https://github.com/user-attachments/assets/509758fc-bf2d-48a2-9f03-26883de11c70" />

#Finding all the matches with .findall()
<img width="735" height="202" alt="image" src="https://github.com/user-attachments/assets/29afc226-80b0-424a-ad98-55e007bd28a0" />

#Using .findall() when the regex has groups
<img width="715" height="159" alt="image" src="https://github.com/user-attachments/assets/e696fe18-7f95-42d8-9d99-b75a9bf3627e" />

 - Pipe is basically 'or' when used for alternative grouping in regexes
 - To find all of the matches and not just the first match we use .findall()
 - If there are groups in a regex and we use .findall() it prints tupes with each group as it's own string
 - .findall() does not overlap, so if there is a number e.g. '12345' and match \d{3}, it'll only print '123' and leave '45' out
 - if the number is 6 digits and we use \d{3}, it'll print two strings, each 3 digits long and they won't overlap
   <img width="510" height="196" alt="image" src="https://github.com/user-attachments/assets/eee728b7-8c8f-4a41-8bea-95da26611466" />

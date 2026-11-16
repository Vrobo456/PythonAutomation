# Week 8

- Matching case insensitive
- Substituting strings

#Case insensitive  
<img width="746" height="149" alt="image" src="https://github.com/user-attachments/assets/c2b0a9d9-f75b-4d85-94b9-25e605436a3a" />  
  

#Using sub() method  
<img width="714" height="68" alt="image" src="https://github.com/user-attachments/assets/1fb5afba-f44b-4b56-b136-54fe643e73a6" />  
<img width="714" height="68" alt="image" src="https://github.com/user-attachments/assets/e0b4b1ec-191c-4209-88ed-fb5a8ab6a996" />  

- To match case insensitive you simply need to pass re.IGNORECASE/ re.I as a second argument in your compile line
- Use sub() method to replace any matches. The example shown earlier replace the match of 'Agent' + any word following it, with 'CENSORED'.

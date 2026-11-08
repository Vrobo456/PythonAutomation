# Week 7

- Matching everything  
- Matching newline characters  
- Matching at the start or the end of a string  

#Matching everything with (.*)  
<img width="801" height="171" alt="image" src="https://github.com/user-attachments/assets/c558cf41-86d4-4d9e-8bf1-d3e014eecd74" />  
#Matching everything the greedy way or non-greedy way  
<img width="801" height="171" alt="image" src="https://github.com/user-attachments/assets/dcb291ed-c24c-4ea0-9c8a-2eee864fb13a" />



#Match newline char. with 're.DOTALL'  
<img width="921" height="193" alt="image" src="https://github.com/user-attachments/assets/9e5e7d7f-968b-4efe-bde8-53a7fd90da15" />



#Matching with '^' at the start  
<img width="603" height="153" alt="image" src="https://github.com/user-attachments/assets/6c953cc8-df51-4b28-b8ab-5dc9d0f8bad9" />

#Matching with '$' at the end  
<img width="641" height="139" alt="image" src="https://github.com/user-attachments/assets/aaebeb8c-1618-45e4-9e01-fc2a6e408d5b" />

#Using '^' and '$' in the same pattern  
<img width="641" height="139" alt="image" src="https://github.com/user-attachments/assets/017a70c5-5f12-4d5d-8d67-652b18627a01" />

#word boundaries when matching at the start/end of a word
<img width="757" height="90" alt="image" src="https://github.com/user-attachments/assets/1712b33f-051e-40b2-bb9d-a9f1f60763e9" />  
<img width="710" height="110" alt="image" src="https://github.com/user-attachments/assets/5daffcee-d79c-46c6-a672-5125ae64b5be" />  

- (.*) matches any symbol and number of symbols except newline. '.' - matches any character, '*' - matches one or more instances of the qualifier
- Even when matching everything, lazy regexes and greedy regexes still work
- To match newline characters with (.*) you need to use 're.DOTALL', e.g. (r'Name: (.*)', re.DOTALL)
- '^' indicates that the pattern is being matched at the beginning of a string (e.g. (r'^cat.*') - will match any string starting with 'cat')
- '$' does the same, but for the end of a string (e.g. (r'.*cat$) - will match any string that ends with 'cat')
- when we use both, the whole string has to match the pattern (e.g. (r'^Hello$') - will only match a string 'Hello')
- word boundaries help find specific words anywhere in the string, (r'\bman.*\b') matches any word that starts with 'man'
- \B exclude word boundaries, so (r'\Bbe\B') matches any word that has 'be' inside, but does not start or end with it. fiber - good, begin - bad

  

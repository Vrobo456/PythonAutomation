#Week 6

-Matching ONE or more qualifiers  
-Matching a specific number of qualifiers  
-Greedy and Non-Greedy matching  


#Using '+' to match one or more qualifiers  
<img width="784" height="192" alt="image" src="https://github.com/user-attachments/assets/7962a6a0-3b1d-47a6-b91b-d9ca7c28a8ec" />


#Matching specific number of qualifiers  
<img width="410" height="82" alt="image" src="https://github.com/user-attachments/assets/2286e7d1-6a21-4d39-9f0a-008e658b7f3a" />
<img width="458" height="82" alt="image" src="https://github.com/user-attachments/assets/b94451ea-3cb2-4566-b6f3-13ace093701d" />


#Matching a range of qualifiers  
<img width="606" height="208" alt="image" src="https://github.com/user-attachments/assets/d3fd80a5-3ccc-4238-9512-c148bfc64c6d" />


#Greedy vs Non-Greedy (lazy)   
<img width="606" height="87" alt="image" src="https://github.com/user-attachments/assets/9a68cc53-46b9-4d0c-b054-bd20e3e69dad" />
<img width="606" height="87" alt="image" src="https://github.com/user-attachments/assets/b225184d-f794-4f4e-b3fe-5ff748b07dd0" />

-Use '+' to match one or more qualifies, it functions similarly. However, since it requires at least one instance, it is not optional like the zero or more conditions using '*'.  
-By putting a number in curly brackets right behind a qualifier, you can specify how many times you want that qualifier to be matched.  
 If you put in two numbers separated by a comma, you will get a range of times the qualifier will be matched.  
 The range includes the upper number, so {2,8} includes the qualifier repeating for 8 times.
-By default, Python's regular expressions are "greedy", meaning if the range is {2,8} and it matches 8 times it will display that it matched 8/ the whole sting is matched.  
 Non-greedy or "lazy" regular expressions will only matched the minimum amount of times possible, so {2,8} will match only 2 times.
 You can achieve lazy expressions using '?' right after the range, e.g. (r' ... {3,5}? ... ')  
 

# Project 1 Create Acronyms using python

## An acronym is a short form of a word created by long words or phrases such as NLP for Natural language processing.


```python
user_input = str(input("Enter a phrase : "))
text = user_input.split()
a = " "
for i in text:
    a = a+str(i[0]).upper()
print(a)    
```

    Enter a phrase : Artifical Intelligence
     AI
    


```python

```

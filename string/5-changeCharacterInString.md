##[ChangeCharacterInString](https://www.hackerrank.com/challenges/python-mutations)
```
def mutate_string(string, position, character):
    return string[:position]+character+string[position+1:]
```       
                  
```
def mutate_string(string, position, character):
    l = list(string)
    l[position]=character
    return ''.join(l)
``` 
                 
###Description
```
Sample Input
abracadabra
5 k
Sample Output
abrackdabra
``` 

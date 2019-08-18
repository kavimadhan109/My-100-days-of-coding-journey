## Statement
```
Given a string in which the letter h occurs at least twice. Remove from that string the first and the last occurrence of the letter h, as well as all the characters between them.
```
## Sample Input 1
```
In the hole in the ground there lived a hobbit
```
## Sample Output
```
In tobbit
```
## Code
```
s = input()
print(s.replace(s[s.find('h'):s.rfind('h')+1],''))
```

# grep Command In Linux
- [x] Syntax
```
grep [option] pattern [files]
```
> 1. Case insensitive search
```bash
$ echo -e "linux\nLinux\nLINUX" | grep "linux"
linux

$ echo -e "linux\nLinux\nLINUX" | grep -i "linux"
linux
Linux
LINUX
```
> 2. Displaying the count of number of matches
```
$ echo -e "linux\nLinux\nLINUX" | grep -c "linux"
1
$ echo -e "linux\nLinux\nLINUX" | grep -c -i "linux"
3
```
> 3. Display the file names that matches the pattern
```
grep [option] pattern [files]
```
> 4. Checking for the whole words in a file
```
grep [option] pattern [files]
```
> 5. Displaying only the matched pattern
```
grep [option] pattern [files]
```
> 6. Show line number while displaying the output
```
grep [option] pattern [files]
```
> 7. Inverting the pattern match
```
grep [option] pattern [files]
```
> 8. Matching the lines that start with a string 
```
grep [option] pattern [files]
```
> 9. Matching the lines that end with a string
```
grep [option] pattern [files]
```
> 10. multiple times
```
grep [option] pattern [files]
```
> 11. Takes patterns from file
```
grep [option] pattern [files]
```

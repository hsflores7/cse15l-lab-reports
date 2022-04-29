# Lab Report 2

[Main Page](https://hsflores7.github.io/cse15l-lab-reports/index.html)


## Updates
* **Fix One**: Adding the if -1 then break
* **Fix Two**: Adding the if statement in Main
* **Fix Three**: Adding a filter so only links with valid charaters make the list
![updates](https://user-images.githubusercontent.com/103228508/164990778-6e654f9d-362b-4ca1-94e6-35ee5fc6be71.png)
![3rd edit](https://user-images.githubusercontent.com/103228508/164992978-664d79aa-c388-41fb-bdeb-6f91e256791f.png)


## Error-inducting test-file
### Error 1: Breaket Crash
[new.md](https://github.com/hsflores7/cse15l-lab-reports/files/8550287/new.md)

The final line is an empty line and this would cause an error without the breaks as well as if the final line wasn't a link, as to say if the finel was just text like on of the orignal way this file was written:
```
[a-funny-link](funny.com)
does this break it?!?
```
And this version did indeed break the code pre-breaks.

### Error 2: No Argument
It is more of the absence of file than a file in particular.

### Error 3: Invalid Link
[another-test.md](https://github.com/hsflores7/cse15l-lab-reports/files/8587767/another-test.md)

If this test ran after the first fix and before the 3rd then it would print the link in the list even though it isn't a legel link

## Symptom of Error
### Error 1: Breaket Crash 
![breaking new test](https://user-images.githubusercontent.com/103228508/164991082-ae8174ec-be5f-4a7e-9ff4-f773c0f32632.png)

### Error 2: No Argument
![no args](https://user-images.githubusercontent.com/103228508/165874070-3e09fbc0-5fe3-4d0b-b420-9171c09c7b1d.png)

### Error 3: Invalid Link
![image](https://user-images.githubusercontent.com/103228508/165877658-cf7e68b3-7a28-415d-847b-c349ff397762.png)


## About the Errors
### Error 1: Bracket Crash
**Bug:** The code lacked a way to deal with a situation, specifically in the getLinks method
**Symptom:** The symptom was an error message not allowing for the code to compile when the file included the above complications
**Failure inducing inputs:** If the final line wasn't a link or if the brackets were not in the link sequence `[]()`

### Error 2: No arguments
**Bug:** The code lacked a way to deal with a situation, specifically in the Main method
**Symptom:** The symptom was an error message not allowing for the code to compile when the file included the above complications
**Failure inducing inputs:** If no aguments were placed then the getLinks method would cause an error as there wasn't an args to get the links from

### Error 3: Invalid links
**Bug:** The code does not filter invalid links
**Symptom:** Does not remove invalid links from the list of links
**Failure inducing inputs:** If a link has invalid character there should not be included in the list of links


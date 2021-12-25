# Uladzislau Roslikau
### Junior Frontend Developer

---

### Contact information:

**E-mail:** uladzislau.rosgro@yandex.ru<br>
**Telegram:** @horumiko<br>
[LinkedIn](https://www.linkedin.com/in/uladzislau-roslikau-6316191b4/)<br>
[Codewars](https://www.codewars.com/users/horumiko)<br>

---

### Briefly About Myself:

Hey, My name is Ulad. I'm from Minsk. I'm starting to study Web-development. Now, I'm a student in Belarussian State University at the Mechanics and Mathematics Faculty. <br>

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.<br>

---

### Skills and Proficiency:
- HTML5, CSS3
- Python
- C++
- JavaScript Basics
- Git, GitHub
- VS Code, IntelliJ IDEA
- Adobe Photoshop, Figma
### Code example:
### JavaScript:
```javascript
function createFunctions(n) {
  var callbacks = [];

    function indexFunction(index){
      return function(){
        return index;
      } 
    }
  
  for (let i=0; i<n; i++) {
    callbacks.push(indexFunction(i));
  }
  
  return callbacks;
}
```
### C++:
```C++
int FindOutlier(std::vector<int> arr)
{
    using namespace std;
    int result;
    vector<int> even, odd;
    for(int i = 0; i < arr.size(); i++){
        if(arr[i] % 2 == 0) even.push_back(arr[i]);
        else odd.push_back(arr[i]);
    }
    if(even.size() == 1){
        result = even[0];
    }else result = odd[0];
    return result;
}
```
### Python:
```Python
def is_divisible_by_6(s):
    #your code here
    result = []
    numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
    for i in numbers:
        new_str = s.replace('*', i)
        if int(new_str) % 6 == 0:
            result.append(str(int(new_str)))
    return result
```
### Courses:
- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
### Languages:
- English \- A2
- German \- A2
- Russian \- Native
- Belarussian \- Native

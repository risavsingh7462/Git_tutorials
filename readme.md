## Table of Content
- [git](#git)
- [JavaScript](#javascript)
## git
### 1.1 Uploding_File_On_Git:)

- 1. Creating Folder
        - On local host
        - On git repository

- 2. Initialize local host
        - ```$git status```
        - ```$git init```

- 3. Add files:-
        - ```$git status```
        - ```$git add .```

- 4. Add origin:-
        - ```$git remote add origin {SSH copy from git repositore file}```

- 5. Commit:-
        - ```$git status```
        - ```$git commit -m "file name" (like version1)```

- 6. Push:-
        - ```$git status```
        - ```$git push -u origin master/main```

### 1.2 CREATE NEW BRANCH
- ```$git checkout -b <branch-name>```

## Javascript
### Variables
Variables are the containers used to store data, we can declare variables in JavaScript by using the keywords `var`, `let`, and `const`.
``` js
var varName = "hello world";
```
- The `var` keyword has no block scope.
- The `var` keyword is either function-scoped or global-scoped.
- In `var`  we can redeclare variables again and again.

``` js 
let userId = 29
```
- In `let` we can not redeclare it we can only update the value of the variable.

``` js 
const COLOR_RED = "#F00";
const COLOR_GREEN = "#0F0";
const COLOR_BLUE = "#00F";
const COLOR_ORANGE = "#FF7F00";

// ...when we need to pick a color
let color = COLOR_ORANGE;
alert(color); // #FF7F00
```

- `const` are nor update nor redeclare they are constants.

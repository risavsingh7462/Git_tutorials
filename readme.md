## Table of Content
- [git](#git)
- [JavaScript](#javascript)
- [jQuery](#jquery)
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

## jQuery
### Installation
- By downloading the compressed jQuery file
- Using the jQuery CDN
``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>jQuery tutorial</title>
  </head>
  <body>
    hello world
    <p>click on p</p>
  </body>
  <!-- <script src="./js/code.jquery.com_jquery-3.7.0.min.js"></script> -->
  <script
    src="https://code.jquery.com/jquery-3.7.0.min.js"
    integrity="sha256-2Pmvv0kuTBOenSvLm6bvfBSSHrUJ+3A7x6P5Ebd07/g="
    crossorigin="anonymous"
  ></script>
  <script>
  
    console.log($); // $ means jquery
    console.log("we are using jQuery")
    // $('selector').action()
  
  </script>
</html>

```

### jQuery Syntax
General syntax of jQuery
``` js
$('selector').action();
```

### jQuery Functions
- `click()`:
On click paragraph tag 'p' the simple message is print on the console.
``` js
 $('p').click(function(){
        console.log("you click on p");
});
```

- `hide()`: hide() function simply hide the content on click. We can select any tag, id, or class.
``` js
 $('p').hide(); //it will hide all the p tags
```
note: if there exist multiple p tags then we can use `this` keyword to target specific p tags.

``` js
 $(this).hide(); // by using this keyword we can hide specific p tag 
```
**for selecting #id or .class**
``` js
 $('#id').hide(); //for selecting id
 $('.class').hide(); // for select class
```

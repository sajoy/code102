# TIL

- local vs global variables
- if statements
  - `if () {}`
- using `&&` and `||` in an if condition
  - `&&` two conditions must be true
  - `||` either condition must be true
- `get` is a function within an object 
  - runs when you access that property
  - ```
        var car = {
            color: 'blue',
            model: 'convertible',
            get brakeStatus () {
                console.log( 'okay!' );
            }
        };

        car.color; // 'blue'
        car.brakeStatus; // 'okay!'
    ```
- function parameters are optional
- function parameters go inside the parentheses `()`
- function code goes inside curly brackets `{}`
- how to return values from functions
    - ```
        function getCookies () {
            return 'a gazillion cookies';
        }

        var what = getCookies(); 
        what; // 'a gazillion cookies'
        
    ```

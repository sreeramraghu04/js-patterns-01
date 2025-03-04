# JavaScript Patterns 01

## assignment

### Create the below patterns using JavaScript

1.  Square star pattern

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let j = 1; j <= 5; j++) {
        str += "*";
      }
      str += "\n";
    }
    console.log(str);
    ```

2.  Left triangle pattern

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let j = 1; j <= i; j++) {
        str += "*";
      }
      str += "\n";
    }
    console.log(str);
    ```

    - another way

    ```js
    let str6 = "";
    let n = "5";
    for (let i = 1; i <= n; i++) {
      for (let k = 1; k <= n - 1; k++) {
        str6 += " ";
      }
      for (let j = 1; j <= i; j++) {
        str6 += "* ";
      }
      str6 += "\n";
    }
    console.log(str6);
    ```

3.  Inverted left triangle pattern

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let j = 5; j >= i; j--) {
        str += "*";
      }
      str += "\n";
    }
    console.log(str);
    ```

4.  Right angle pattern

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let j = 1; j <= i; j++) {
        str += "*";
      }
      str += "\n";
    }
    console.log(str);
    ```

5.  Inverted right angle pattern

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let j = 5; j >= 1; j--) {
        if (j <= i) {
          str += "*";
        } else {
          str += " ";
        }
      }
      str += "\n";
    }
    console.log(str);
    ```

6.  Pyramid

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let k = 1; k <= 5 - i; k++) {
        str += " ";
      }
      for (let j = 1; j <= i; j++) {
        str += "* ";
      }
      str += "\n";
    }
    console.log(str);
    ```

7.  Inverted pyramid

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let k = 1; k <= i; k++) {
        str += " ";
      }
      for (let j = 1; j <= 6 - i; j++) {
        str += "* ";
      }
      str += "\n";
    }
    console.log(str);
    ```

8.  Square number pattern

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let j = 1; j <= 5; j++) {
        str += i;
      }
      str += "\n";
    }
    console.log(str);
    ```

9.  Square number pattern

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let j = 1; j <= 5; j++) {
        str += i;
      }
      str += "\n";
    }
    console.log(str);
    ```

10. Hollow square pattern

    ```js
    let str = "";
    for (let i = 1; i <= 5; i++) {
      for (let j = 1; j <= 5; j++) {
        if (i === 1 || i === 5 || j === 1 || j === 5) {
          str += "*";
        } else {
          str += " ";
        }
      }
      str += "\n";
    }
    console.log(str);
    ```

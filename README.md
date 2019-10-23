Steps to reproduce:

1. yarn
2. ng serve --aot
3. Open localhost:4300 in Chrome
4. Change font-size in _home.component.scss_ from 10px to 80px
5. Save the file

Result:

1. Font should be changed but it isn't
2. Only saving file for the second time reflects changes in the browser
3. Serving it using JIT works fine: ng serve
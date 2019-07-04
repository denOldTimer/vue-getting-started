[![vue][vue-logo]][vue-link]

[vue-logo]: https://vuejs.org/images/logo.png
[vue-link]: https://vuejs.org/

# My Vue.js lessons

Vue, The Progressive JavaScript Framework

First off these lessons are base upon the youtube crash course given by M. Schwarzmueller @ Academind : Getting Started with Vue.js

[![Academind][course-logo]][course-link]

[course-logo]: https://yt3.ggpht.com/a/AGF-l7-L1jJvOCpat-6U8PVblQ_cSowHb42QQubFSw=s48-mo-c-c0xffffffff-rj-k-no
[course-link]: https://www.youtube.com/watch?v=nyJSd6V2DRI&list=PL55RiY5tL51p-YU-Uw90qQH419BM4Iz07

## Lesson 1 - Setting Things Up

1.  Setting Things Up

    - Getting started using inline script that can be find on the vuejs.org.
    - Adding our css and js links to the index
      - Remember to add your app.js to the bottom of your html document just before the end body-tag
    - In the body add a div with the id of app so that vue can target this dom element as root.
    - And within the div a p-tag

2.  Setting up index.js and vue
    - create a VUE `new Vue()`instance and pass the object `{}`
    - add property : `el` (reserve word) to target root dom element type: string
    - add property : `data` (reseved word) type : Array `{}`
    - within data add a state : ex. `title` (not a reserve word)
      - title can contain html structure or just a string ex. 'Hellow World'
    - next add within the html dom where you want to show the data (title) using dubble curly braces like Blade

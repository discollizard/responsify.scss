# responsify.scss
## a quick and simple way to quickly responsify your web app using sass
***
## How to use
To use responsify, just declare the css rule you wish to alter, then the 4 values (in order: sm, md, lg, xl) that the rule will assume depending on the current screen size:
```
  @include responsify('font-size', 6vw, 5vw, 4vw, 3vw);
```

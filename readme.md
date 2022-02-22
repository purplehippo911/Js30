# JavaScript30 - My attempt at the challenge

Completed solutions for the JavaScript 30 Day Challenge.

![](https://javascript30.com/images/JS3-social-share.png)

Grab the course at [https://JavaScript30.com](https://JavaScript30.com)

## What I Learned

I was new to javascript and did'nt know what to build and this course transformed my javascript a bit more. I learned about DOM manipulation, functions, arrow functions, capture, event delegation, how to use objects and much more. NOw that I'm finished with this course I feel more confindent in my JS. I'm going to continue with making projects with JS with for example Frontend Mentor. I'm planning on becoming more confident with vanilla JS(normal JS), and then learn React.

## Some code I'm proud of

```js
function randomHole(holes) {
  const idx = Math.floor(Math.random() * holes.length);
  const hole = holes[idx];
  if (hole === lastHole) {
    console.log("Ah nah thats the same one bud");
    return randomHole(holes);
  }
  lastHole = hole;
  return hole;
}
```

## Author

![purplehippo911](https://github.com/purplehippo911)

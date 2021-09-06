# Sergey Serzhan

## Contact information:

:iphone: **Phone:** +375296415992
:email: **E-mail:** serzhansergey96@gmail.com
![Telegram icon](/telegram-icon.png) **Telegram:** @sergeyserzhan

## About myself:

My goal is to develop in front-end development. I have no work experience but I am able to learn quickly and am good at problem solving.

## Skills:

- HTML5
- CSS3
- JavaScript
- Git

## Code example:

**Human Readable Time**: Write a function, which takes a non-negative integer (seconds) as input and returns the time in a human-readable format (HH:MM:SS).

```javascript
function humanReadable(seconds) {
  let h, m, s;
  const isLessThanTen = function (num) {
    if (num < 10) return "0" + num;
    else return num;
  };
  h = Math.floor(seconds / 3600);
  seconds = seconds - h * 3600;
  h = isLessThanTen(h);
  m = Math.floor(seconds / 60);
  s = seconds - m * 60;
  m = isLessThanTen(m);
  s = isLessThanTen(s);
  return `${h}:${m}:${s}`;
}
```

## Education:

- HTML and CSS on [MDN Web Docs](https://developer.mozilla.org/ru/) and [YouTube](https://www.youtube.com/)
- JavaScript [Udemy course](https://www.udemy.com/course/the-complete-javascript-course/)

## English level:

**A2**

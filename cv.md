# Pavel Altov

## Frontend Developer

---

### Contact information

**Phone:** +375292588229

**E-mail:** Glucus2@yandex.ru

**Discord** Pavel Altov

**Slack** Pavel Altov

---

### About

My first commercial experience was in about 2005 when I was passionate about 3DS Max. I was translating some tutorials into Russian and got some projects to do. Unfortunately, the disappointment came rather quickly when I found out that most employers were looking a 3D modeller and an artist at the same time. I have never pretended to be an artist.

Next was a long-term career in a printing center. I entered as a complete beginner, and step by step has become a head of production department. Later I realized I have achieved everything I could in my current position. Plus with the development of remote services and jobs the industry is slowly dying.

So I decided to look for something perspective I can be good at, and discovered a frontend development. I have started with HTMLAcademy and then watched tons of courses and tutorials, realized some small projects. [Old good Pacman game realization]https://github.com/User0k/PacMan-online

---

### Tech skills:

* HTML
* CSS
* Javascript ES6+
* Webpack, Gulp
* Adobe Photoshop, Figma

**familiar with**
* React
* Bootstrap
* JQuery
* Node.js

---

### Code sample

**Maximum subarray sum (Codewars, 5kyu)** *The maximum sum subarray problem consists in finding the maximum sum of a contiguous subsequence in an array or list of integers*

```
const maxSequence = function(arr){
  let intermediate = 0, res = 0;

  for (let i = 0; i < arr.length; i++) {
    for (let j = 0; j <= i; j++) {
      intermediate = arr.slice(j, arr.length - i + j).reduce((a, b) => a + b);
      if (intermediate > res) res = intermediate;
    };
  };

  return res;
}
```
---

### Courses:

* [Современный JavaScript + Vue с нуля на реальных проектах](https://www.udemy.com/certificate/UC-31c76af1-6e98-44e7-b183-0b39ae7054a8/?utm_source=sendgrid.com&utm_medium=email&utm_campaign=email)
* [React course & last features by learn.javascript](https://learn.javascript.ru/courses/react-20210702/glucus2/en/certificate.jpg)
* in progress [NodeJS - The Complete Guide](https://www.udemy.com/course/nodejs-the-complete-guide)

---

### Languages:

*Russian - Native

*English - B1+
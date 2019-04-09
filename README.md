# Project: Mouseshadow

## About
I've been doing some form of web development for about seven years or so... mostly basic HTML, CSS and JavaScript. I've taken two of [Udacity's](https://www.udacity.com) nanodegree programs: Front End and Full Stack Web Developer. I have learned a lot from those courses but I know that there are situations and use cases that I haven't seen or been exposed to.

I recently heard about Wes Bos and also his 30 Day JavaScript challenge. It's a free course (at least during the writing of this) and it can be found here: [javascript30.com](https://javascript30.com)

This project is a practice in writing vanilla JavaScript and to learn about other use cases.

### View Project
[Click here to view the live project.](https://junclemente.github.io/j30-mouseshadow/)


#### Project takeaways
* `this` vs `e.target` - `this` is referencing the object in the eventListener (the thing that you listened on), ie: `hero.addEventListener('mousemouve', shadow)`. In this example, `e.target` is referencing the child of `.hero` (the thing that you triggered on) therefore, the value shown is close to (0, 0) when in the top-left corner of the `h1`.
* `offsetLeft`, `offsetTop`, `offsetWidth`, `offsetHeight`- These values can be used to grab the mouse location and then added, subtracted or combined in any which way to do other types of manipulations. 
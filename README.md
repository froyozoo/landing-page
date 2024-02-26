# landing-page
Flexbox Landing Page Project

Using all the knowledge I've learned from CSS and Flexbox lessons, I was to create a nice-looking layout of a landing page.

During my first go at it, I initially succeeded in the placement of all segments using flexbox. However, I could not figure out why the segments were not vertically spread out, as in my 

`body {
  display: flex;
  flex-flow: column;
  justify-content: space-between;
}`

was not working.

After asking on Discord, and remembering one of the previous exercises where `height: 100vh` was mentioned, I was able to resolve the problem, but not before I decided to start over from scratch with different class names and slightly more simplified.

Lesson learned!
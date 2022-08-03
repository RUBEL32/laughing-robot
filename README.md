
<!DOCTYPE html>
<html>
    <head>
        <title>Text animation</title>
        <style>
:root {
  --effect: hover 1s linear infinite;
}
*{
   margin:0;
}
body {
  display: flex;
  width: 100vw;
  height: 100vh;
  background: black;
  align-items: center;
  justify-content: center;
}
div {
  text-align: center;
}
p {
  display: inline-block;
  text-transform: uppercase;
  text-align: center;
  font-size: 4em;
  font-family: arial;
  font-weight: 600;
  transform: scale(.5);
  color: #121212;
  -webkit-text-stroke: 2px gray;
}
p:nth-child(1) {
  animation: var(--effect);
}
p:nth-child(2) {
  animation: var(--effect) .125s;
}
p:nth-child(3) {
  animation: var(--effect) .25s;
}
p:nth-child(4) {
  animation: var(--effect) .375s;
}
p:nth-child(5) {
  animation: var(--effect) .5s;
}
p:nth-child(6) {
  animation: var(--effect) .675s;
}
p:nth-child(7) {
  animation: var(--effect) .75s;
}
p:nth-child(8) {
  animation: var(--effect) .90s;
}
p:nth-child(9) {
  animation: var(--effect) .60s;
}
@keyframes hover {
  0% {
    transform: scale(.5);
    color: #121212;
    -webkit-text-stroke: 2px gray;
  }
  20% {
    transform: scale(1);
    color: pink;
    -webkit-text-stroke: 3px red;
    filter: drop-shadow(0 0 1px black)drop-shadow(0 0 1px black)drop-shadow(0 0 3px red)drop-shadow(0 0 25px red)hue-rotate(10turn);
  }
  50% {
    transform: scale(.5);
 color: #121212;
    -webkit-text-stroke: 2px gray;
  }
}
        </style>
    </head>
    <body>
    <div> 
  <p>V</p>
  <p>A</p>
  <p>I</p>
  <p>B</p>
  <p>H</p>
  <p>A</p>
  <p>V</p>
  <p>please Upvote</p>
</div>     
    </body>
</html

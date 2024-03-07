# 8-1 but for real this time
Apparently I can't read and I did Thursday's assignment for Tuesday instead of vice versa... oopsie 🤷‍♀️. But anyway here are random code strings/values I made up.

### String Concatenation, Coercion, and Template 
```
// using const to assign strings and primitive data types.
const firstName = "Rye";
const tombMessage = "Here lies ";
console.log(tombMessage, firstName);

// I can shake it up a bit with operators and coercion
const firstName = "Rye";
console.log ("Here lies " + firstName + " someone dropped a piano on their head");
// Or if I don't want to keep using coercion, I can use template literals and make things a bit more neat
console.log (Here lies ${firstName}, Born ${birthYear}. Died on ${deathYear} by ${causeofDeath};
//yes I know there isnt a causeofDeath string in here just roll with it
```
### Numbers, `const` and `let`
```
// Don't need quote marks and can do almost whatever I want with math magic. Numbers assigned with const can't be changed
const birthYear (2001);
// using let allows me to make a number that can be reassigned later. Who knows? I might come back from the dead and die later.
let deathYear (2024);
deathYear = null;
// We can use simple gradeschool math to figure out how many years I lasted

function totalYears (birthYear, deathYear) {
  return deathYear - birthYear;
}
// Theres multiplication "*" and division "/" but I don't think I can demonstrate those with these numbers. unless you want to divide the years I lived or multiply them for some reason.
// I'm not even going to pretend I know how to apply % in Javascript
```
### Booleans and the other operators
```
// Can be as simple as an off and on switch if you are lucky
const dead = "true"
const alive = "false"
// Unfortunately I have to mix it up. Can't just have raw booleans, I need to be able to determine the truth of the values, here's the AND boolean operations in the works.
const dead = true;
const alive = false;
const rotten = true;

const necrosis = dead && rotten; // true
const necrosis = alive && rotten; // false


// Usually people die when they are killed. And you really want them to not come back
console.log(dead +== alive);
// false
console.log(dead !== alive);
// true

// If you ever seen Return of the Living Dead, you don't HAVE to die to experience necrosis

const necrosis = dead || alive; // true
 // 245-Trioxin is one helluva chemical

// Again, you do NOT need to die to experience necrosis, but usually you don't want to be...

const necrosis = !alive;
// just the many ways you can write code of someone rotting 😌
```


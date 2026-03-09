1️⃣ What is the difference between var, let, and const?

 => var (The Old Way): It is function-scoped and can be re-declared. It has some "weird" behaviors like hoisting (it exists before the code even runs), which can lead to bugs.

let (The Modern Standard): It is block-scoped (lives only inside { }). Use this when you know a value will change later (like a counter).

const (The Default): Also block-scoped, but the value cannot be reassigned. Always use const unless you are certain the variable needs to change.


2️⃣ What is the spread operator (...)?

=> The spread operator "unpacks" elements from an array or objects. Imagine opening a bag of marbles and spreading them out on the table.


3️⃣ What is the difference between map(), filter(), and forEach()?

=> map() (The Transformer): It goes through every item, changes it based on your logic, and returns a brand new array of the same length.

filter() (The Bouncer): It checks every item against a condition. If it passes, it stays; if not, it's out. It returns a new array (usually shorter).

forEach() (The Worker): It just loops through the items and does something (like console.log). It returns nothing (undefined).


4️⃣ What is an arrow function?

=> Arrow functions provide a shorter syntax for writing functions. They are great for one-liners and handle the this keyword differently than traditional functions.


5️⃣ What are template literals?

=>  Template literals make it easy to join strings and variables without using a bunch of + signs. They use backticks (`) instead of quotes.
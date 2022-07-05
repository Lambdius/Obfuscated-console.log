### Obfuscated JS 💩

> The idea to write something like this came from two kata from CodeWars: [Task 1](https://www.codewars.com/kata/57f90a8d5cae44a9dc000091), [Task 2](https://www.codewars.com/kata/57f92db48b0760410a0001e7)

We know perfectly well that you can do magic in JavaScript, so we decided to create a function, without actually declaring it, which should output the phrase "JS is wierd" to the console, while we are forbidden to use letters and numbers.

**Step-by-step instruction:** 👣
1. Get letters: `[ c, o, n, s, t, r, u ]`.
2. Get the word `constructor`.
3. Is to get the `constructor` function property.
4. Get the letters: `[ B, f, e ]`.
5. Get the word `Buffer`.
6. Declare a variable `_` with the value of the `Buffer` object.
7. Get the letters: `[ l, i ]`.
8. Get the word `slice`.
9. Get the word `String` using the `slice` method.
10. Get the letters: `[ a, m, h, C, d ]`.
11. Declare a variable `__` with the value of the method `String.fromCharCode`.
12. Get the letter: `[ g ]`.
13. Overwrite the `_` variable with the new value of the `console.log` method.
14. Put it all together.

---

**You can try to deobfuscate this code with online JS deobfuscators:** 😅
- [deobfuscate.io](https://deobfuscate.io/)
- [de4js](https://lelinhtinh.github.io/de4js/)
- [codeamaze](https://codeamaze.com/code-beautifier/javascript-deobfuscator)
- And many others...

---

> To start, use the command - `npm start`
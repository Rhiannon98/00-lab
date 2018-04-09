# 1-ES6-practice

## Feature Tasks

Follow these instructions carefully and in order.

1. Open the HTML file in the browser to ensure that it works.
2. Turn all `var` variable declarations into `let`.
3. After you do, there will be one error. Find that line in the code, delete that line and respond to the adjacent TODO item.
4. Return to the browser to ensure that the code works again.
5. **Save the code, and do a Git "add" and "commit".**
6. Now, in the code, convert all `let` variable declarations into `const`.
7. Bugs will erupt everywhere. Debug by using the error messages in the browser console, turning `const` declarations back into `let` where necessary. Expect there to be some back-and-forth between your code editor and your browser.
8. When you think you have things working, clear local storage and reload the page to ensure that the code still works when starting from a totally clean state.
9. **Save the code, and do a Git "add" and "commit".**
10. Now find all concatenations in the code and convert them into template literal notation.
11. Reload the browser to ensure that the code works as expected.
12. **Save the code, and do a Git "add" and "commit".**
13. Answer the following questions:

---

##### Investigate how `let` and `const` are now used in the code. Where did you need to convert `const` into `let` to make the code work? Can you identify any patterns/similarities?

(My answer here)

Wherever there was an instance of any type of loop with the variable `i` there had to be a `let` stated. `i` in this case is changing in order for the loop to run properly, therefore using a `const` would provide an error. Some of the global variables that were either arrays being filled or being redefined or added to needed to be changed to `let` as well. I always had the ability of changing every variable to a `let` and the code still being able to function just the same. 

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

(My answer here)

Honestly, the template literal notation makes more sense to my head to read everything. It formats it as though we are implementing tools from a word document. Not having to add awkward breaks to have a new line start is pretty great. Also, looking back now at the 201 work seems like a long road into the same effect if I were to use jQuery. So knowing that this was always an option is honestly really aggrevating thanks to all the headaches JavaScript caused me and my fellow peers.
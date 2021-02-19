# Unlock-Synoriq

## Git and GitHub Beginner
Playlist Link:[https://www.udemy.com/course/react-the-complete-guide-incl-redux/learn/lecture/13556100](https://www.udemy.com/course/react-the-complete-guide-incl-redux/learn/lecture/13556100)

1. [Introduction](#Tutorial-1)
2. [What is React?](#Tutorial-2)
3. _
4. [Real-World SPAs & React Web Apps](#tutorial-4)
5. [Writing our First React Code](#tutorial-5)
6. [Why Should we Choose React?](#tutorial-6)
7. [React Alternatives](#tutorial-7)
8. [Understanding Single Page Applications and Multi Page Applications](#tutorial-8)
9. [Course Outline](#tutorial-9)
10. [How to get the Most out of This Course](#tutorial-10)
11. [Useful Resources & Links](#tutorial-11)
12. [Module Introduction](#tutorial-12)
13. [Understanding "let" and "const"](#tutorial-13)
14. [Arrow Functions](#tutorial-14)
15. [Exports and Imports](#tutorial-15)
16. [ Understanding Classes](#tutorial-16)
17. [Classes, Properties and Methods](#tutorial-17)
18. [The Spread & Rest Operator](#tutorial-18)
19. [Destructuring](#tutorial-19)
20. [Reference and Primitive Types Refresher](#tutorial-20)
21. [Refreshing Array Functions](#tutorial-21)
22. [Wrap Up](#tutorial-22)
23. [Next-Gen JavaScript - Summary](#tutorial-23)
24. [JS Array Functions](#tutorial-24)
25. [Module Introduction](#tutorial-25)
26. [The Build Workflow](#tutorial-26)
27. [Using Create React App](#tutorial-27)
28. [Understanding the Folder Structure](#tutorial-28)
29. [Understanding Component Basics](#tutorial-29)
30. [Understanding JSX](#tutorial-30)
31. [JSX Restrictions](#tutorial-31)
32. [Creating a Functional Component](#tutorial-32)
33. [Components & JSX Cheat Sheet](#tutorial-33)
34. [Working with Components & Re-Using Them](#tutorial-34)
35. [Outputting Dynamic Content](#tutorial-35)
36. [Working with Props](#tutorial-36)
37. [Understanding the "children" Prop](#tutorial-37)
38. [Understanding & Using State](#tutorial-38)
39. [Props & State](#tutorial-39)
40. [Handling Events with Methods](#tutorial-40)

###### Tutorial 1
* React is a JS Library.
* Use to creates Web apps as well as mobile apps.
###### Tutorial 2
* React is a JS Library used to create UI.
###### Tutorial 4
* In react we work on components.
###### Tutorial 5
* We use `render` function to render javascript componentto real dom.
* we have `className` to use a block as a class.
* Components save our time as we can make them dynamically.
* react have props that helps to give all the attribute during rendering a function.
* `{props.attributeName}` to use props property.
###### Tutorial 6
* We can easily write complex code.
* React saves our time.
###### Tutorial 7
* Angular, VUE, JQuery, 
###### Tutorial 8
* We have to type of application 1st Single Page and 2nd Multi Page Application.
###### Tutorial 9
* Course Outline
###### Tutorial 10
* Continous coding
###### Tutorial 11
* documentation: https://reactjs.org/
###### Tutorial 12
* latest javascript
###### Tutorial 13
* var is older version
* let and const are latest.
* we use let for variable values.
* we use const for fixed values.
* Give TypeError if we try to change const value.
###### Tutorial 14
* Syntax of arrow function
```js
const myFunc = () => {
    ...
    }
```
* this keyword don't give any issues in arrow function
###### Tutorial 15
* we can import or export any function of any file to any other file.
* export syntax `export default funcName` or `export const varName = value`
* In case of function our import syntax looks like `import funcName from filePath` and in case of variable our import syntax looks like `import { varName } from filePath`.
###### Tutorial 16
* class contains property and methods.
* we can create constructor.
* we can use inheritance in class.
* to call class we need to store it in a const variable.
* we need to use `super();` function to call parent class.
###### Tutorial 17
* we can skip the constructor function in ES7.
* ES7 have arrow function to declare a method.
###### Tutorial 18
* Spread operator is used to split array or object properties.
* syntax `...`
* Merge operator is used to merge array/list.
* syntax `...`
###### Tutorial 19
* Destructing easily extract array/object propoerty and store that in a variable.
###### Tutorial 20
* Object reference the value (copy the pointer).
###### Tutorial 21
* map is used to map previous array element with new one.
###### Tutorial 22

###### Tutorial 23
* MDN Documentation: [ https://developer.mozilla.org/en-US/docs/Web/JavaScript/]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/)
###### Tutorial 24
* JavaScript array functions like map() , filter() , reduce()
###### Tutorial 25
###### Tutorial 26
* Need to optimize code
* Use Next-Gen JS Features.
* Use dependency management tool like npm and yarn.
* Use Bundler like webpack.
* Advance compiler.
* Development Server.
###### Tutorial 27
* use `npm install -g create-react-app` to install create-react-app library globally in system.
* use `create-react-app appName` to install all necessary files.
* use `npm start` inside the project directory to run the code on localhost. Then open [http://localhost:3000](http://localhost:3000).
###### Tutorial 28
* check all installed dependencies in package.json file.
* Also you can check some scripts there.
* React projects contain only 1 html file.
###### Tutorial 29
* Use render() method to render anything on screen.
* We export as an default export.
###### Tutorial 30
* render functioning in jsx.
###### Tutorial 31
* We can't use class.
* We need to add any content in a single root element.
###### Tutorial 32
* Function syntax
```js
const funcName = (argumentList) => {

}
```
###### Tutorial 33
* JSX is NOT HTML but it looks a lot like it
###### Tutorial 34
* We can reuse any component.
###### Tutorial 35
* If we want something to treat as JS then we need to wrap inside curly braces.
###### Tutorial 36
* we use `props` which is used for all the properties.
###### Tutorial 37
* use `props.children` to print other content we didn't stored in variable. 
###### Tutorial 38
* We use state property to make it easier code.
* To call any state property our syntax is `this.state.propertyName`.
###### Tutorial 39
* props  allow you to pass data from a parent (wrapping) component to a child (embedded) component.
###### Tutorial 40
* Use `onClick={this.handlerName}` to change the state.

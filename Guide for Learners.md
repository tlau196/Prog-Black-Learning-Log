# Guide to TypeScript and an Introduction to Rust and Actix Web

## Motivation
---
It's always good to know why you should learn something before learning it, and this is particularly important for TypeScript and Rust. To begin with they may seem to be two completely unrelated languages and you may even see little point in TypeScript considering it does everything that JavaScript can do with nothing but extra steps, but I assure you there is a place for TypeScript and Rust is not a language incompatible with the web.

To begin TypeScript is an extension to JavaScript that is statically typed. This means that it has extra syntax on top of JavaScript allowing for the use of types. JavaScript's lack of types and type safety often makes it difficult to know what types of data are being passed, this can lead to very confusing situations such as functions accepting and operating on values that are not even the type that you intended to be used in that function. Typescript fixes this by allowing programmers to specify what type each variable should be and what type the arguments of functions should be.

Rust on the other hand is a completely different language which functions at a much lower level than JavaScript. The motivation here for using it is it's much lower resource usage compared to JavaScript. When we use Rust with a module called Actix web, we are able to write a back end web REST API where API calls are much faster compared to their equivalent JavaScipt solution.

Aside from Rusts advantages over JavaScript it also reasons you may want to use it over other languages of similar speed and closeness to low level languages such as C++. It is safer than languages such as C and C++ due to features such as built in memory management including a garbage collection system, all while maintaining speed.

When paired together the combination make for a very good way create faster web apps.

## Prerequisites
--- 
### For Typescript
Before learning TypeScript it is a very good idea to learn JavaScript due to the fact that TypeScript is simply a syntactic addition to JavaScript. Due to the purpose of Below are some good resources for JavaScript:
- [MDN Web Docs - JavaScript ](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [W3 Schools - JavaScript](https://www.w3schools.com/js/default.asp)

MDN Web Docs is more suitable for people who are already quite familiar with programming and provides a complete guide to web development using JavaScript, HTML, and CSS.

W3 Schools is more suitable to people who are maybe less familiar with programming, it also comes with small exercises to test knowledge and teaches the language in a which anyone from beginners to advanced programmers can understand with ease.

Before starting along the path to programming in TypeScript and using Rust Actix web it is also a requirement to know HTML and as these are the foundation to front end web apps. I recommend also learning these from the sites above. Links to their HTML/CSS guides are below:
- [MDN Web Docs - HTML and CSS](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML) 
- [W3 Schools - HTML and CSS](https://www.w3schools.com/html/default.asp)

Although not required I would also recommend utilising the bootstrap framework. This is a web front end framework which comes as a set of CSS and JavaScript files. When used in front end HTML it can easily make your website look a lot nicer with menu bars, animations and more!

- [Bootstrap Docs](https://getbootstrap.com/docs/5.2/getting-started/introduction/)
- [W3 Schools - Bootstrap Guide](https://www.w3schools.com/bootstrap5/index.php)

If you have never done any web development before I would definitely recommend reading and working through the MDN web docs guides.

### For Rust
Although you could in theory learn Rust without having much prerequisite knowledge, Learning Rust will be very difficult. I would definitely recommend learning some other general purpose programming languages before Rust. These include languages such as Python, C#, C++, Java, C and other similar languages. 

Prerequisite knowledge in C or C++ would be particularly helpful as they are quite similar languages, especially when it comes to their complexity and ability to manipulate memory. That said if you do not know C or C++ and want to learn Rust I would not recommend learning them as a prerequisite (Rust is a language which aims to replace languages like C and C++).

If you are not very familiar with programming I recommend starting from a simpler language such as python which you can start learning from the links below:
- [W3 Schools - Python](https://www.w3schools.com/python/default.asp)
- [Codecademy](https://www.codecademy.com/catalog/language/python)

Codecademy here is another great general resource for new programmers to learn a multitude of languages by interactively writing small programs to learn new concepts and syntax. So if you are someone who learns better by doing then I recommend this site.

## Learning Materials
---
### TypeScript
Below or some helpful resources for learning TypeScript:
- [W3 Schools - TypeScript](https://www.w3schools.com/typescript/index.php)

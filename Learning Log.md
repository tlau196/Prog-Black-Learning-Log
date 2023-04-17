# Learning Log

## 27.3.2023: Typescript and finding a project
Over the last two weeks I have began to learn typescript and the basics of rust. This is in preparation of working on a collaborative website designed for the badminton society at Durham. Most of the javascript for the project will be written in Typescript and the back end will be written in rust. I been learning rust through the online book [The Rust Programming Language](https://doc.rust-lang.org/book/). 

So far I have been able to cover variables, variable mutability, data types, and functions along with rust ownership and structs. I have also been translating some of my existing python programs from previous projects and assignments into rust for practice. On the Typescript side I have been learning from [w3schools](https://www.w3schools.com/typescript/typescript_object_types.php). So far Object types, arrays, tuples and enumerated values have been covered.

My goals for this project are to successfully write front end client side fetch API in typescript and be able to modify and add functionality to a REST API written in rust. The collaborative website will be for members of the badminton society to be able to create profiles for themselves and record their games and opponents. Through this we will be able to implement an elo system creating a general approximation of how good a player is. I plan to handle most of the front end html and javascript however we may decide to switch the fetch API to also be written in rust.

## 3.4.2023: More Rust and Starting project
Over this week I have learnt more Rust going back over to get a better understanding of Rust ownership concerning pointers and Rust's built in garbage collection system, most of which was learnt from the rust programming language book. This was mostly done between Monday and Wednesday. Most of the rest of the week was spent starting working on the website project. Most of this work was just creating a dashboard type html template page where users can see their profile statistics, these include: ELO, recent games and more.

The template page I built using bootstrap has helped develop my knowledge in how to use bootstrap grids and containers to lay out elements on the page. So far the information on the page such as games and user elo are just stand in text as I have not started doing the front end javascript. Much of the lack of actual functionality at the moment is also due to the current lack of a back end API.

The current next steps for me are to practice and familiarise myself more with typescript so I can start working on the clientside fetch API as soon as some of the back end rust API is implemented and functional. There have been no changes to my final goal of helping produce a functional front end web page and typescript fetch API.

## 10.4.2023
Over this week I have started working more in typescript rewritting some of the javascript files from my first programming black assignment to familiarise myself with typescript. I have also started rewritting my SAT solver, from the Computational Thinking summative assignment, to further develop my ability to code in RUST. I have found rewritting code I have written before in other languages a good way to learn new languages as I can concentrate more on the syntax of the language and ways to utilise features of the languages, such as statically typed variables and pointers/refferences, instead of having waste time thinking about problem solving and algorithms.

Concerning the collaborative project I'm working on I have added more features to the page such as a functional graph of elo over time and started some work on a simple generic fetch API. I can't start work on a solid fully functional fetch API yet as I still need to wait on the back end of the site to be pushed to the git repository. So nothing has changed in terms of my goals for this week of contributions to the project.

My current plan for the rest of this week are to keep on rewritting my SAT solver in RUST and to keep working on creating a generic fetch API which I can quickly adapt to work with the backend rust server when it is pushed and working. I will also try and utilise bootstrap more to create a more dynamic profile page for users of the site allowing for user customisation of what information each user wants to be seen on their profile and the order in which they want the information to be seen.

Also note that the reason the reason behind the mismatched git commit dates and the commit dates on Github are due to a error with pushing to Github that I didn't notice until trying to push today's log.

## 17.4.2023
Due to the incompletion of the server side API I am still yet to properly implement a fetch API and DOM manipulation typescript for changing the contents of the user profile page depending on the user signed in. There is also no currently functional way of checking for hashes and no login page which has stopped me implementing a way to route users to their respective profile pages after they have been logged in. Fortunately I have still found more ways I can contribute despite this, by utilising a site called moqups I have been able to help redesign the UI for the user page slightly. This has resulted in a nice, but unfortunately not functional, design for the profile page. Due to this being a simply a design and not actually written in html it has not been pushed to the GitHub repo.

I have also decided to continue learning rust and typescript, again by rewriting previous code I have written in other languages. In addition to this I have started my guide for learners and hope to have this completed by the end of this week.

My current plan for this rest of this week is to continue working on, and hopefully complete my guide for learners.

## Start of My Journey

When I first started my computer science journey in early 2017, I understood and practiced simple computer tasks. Still, I did not fully comprehend just how sophisticated and inspiring computer science is. I started learning Python, a comfortable and forgiving language to learn. Python exposed me to the fundamental concepts of any language, data types, variables, etc. Then I ran into the for and while loops. In short, loops wrecked my world, not because I didn’t understand what they were or their purpose, but I didn’t understand how or why they worked. That is when I fell down the hypothetical rabbit hole. I am an individual that has a burning desire to understand the world around me. At ten years old, I took the family computer and broke it down to every last screw, and then I attempted to reassemble it. Seeing the computer on the surface wasn’t good enough for me; I needed to understand what was inside that made the computer work. Python, being as mysterious as it was, became my new target. That trend would continue through my professional exploration of computer science. Because of how massive the field is, I know I will continue developing my knowledge and myself.
	
## What Did I Learn?

###### Teamwork and Collaboration

I learned that software engineers do not work alone; codebases, especially those in large projects, have many dynamics that need to integrate into synergetic harmony. It requires too much effort for one person to be effective in an environment with strict deadlines and quality control concerns. As such, with the insertion of multiple developers, codebases can get messy. Teams need to have a useful paradigm and business processes to provide results regularly. I perform work based on the AGILE methodology and used version control software Git to organize the code. I had the opportunity to explore multiple roles, including developer, tester, scrum master, and even a product manager. Utilizing Git, I obtained first-hand experience working on remote repositories. I made pull requests, created developmental branches, created new features, pushed code back to the repository, and reviewed other collaborators’ code before merging new code into the master branch.
    
###### Communication to Stakeholders
    
Not everything task I have performed included technical skills. I learned that clients and investors play a significant role in the developmental process. Software teams need to communicate with their clients to produce user requirements consistently and effectively; in the agile methodology, this process leads to user stories, a tool to develop functionality in software. Developers can create elaborate programs with all of the bells and whistles, but if that program does not meet the client’s needs or is too complicated to use, it is virtually useless. After all, what is the purpose of a business that does not satisfy its clients’ needs? 
    
###### Data Structures and Algorithms
	
The topic with the most demanding needs of cognitive ability was data structures and algorithms. Nearly every function produced in a programming language fits the algorithm’s definition as a set of instructions for a computer to interpret. The particular algorithms and data structures I studied were of unified importance to software development and laid a foundation to produce even more complicated, useful, and efficient algorithms in the future. To build this foundation, I utilized the C++ language as its low-level architecture was immensely helpful to create a deep understanding of how the computer interprets instructions, including managing the computer’s RAM, which is handled automatically by many higher-level languages. 
	
The efficiency of an algorithm is measured by how effectively the algorithm can scale with large inputs. There are two factors that a developer needs to consider when developing an algorithm: time complexity and space complexity.  Software engineers use Big “O” notation to demonstrate time and space complexity. For example, O(1) and O(log n), known as constant and logarithmic time, is considered to scale effectively with large datasets. On the other hand of the spectrum, O(n^2) and O(n!) (exponential and factorial) rise drastically with a large dataset and are not considered practical in most cases. Unfortunately, this may lead to a trade-off between time and space. Does this program need to be fast to process large amounts of data? Or does the program need to conserve space in memory? It is up to the developer to produce an algorithm that will best fit the organization’s needs or client. These are just a few of the reasons I find data structures and algorithms one of the most intriguing topics in computer science
    
###### Software Engineering and Databases
	
The critical marker between a simple script and a fully functioning proper application is the relationship between software programs and databases. Programs run on the computer’s RAM, which is thought of as volatile memory as it deletes itself when the program restarts. For the program to be more useful, it can use persistent memory, meaning the memory will save even after a restart. The way to engineer this design is to link the program to a database. Many databases are available, but the most common ones are structure query language(SQL) or non-structured query language(No-SQL). SQL utilized a table-like architecture, like an Excel spreadsheet, to structure data, while No-SQL uses documents similar to objects in most programming languages. Online forums have heavily debated as to which one is the best. Still, they both have advantages and disadvantages and deserve deep consideration when choosing a database.
    
###### Security
    
There is one more topic that does need addressing, security. As the world’s individuals become more integrated with technology, there lies the potential to exploit holes in programs’ security. The prospect of the exploitation of private information is a massive concern for me. Security is a topic of enormous scale, and there are many techniques in play to kept information secured. There are techniques that a software engineer can employ that will help security. The first line of defense for a software engineer is to validate user inputs. Software is particularly vulnerable at any point where a hacker could send code to the program.  So a developer should never trust user input and always validate the data coming in.
	
###### Conclusion
	
I have tried to summarize what I have learned during my time in the computer science program, but even a summary does not elaborate on the details I consider essential. Let it be known that this summary does not effectively document everything I have learned over the years. It will take many more pages and then possibly a publisher to demonstrate the knowledge I have gained. Hopefully, it does justice enough, and I am forever grateful for the exposure and professional development.
	
## Code Review Example

 <iframe width="420" height="315"
src="https://youtu.be/b2YMmRToSyE">
</iframe> 

There are some obvious and not-so-obvious benefits of conducting code reviews. The first benefit of working on regular code reviews is that you will become a better developer. Mistakes in the code will be brought to your attention, and you will learn why it is a mistake and possibly learn a better solution to the initial problem. Other benefits include a more consistent design of the code base, better team building, and team members’ confidence. Some people may find that conducting code reviews takes too much time out of their day, but this is a destructive mindset. Not conducting a code review will significantly increase the chance that a major bug will be introduced in the program’s production and substantially damage investors’ reputation and financial security. Not to mention and take more time to find and fix the same bug. These consequences could be avoided if the bug was found in the SDLC development phases. This is why code reviews are considered a best practice.
 
## Test-driven Development Example

[View Source Code on Github](https://github.com/Lucci-k/medical-receptionist-jest-example)

The original artifact was created in August 2020. It was a buggy Java Maven projected intent to use medical receptionists to log patient’s history. As the students, we were tasked with writing test cases using the Junit library to expose bugs in the project to make it function as intended.
	
###### Inclusion

I have several reasons I had decided to include this project in my portfolio. I wanted to showcase my ability to think about the SDLC, particularly my knowledge of the importance of testing code. My original test cases back in 2020 were rather sloppy and hastily done. The enhancements I had made shows a much deeper understanding of the test first paradigm. 

###### Enhancements and Challenges

The core of this project was to use Jest to write test cases, and that is where I faced my first challenges. Jest was unfamiliar territory, so I began studying the documentation https://jestjs.io/en/ to understand the structure of writing the test cases and learn the most common methods I will be using. Including test(), expect(), toBe(), toContain(), toContainEqual(). I also learn how to install it by using NPM, which was a simple enough process. Learning the Jest syntax was straightforward, but analyzing my older code to find faults in my logic was much more beneficial than learning new syntax. I then had to translate my old Java code into JavaScript. 

I found out rather quickly that JavaScript has many downsides if you plan to use it in an object-oriented paradigm, which this project was. Most notably, the inability to have a true private variable for encapsulation. Though I am not as familiar with it, JavaScript appears to be better adept for functional programming. Even so, I carried on anyway. JavaScript is also a loosely typed language, and there was a couple of occasions I had to deal with data type errors. TypeScript may have been beneficial in this project as well. 

Writing the tests first was a goal of mine, but I did run into issues doing this. I was not always sure what would need to be returned from the class methods, so I gave my best approximations. This process resulted in me revisiting most of my test cases to rewrite what was actually being returned from the project’s methods. My future recommendation to remedy this is to create UML graphics to organize better how the code should interact. I feel I can save much more time and frustrations doing the coding process by doing more planning.

## Dijkstra's Algorithm Example

[View the Project in Action] (https://dazzling-turing-b3d4c3.netlify.app/)

[View Source Code on Github](https://github.com/Lucci-k/medical-receptionist-jest-example)

I first started this project at the beginning of February 2021. It is an implementation of Dijkstra’s algorithm, also known as the shortest path algorithm. Dr. Edsger W. Dijkstra made the algorithm in 1956 while having coffee with his fiancé in Amsterdam. The algorithm is useful to find the shortest distance between two nodes. Nodes are data structures that are referenced together in a graph. A graph is a collection of nodes that may be directly or indirectly referenced together.  

I implemented the algorithm in a simple web app that is not too pretty currently. The app allows you to create “walls” to impede the algorithm. The user can then watch algorithm navigation around the walls to find the shortest distance between the start node and finish node.

For this artifact, I opted to use React, a JavaScript library that uses a JSX language that uses HTML-like syntax. I choose to use React because native JavaScript, HTML, CSS proved to be taking a long time to implement this project. I decided to dump what I have produced to save some time in the long run.

###### Inclusion

This project has been something I have wanted to invest in for quite some time. I believe the combination of JavaScript, React, and Dijkstra’s algorithm showcase skills in multiple areas. Furthermore, this project will allow someone to interact with the algorithm. It has the potential to be more engaging for a person as they can change the board for the algorithm to navigate and see the algorithm do its work versus just looking at some lines of codes and seeing the output.  

###### Enhancements and Challenges

There is much potential to improve this project. CSS is minimal, and so far, it is only used to the visual nodes (the graph) in the correct shape. The app can be made much prettier in the future. I implemented not-so-efficient functions in the project. For example, there are two nested “for” loops in the code, which is terrible because they are running exponentially. The code needs to be refactored. The nodes are also stored in an array, and the algorithm has to sort through the arrays continually. A heap could potentially be a better replacement for the arrays. 

One of the main frustrations I faced in this project was breaking down how to implement the algorithm. There are numerous sources on the web that explain what the algorithm does in varying complexity. Unfortunately, I didn’t find any good step-by-step sources. I want to write a blog or post on a forum an easy-to-understand guide on implementing this algorithm in the future. Hopefully, that guide will help someone in my shoes in the future.

## RESTful API with NodeJS	

I create the original version of version of this project in August 2020. In the original version. The project was a back-end that took HTML GET, POST, PUT, and DELETE requests through an URL. From there, the API made a connection to a Mongo database to retrieve data for the user. The API was written in Python with the PyMongo and Bottle frameworks. This newer version is written in NodeJS and uses the Express framework and the MongoClient driver. Unlike the old one, the new API uses query parameters, which can be retrieved from HTML forms from the front end. There are also other improvements made, which are detailed later in this document.

###### Inclusion
	
I have decided to include this API in my online portfolio to showcase my knowledge of back-end systems. I realize that the third enhancement asked for a project with databases, but I feel working with databases in isolated conditions is not immensely helpful in the real world. By making an API, I can prove my ability to interact with a database through an outside entity and create the infrastructure required for a back-end system.  

###### Enhancements and Challenges

[View Source Code on Github](https://github.com/Lucci-k/rest-server-NodeJS-Example)

While creating this API and review the original version, I found many areas for improvement. I decided to change the language to NodeJS because it is a more popular language written for back-ends. The native HTML driver felt somewhat ugly to me, so I decided to include the express library to make the project more comfortable to read and understand. I also choose to make variable names more descriptive and refactor repeated code where possible. I kept the API relatively small and made just enough functions to demonstrate the ability to make different requests. There plenty of room to further expand the API to create more functionality. For example, I could create more ways to search for properties with different parameters.
	
The original version of the project did not make use of query parameters. I decided to make sure to take use query parameters for the potential of being able to extract the parameters from an HTML form in the future. I even thought about including a simple front end to interact with the API, but I decided against it to save some time. Another improvement I made was I put the Mongo database on the cloud. In the last project, everything was localized and isolated from any networks, which is not particularly useful for a proper application. 
	
I confronted one error that was a particular issue for me. When using the aggregate method from MongoClient, I kept receiving a cursor object reference error. I resorted to stackoverflow.com to understand what was happening. I learned that this error occurs when two objects reference each other, which creates a cyclic reference. I am still wrapping my head around where the cycle was happening in the code. What I did know at the time was that the aggregate function was returning a cursor object, and that was the method giving me issues. I learned the cursor object was iterable, so I decided I should iterate through the object and push each element to an array, thinking that an array is not an object and thus I would not receive the error. I was guessing here, but the solution did work, and I could get the data I was looking for in the end. I believe that this issue is because of the JavaScript engine, as I do not recall having this issue with Python.


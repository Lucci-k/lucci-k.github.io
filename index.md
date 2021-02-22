## Start of My Journey

    When I first started my computer science journey in early 2017, I understood and practiced simple computer tasks. Still, I did not fully comprehend just how sophisticated and inspiring computer science is. I started learning Python, a comfortable and forgiving language to learn. Python exposed me to the fundamental concepts of any language, data types, variables, etc. Then I ran into the for and while loops. In short, loops wrecked my world, not because I didn’t understand what they were or their purpose, but I didn’t understand how or why they worked. That is when I fell down the hypothetical rabbit hole. I am an individual that has a burning desire to understand the world around me. At ten years old, I took the family computer and broke it down to every last screw, and then I attempted to reassemble it. Seeing the computer on the surface wasn’t good enough for me; I needed to understand what was inside that made the computer work. Python, being as mysterious as it was, became my new target. That trend would continue through my professional exploration of computer science. Because of how massive the field is, I know I will continue developing my knowledge and myself.
	
## What Did I Learn?

### Teamwork and Collaboration

    I learned that software engineers do not work alone; codebases, especially those in large projects, have many dynamics that need to integrate into synergetic harmony. It requires too much effort for one person to be effective in an environment with strict deadlines and quality control concerns. As such, with the insertion of multiple developers, codebases can get messy. Teams need to have a useful paradigm and business processes to provide results regularly. I perform work based on the AGILE methodology and used version control software Git to organize the code. I had the opportunity to explore multiple roles, including developer, tester, scrum master, and even a product manager. Utilizing Git, I obtained first-hand experience working on remote repositories. I made pull requests, created developmental branches, created new features, pushed code back to the repository, and reviewed other collaborators’ code before merging new code into the master branch.
    
### Communication to Stakeholders
    
    Not everything task I have performed included technical skills. I learned that clients and investors play a significant role in the developmental process. Software teams need to communicate with their clients to produce user requirements consistently and effectively; in the agile methodology, this process leads to user stories, a tool to develop functionality in software. Developers can create elaborate programs with all of the bells and whistles, but if that program does not meet the client’s needs or is too complicated to use, it is virtually useless. After all, what is the purpose of a business that does not satisfy its clients’ needs? 
    
### Data Structures and Algorithms
	
    The topic with the most demanding needs of cognitive ability was data structures and algorithms. Nearly every function produced in a programming language fits the algorithm’s definition as a set of instructions for a computer to interpret. The particular algorithms and data structures I studied were of unified importance to software development and laid a foundation to produce even more complicated, useful, and efficient algorithms in the future. To build this foundation, I utilized the C++ language as its low-level architecture was immensely helpful to create a deep understanding of how the computer interprets instructions, including managing the computer’s RAM, which is handled automatically by many higher-level languages. 
	
    The efficiency of an algorithm is measured by how effectively the algorithm can scale with large inputs. There are two factors that a developer needs to consider when developing an algorithm: time complexity and space complexity.  Software engineers use Big “O” notation to demonstrate time and space complexity. For example, O(1) and O(log n), known as constant and logarithmic time, is considered to scale effectively with large datasets. On the other hand of the spectrum, O(n^2) and O(n!) (exponential and factorial) rise drastically with a large dataset and are not considered practical in most cases. Unfortunately, this may lead to a trade-off between time and space. Does this program need to be fast to process large amounts of data? Or does the program need to conserve space in memory? It is up to the developer to produce an algorithm that will best fit the organization’s needs or client. These are just a few of the reasons I find data structures and algorithms one of the most intriguing topics in computer science
    
### Software Engineering and Databases
	
    The critical marker between a simple script and a fully functioning proper application is the relationship between software programs and databases. Programs run on the computer’s RAM, which is thought of as volatile memory as it deletes itself when the program restarts. For the program to be more useful, it can use persistent memory, meaning the memory will save even after a restart. The way to engineer this design is to link the program to a database. Many databases are available, but the most common ones are structure query language(SQL) or non-structured query language(No-SQL). SQL utilized a table-like architecture, like an Excel spreadsheet, to structure data, while No-SQL uses documents similar to objects in most programming languages. Online forums have heavily debated as to which one is the best. Still, they both have advantages and disadvantages and deserve deep consideration when choosing a database.
    
### Security
    
    There is one more topic that does need addressing, security. As the world’s individuals become more integrated with technology, there lies the potential to exploit holes in programs’ security. The prospect of the exploitation of private information is a massive concern for me. Security is a topic of enormous scale, and there are many techniques in play to kept information secured. There are techniques that a software engineer can employ that will help security. The first line of defense for a software engineer is to validate user inputs. Software is particularly vulnerable at any point where a hacker could send code to the program.  So a developer should never trust user input and always validate the data coming in.
	
### Conclusion
	
    I have tried to summarize what I have learned during my time in the computer science program, but even a summary does not elaborate on the details I consider essential. Let it be known that this summary does not effectively document everything I have learned over the years. It will take many more pages and then possibly a publisher to demonstrate the knowledge I have gained. Hopefully, it does justice enough, and I am forever grateful for the exposure and professional development.
	
## Code Reviews

 <iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe> 

	There are some obvious and not-so-obvious benefits of conducting code reviews. The first benefit of working on regular code reviews is that you will become a better developer. Mistakes in the code will be brought to your attention, and you will learn why it is a mistake and possibly learn a better solution to the initial problem. Other benefits include a more consistent design of the code base, better team building, and team members’ confidence. Some people may find that conducting code reviews takes too much time out of their day, but this is a destructive mindset. Not conducting a code review will significantly increase the chance that a major bug will be introduced in the program’s production and substantially damage investors’ reputation and financial security. Not to mention and take more time to find and fix the same bug. These consequences could be avoided if the bug was found in the SDLC development phases. This is why code reviews are considered a best practice.
 
## Artifact

[View on Github](https://github.com/Lucci-k/medical-receptionist-jest-example)

	The original artifact was created in August 2020. It was a buggy Java Maven projected intent to use medical receptionists to log patient’s history. As the students, we were tasked with writing test cases using the Junit library to expose bugs in the project to make it function as intended.
	
## Portfolio Inclusion

	I have several reasons I had decided to include this project in my portfolio. I wanted to showcase my ability to think about the SDLC, particularly my knowledge of the importance of test code critically. My original test cases back in 2020 were rather sloppy and hastily done. The enhancements I had made shows a much deeper understanding of the test first paradigm. 
	
## Objectives

The following is a list of my planned objectives for my enhancements of this project:

-Create more robust test cases.
-Build knowledge in another popular testing library.
-Convert the original project to JavaScript. 
-Build test cases before writing the project’s code.
-Improve the readability and comments of the code.

	These are all the objectives I have accomplished. There is one small exception. I did not build a CLI or a GUI for a user to interact with the project. The reason for this is that this project was much more time consuming than what I was able to allot to it. My core objectives were still met, and I believe the project’s state shows my ability to write tests well enough. At this point, my time will be better spent working on my other due enhancements.

## Enhancements and Challenges

	The core of this project was to use Jest to write test cases, and that is where I faced my first challenges. Jest was unfamiliar territory, so I began studying the documentation https://jestjs.io/en/ to understand the structure of writing the test cases and learn the most common methods I will be using. Including test(), expect(), toBe(), toContain(), toContainEqual(). I also learn how to install it by using NPM, which was a simple enough process. Learning the Jest syntax was straightforward, but analyzing my older code to find faults in my logic was much more beneficial than learning new syntax. I then had to translate my old Java code into JavaScript. I found out rather quickly that JavaScript has many downsides if you plan to use it in an object-oriented paradigm, which this project was. Most notably, the inability to have a true private variable for encapsulation. Though I am not as familiar with it, JavaScript appears to be better adept for functional programming. Even so, I carried on anyway. JavaScript is also a loosely typed language, and there was a couple of occasions I had to deal with data type errors. Writing the tests first was a goal of mine, but I did run into issues doing this. I was not always sure what would need to be returned from the class methods, so I gave my best approximations. This process resulted in me revisiting most of my test cases to rewrite what was actually being returned from the project’s methods. My future recommendation to remedy this is to create UML graphics to organize better how the code should interact. I feel I can save much more time and frustrations doing the coding process by doing more planning.


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Lucci-k/lucci-k.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Lucci-k/lucci-k.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

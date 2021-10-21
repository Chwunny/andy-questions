**1. All technical people have an "approach" to solving large, complex problems, and in my experience, these approaches generally fit into one of three categories:**
- "circle looking for an opening",
- "pick it apart one piece at a time",
- "dive in with both feet".
**None of these are wrong, but they are different. Which best describes your approach and why?**

I think every approach has pros and cons and it depends on the type of problem you're solving, but I personally tend to lean towards picking a problem apart one piece at a time. I find it easier to compartmentalize and solve one problem at a time, it's typically much easier to explain your process to others this way as well. Good documentation is key!

**2. In my experience, technical people tend to fit into one of two categories which I term "leapers" and "grinders". A leaper will make significant intuitive jumps forward based on incomplete information and be right perhaps 70% to 80% of the time, making it worth the risk. A grinder starts at point A and grinds through every permutation on the way to point B, leaving no direct conclusion untouched, but arriving much slower than a leaper.A good technical team requires a balance of both - leapers to push the grinders forward and work outside the box, and grinders to catch the mistakes and fill in the gaps. Which are you and why?**

I try to be both. If leaping is a possibility then I will do that, but only if I have solid foundational knowledge of the topic. For issues that I'm unfamiliar with I like to take a step back and take it slow, read all of the documentation, and really pick it apart until I feel familiar enough to teach the information to somebody else. If you're comfortable to teach somebody else you typically have a solid understanding of the topic at hand.

**3. What percentage of the software development life cycle do you generally expect to be consumed by each of the following activities: design, coding, testing?**

Just off the top of my head I would say 30% design, 40% coding, 30% testing.

**4. How significant is the impact of data structure design in the long-term effectiveness of a solution and why?**

Very important, if your data structure changes your code will have to change to account for that. Obviously nobody can see the future, but there are a lot of steps you can take make sure you plan out a strong future proof data structure.

**5. What is the difference between a waterfall methodology and an iterative methodology and what are the primary factors in choosing between them?**

With waterfall you plan every step of the phase and then only execute on what you planned, where as with iterative you are continuously planning, integrating, testing, deploying, then repeating. In short, if an applications features are mostly independent of each other choose iterative, if the features all depend on each other then you should choose waterfall.

**6. Why might one model a system with UML and/or use-cases versus more data flow and process flow diagrams?**

UML diagrams represent structural and behavioral view of the system, where data flow is a graphical representation of how data flows through a system

**7. When modeling and designing a system, which of the following aspects would you consider primary and the foundation that drives the other aspects: user interface; data structures; or processing logic?**

Data structure. The processing logic is usually dependent on the data structure, and the user interface can really be anything you want it to be.

**8. What would you consider the key criteria in evaluating multiple alternative models of a system where each can be generally validated as a “correct” solution?**

How much time it will take to code the solution, the scalability of the solution, and the reusability/modularity of the solution.

**9. How do an interpreter, a “Just-In-Time” compiler, a virtual machine, and a compiler differ?**

JIT: Access to dynamic runtime information, can make better optimizations.
Compiler: Compiles all code to machine language before the program is ran.
VM: An environment designed to execute platform-independent programs

**10. What are the typical logical hosting or deployment components in a modern application?**

**11. What is an Object-Relational mapping (ORM) tool?**

A tool or program used to convert data between OOP languages and relational databases

**12. Describe enumerations and how they are used.**

Enumerations are used to represent a group of named constants. For example: {Monday, Tuesday, Wednesday} would belong to the enum Days

**13. What is operator precedence and why is it important?**

Operator precedence determines how operators are parsed concering each other for example:
(13 - 5 _ 2) = 3, because the _ operator takes precedence over the - operator

**14. What is “separation of concerns” and why does it matter?**

A design principle for seperating parts of a program. Each part addresses a different issue or concern. Seperation of concern can lead to more freedom of design, such as simplication of code.

**15. What is "inversion of control" and why does it matter?**

Instead of the program controlling the flow of the user interation, the user controls in what order they want add data and when they want to save said data. Therefore control is inverted to the user.

**16. What is “dependency injection” and why is it used?**

Providing an object or class the object it needs instead of having it contruct the dependency itself. It's useful for testing an object and/or its dependencies.

**17. What is functional decomposition, and why it is important?**

A nmethod of analyzing a complex process and breaking it down into smaller pieces. Decomposition promotes problem solving and overall understanding of the process.

**18. What is cohesion and how can poor cohesion be a problem?**

The measure of how elemments of a module are functionally related. Strongly related elements should be kept close together, while non related elements should be kept away from each other. Seperation of conerns.

**19. What is defensive programming?**

Writing software that can continue operation even in the midst of unforeseen issues.

**20. Briefly explain Ant, Maven, and Gradle, how do they differ and identify any experience you have with them.**

No experience.

**21. What is the difference between loose coupling and tight coupling and what are the implications of each?**

Loose coupling is when the relationship between two components is low, while tight coupling is the opposite. Loose components are more isolated and independent. Tightly coupled components reduces the flexibility and modularity of components.

**22. Explain the key differences between a procedural program and an event driven program.**

Procedural programs are linear and only run as they are defined, whereas event driven programs can respond to user generated events such as mouse clicks or scrolling

**23. In functional programming, what is a “monad”?**

A function that returns an instance of the same type. At least in JavaScript, monads are not necessarily good because they are ugly.

**24. What is a “tuple”?**

A tuple is an immutable collection of values seperated by commas and enclosed in parenthesis

**25. What are the typical expressions of flow control in a modern programming language and what do they do?**



**26. What is the difference between an iterative algorithm and a recursive algorithm and when might each be used?**

An iterative algo is just a statement that loops over and over again until a specified time, while a recursive algo calls itself repeatedly until its base condition is met

**27. What is tail end recursion and why might it be worth eliminating?**

A function where the last operation is a recursive call. Writing a normal loop can be more efficient becuase it uses less resources to accomplish the same goal.

**28. What is "technical debt" and why is it significant?**

Technical debt is the implied cost or consequence of taking the easy route instead of taking a longer more thought out approach. This is significant because using the easier solution can lead to wasted time and lost resources. Do it right the first time!

**29. What is refactoring, and why it is done?**

Restructuring your code without changing the functionality to improve design, readability, structure, etc.

**30. What is the difference between synchronous and asynchronous processing and why might each be used?**

You can only execute one process at a time with synchronous, you can execute multiple processes at one time with asynchronous code.
The use case here is pretty obvious here I feel, if you need to run multiple parts of your file at one time, use asynchronous code.

**31. What is the difference between real time, near time, and batch processing and when might each be used?**

Real time: Data thats collected, processed, and analyzed on a continual basis.
Near time: A snapshot of recent historical data.
Batch processing: An efficient way to process large amounts of complex data
Real time for when you need data immediately, near time for when speed is important but data is not immediately required, and batch data for long continuous processes.

**32. What are design patterns and what are some examples of them?**

Design patterns are resusable solutions to common or recurring problems. 
A common one in JavaScript is the use of modules.

**33. What is a domain specific language (DSL) and why is it used?**

A language created to solve one specific problem, becuase they can be specialized to target a specific class of issues

**34. What are the core principles of object-oriented development and why are the important?**

Encapsulation, Data Abstraction Polymorphism, and Inheritance. Because they allow more modularity and reusability in your code while also reducing complexity in the case of encapsulation.

**35. What is the difference between hierarchical data structures, relational data structures, and graph data structures?**

Hierarchical: Used to organize data with one-to-many relationships.
Relational: Can utilize both one-to-many and many-to-many relationships, queries can be slow though.
Graph: No schema database, used to store data with complex relationships, think of a family tree.

**36. What is meant by "impedance mismatch" between hierarchical, relational, and graph data structures, and what challenges arise from it?.**

Hierarchical and relational databases can expereience impedance mismatch when they are served by an object oriented programming language.
Because graph data structures are so modular they rarely suffer from impedance mismatch because you can insert essentially anything into them.

**37. What is the difference between a strongly typed language and a weakly typed language, and when each might be used?**

Strongy typed languages wont allow implicit conversions between non related types, whereas weakly typed languages would

**38. What are the differences between creating a new class, extending an existing class, and implementing an interface, and the reasons why each might be used?**

Creating a new class can define data structure and methods, extensions can use their parent class methods, but classes cannot use their childrens methods. Interfaces can not be used to create objects.

**39. C: Assuming you have a standard C compiler (ANSI) but none of the standard libraries, recreate the standard library strcpy function, matching the functionality and specification exactly.**

**40. Java: What is the difference between == and equals()?**

one is a method and one is an operator. == checks if both objects point to the same location in memory, equals() compares the values of the objects

**41. Java: What does it mean to “intern” a string?**

You can intern a string value if many of that same value appear, this saves memory

**42. Java: What is the difference between String, StringBuffer, and StringBuilder and the pros and cons of each?**

Strings are immutable so they will not change, if you try to concat the string it will take up a new place in memory.
StringBuffer will change the actual value of the string, whereas StringBuilder is similar to buffer but it can use multiple threads, causing a penalty to performance

**43. Java: Describe the differences between public, protected, private, package, and static scope.**

**44. Java: What are the 4 public methods every object has and their respective signature?**

**45. What is the difference between overriding and overloading a method?**

**46. What are generic, parametrized, or template types?**

**47. What is the difference between a collection and an iterator?**

Iterator can move to next() element or remove() an element.
Collection can add(), iterate, remove(), and clear() elements of the collection

**48. What is the purpose of source code annotations?**

Making the intent of your code explicit.

**49. Briefly describe the function of PDF technology, the principal features of the format, and some of the typical tools and technologies for working with it.**

PDF is an software/hardware independent format to view documents with. Principal features include reliabilty, cross-platform, secure, and true to the original file. The only PDF tool you should use in my opinion is Adobe acrobat, its expensive but worth it if you work with PDFs every day.

**50. Why might you implement a system with multiple threads using shared resources, what precautions are necessary, and what tools and techniques are available to address them.**

Take advantage of full CPU power, run multiple processes concurrently, multiple threaded processes typically use less resources.
Multiple threaded applications are more difficult to pick apart and understand, harder to debug, and can actually lower performance if not optimized correctly. 

**51. What are the key elements of a transactional system and what do they mean?**

Inputs: Any customer input such as orders, invoices, etc.
Processing: Input provided is then processed to get an output
Storage: Storage of processed material
Output: Any generated material is considered output

**52. What is the maximum number of data elements that a typical person can keep track of at one time and how should this affect system design?**

An average person can typically keep track of 3 or 4 things in their active conciousness at once. When it comes to design this shows us to keep things simple in most cases and not overwhelm the user with needless distractions.

**53. Identify some key objective metrics that can be used the evaluate code quality and what they indicate.**

Code maintainability, readability and formatting, good documentation, code is efficient (has good time and space complexity).
No code is perfect, but having a good balance of the above metrics can lead to very high code quality.

**54. Explain "continuous integration", how it affects the development process and its principal benefits**

CI/CD is the process of automatically integrating code changes from multiple sources then building and testing said version, checking for syntax errors, and reviewing code with automated tools. It's beneficial to the SDLC because it allows teams to test and deploy new code much faster than they would otherwise be able to.

**55. What are the benefits of source code control system and why might one opt for a distributed rather than centralized tool?**

SCCS's are easy to use and typically rely on Git which is universally used and accepted. They typically include systems to compare old and new code, manage merge requests, and overall make life a lot easier. Especially if you've made application breaking changes that you're not sure how to reverse. Systems like Github kind of combine distribution and centralization into one in my opinion. Each engineer has access to version control through git commands, while an admin or senior dev can easily review code and make comments/requests through Github. The best of both worlds!

**56. What are the key types of testing and why is each done?**

I'm familiar with Unit testing, Integration tests, Performance testing, Smoke testing, and Functionality testing.
Unit tests for functions or modules of your code, integration testing to make sure all parts of your application play well together, performance testing to ensure your application loads in a timely manner and is uses resources efficiently. Smoke testiing to ensure basic functionality of an application such as "Does the requested page load?", and functionality testing to ensure that the user interface performs as expected.

**57. What tools and/or techniques do you generally recommend for testing an application and why?**

I've really only used Selenium and Jest, so I need more experience with the subject. That besing said, I really enjoy the syntax and ease of use that come with Jest and Selenium.

**58. What is Service Oriented Architecture (SOA) and why is it used?**

SOA provides infrastructure automation which reduces integration cost. Rerliable, scalable, platform independent, reusable, easy to maintain.

**59. What are microservices and why are they used?**

Mircoservices are the counterpart to monolithic applications. You can use the microservice architecture to split your application into multiple smaller components which greatly increases speed and efficiency of your application. A good example of a microservice would be a RESTful API.

**60. What is the function and value of an Extract, Transform, and Load (ETL) tool and when might it be used?**

ETL is a data management process that starts with searching for or extracting data and then transforming it into a usable format. Finally, loading the formatted data to a location or application that can utilize it. ETL tools are invaluable for businesses because they present a solution to automatically and efficiently handle complex data and reduce errors.

**61. What is the function of an Enterprise Service Bus and why might it be used?**

A platform used to distribute work among components of an application.

**62. What are the types of features and capabilities you would expect from an "enterprise" solution and why?**

Reliabilty, concistency, solid architecture. Enterprise solutions are typically bespoke, so you would expect them to mesh well with all facets of the business integration system.

**63. What is a WSDL file and how is it used?**

Web Service Description Language are used to describe the functionality of SOAP based web services.

**64. What is Electronic Document Interchange (EDI) and what are some specific standards and uses for it?**

Intercompany communication of business documents in standard format. Replaces paper based documents which saves time and helps eliminate costly errors.

**65. What is the Lightweight Directory Access Protocol (LDAP) and what are its primary uses?**

LDAP is a form of language that allows users to find information very quickly.
LDAP directories typically contain data that is descriptove, static, valuable

**66. What is a data warehouse and what are its principle characteristics?**

A data warehouse is a type of data management system. It typcially utilizes a relational database, some form of ETL solution, Stats analysis and reporting, and other analytical applications

**67. What is Online Analytical Processing (OLAP) and what are examples of its uses?**

Software used to perform multidimensional analysis at high speeds on large volumes of data. Uses include business reporting, marketing, management reporting, budgeting/forecasting, and financial reporting.

**68. What is a star join and what is it used for?**

When a large table of data is joined by two or more smaller tables. Some benefits are simpler queries, query performance gains, and fast aggregation of data.

**69. What is the difference between a traditional database indexed query and a full text search engine query?**

Indexed queries are good for searching for specific values in a database, while search engines can use unstructured text to query data and return results.

**70. What is JSON and when is it used?**

JavaScript Object Notation. JSON is a way to represent text based data structures. Widely seen as the standard for sending data between the client, server, and web.

**71. Some developers advocate every method or function having exactly one exit or return point. In your opinion, is it ever appropriate to have more than one exit or return point in a function or method, and if so when and why?**

It's hard to say for sure. The beauty of programming is that you can do anything! That being said, I tend to lean towards the idea that functions with multiple exit points are probably too large, and that they're probably at the point where you would consider refactoring or redesigning the scope of the functions responsibility.

**72. What is the function and importance of code walkthroughs, and how formal do you feel such a process should be?**

One person presents/walks through their code explaining their thought process, potential edge cases, areas that could be imporved, etc.
Very important for not only peers to be a part of, but I also think exercises like this can improve the skills and thought process of the engineer presenting tremendously. I think it depends on the context of the word formal in this case. I personally think that that code walkthroughs should have a casual feeling so that peers feel comfortable asking questions and pointing out possibler errors. Code walkthroughs should happen often and be standard procedure.

**73. In your experience and opinion, what is the importance of code style aspects (indentation; line width; curly brace usage; tabs versus spaces; white space usage; comments; Documentation comments; class, method, and variable naming; method and class length), and do you think any should be standardized for a team or project?**

This is a great question. Obviously code style is personal preference, and I also think its fine for somebody to code in any style they want as long as their code is readable and they document it well. However, for teams/projects tools like ESLint and Prettier are invaluable, everybody can code in their own style and then its automatically formatted in an opinionated way. I think people on the same team should use a tool like prettier at the very least, it will save time and resources in the long run.

**74. Briefly explain the function and value of XML?**

XML is a markup language like HTML. Except that XML carries data, and HTML displays data. Another important note is that XML tags are not predefined like with HTML, they can be anything you want.

**75. What is a URL and how is it different from a URI?**

URL identifies the address or location of a resource, while a URI is a unique identifier of a specific resource.

**76. What does the acronym CRUDS refer to?**

Create, Read, Update, Delete

**77. What is the function and use of a “promise” in JavaScript?**

A promise is a proxy for a value not yet known. This can allow you to do many things such as await data from an API or make a CRUD call to your server. Promises have 3 states pending, fulfilled, rejected. Once a promise has been fulfilled the associated .then() blaock of code will run

**78. What is the different between JavaScript and TypeScript?**

TypeScript is a strongly typed version of javascript. Which is useful for many applications and when used correctly can save you from creating bugs by leaving no value weakly typed

**79. How are JavaScript modules made and used?**

Modules are objects containing methods that are created using the module.exports = { } syntax. These methods are typically reused and are very useful for keeping your code more clean and concise

**80. What is the use of a the “package.json” file?**

package.json is a json object that defines the name, dependencies, scripts, config, and other data about your application.

**81. What is the difference between “npm” and “yarn”?**

yarn is a newer improved "version" of npm, it basically does the same things as npm but has some key functionality differences such as improved performance and slightly different syntax in some cases.

**82. What does Webpack do?**

Webpack bundles and compiles your code so that the browser can read it

**83. What is a Progressive Web Application or “PWA”?**

A PWA is like a normal web application except that theyre typically faster and more efficient. PWAs require service workers that run seperately from the UI which can lead to near instantaneous load times.

**84. What is a Single-Page Application, or “SPA”?**

A SPA is a website that has the page dynamically updated rather than being downloaded from a server. This way all the necessary code only needs to be loaded once. All elements are fetched and rerendered as the user navigates the page.

**85. What is Server-Side Rendering or “SSR”?**

The web browser requests information from the server which is instantly sent back as a fully rendered page.

**86. What are the primary similarities and differences between React and Angular?**

Angular is a framework built with typescript while React is just a javascript library. Angular has unique syntax while React is just plain HTML and JavaScript. Both are very performant. Angular has a higher learning curve. Angular supports 2 way data binding while React only supports one way data binding.

**87. What is destructuring in JavaScript?**

Destructuring is pulling properties off of an object to be used later. The primary upside to this is that it promotes clear code and readability. Personally one of my favorite facets of javascript.

Syntax: const { prop1, prop2 } = object

**88. What are the JavaScript “async” and “await” keywords used for?**

async is used to create and asynchronous function, which is guaranteed to return a promise.
await pauses your code on the line it's used until the promise is resolved.

**89. In JavaScript what is the difference between false and falsey**

false is the strict boolean type false. Falsey values are values that are coerced to false boolean context. Some examples of falsey values are:
null, undefined, NaN, 0, any empty string

**90. Explain what a try/catch/finally construct does.**

A try catch finally is a block of code to be ran, the program will try the code, if it fails an error will be thrown, then the finally bloack of code is ran. The finally block will run even if there was no exception thrown.

**91. What is a regular expression and what is an example of one?**

A regex is an expression representing a pattern that is used to match text.
An example of one would be: let regex = /[abcdefg]/i
The pattern above would look for any of the characters inside of the brackets, while the i flag denotes case insensitivity

**92. What are the difference between a C++ virtual constructor and virtual destructor?**

A constructor initializes a class object, while a virtual destructor is destroys instances of the class object.

**93. What is the correct level of adoption for UML is a particular project?**

**94. Explain the basic concept of a relational database management system (RDBMS)**

Data is added in tables with rows and columns, columns denoting the type of data, rows containing the corresponding data

**95. Explain the concept of template-based content production, it's advantages and disadvantages, typical usage scenarios, and give examples of template types and common tools.**

**96. Briefly explain the concept of public key/private key encryption and identify some typical algorithms and common uses.**

A cryptographic system that uses pairs of keys. Pairs consist of an openly distributed public key, and a private key which is only known to the owner. An example of a common algorithm would be a trapdoor function, a function that is easy to compute one way but very difficult to find the inverse of. Very difficult as in theoretically possible, realistically impossible (from a time perspective).

**97. What is a cryptographic hash, what are some common algorithms for it and typical usages?**

A hash function is another one way function that turns data into a random string of characters also known as a hash. Typically deterministic, infeasible to reverse engineer a message from a hash, and takes advantage of the avalanche effect.
I've used BCrypt pretty extensively in a few personal projects which is based on the blowfish cipher.

**98. What is a digital signature, how is one produced, and how are they used?**

A message combined with a private key to create a digital signature on a message. Decrpyed using the senders public key.

**99. Is the structure of an RDMS strongly or weakly typed?**

Strongly typed

**100. How is data retrieved from an RDBMS?**

SELECT * FROM table_name;

**101. How is data changed in an RDBMS?**

UPDATE table_name
SET column = values
WHERE condition;

**102. How is the structure of an RDBMS defined?**

A collection of unique tables. Tables can reference each other with the use of unique reference IDs

**103. How is data from two RDBMS tables retrieved together?**

SELECT table1.value1, table2.value2
FROM table1
JOIN table2 ON table1.ID = table2.ID

**104. What are the ways data from an RDBMS table can be filtered based on the contents of one or more other tables?**

SELECT table1.value, table2.value
FROM table1
JOIN table2 ON table1.ID = table2.ID
WHERE username = 'value'

**105. What are the types of joins and how do they differ?**

INNER JOIN & OUTER JOIN:
Inner join gives only the two rows the tables have in common
Outer join gives all rows in table 1, plus any common rows in table B, which can lead to null values

**106. What are the types of subqueries and how do they differ?**

Single or multiple row/column subqueries as well as Nested and correlated subqueries.
Single or multiple subqueries will return one or more colums and/or rows, nested and correlated subqueries will return data based on the first query(s)

**107. What are the basic concepts used typically used in a modern RDBMS to improve performance?**

Optimize queries, improve indexing

**108. What are the key elements of a transactional system and what do they mean?**

Inputs: Any customer input such as orders, invoices, etc.
Processing: Input provided is then processed to get an output
Storage: Storage of processed material
Output: Any generated material is considered output

**109. What is the difference between an RDBMS and a NoSQL or MapReduce based storage engine?**

Relational databases store data in tables, while non-relational databases do not use a row/column schema.

**110. What is the SSH command and how does it work?**

Secure Shell is used to provide a secure encrpteed connection between two hosts over an insecure network

**111. What does a packet filter do?**

Monitors outgoing and incoming network traffic (Packets, in this case) and filters packets based on source and destination IP addresses, protocols, and ports.

**112. What are the basic Linux commands for navigating the file system?**

ls, cd, pwd: shows the files in your current directory, change directories, print working directories

**113. What are the basic Linux commands for manipulating and viewing files?**

cp, mv, rm, mkdir: copy files and directories, move or rename files/directories, remove files/directories, create directories

**114. What is a net mask and how does it apply?**

A net mask is used to divide an IP address into two parts. One to identify the host, one to identify the network the host belongs to.

**115. What is the difference between a network router and a network switch?**

A switch connects multiple devices in a network, a router connects multiple switched and their networks to a larger combined network.

**116. How do TCP and UDP connections differ?**

TCP: Connection oriented protocol
UDP: Connectionless protocol
Overall, UDP is faster, simpler, and efficient.

**117. What is the relationship between the source port and the destination port of an IP connection?**

The source port identifies the process that sent the data and the destination port identifies the process that receives the data.

**118. What is a named pipe and how is it used?**

Named pipes can be used to communicate between processes on the same computer or between processes on different computers across a network.

**119. What is the difference between a block device and a character device?**

Character devices communicate by sending single characters of data, where Block devices communicate by sending entire blocks of code.

**120. What are the basic file permissions in a traditional Unix file system and what do they mean?**

r--, -w-, --x, -wx: Read, Write, Execute, Write & Execute

**121. Briefly explain the differences between HTTP, HTTPS, SMTP, FTP, and SFTP**

HTTP/HTTPS are for transferring files between the web server and client, with the latter being a more secure option.
FTP is for transferring files between computers, while SFTP uses SSH to transfer files over a secure connection.
SMTP stands for Simple Mail Transfer Protocol, which is how email servers connect to and communicate with each other.

## Computer Science & Software Engineering
- [The Art of Computer Programming - Donald Knuth](https://www.amazon.com.br/Computer-Programming-Volumes-1-4a-Boxed/dp/0321751043/ref=sr_1_1?qid=1575407297&refinements=p_lbr_books_authors_browse-bin%3ADonald+E.+Knuth&s=books&sr=1-1)
- [Clean Code: A Handbook of Agile Software Craftsmanship - Robert C. Martin Series](https://www.amazon.com.br/dp/B001GSTOAM/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1)
- [The Mythical Man-Month: Essays on Software Engineering](https://www.amazon.com.br/Mythical-Man-Month-Anniversary-Software-Engineering-ebook/dp/B00B8USS14/ref=sr_1_1?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=11LSVPQBNSMUS&keywords=the+mythical+man-month+essays+on+software+engineering&qid=1568834047&s=gateway&sprefix=The+Mythical+Man-Month%3A+Essays+on+Software+Engineering%2Caps%2C338&sr=8-1)
- [Eletrônica – Para Autodidatas, Estudantes e Técnicos – 2ª Edição, de Gabriel Torres](https://pay.hotmart.com/U8059089S?checkoutMode=10&utm_source=site&utm_medium=link&utm_content=link&utm_campaign=organico&sck=site&bid=1584206239824)
- [Rob Pike's 5 Rules of Programming](https://users.ece.utexas.edu/~adnan/pike.html)
- https://martinfowler.com/
- [Livro Clean Architecture - Uncle Bob](https://imasters.com.br/back-end/introducao-clean-architecture)
- [Teach Yourself Programming in Ten Years - Peter Norvig](http://norvig.com/21-days.html)
- [Coding Interview University](https://github.com/jwasham/coding-interview-university)
- [Teach Yourself CS](https://teachyourselfcs.com/)
- [Web Developer Roadmap](https://github.com/kamranahmedse/developer-roadmap)
- [How Browsers Work: Behind the scenes of modern web browsers](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)
- [Roadmap.sh](https://roadmap.sh/)
- [https://developer.mozilla.org/en-US/](https://developer.mozilla.org/en-US/)
- [https://thewisedev.com.br/](https://thewisedev.com.br/)
- [Software Engineering at Google - SWE BOOK](https://abseil.io/resources/swe-book)

## Principles
- “Bad software that adds value > Perfect software that adds no value.”
- “Learn to say: I DON’T know, and if necessary, try to learn.”
- “Premature optimization: the root of all evil.”
- “Remember that dinosaurs are almost always the best references.”
- “Those who think little, err a lot” - Leonardo da Vinci
- "In God I trust. All others must bring data.”
- “Lack of money is the root of all evil.”
- “There is no silver bullet.”
- “Make it work > Do it right.”
- “Increase revenue > decrease costs.”
- “SaaS > PaaS > IaaS > In-House”
- “You != Unicorn”
- “Always try to understand what is going on under the hood.”
- “Writing code != programming != software engineering”
- “Maintenance > Performance”
- “No metrics, no optimization”
- “Never stop questioning”
- “Software engineering is 80% THINKING about the problem, and 20% HOW to solve the problem.”
- “The more knowledge you have, the less you know. EGO = 1 / knowledge.”
- “Everyone should care about quality”
- “At least 80% of the code of good software has been redone, reduced or better yet, deleted. Less is more."
- “2+2 is not 5, no matter how many people say that.”
- “Principles > Analogy.”
- “Talk to and learn from people smarter than you.”
- “Always try to use the only source of truth.”
- “Don't reinvent the wheel. That's what ready-made frameworks and libraries exist for.”
- “It is always good to study a tool deeply before putting it into production.”
- “Modularization is everything.”
- “Good artists copy, great artists steal.”
- “Innovation only exists in a world of restriction, not abundance.”
- “There will always be something to improve. Done is better than perfect.”

## Bits & Bytes
- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/81565313-8168bf80-936f-11ea-900a-0d9e44dfa7a4.png">

## Clean Architecture
- [TheWisePad - NodeJS & Typescript BackEnd REST API Example - Otavio Lemos](https://github.com/otaviolemos/thewisepad-core)
- [Livro Arquitetura Limpa na Prática, do Otávio Lemos](https://www.otaviolemos.com.br/)
- [https://github.com/khaosdoctor/layered-typescript-bookstore](https://github.com/khaosdoctor/layered-typescript-bookstore)
- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/81711643-3ff91280-944a-11ea-8062-233c6134aed2.jpg">
- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/175309513-433edc44-39fc-4da7-9242-ff9b90e14970.png">
- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/175309509-bf2b2327-1528-4d37-9988-b9b5ff365daf.png">

<h2>Clean Code</h2>
<p>When defining a name, we need to keep two main points in mind:</p>
<ul>
<li>Be precise: we need to convey the central idea of our variable or method, without going around, being concise and direct.</li>
<li>Don't be afraid of big names: a well-descriptive name, even if it is long, will allow a better understanding and later maintenance of the code.</li>
</ul>
<p>To finish, it is recommended that:</p>
<ul>
<li>Methods or Functions: they must have verb names, in order to express what their purposes are;</li>
<li>Classes and Objects: nouns must be used.</li>
</ul>
<p>According to Robert C. Martin, the first rule of functions is as follows:</p>
<ul>
<li>“They need to be small.”</li>
</ul>
<p>The second rule of functions says the following:</p>
<ul>
<li>“They have to be even smaller.”</li>
</ul>

<br>
<h2>Keep It Simple Stupid - KISS</h2>
<p>Clean tests follow the rules of the acronym FIRST (Fast, Independent, Repeatable, Self-validation, Timely).</p>

<ul>
<li>Speed: Tests should be fast so they can be run multiple times;</li>
<li>Independence: when tests are dependent, a failure can cause a domino effect making individual analysis difficult;</li>
<li>Repeatability: it must be possible to repeat the test in any environment;</li>
<li>Self-validation: good tests result in “true” or “false” responses. Otherwise, the fault can become subjective;</li>
<li>Timeliness: Tests need to be written before the production code, where the tests will be applied. Otherwise, the code may become too complex to be tested or the code may even be untestable.</li>
</ul>

<br>
<h2>Don't Repeat Yourself - DRY</h2>
<p>DRY is the acronym for Don’t repeat yourself. It is the concept that says that each piece of knowledge of the system must have only one representation. In this way, avoiding code ambiguity. In other words, there should not be two parts of the program that perform the same function, that is, the famous copy and paste in the code.

<p>But why avoid repetition? Simple!</p>

<p>Anyone who has a second home on the beach or in the countryside knows how complicated it is to maintain both. Even though repetition may seem harmless in simpler programs, it can become a problem as software grows and maintenance and development become more and more complex.</p>

<p>A good way to avoid code duplication is to correctly apply the single responsibility technique. For each function or method, use only one part of the method (or function). The correct thing is to abstract only that part and create a new one!</p>

<p>Some condition ambiguities are not as destructive to code, but over time they can be. So try to avoid them as much as possible.</p>

<p>Better safe than sorry. That famous saying applies to software development as well. Good developers think that things can go wrong, because they eventually will. In this way, the code must be prepared to deal with these problems that will arise.</p>

<p>Today most languages have features to handle errors in code through Exceptions and try-catch blocks.</p>

<p>Exceptions: mechanism that signals exceptional events. For example, trying to insert the character “a” into an integer variable;</p>

<p>Try-catch blocks: catch the mentioned exceptions. Therefore, they must be used globally. After all, methods already have their functions (which is not handling errors).</p>

<p>To end this topic, an excellent tip for not generating errors in your code is simply not to use “null”, both as a parameter and as a function return. These returns often require unnecessary checks that, if not done, can generate errors.</p>



## YAGNI - You Aren't Gona Need It
<p>"You aren't gonna need it" (YAGNI) is a principle of Extreme Programming (XP) which states that the programmer should not add any functionality until it is actually needed.</p>
<p>"Always implement features when you really need them, and never when you anticipate needing them".</p>
<p>It seems obvious isn't it, but think about it. how many times have you implemented a feature in a project just because you thought the client would love it, or that it would give the project that edge?</p>
<p>This does not mean that you should avoid writing flexible code.
<p>It means that you should not include functionality in your code based on the fact that you might need it later.</p>
<p>There are two main reasons for practicing YAGNI:</p>
<p>You save time, because you avoid writing code that you won't need at the moment;</p>
<p>Your code gets better, because you avoid polluting the code with 'guesses' that turn out, in most cases, to be wrong guesses;</p>
<p>1- If you don't need the feature now then don't implement it. You don't need it.</p>
<p>2- Do you really think you'll save time overall by spending more time now than in the future?</p>


## [Semantic Versioning 2.0.0](https://semver.org/lang/pt-BR/)

<p>Given a MAJOR.MINOR.PATCH version number, increment a:</p>

<ol>
   <li>Major version(MAJOR): when making incompatible API changes,</li>
   <li>Minor version(MINOR): when adding functionality keeping
compatibility, and</li>
   <li>Patch version(PATCH): when to fix bugs while maintaining compatibility.</li>
</ol>

<p>Additional pre-release labels and pre-release metadata
build are available as an extension to the MAJOR.MINOR.PATCH format.</p>


## Microservices
<ul>
<li><a href="https://martinfowler.com/microservices/">https://martinfowler.com/microservices/</a></li>
<li><a href="http://blog.cleancoder.com/uncle-bob/2015/05/28/TheFirstMicroserviceArchitecture.html">http://blog.cleancoder.com/uncle-bob/2015/05/28/TheFirstMicroserviceArchitecture.html</a></li>
<li><a href="https://martinfowler.com/articles/microservices.html">https://martinfowler.com/articles/microservices.html</a></li>
<li><a href="https://www.redhat.com/pt-br/topics/microservices">https://www.redhat.com/pt-br/topics/microservices</a></li>
<li><a href="https://www.redhat.com/pt-br/topics/microservices/what-are-microservices">https://www.redhat.com/pt-br/topics/microservices/what-are-microservices</a></li>
</ul>
<p>Microservices are an architectural approach to building applications. What differentiates the microservices architecture from traditional monolithic approaches is how it breaks down the application by basic functions. Each role is called a service and can be created and deployed independently. This means that each individual service can function or fail without compromising the others.</p>
<img src="https://user-images.githubusercontent.com/19540357/82092070-ee14ee80-96ce-11ea-8a1b-9a5ca23f6cab.png" class="w-100 img-fluid">
<p>Think about the last time you accessed a store's website. Chances are you used the site's search bar to look for products. This search represents a service. You may also have seen related product recommendations drawn from a database of shopper preferences. That too is a service. Did you add any items to the shopping cart? That's right, this is another service.</p>
<img src="https://user-images.githubusercontent.com/19540357/82092072-ef461b80-96ce-11ea-8075-33de76f90301.png" class="img-fluid w-100">
<p>What are the benefits of microservices architecture?</p>
<p>With microservices, your teams and day-to-day tasks can become more efficient through distributed development. Furthermore, it is possible to develop several microservices at the same time. This means you can have more developers working simultaneously on the same application, which results in less time spent on development.</p>
<ul>
<li>Get to market faster => Because development cycles are shortened, the microservices architecture supports faster deployments and upgrades.</li>
<li>Highly scalable => As demand for certain services increases, you can deploy across multiple servers and infrastructures to meet your needs.</li>
<li>Resilient => Independent services, if built correctly, do not affect each other. This means that if one element fails, the rest of the application remains up and running, unlike the monolithic model.</li>
<li>Easy to Deploy => Because microservices-based applications are more modular and smaller than traditional monolithic applications, the concerns resulting from such deployments are negated. This requires greater coordination, but the rewards can be extraordinary.</li>
<li>Accessible => Because the larger application is broken down into smaller pieces, developers have an easier time understanding, updating, and improving those pieces. This results in faster development cycles, especially when agile development technologies are also employed.</li>
<li>More open source => Due to the use of polyglot APIs, developers are free to choose the best language and technology for the required function.</li>
</ul>

## [Twelve Factor App](https://12factor.net/pt_br/)
<ul>
<li>i. Codebase -> A traceable codebase using revision control, lots of deploys</li>
<li>II. Dependencies -> Declare and isolate dependencies</li>
<li>III. Settings -> Store settings in environment</li>
<li>IV. Support Services -> Treat support services as linked resources</li>
<li>v. Build, release, run -> Strictly separate builds and run in stages</li>
<li>VI. Processes -> Run the application as one or more stateless processes</li>
<li>VII. Port binding -> Export services by port binding</li>
<li>VIII. Concurrency -> Scale by a process model</li>
<li>IX. Disposability -> Maximize robustness with fast startup and shutdown</li>
<li>X. Similar dev/prod -> Keep development, testing, production as similar as possible</li>
<li>XI. Logs -> Treat logs as flow of events</li>
<li>XII. Admin Processes -> Run admin/management tasks as point processes</li>
</ul>

## UML - Unified Modeling Language
<ul>
<li><a href="https://app.diagrams.net/">https://app.diagrams.net/</a></li>
<li><a href="https://www.uml-diagrams.org/">https://www.uml-diagrams.org/</a></li>
<li><a href="https://www.ateomomento.com.br/diagramas-uml/">https://www.ateomomento.com.br/diagramas-uml/</a></li>
</ul>
<p>It is a notation language (a way of writing, illustrating, communicating) for use in systems design.</p>

<p>This language is expressed through diagrams. Each diagram is composed of elements (graphic shapes used for drawings) that are related to each other.</p>

<p>UML diagrams are divided into two major groups: structural diagrams and behavioral diagrams.</p>

<p>Structural diagrams should be used to specify details of the system structure (static part), for example: classes, methods, interfaces, namespaces, services, how components should be installed, how the system architecture should be, etc.</p> p>

<p>Behavioral diagrams should be used to specify details of system behavior (dynamic part), for example: how functionalities should work, how a business process should be treated by the system, how structural components exchange messages and how they respond to calls etc.</p>
                
<p>"João wants A, explains to the team something “similar” to B. Marcos understands that João wants C, and explains to Claudia that it is to make a D. Claudia makes a “D that looks more like an E”, and delivers a “half E” for John. And John wanted an A…”</p>
<img src="https://user-images.githubusercontent.com/19540357/81796156-6b7c0b80-94e3-11ea-9f9e-fea8f7b96834.png" class="img-fluid w-100">
<br><br>
<p>The UML is like a universal language for software production professionals, it is a “Google Translate” that greatly helps clear and objective communication between people involved in the production process (Business Analysts, Product Owner, Scrum Master, Architects , Developers, Project/Product Managers and other interested parties).</p>
<p>The goal of a UML diagram is to pass a message in a standardized way, where all receivers of this message understand the used pattern.
<p>It's the famous: "Do you understand or do you want me to draw it?"</p>

<p>Imagine that in the same room, without internet and telephone, there are three people who only speak their native language: one Chinese, one French, and one Brazilian.</p>

<p>In this room there is only paper and pencil. The Frenchman wants a coffee.</p>

<p>What will be the most efficient way, considering the resources available in the room, for French to convey the message “I want a coffee”?</p>

<p>Maybe drawing a coffee cup!</p>

<p>Making this clear, in a simple, objective, transparent and pragmatic way, is good communication.</p>

<p>Taking the above reasoning to software projects, the UML must be used to communicate what you want and/or how you want, efficiently.</p>


## DDD - Domain Driven Design

<ul>
<li><a href="ddd.pdf">Livro Domain Driven Design - Eric Evans</a></li>
<li><a href="http://www.macoratti.net/11/05/ddd_liv1.htm">http://www.macoratti.net/11/05/ddd_liv1.htm</a></li>
<li><a href="http://dddsample.sourceforge.net/architecture.html">http://dddsample.sourceforge.net/architecture.html</a></li>
<li><a href="http://www.agileandart.com/2010/07/16/ddd-introducao-a-domain-driven-design/">http://www.agileandart.com/2010/07/16/ddd-introducao-a-domain-driven-design/</a></li>
<li><a href="https://www.infoq.com/minibooks/domain-driven-design-quickly/">https://www.infoq.com/minibooks/domain-driven-design-quickly/</a></li>
</ul>
<p data-line-start="0" data-line-end="1">What is most important in software?</p>
<ul>
<li>The code and technology used, the developer would say.</li>
<li>The tests, the tester would say.</li>
<li>The project plan, the manager would say.</li>
<li>The architecture used, the architect would say.</li>
</ul>
<p>Anything missing?</p>
<ul>
<li>The customer failed to respond, the most important thing is for the software to solve his problem.</li>
<li>Conclusion: The most important thing is the business rule and the value that the software adds to the customer.</li>
</ul>
<p>Domain-Driven Design (DDD) is a software development approach that brings together a set of concepts, principles and techniques whose focus is on the domain and on the logic of the domain with the objective of creating a Domain Model or (model of the domain). domain).</p>
<p>Using DDD means developing software according to the domain related to the problem we are proposing to solve.</p>
<p>Note: In this context, domain is what the software program models and the problem it proposes to solve = business rules.</p>
<p>Knowing the domain is fundamental and creating a model and adopting an architecture for the application that best reflect the concepts of the domain is not an easy task nor a task only for the analyst.</p>
<p>DDD suggests a standard architecture so we can focus on the domain.</p>
<p>The following is a suggested layered architecture that can be used in the domain model</p>
<img class="image-fluid w-100" src="https://user-images.githubusercontent.com/19540357/81709309-2b1b7f80-9448-11ea-9b4f-cb03c94cf338.jpg">
<br><br>
<ul>
     <li>User Interface - Presents information to the user and interprets his commands.</li>
<li>Application - Layer that coordinates application activity. Contains no business logic.</li>
<li>Domain - Contains information about the domain. It's the heart of the business.</li>
<li>Infrastructure - Acts as a support library for the other layers. Performs communication between layers. Implements the persistence of business objects.</li>
</ul>
<p>The focus of the approach is to create a domain that “speaks the language” of the user using what is known as the Ubiquitous language.</p>
<p>Ubiquitous language (common language) means that when working with DDD we must talk using the same language, in a single model, so that it is understood by the client, analyst, designer, designer, tester, manager, etc. in this language, which would be the language used in everyday life.</p>
<p>What are the advantages of using DDD?</p>
<ul>
<li>The code becomes less coupled and more cohesive;</li>
<li>The business is better understood by everyone on the team, which facilitates development;</li>
<li>DDD is neither a 'silver bullet' nor a universal architecture, but an approach that should be considered and applied or not applied to your problem after you have thought and studied a lot about its applications and their consequences.</li> >
</ul>
<p data-line-start="38" data-line-end="39">Remember, you don't have to go around applying (trying to apply) DDD to all kinds of projects.</p>


## CAP theorem
<p>Also called <a href="http://www.cs.berkeley.edu/~brewer/cs262b-2004/PODC-keynote.pdf">Brewer's Theorem</a>, it states that it is impossible that Distributed data storage simultaneously provides more than two of the following three guarantees:</p>


<ul>
<li>
<p><strong>Consistency</strong>: Each read gets the most recent write or an error</p>
</li>
<li>
<p><strong>Availability</strong>: Each request receives a response (no error) - no guarantee it contains the most recent write</p>
</li>
<li>
<p><strong>Partition tolerance</strong>: The system continues to function despite an arbitrary number of messages being dropped (or delayed) across the network between nodes</p>
</li>
</ul>


<p>No distributed system is safe from network failures, so <strong>partition</strong> should generally be tolerated. In the presence of partitions, two options are given: <strong>consistency</strong> or <strong>availability</strong>.</p>


<p>When choosing <strong>consistency</strong> regarding availability, the system will return an error or a timeout if specific information cannot be guaranteed to be updated due to its sharing on the network.</p>


<p>When choosing <strong>availability</strong> over consistency, the system will always process the query and try to return the latest available version of the information, even if it cannot guarantee that it is up to date due to partitions.</p>


<p><strong>Super Short Version</strong>: Databases can only choose 2 out of 3 elements. It is mathematically impossible to have all 3.</p>

<img class="mb-5 image-fluid w-100" src="https://user-images.githubusercontent.com/19540357/80586972-2ab4ca80-89ec-11ea-9c23-91775eff634f.png">


## Computer network

  - IPv4 == Internet Protocol Version 4
     - format by 4 bytes (10111011.01101011.11111011.01011011) = 2^32 = 4,294,967,296
     - Example: 192.168.0.1
     - <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/81460486-2d09e800-9195-11ea-998d-3a49cd03a6f1.png">
  - IPv6 == Internet Protocol Version 6
     - Version 6, due to lack of addresses currently
     - 3.4x10^38 addresses
     - <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/81460485-2b402480-9195-11ea-9b34-7a652e058b98.jpg">
  - MacAddress == Media Access Control
     - Physical "unique" address associated with the communication interface, which connects a device to the network.
     - Its identification is recorded in hardware, that is, in ROM memory (Read-Only-Memory).
     - The first three bytes are intended to identify the manufacturer - they are provided by the IEEE itself
     - The last three bytes are defined by the manufacturer, which is responsible for controlling the numbering of each plate it produces. Despite being unique and recorded in hardware, the MAC address can be changed using specific techniques.
  - HTTP == HyperText Transfer Protocol
     - Used for hypermedia and hypertext information systems
     - HTTP: Port 80
     - HTTPS: Port 443
  - OSI Layer & TCP/IP Protocols
     - <strong>Transmission Control Protocol</strong> is a set of communication protocols between networked computers. The protocol suite can be seen as a layered model (OSI Model), where each layer is responsible for a group of tasks, providing a set of well-defined services to the upper layer protocol. The higher layers are logically closer to the user (called the application layer) and deal with more abstract data, relying on lower layer protocols for tasks with a lower level of abstraction. <strong>It is connection-oriented, that is, before sending the data, a communication is made between the sender and the receiver and a communication channel is created, then the data is transmitted. Example of use: FTP (File Transfer Protocol) managers, such as FileZilla, as they need to guarantee the integrity of receiving/sending the file.</strong>
     - Benefits
        - Standardization: A standard, routable protocol that is the most complete and accepted protocol currently available. All modern operating systems support TCP/IP, and most large networks rely on TCP/IP for most of their traffic.
        - Interconnectivity: a technology for connecting dissimilar systems. Many standard connectivity utilities are available to access and transfer data between these dissimilar systems, including FTP (File Transfer Protocol) and Telnet (Terminal Emulation Protocol).
        - Routing: Allows and enables older and newer technologies to connect to the Internet. It works with line protocols such as P2P (Point to Point Protocol) allowing remote connection from dial-up or dedicated line. It works with the IPCs and interfaces mechanisms most used by operating systems, such as Windows sockets and NetBIOS.
        - Robust Protocol: scalable, multiplatform, with a structure to be used in client/server operating systems, allowing the use of applications of this size between two distant points.
        - Internet: it is through the suite of TCP/IP protocols that we get access to the Internet. Local networks distribute Internet access servers (proxy servers) and local hosts connect to these servers to gain access to the Internet. This access can only be achieved if the computers are configured to use TCP/IP.
     - Total TCP Ports: 2^16 = 65,536
    - <strong>UDP = User Datagram Protocol</strong> is a simple transport layer protocol. It is described in RFC 768 and allows the application to send a datagram encapsulated in an IPv4 or IPv6 packet to a destination, but without any kind of guarantee that the packet will arrive correctly (or in any way). <strong>It is not connection oriented, so data is sent without being sure that the receiver has received the data. Example of use: those who do not need to guarantee the arrival of the data. All video and voice programs are of the UDP type (skype, all programs of the "Voice over IP" type and video streaming). </strong>
     - <strong>ICMP = Internet Control Message Protocol</strong> is a protocol that is part of the IP Protocol, defined by RFC 792, and is used to provide error reports to the original source. Any computer using IP needs to accept ICMP messages and change its behavior according to the reported error.
        - TYPE (8 bits): identifies the message type, for example, if the value is 8 it is a request (echo request). If the content is 0 it is an echo reply.
        - CODE (8 bits): used together with the TYPE field to identify the type of ICMP message being sent.
        - CHECKSUM (16 bits): checks the integrity of the ICMP packet.
        - MESSAGE CONTENTS (Variable Size): contains the content of the ICMP message.
     - <strong>Open System Interconnection</strong> is a computer network model intended to be a standard for communication protocols between the most diverse systems on a local area network (Ethernet), ensuring communication between two computer systems ( end-to-end) divided into 7 layers.
     - <strong>PING or Latency</strong> is a utility that uses the ICMP protocol to test connectivity between devices. It is a command available in virtually all operating systems. Its operation consists of sending packets to the destination equipment and "listening" to the responses. If the destination equipment is active, a "response" (the "pong", an analogy to the famous game of ping-pong) is returned to the requesting computer. $ ping -c 5 google.com
     - <strong>Firewal or Wall of Fire</strong> is a device of a computer network whose objective is to apply a security policy to a certain point of the network. The firewall can be packet filters, application proxy, etc. Firewalls are commonly associated with TCP/IP networks[1]. This security device exists in the form of software and hardware, the combination of both is technically called an "appliance".
     - <strong>Gateway = Connection bridge</strong> has the following meanings:
       - In a communications network, a network node equipped to interface with another network using different protocols.
        - A computer or computer program configured to perform the tasks of a gateway.
        - What is it used for: Organizing information traffic between a final device (computer, notebook, smartphone, tablet, etc.) and the Internet, in addition to “translating” information between heterogeneous networks. That is, to allow communication between different environments and architectures. Thus, the tool is capable of converting data between different systems, so that each side is able to “understand” the other.
        - Examples of use: router and firewall.
    - <strong>Proxy="Proxy or Representative"</strong> is a server (a computer system or an application) that acts as an intermediary for requests from clients requesting resources from other servers. A client connects to the proxy server, requesting some service, such as a file, connection, web page, or other resource available from a different server, and the proxy evaluates the request as a means of simplifying and controlling its complexity. An HTTP caching proxy or, in English, caching proxy, allows for example that the client requests a document on the World Wide Web and the proxy looks for the document in its box (cache). If found, the request is fulfilled and the document is returned immediately. Otherwise, the proxy fetches the document from the remote server, delivers it to the client, and saves a copy in its cache. This allows a decrease in latency, since the proxy server, and not the original server, is requested, also providing a reduction in bandwidth usage.
     - <strong>Traceroute</strong> is a diagnostic tool that traces the route of a packet through a computer network using IP and ICMP protocols. Its operation is based on the use of the <strong>Time to Live (TTL)</strong> field of the IPv4 packet[8] destined to limit its lifetime. This value is decremented each time the packet is forwarded by a router. When the value reaches zero, the packet is discarded and the originator is alerted by an ICMP TIME_EXCEEDED message. $ traceroute google.com
     - <strong>PAN = Personal Area Network</strong> is a home network that connects diverse resources throughout a residence. Through Bluetooth technology and/or USB cable a PAN network is obtained.
     - <strong>LAN = Local Area Network</strong> is a set of hardware and software that allows individual computers to communicate with each other, exchanging and sharing information and resources. These networks are called local because they cover a very limited area, but with the technological advancement the LAN has surpassed the 100 m coverage to extend to a larger area.
     - <strong>MAN = Metropolitan Area Network</strong> are networks larger than LANs. This type of network is characterized by having a greater range than the LAN type, covering nearby cities or metropolitan regions, for example. In a more practical definition, let's imagine, for example, that a company has two offices in the same city and wants the computers to remain interconnected. For this there is the metropolitan area network, which connects several local networks within a few tens of kilometers.
     - <strong>WAN = Wide Area Network</strong> is a computer network that spans a large geographic area, often a country or continent. A classic example of a typically WAN network is the Internet itself, as it covers a global geographic area, connecting countries and continents.
    - Camadas OSI
       - <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/81460482-29766100-9195-11ea-8219-d1138b16d965.jpg">
    - Tree Way Handshake
       - <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/81460481-28ddca80-9195-11ea-883a-d2b94b63cfa2.jpg">

## DNS

- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/126329587-680de6c9-c47a-4142-b1f4-e3a95cc05707.png">

## Domain
   - <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/81460480-28453400-9195-11ea-92b5-ac79f2370427.jpg">
   - URL = Uniform Resource Locator (Domain Name)
      - https://google.com
   - subdomain
      - https://play.google.com
   - URN == Uniform Resource Name
      - /maps (resource that will be used in the URL)
   - URI == Uniform Resource Identifier
      - https://google.com/maps (URL + URN)
   - TDL == Top Level Domain or Top Level Domain
      - The IANA (Internet Assigned Numbers Authority) currently distinguishes the following groups of top-level domains
         - country-code top-level domains (ccTLD) are always two letters and derive from the ISO 3166-1 alpha-2 code
         - generic top-level domains (gTLDs): always have more than two letters
         - sponsored top-level domains (sTLD)
         - unsponsored top-level domains
         - infrastructure top-level domains
         - internationalized top-level domains (IDN)
         - internationalized country code top-level domains or IDN ccTLD
         - testing top-level domains
   - DNS == Domain Name System
      - It is a hierarchical and distributed name management system for computers, services or any machine connected to the Internet or a private network.
      - By default, DNS uses User Datagram Protocol (UDP) on port 53 to serve requests and requests.
      - BIND == Berkeley Internet Name Domain is the server for the most widely used DNS protocol on the Internet, especially on Unix-like systems.
      - 13 Root Servers
         - https://www.iana.org/domains/root/servers
         - The authoritative name servers that serve the DNS root zone, commonly known as the “root servers”, are a network of hundreds of servers in many countries around the world. They are configured in the DNS root zone as 13 named authorities, as follows.
		```
		List of Root Servers
		HOSTNAME            IP ADDRESSES    MANAGER
		a.root-servers.net  198.41.0.4,     2001:503:ba3e::2:30 VeriSign, Inc.
		b.root-servers.net  199.9.14.201,   2001:500:200::b University of Southern California (ISI)
		c.root-servers.net  192.33.4.12,    2001:500:2::c  Cogent Communications
		d.root-servers.net  199.7.91.13,    2001:500:2d::d University of Maryland
		e.root-servers.net  192.203.230.10, 2001:500:a8::e  NASA (Ames Research Center)
		f.root-servers.net  192.5.5.241,    2001:500:2f::f Internet Systems Consortium, Inc.
		g.root-servers.net  192.112.36.4,   2001:500:12::d0d  US Department of Defense (NIC)
		h.root-servers.net  198.97.190.53,  2001:500:1::53 US Army (Research Lab)
		i.root-servers.net  192.36.148.17,  2001:7fe::53 Netnod
		j.root-servers.net  192.58.128.30,  2001:503:c27::2:30 VeriSign, Inc.
		k.root-servers.net  193.0.14.129,   2001:7fd::1 RIPE NCC
		l.root-servers.net  199.7.83.42,    2001:500:9f::42  ICANN
		m.root-servers.net  202.12.27.33,   2001:dc3::35  WIDE Project
		```

## Cloud

 - <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/81460484-2b402480-9195-11ea-98d4-138ff2e19e5f.png">
 - <strong>SaaS</strong>
    - SaaS (Software as a Service) allows users to connect and use cloud-based applications over the Internet. Common examples are email, calendar, and Office tools (such as Microsoft Office 365).
     - SaaS provides a complete software solution that you can purchase on a prepaid basis from a cloud service provider. You can lease use of the application for your organization and your users to connect to it over the Internet, typically through a web browser. All underlying infrastructure, middleware, application software, and application data reside in the service provider's datacenter. The service provider manages hardware and software and, with the appropriate service contract, ensures the availability and security of the application and its data.
     - <em>Example: Hosted apps/applications (Office 365, Google Docs)</em>
     - <strong>PaaS</strong>
        - PaaS (Platform as a Service) is a complete cloud-based development and deployment environment with features that allow you to deliver everything from simple cloud-based applications to sophisticated cloud-enabled enterprise applications. You purchase the necessary resources through a cloud service provider on a prepaid basis and access them over a secure Internet connection.
        - Just like IaaS, PaaS includes infrastructure – servers, storage and networking – as well as middleware, development tools, BI (business intelligence) services, database management systems and much more. PaaS is built to support the complete web application lifecycle: build, test, deploy, manage, and update.
        - <em>Example: Development Tools, Database Management, Business Analysis, Operating Systems.</em>
        - <strong>IaaS</strong>
           - IaaS (Infrastructure as a Service) is an instant computing infrastructure provisioned and managed over the Internet. Scale up or down on demand and only pay for what you use.
           - IaaS helps you avoid the expense and complexity of purchasing and managing your own physical servers and other datacenter infrastructure. Each feature is offered as a separate service component, and you can only rent a specific one for as long as you need it. The cloud computing service provider manages the infrastructure, while you purchase, install, configure and manage your own software – operating systems, middleware and applications.
           - <em>Example: Servers and Storage Network Security/Firewalls Datacenter Building/Physical Floor Plan</em>

## DevOps

- [Youtube Channel - TechWorld with Nana](https://www.youtube.com/c/TechWorldwithNana)

## Docker
- [docker.com](https://www.docker.com/)
- [DockerHub](https://www.docker.com/products/docker-hub/)
- [YouTube - Docker Tutorial for Beginners [FULL COURSE in 3 Hours]](https://www.youtube.com/watch?v=3c-iBn73dDE)
- [YouTube PlayList - What is Docker? from TechWorld with Nana](https://www.youtube.com/watch?v=jPdIRX6q4jA&list=PLy7NrYWoggjzfAHlUusx2wuDwfCrmJYcs)
- https://livro.descomplicandodocker.com.br/

## Kubernetes

- [Documentation](https://kubernetes.io/pt-br/docs/_print/)
- [YouTube Video - Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]](https://www.youtube.com/watch?v=X48VuDVv0do)

- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/165997551-bb8923f1-4bec-409b-b604-b73ddd1049f7.svg">
- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/165997536-0fc77950-4b57-4dd7-9960-1341e6983ca6.png">
- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/165997544-f2b90436-5d0a-4852-b9be-cea8d1ed6af7.png">
- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/165997547-17182379-efbc-414e-8253-d0c593b42f77.png">
- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/165997549-f5b6d977-1e0c-4352-b652-e25e0939a757.png">
- <img style="width: 100%" src="https://user-images.githubusercontent.com/19540357/165997557-f677bf5a-d7d6-4011-a260-fbeeee2e03c0.png">
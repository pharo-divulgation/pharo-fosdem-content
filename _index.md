---
title: Pharo
themes:
 - Programming languages
website: https://www.pharo.org
logo: stands/pharo/Pharo_Beacon_v3.0.png
description: |

 <h3> Open source is about <a href="https://pharo.org/community" target="_blank"> Community </a></h3>
 <p> The only thing we love more than our language, is our community. Pharo, community and our wonderful Smalltalk neighbours. With 28 years running ESUG conference has been our home since always. And we really think that the best way to show how beautiful is our community is by sharing our last experience together, on 2019, at Koln, Germany. 
  We hope COVID-19 to be soon an awful memory, and to come back to feel all this wonderful human beings sharing all this passion.
  
 
  You may join us on our different communications endpoints :)  <br/>
  
  
  Discord: <a href="https://discord.gg/QewZMZa">https://discord.gg/QewZMZa</a> <br/>
  
  Mailing List: <a href="https://lists.pharo.org/">https://lists.pharo.org/</a> <br/>
  
  PharoWeekly: <a href="https://pharoweekly.wordpress.com/">https://pharoweekly.wordpress.com/</a> <br/>
  PharoDev: <a href="https://thepharo.dev/">https://thepharo.dev/</a> <br/>
  
  
 </p>  
 <iframe width="1024" height="615" src="https://www.youtube.com/embed/q9VYlfbdKys" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  


 
 

 
showcase: |
  
  <p>Come to our stand to meet the community behind Pharo. Meet key engineers and researchers behind the language development. Meet the rich multiple communities that pharo hubs, from radically different origins. 
  From public research to private business, from software & language research & development to  human rights hacktivism, Pharo community is a really rich meltingpot of international technological improvement, political struggle and beautiful human exchange!   </p>
  

  
  Pharo is a smalltalk inspired language. Smalltalk is recogniced as one of the most elegant languages ever existed. Besides the aesthetics, Pharo, as any other small talk language, provides a live programming experience. Something that is mind blowing for most of the people coming from other technologies. Finally, the community of Pharo is a human size community, where people's opinion matter, and there contribution is made easy. Newcomers are always welcome :). 
  Pharo is a pure object-oriented programming language and a powerful environment, focused on simplicity and immediate feedback (think IDE and OS rolled into one). Simple & powerful language: No constructors, no types declaration, no interfaces, no primitive types. Yet a powerful and elegant language with a full syntax fitting in one postcard! Pharo is objects and messages all the way down. Live, immersive environment: Immediate feedback at any moment of your development: Developing, testing, debugging. Even in production environments, you will never be stuck in compiling and deploying steps again! Amazing debugging experience: The Pharo environment includes a debugger unlike anything you've seen before. It allows you to step through code, restart the execution of methods, create methods on the fly, and much more! Pharo is yours: Pharo is made by an incredible community, with more than 100 contributors for the last revision of the platform and hundreds of people contributing constantly with frameworks and libraries. Fully open-source: Pharo full stack is released under MIT License.

new_this_year: |
 Pharo language has two faces, the industrial face and the research face. This last year we have been brewing many new things. Language/VM: We have take over the development of the JIT Compiler, implement a large battery of tests. Extend it to ARM64bits. We implemented a new system for threaded FFI calls, that allow us to have partial parallelism. We added new technologies on concurrent programming, that allow consistent definition of tasks and at some point binding with FFI threads if it is the case. IDE: We are working on automated distributed testing for reduce the testing time of the projects, allowing the developers to quickly run tests on development. We have been developing bindings to GTK, and extending our own IDE to have multiple bindings (so far, GTK and Morphic -a native approach-). We are beta testing our new debugger, and inspecting tools for live programming development. Including replay, object specific debugging, and other state of the art features. We implemented a markdown subset parser and rendered for having the language comments written in markdown. Learning: Full new Mooc online: https://www.fun-mooc.fr/courses/course-v1:inria+41024+session01/about 
layout: stand
---
This article is based the french magazine Programmez! #244
[https://www.programmez.com/magazine/article/smalltalk-le-retour-dun-langage-mythique-0](https://www.programmez.com/magazine/article/smalltalk-le-retour-dun-langage-mythique-0)
And on the [https://nootrix.com/fr/tutoriels/smalltalk-magazine-2020-11/?elementor-preview=1195&ver=1608481092#introduction](https://nootrix.com/fr/tutoriels/smalltalk-magazine-2020-11/?elementor-preview=1195&ver=1608481092#introduction) 


Introduction 
==============


Smalltalk is not the best known programming language. And yet, it played a huge role in microcomputing and the great technological revolutions of the 70s and 80s. 
We invites you to discover and rediscover this fantastic language before taking a long look at Pharo, a modern implementation of Smalltalk.

40 years has passed from the born of smalltalk, and still its syntax (remarkably simple), has not been modified. 
If you've ever heard of Smalltalk, you may also have heard that its syntax fits on a simple postcard. 
This is neither a legend nor an exaggeration: one postcard is indeed enough to define the entire syntax of Smalltalk.
![Postcard](https://i2.wp.com/nootrix.com/wp-content/uploads/2020/12/pharoSyntax.jpg)
As you have seen, Smalltalk syntax is both shockingly simple and incredibly powerful.




Pharo is a direct and free descendant of Smalltalk, launched in 2008 under MIT license. It combines stability and innovation, thanks to a community that includes both companies and academic institutions.

Forget about files! when we code, we think in terms of packages, classes and methods. It is precisely these concepts that are put forward by Pharo's System Browser tool.

2 files to control them all. The Pharo developer creates and initializes the objects that make up the program. Then, he saves the contents of the working memory in a binary file called image. At runtime, the Pharo virtual machine transfers the contents of the image file to the RAM memory. All the saved objects are then ready to use. The majority of the initialization operations being made during the development, the loading of the program is done at lightning speed! 

Interactive test-driven development. Another feature of Pharo is its ability to replace code while it is running. Application development can thus be carried out incrementally. The fields and methods needed are added as features are introduced. Objects are automatically updated by Pharo in order to integrate the changes without ever having to restart any interpreter or recompile files. 

This interactivity combines perfectly with the TDD (Test Driven Development) approach of test-driven development, well known in agile project management methodologies.










---
title: "0- The return of a mythitcal programming language"
---
![Pharo](https://pharo.org/web/files/pharo.png)

This article is based the french magazine [Programmez! #244](https://www.programmez.com/magazine/article/smalltalk-le-retour-dun-langage-mythique-0)
and on the [Nootrix article](https://nootrix.com/fr/tutoriels/smalltalk-magazine-2020-11/?elementor-preview=1195&ver=1608481092#introduction) 






​​​​​





​​​​​

Introduction 
==============


Smalltalk is not the best known programming language. And yet, it played a huge role in microcomputing and the great technological revolutions of the 70s and 80s. 
We invites you to discover and rediscover this fantastic language before taking a long look at Pharo, a modern implementation of Smalltalk.

40 years has passed from the born of smalltalk, and still its syntax (remarkably simple), has not been modified. 
If you've ever heard of Smalltalk, you may also have heard that its syntax fits on a simple postcard. 
This is neither a legend nor an exaggeration: one postcard is indeed enough to define the entire syntax of Smalltalk.
​​​​​

As you have seen, Smalltalk syntax is both shockingly simple and incredibly powerful.



Time passes really fast! Pharo 8.0 was alpha on ESUG '19! Today, our alpha Pharo version, is Pharo 9.0. 


This video is from ESUG 19. When Pharo 8.0 alpha features were presented! Today we are having way more interesting things to share, but COVID imposed it self on ESUG last year. 

{{<youtube qSKqB2R3yGU>}}
​​​​​





​​​​​


Power of simplicity 
==================	





​​​​​
Pharo is a direct and free descendant of Smalltalk, launched in 2008 under MIT license. It combines stability and innovation, thanks to a community that includes both companies and academic institutions.

Forget about files! when we code, we think in terms of packages, classes and methods. It is precisely these concepts that are put forward by Pharo's System Browser tool.

2 files to control them all. The Pharo developer creates and initializes the objects that make up the program. Then, he saves the contents of the working memory in a binary file called image. At runtime, the Pharo virtual machine transfers the contents of the image file to the RAM memory. All the saved objects are then ready to use. The majority of the initialization operations being made during the development, the loading of the program is done at lightning speed! 

Interactive test-driven development. Another feature of Pharo is its ability to replace code while it is running. Application development can thus be carried out incrementally. The fields and methods needed are added as features are introduced. Objects are automatically updated by Pharo in order to integrate the changes without ever having to restart any interpreter or recompile files. 

This interactivity combines perfectly with the TDD (Test Driven Development) approach of test-driven development, well known in agile project management methodologies.







​​​​​





​​​​​

The Pharo's Virtual Machine
===========================






This VM has interesting capabilities that highlight the power of Smalltalk. In addition, it is an excellent VM for both research and production use because of its long and rich history and its very promising future.

The VM Pharo is the product of a continuous evolution over a long period of time. It includes elements that were introduced in the original versions of Smalltalk and have evolved since then. It includes modern techniques such as Just In Time compilation and advanced automatic garbage collectors.

One of the main advantages of the VM Pharo is that it is written in Pharo. It can be run like any other Pharo program. This allows us to write tests, to simulate the execution of the VM, to modularize it, to use all existing Pharo tools and to document it like any other program. 

By testing, and writing the source code of the virtual machine on Pharo it self, we are not only looking for fancing and for high level language power, but specially to desmythify the subject, and to empower humans to enage on the virtual machine development.  This is what we consider to be truly open-source version.

The Pharo VM is available for 64-bit ARM/x86/x64; updated versions for Windows, Linux and Mac. 

The following video shows the first steps of Pharo VM 




​​​​​


{{<youtube MGivF9O8vn4>}}







​​​​​





​​​​​

Iceberg: How did Pharo came to use GIT
=======================================



​​​​​


For the past two years, Pharo has offered a very close integration with the Git backend manager, which replaced Monticello, the version manager Pharo had been using since 2008. Not only can projects written in Pharo be stored on Git forges and repositories, but the Pharo project itself is managed with a Git repository. 

Iceberg (our tool for GIT integration) offers the best of both worlds: programming with living objects, one of Smalltalk's fundamental concepts, and transparent text backup as the IDEs on the market traditionally do.

To simplify the installation of Pharo and Git Uceberg uses the libgit library, which implements the basic Git functionalities, and is written in C in a portable way. Iceberg use libgit via the UnifiedFFI library.

UnifiedFFI allows to interface Pharo with extensive libraries. FFI allows to apply external libraries that have a standard calling convention, such as C code, with a dynamic link.

The following video shows how Icerberg makes our lives happier 





​​​​​





​​​​​

{{<youtube -ujX0Jt7-64>}}










​​​​​





​​​​​






​​​​​





​​​​​
TaskIt: The concurrent tasks framework
=======================================


TaskIt appear on the context of the development of robotics applications. It came to introduce different concepts required to properly address processing on the Pharo image. 
After many years of development and refinement by usage in multiple contexts, TaskIt has been finally accepted and incorporated into the Pharo 9 image.
TaskIt counts with different processing architectures within the image such as Workers, UI task runners, and single shot runners. TaskIt also counts with a pool form managing architectural concurrency. 





​​​​​





​​​​​
TaskIt presentation at ESUG 19
{{<youtube jDEYNRqhDf4>}}




![Pharo](https://pharo.org/web/files/pharo.png)

 Is a pure object-oriented programming language and a powerful environment, focused on simplicity and immediate feedback (think IDE and OS rolled into one).
 Check out our website! [https://www.pharo.org/](https://www.pharo.org/)
 
**Simple & powerful language**

No constructors, no types declaration, no interfaces, no primitive types. Yet a powerful and elegant language with a full syntax fitting in one postcard! Pharo is objects and messages all the way down.

**Live, immersive environment**

 Immediate feedback at any moment of your development: Developing, testing, debugging. Even in production environments, you will never be stuck in compiling and deploying steps again!

**Amazing debugging experience**

 The Pharo environment includes a debugger unlike anything you've seen before. It allows you to step through code, restart the execution of methods, create methods on the fly, and much more!

**Pharo is yours**

 Pharo is made by an incredible community, with more than 100 contributors for the last revision of the platform and hundreds of people contributing constantly with frameworks and libraries.


**Fully open-source**

 Pharo full stack is released under MIT License.
  
**Full of Awesome :)**

Pharo environment count with many awesome libraries and frameworks! [Awesome Pharo](https://github.com/pharo-open-documentation/awesome-pharo)


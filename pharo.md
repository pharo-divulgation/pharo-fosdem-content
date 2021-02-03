---
title: "1 - The Return of a Mythical Programming Language"
---

{{< figure src="/stands/pharo/Pharo_Beacon_v3.0.png" title="" width="30" link="https://www.pharo.org" target="_blank">}}
[Stand](/stands/pharo) | [Next](/stands/pharo/learning-pharo) 

This article is based the french magazine [Programmez! #244](https://www.programmez.com/magazine/article/smalltalk-le-retour-dun-langage-mythique-0)
and on the [Nootrix article](https://nootrix.com/fr/tutoriels/smalltalk-magazine-2020-11/?elementor-preview=1195&ver=1608481092#introduction) 






​​​​​


TEST FOR EMbeDDING VIDEO: 

<div class="video">
  <video preload="none" controls="controls">
    <source src="http://rmod-files.lille.inria.fr/Videos/UnitGraine-object-oriented-programming-Ducasse.mp4" type='video/mp4;' />
  </video>
</div>



​​​​​

Introduction 
==============


Smalltalk is not the best known programming language. And yet, it has played a huge role in microcomputing and the great technological revolutions of the 70s and 80s. We invite you to discover and rediscover this fantastic language before taking a long look at Pharo, a modern Smalltalk implementation.

40 years has passed since Smalltalk was born, and still its remarkably simple syntax has not been modified. 
If you've ever heard of Smalltalk, you may also have heard that its syntax fits on a simple postcard. 
This is neither a legend nor an exaggeration: one postcard is indeed enough to define the entire syntax of Smalltalk.
​​​​​Smalltalk syntax is both shockingly simple and incredibly powerful!


Time passes really fast! Pharo 8.0 was alpha on ESUG '19! Today, our alpha Pharo version is Pharo 9.0.
The following video, from the ESUG'19 conference, showcases the features of the Pharo 8.0 alpha release.
The upcoming 9.0 version has way more interesting things to share!

{{<youtube qSKqB2R3yGU>}}
​​​​​



​​​​​


Power of simplicity 
==================	





​​​​​
Pharo is a direct and free descendant of Smalltalk, launched in 2008 under the MIT license.
It combines stability and innovation, thanks to a community that includes both companies and academic institutions.

Forget about files! When we code, we think in terms of packages, classes and methods.
It is precisely these concepts that are put forward by Pharo's IDE.
We have **2 files to control them all**. The Pharo developers creates and initializes the classes and objects that make up the program. Then, they save the contents of the working memory in a binary file called an image. At runtime, the Pharo virtual machine transfers the contents of the image file to the RAM memory. All the saved objects are then ready to use. The majority of the initialization operations being made during the development, the loading of the program is done at lightning speed!

Another key feature of Pharo is its ability to replace code while it is running, allowing **interactive test-driven development**. Application development is carried out incrementally. Fields and methods are added as they are needed. When such changes happens, objects are automatically updated without ever having to restart the program or do a full recompilation.
This interactivity combines perfectly with the TDD (Test Driven Development) approach of test-driven development, well known in agile project management methodologies.







​​​​​





​​​​​

The Pharo's Virtual Machine
===========================




The Pharo VM has interesting capabilities that highlight the power of Smalltalk. In addition, it is an excellent VM for both research and production use because of its long and rich history and its very promising future. The Pharo VM is the product of a continuous evolution over a long period of time. It includes elements that were introduced in the original versions of Smalltalk and have evolved since then. It includes modern techniques such as Just In Time compilation and advanced automatic garbage collectors.

One of the main advantages of the Pharo VM is that it is written in Pharo and can be run like any other Pharo program. This allows us to test and simulate it, while using existing Pharo tools on it like any other program. 
By testing, and writing the source code of the virtual machine on Pharo itself, we are not only looking for fancing and for high level language power, but specially to demystify the subject, and to empower developers to get into the virtual machine development. This is what we consider to be a truly open-source version.

The Pharo VM is available for ARMv7, ARMv8, x86 and x86-64; updated versions for Windows, Linux and Mac. 
The following video shows some of the latest steps done on the Pharo VM:




​​​​​


{{<youtube MGivF9O8vn4>}}







​​​​​





​​​​​

Iceberg: How did Pharo came to use GIT
=======================================



​​​​​


For the past two years, Pharo has offered a very close integration with the Git backend manager, which replaced Monticello, the version manager Pharo had been using since 2008. Not only can projects written in Pharo be stored on Git forges and repositories, but the Pharo project itself is managed with a Git repository. 

Iceberg (our tool for GIT integration) offers the best of both worlds: programming with living objects, one of Smalltalk's fundamental concepts, and transparent text backups as the IDEs on the market traditionally do.

To simplify the installation of Pharo and Git Iceberg uses the libgit library, which implements the basic Git functionalities, and is written in C in a portable way. Iceberg uses libgit via the UnifiedFFI library.
UnifiedFFI allows to interface Pharo with extensive libraries. FFI allows to apply external libraries that have a standard calling convention, such as C code, with a dynamic link.

The following video shows how Icerberg makes our lives happier:





​​​​​





​​​​​

{{<youtube -ujX0Jt7-64>}}










​​​​​





​​​​​






​​​​​





​​​​​
TaskIt: The concurrent task framework
=======================================


TaskIt appears on the context of the development of robotics applications, introducing concepts to address concurrent processing on Pharo. 
After many years of development and refinement by usage in multiple contexts, TaskIt has been finally incorporated into the standard Pharo 9 release.
TaskIt counts with different processing architectures within the image such as Workers, UI task runners, and single shot runners. TaskIt also counts with worker pools to manage architectural concurrency. 





​​​​​





​​​​​
The following presentation showcases TaskIt at ESUG 19
{{<youtube jDEYNRqhDf4>}}

​​​​​


​​​​​




[Pharo](/stands/pharo/pharo) 
| [Learning Pharo](/stands/pharo/learning-pharo) 
| [Contribute!](/stands/pharo/contribute-pharo)
| [Visualizations](/stands/pharo/visualfwk)
| [The Moose Platform](/stands/pharo/pharo-software-analysis)
| [Interoperability](/stands/pharo/pharojs)
| [Some fun :)](/stands/pharo/fun-with-pharo)
| [Using blockchain](/stands/pharo/pharo-blockchain)
| [Robotics, AI and mathematics](/stands/pharo/pharo-robotics)
{{< figure src="/stands/pharo/Pharo_Beacon_v3.0.png" title="" width="30" link="https://www.pharo.org" target="_blank">}}


---
title: Pharo
themes:
 - Community advocacy
website: https://www.pharo.org
logo: stands/pharo/Pharo_Beacon_v3.0.png
description: |


 
 <h3> The community </h3>
 <p> The only thing we love more than our language, is our community. Pharo, community and our wonderful Smalltalk neighbours. With 28 years running ESUG conference has been our home since always. And we really think that the best way to show how beautiful is our community is by sharing our last experience together, on 2019, at Koln, Germany. 
  We hope COVID-19 to be soon an awful memory, and to come back to feel all this wonderful human beings sharing all this passion. 
 </p>

  
 <iframe width="1024" height="615" src="https://www.youtube.com/embed/q9VYlfbdKys" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 

 
showcase: |
  
    <p>Come to our stand to meet the community behind Pharo. Meet key engineers and researchers behind the language development. Meet the rich multiple communities that pharo hubs, from radically different origins. 
     From public research to private business, from software & language research & development to  human rights hacktivism, Pharo community is a really rich meltingpot of international technological improvement, political struggle and beautiful human exchange!   </p>

    <h5>Our programme at FOSDEM:</h5>
    <ul class="list-unstyled">
        <li>
        <h6>Saturday</h6>
        <ul class="list-unstyled">
            <li><b>entire day</b>: enter in our raffle for a chance to win some Belgian beer</li>
            <li><b>10:00 - 11:00</b>: meet our main video developer V. (chat)</li>
            <li><b>13:00 - 14:00</b>: behind the scenes: FOSDEM setup (video)</li>
            <li><b>16:00 - 17:00</b>: how do I sign up for volunteering (chat & video)</li>
        </ul>
        </li>
        <li class="mt-2">
        <h6>Sunday</h6>
        <ul class="list-unstyled">
            <li><b>entire day</b>: enter in our raffle for a chance to win some Belgian beer</li>
            <li><b>10:00 - 10:30</b>: an inside look in the cloak room (video)</li>
            <li><b>13:00 - 14:00</b>: Q&A with the mysterious network team (chat)</li>
            <li><b>15:00 - 16:00</b>: announcement of the winners of our Belgian beer (chat)</li>
        </ul>
        </li>
    </ul>

new_this_year: |
    In 2021

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










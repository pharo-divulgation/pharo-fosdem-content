---
title: "4- The Moose Platform: the Pharo platform for software analysis"
---
{{< figure src="/stands/pharo/Pharo_Beacon_v3.0.png" title="" width="30" link="https://www.pharo.org" target="_blank">}}
[Previous](/stands/pharo/visualfwk) | [Stand](/stands/pharo) | [Next](/stands/pharo/pharojs) 

{{< figure src="https://moosetechnology.org/pictures/moose-icon.png" title="" width="100" link="http://www.modularmoose.org" target="_blank">}}

Moose is a free and open source platform for software and data analysis built in Pharo.

Moose offers multiple services ranging from importing and parsing data, to modeling, to measuring, querying, mining, and to building interactive and visual analysis tools. Moose was born in a research context, and it is currently supported by several research groups throughout the world. It is increasingly being adopted in industry. 

Presentation of the platform novelties at ICSR20
-------------------

​​​​​{{<youtube It2Oy18Pi_s>}}

​​​​​



Overview
---------
​​​​​The philosophy of Moose is to enable the analyst to produce new dedicated analysis tools, and to customize the flow of analysis. While Moose is mainly used in software analysis, it is built to work for any data.

To achieve this it offers multiple mechanisms and frameworks:

1. Importing and meta-meta-modeling is achieved through a generic meta-described engine. Any meta-model is described in terms of a self-described meta-meta-model, and based on this description, the import/export is provided through the MSE file format. Through this file format, Moose can exchange data with external tools.
2. For parsing, Moose provides a novel framework that makes use of several parsing technologies (like parsing expression grammar) and that provides a fluent interface for easy construction.
3. Software analysis is specifically supported through the FAMIX family of meta-models. The core of FAMIX is a language independent meta-model that is similar to UML but it is focused on analysis. Furthermore, it provides rich interface for querying models.
4. Visualization is supported through two different engines: one for expressing graph visualizations, and one for expressing charts. They both provide a fluent interface for easy construction.
5. Browsing is an important principle in Moose, and it is supported in multiple ways as well. A generic interface enables the analyst to browse any model. To be able to specify specific browsers, Moose offers a generic engine that eases the specification through a specific fluent interface.



Documentation
------------

From [Installing](https://moosetechnology.github.io/moose-wiki/Beginners/InstallMoose.html)
To [Creating custom metamodels](https://moosetechnology.github.io/moose-wiki/Developers/CreateNewMetamodel.html)
Moose counts with a large documentation on the github page [MooseWiki](https://moosetechnology.github.io/moose-wiki/)





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
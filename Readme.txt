Copyright 2015 by Academy of Mathematics and Systems Science Chinese Academy of Sciences(University of Chinese Academy of Sciences)

GMap1.0 is a tool for ontology matching, which combines the sum-roduct networks and noisy-or model. 

Time:8/31/2015  Author:Weizhuo Li & Qilin Sun  EMail:liweizhuo2014@gmail.com

Software: Java 1.6 or higher. 
Hardware: 2GB RAM or more. If you want to  match the larger ontologies such as mouse.owl and human.owl, you need at least 16GB RAM(you can set the arguments of virtual machine as "-Xms10000m -Xmx15000m" in the Run Configurations). The CPU is not limited, but we still hope that the CPU in your computer is as efficient as possible, which can reduce a lot of time consumption.

Usage for OAEI2015
This distribution of GMap has been wrapped according the SEALS platform (http://www.seals-project.eu/) requirements in order to participate in the OAEI evaluation campaign (http://oaei.ontologymatching.org/). Section 5.2 of the OAEI wrapping tutorial (http://oaei.ontologymatching.org/2015/tutorial/tutorialv4.pdf) explains how to run a SEALS-like tool using the SEALS OMT Client (http://oaei.ontologymatching.org/2015/tutorial/seals-omt-client.jar)


Usage for personal computer 
a)If you install Eclipse, you can import this project directly and run the MatcherBridge.java. There are some ontologies saved in file named Ontologies and you can use them to test GMap.

b)If you want to run the GMap by the command line. you only to finish three steps:
1. Use the command line to enter the root directory of GMap project(OM_SPN). 
2. Ensure that your tested ontologies have been listed in "Ontologies" file.
3. Run command "java -Xms10000m -Xmx15000m -cp .;bin/;lib/* Actions.MatcherBridge file:Ontologies/cmt.owl file:Ontologies/Conference.owl" in Windows environments or Run command "java -Xms10000m -Xmx15000m -cp conf;bin;lib/* Actions.MatcherBridge file:Ontologies/cmt.owl file:Ontologies/Conference.owl" in Linux environments

c)You can replace cmt.owl or Conference.owl with another ontologies, but the format of them should be ".rdf" or ".owl" or ".ttl".

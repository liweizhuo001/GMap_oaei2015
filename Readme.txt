Copyright 2015 by Academy of Mathematics and Systems Science Chinese Academy of Sciences(University of Chinese Academy of Sciences)

GMap is a tool for ontology matching, which combines the sum-roduct networks and noisy-or model. 

Time:8/31/2015  Author:Weizhuo Li & Qilin Sun  Mail: liweizhuo@amss.ac.cn

Software: Java 1.6 or higher. 
Hardware: 2GB RAM or more. If you want to  match the larger ontologies such as mouse.owl and human.owl, you need at least 16GB RAM(you can set the arguments of virtual machine as "-Xms10000m -Xmx15000m" in the Run Configurations). The CPU is not limited, but we still hope that the CPU in your computer is as efficient as possible, which can reduce a lot of time consumption.

Attention: This project may leave out a folder called "lib", you should create this folder with nothing.

Usage for OAEI2015
This distribution of GMap has been wrapped according the SEALS platform (http://www.seals-project.eu/) requirements in order to participate in the OAEI evaluation campaign (http://oaei.ontologymatching.org/). Section 5.2 of the OAEI wrapping tutorial (http://oaei.ontologymatching.org/2015/tutorial/tutorialv4.pdf) explains how to run a SEALS-like tool using the SEALS OMT Client (http://oaei.ontologymatching.org/2015/tutorial/seals-omt-client.jar)

However, This project can not run completely by itself. You can download the whole project as following:
GMap: https://github.com/liweizhuo001/GMap
GMap1.1: https://github.com/liweizhuo001/GMap1.1

More details for Reading:
[1] Li W  "Combining sum-product network and noisy-or model for ontology matching" available at:  http://ceur-ws.org/Vol-1545/om2015_TSpaper1.pdf
[2] Li W, Sun Q.  "GMap: results for OAEI 2015" available at:  http://ceur-ws.org/Vol-1545/oaei15_paper6.pdf

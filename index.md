---
title       : Adaptation on Rugged Landsapes
subtitle    : Summary of Levinthal, 1997
author      : C.W. Dillon
job         : CSS739, COT
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}

--- .class1

### Adaptation on Rugged Landscapes 
   
</br>   
   
* * * * 

A working summary of 
D. Levinthal's 1997 paper

* * * * 
  
</br>
</br>
   
<small> 
[CW Dillon](http://www.css.gmu.edu/?q=node/15) 

for _Computational Organizational Theory_, CSS739

George Mason University
</small>


*** =pnotes

I am a PhD student in the Department of Computational Social Sciences, at the Krasnow Institute for Advanced Studies. We focus primarily on neurosciences and applications of complexity theory from a behavioral perspective. This seminar, by Dr. Maksim Tsvetovat is presented as a special topic in social network analysis.

---

### Overview

* A model of organizational adaptation 
  * I assumed that this is an ABM because of the description 
* Pretty rigid (lots of assumptions)
* L's examples
* Interesting because...

--- .class #id 

### What the Model is About

* Organizations assumed to adapt to fit their environment (or die)
* Survival of the fittest, most adaptable, and luckiest
* Includes a complex adaptive version

---

### Organizations

* Orgs have $N$ attributes
  * Sample model has 10 attributes
  * Initial values are either 0 or 1
* Each attribute assumed to be influenced by $K$ other attributes
  * $K=0$ means each attribute is independent of all others (tightly-coupled)
  * $K=N-1$ means each attribute is dependent on all others (loosely-coupled)

---

### Environment

* Environment is a space with 1 or more peaks
* Number of peaks can reach $2^K$, where $K=N-1$
* Changes in response to number of ``fit'' firms, in CAS version


---

### Adaptations

* In each turn, orgs can alter one attribute to better fit the landscape
* No cost of adaptations
* Assumed that all adaptations are for the better
* Some firms not able to adapt (where $K$ approaches $N-1$)
* Can also change every attribute to random value: ``long jump''

---

### Experiments


---

### Results

* Diversity of orgs can be explained by diversity of the environment
* Tightly-coupled orgs are less likely to survive by adaptation: 
  * change in one attribute impacts many others
  * better to make ``long jumps'' in dynamic landscapes
* Loosely-coupled orgs survive by: 
  * adapting quickly (change is easy)
  * making few ``long jumps''


---

### It's Interesting Because...

* Consider two org types: government offices, restaurants
  * How many attributes determine success? $N$
  * How tightly-coupled are they? $K$
  * How radically does their landscape change?
* Survival or death and replacement





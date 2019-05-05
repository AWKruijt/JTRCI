# JTRCI: Jacobson & Truax reliable change indices

----

A newer version of this package is available at github.com/AWKruijt/JT-RCI (notice the added hyphen). 

I strongly advise switching to JT-RCI for any new projects. This current version is kept online because I know that manuscripts using it in their (shared) syntax are currently under review. In time the old JTRCI version will be removed from github.

In this old version (@ awkruijt/JTRCI) the higherisbetter option does *not* work correctly when type = "JT" (does work for type = "RCI") - the new version (awkruijt/JT-RCI) fixes this and is generally more streamlined. 

When switching, it is good to know that in the new version the following parameter names have changed: 

JT.crit -> JTcrit   
type -> indextype   
norm.M -> normM   
norm.SD -> normSD  

----

Obtain and plot Jacobson and Truax reliable change indices

JTRCI(x.pre = NA, x.post = NA, reliability = NA, ppid = NA, type = "JT", plot = T, table = F, higherIsBetter = F, JT.crit = "auto", norm.M = NA, norm.SD = NA

screenshots:

<img width="460" height="300" src="https://github.com/AWKruijt/JTRCI/blob/master/screenshots/screenshot%20RCI.png">
  
<img width="460" height="300" src="https://github.com/AWKruijt/JTRCI/blob/master/screenshots/screenshot%20plot%20RCI.png">

<img height="300" src="https://github.com/AWKruijt/JTRCI/blob/master/screenshots/screenshot%20JT.png">
  
<img width="460" height="300" src="https://github.com/AWKruijt/JTRCI/blob/master/screenshots/screenshot%20plot%20JT.png">

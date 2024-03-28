#  All my code, factored into small, seperately usable, chunks 

"I wouldn't give a fig for the simplicity on this side of complexity; I would give my right arm for the simplicity on the far side of complexity"    
--  Oliver Wendell Holmes, Sr..

“Any intelligent fool can make things bigger, more complex, and more violent. It takes a touch of genius — and a lot of courage to move in the opposite direction.”  
―- E.F. Schumacher

“I have only made this letter longer because I have not had the time to make it shorter.”    
-— Blaise Pascal

"One of my most productive days was throwing away 1000 lines of code."  
-- Ken Thompson

“Simplicity is a great virtue but ...complexity sells better.”   
-― Edsger Wybe Dijkstra

Seems I can't use gists for this (since I can't assign a name to a gist). So here's my work in tiny chunks with a Makefile system in dotrc/Makefile that syncs all the parts.

All these repos are downloadable and usable in isolation. But here's a detail that, for the most part, you can ignore. Certain extra functions (that I use, and you probably do not care about) are   managed from a master [Makefile](../Makefile) that (e.g.) 

- regenerates the README.md file in repo1 using tools from repo2 
- sets the local read-only bits (which are not shared by Github) so even is a file appears in 2 repos, it can only be updated in one.

Share and enjoy

t

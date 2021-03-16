# Proposals

My ideas for my final project are...
Something must have gone wrong with my submission because I don’t think I received comments. I apologize for the inconvenience. As a result I am just going to go ahead and make the plan for the wikipedia one. If it is insufficient or lacking, I am more than happy to switch to the other proposal. 


Proposal 1:
I come from  a humanities/ social science background, and although professors often discouraged it, Wikipedia’s citations were fertile grounds to starting a comprehension research project. Wikipedia provided the perfect first step to see who were the top scholars on any given  In this project I would hope to build a tool that streamlines the process for starting a research project or delving into a subject. Using the Wikipedia and pywikibot packages, I would like to be able to build an tool that allows you to search for an entry/author/thinker/piece of literature, and gets the citations, footnotes, and quotes that are in a given entry. The tool would scrape the web using Beautiful Soup to collect the links/ documents that are in the footnotes and build a database of the scholarship  that is done for a given entry. Then looking at the list of scholars for a given entry, the tool would look to see if there are any wikipedia entries for a given scholar on a subject and using Google’s scholarly API it would provide links to other works by a given scholar to see what further research they had done and to see whether they had discussed subjects in other entries. Finally, if this is not too much work, I would then hope to visualize connections between authors and entries using Pyvis. 

Week 4: The first goal is to sketch an example of what I want my program to do with a specific article. By the end of the week I would like to familiarize myself with the wikibots and figure out how to search, store a citation, sort out a given citations link,  author, and title (potentially may need to cross reference). I should probably build an object to do this

Week 5: First, I would like to start learning how to use Beautiful Soup to find links, and also use Google’s scholarly API to get relevant information. Second, I want to start structuring what my database would look like, and how I would like to store it. Hopefully I could start populating it as well. 

Week 6: I want to start building the UI part of my tool, prompting to search for an article or to enter their syllabus. And to start building a default database from my own syllabi or different course syllabi

Week 7: This week will be dedicated to building the network that links authors and works. This will make it so that I can start building out sources that relates to a given material, even checking the citations in the author’s own work

Week 8: I will build a tool that collects documents and from a given scholar. I will also have the UI up and running with ways to look a list of documents

Week 9: If I have time I will want to build a visualization feature. If not I will spend my time tweaking so it is fully operational 



Proposal 2:
I would also like to work on data science and visualization tools offered by python. Using packages like numbly, pandas, and marplotlib. I would like to visualize and analyze datasets offered by the Chicago open API. It may change, but there a few ideas that have come to mind for me. Using Crime data by zip code I could see the extent to which covid case rates were potentially related to different crimes like domestic battery, abuse, etc, and I could even run some simple regressions. Using other available datasets on the Chicago api like Income by Zip Code or “L” train entry by station, I would show look for further patterns between covid cases, vaccination rates and sociological trends Alternatively, Chicago offers extensive data on covid cases and deaths by zip code and now it seems they have started collecting data on vaccinations/ first dose vaccinations by zip code as well. At the most basic levels, I would like to visualize these datasets using Marker, google Earth Api, or using a Chicago shapefile. The goal would be to show the populations most effected by covid and whether there is an equitable vaccination effort in those areas. Yet, much of this data is already available and visualized on most major news websites. I would like to dig a bit deeper to find some trends or telling information. 

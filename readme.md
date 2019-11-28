---
title: "AGILE PhD School - Key Takeaways"
author: "Marcin Szwagrzyk"
date: "28 11 2019"
output: html_document
---

## Visualisation
I came to PHD School with a particular visualisation problem - I even presented it on monday:
how to visualize hundreds of modelling areas, and results for those units? 
Those areas are aggregations of basic units - like communes - and it is hard to show them at once (they overlaying each other). 

On Tuesday we had a workshop with Topi Tjukanov and I liked vey much two things Topi showed us:

QGIS blending styles helped me to some extent to display features that overlay each other
![land use modelling areas](areas.png)


Time Manager also is very nice to show the quantity of modelling areas:
![gif](gif.gif)

I have still some ideas about visualisazing trajectories in spatial units and I will
still look for a nice ways how to do it.


## Reproducibility
On Wednesday we had a workshop about reproducibility: version control, repositories etc..
Reproducibility guidelines which we get to know are mostly about the data, tools and software used in a paper. 

The data should be accesible and licensed.
During my Phd I used the same set of input data that  was  described in a paper I am a co-author:

![legacies](legacies.png)
![legacies_results](results.png)

It was a simple dataset: one land cover map and 12 explanatory variables maps.
Data from this paper was meant to be make public. So I think there will be no problem to put it into repository.


And as I mentioned before - I used hundreds of modelling areas, but they were generated automatically from just 3 sets of basic units.


The computional environment should be provided and doccmented.

My whole modelling procedure was developed in Python, with using of diffrent libtraries (like ArPy, pandas, scikit learn, matplotlib)

All of this code I uploaded already (yesterday and today) on my GitHUB repository
[my repository](https://github.com/marcinszwagrzyk/LandUse_MAUP_model)
![my repository](git.png)

But the code is now very unclean and need to be polished, before being ready to be reused by somebody else on diffrent data.



## Science Communication
Topic of my Phd is generally hard to communicate because it touches two major fields: land use modelling (GIS oriented, modern field) and MAUP (classical geograpical theory). Thera are few people who are fmiliar with both of those topics.

But in general, the readers of my work will  rather the people who work with land use models. So, there are mostly geographers. The benefit they will get from reading my work is that they will have a guideline how to proceed with land use modelling

But my Phd thesis has one disadavntage: it is in Polish. So the audience is now very limited.
Writing a paper in English will be much better.
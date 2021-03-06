# Sharks location and global warming

## Introduction

The idea of this project was to investigate if the provided data confirmed some theories about the new patterns of shark attacks, and its relation with global warming. Two locations were explored in this analysis: Florida and New South Wales.

Besides this investigation, another goal was to import data from excel, clean it, and investigate if they matched with the theories read previously.




![Sharks](https://github.com/guilhermeoliveiradoc/Shark-Project/blob/main/shark1.jpg)



## Seting up the problem

Annualy the blacktip sharks migrate from North Carolina to southern Florida during the coldest months. Acording to the biologist Stephen Kajiura, this pattern has been disturbed by the unusual heat of the season, that desistimulates the male sharks to change their locality.
This could be verified by analysing the number of attacks in Florida - they should have suffered a decrease if this statement is true.

Something similar happens to the cenario in New South Wales: the number of attacks increased dramatically in the last 10 years, and fattal atacks are becoming more common.

According to the newspaper The Guardian, the scientists also consider that the idiosyncrasies of ocean upwellings, currents and fish distribution, are affecting the way this predator is moving - after all, they usually go after their prey. This may be a reason to the increasing overlapping with humans.

Considering the information above, some questions were made to guide the project:

- the attacks are rising?  If so, how did it behave in the last decade and years?

- is the local of attacks changing?  How could I check that using the shark attack database?

- what could be the reasons for the changes, if verified?

- is there any other information that corroborates the hypotesis?





![Florida](https://github.com/guilhermeoliveiradoc/Shark-Project/blob/main/florida.JPG)



## Processing the data

The first action was to import the database and make some changes on it, in order to organize the information in separated columns. After that, some operations were made to check if my main variables were valid, and if modifications were needed.

There were some invalid information in the 'Year' and 'Fatal' column that were adjusted, and also a data domain were set - I considered the data stored after 1900's, were the quality and stability of the occurences are more reliable.

The next step was to calculate where were the places the attacks were more frequent, and a brief investigation on the locations that has been suffering this alterations were made - for instance, I analised the number of attacks for North Carolina to check if it suffered a increase in the attacks rating as the articles were mentioning, and indeed it has increased.



## Results

The main areas that occurs shark attacks are:


Florida - 31.2%

New South Wales - 11.6%

California - 8%

Queensland - 7.3%

Hawaii - 7.1%


And Countries:


USA: 51%

Australia: 26%

South Africa: 12.8%

New Zeland: 2%

Brazil: 1.9%



Both the hypotesis seem to be corroborated by the data. In Florida there were a decrease in the overall attack cases in the last decade, and also in the last 5 years:

Last Decade:     13.9% of decrease

Last 5 years:     6.5% of decrease

Max cases:        44 in 2003

Mean:             11 cases/year


![Gr??fico Florida](https://github.com/guilhermeoliveiradoc/Shark-Project/blob/main/florida11.JPG)


* one conflicting data is that between 1997 and 2007, the number of attacks increased by 71%. The articles mentioned that surfers are exploring more beaches that were not acessible before, and the population in general have more access to the coast, making the encounters with sharks more likelly to occur. It's a intersting toppic to look for more information.

The data for North Carolina also confirmed the biologist: there has been a rise in the number of cases.

Between 2005 - 2016:      2.81 cases / year

Between 2011 - 2016:       3,83 cases / year

The highest point was in 2015, with 8 cases


![North Carolina](https://github.com/guilhermeoliveiradoc/Shark-Project/blob/main/NC1.JPG)


The data related to New South Wales also paired with the biologist's saying. The area experienced a significant rise in its mean between the two decades observed.

Between 1997 - 2006:      3.55 atacks / year

Between 2016 - 2007:      11.1 attacks / year

The mean of the whole period:   3.64 attacks/ year

The peak was in 2009, with 19 attacks


![New South Wales](https://github.com/guilhermeoliveiradoc/Shark-Project/blob/main/nsw1.JPG)


## Another interesting factor
During the research and readings, a information seemed relevant to the context: we can see the overall increase in the attacks, even with the population of sharks dramatically smaller. According to The Guardian:

    _"Tiger shark numbers have dropped by more than 70% in the past 30 years. As for whites? Recent surveys of the species, legally protected as ???vulnerable???, suggest their numbers are stable, although population modelling indicates they may be increasing slightly"_

This might be an indicator that the changes in the fish and shark distribution are rapdly advancing.



## References
1. https://www.nationalgeographic.com/environment/article/costa-rica-shark-island-now-massive-marine-reserve
2. https://www.tampabay.com/environment/blacktip-sharks-begin-annual-migration-to-floridas-south-atlantic-coast-20190228/
3. https://www.nationalgeographic.com/animals/article/animals-sharks-oceans-global-warming
4. https://oceanleadership.org/more-sharks-ditching-annual-migration-as-ocean-warms/
5. https://edition.cnn.com/2020/01/22/us/florida-shark-attack-capital-trnd/index.html
6. https://www.firstcoastnews.com/article/life/animals/a-history-of-shark-attacks-in-florida-jacksonville-tampa-west-palm-beach-stuart-pensacola-panama-city-fernandina/77-880716c6-d500-4cb5-9f8c-6ae376692873
7. https://www.mynews13.com/fl/orlando/news/2019/01/28/shark-attacks-are-down--but-florida-is-still-shark-bite-capital

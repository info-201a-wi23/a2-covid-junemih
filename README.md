# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?

100 million

Guess: How many total COVID-related deaths do you think there have been in the U.S.?

1 million

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?

Either New York or California have the highest number of cases, and the states with the lowest populations such as Wyoming and Vermont likely have the lowest number of cases.

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences

The number of COVID cases and deaths did not surprise me because I was vaguely familiar of the figures from watching the news. The state with the highest number of cases did not surprise me because I know that California has both a high population and a high population density. I was shocked about the lowest number of cases however, because my guesses did not line up with the actual results.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

The county with the highest number of cases in Washington is Pierce county, and I am actually not surprised because I knew this earlier from the news.

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

There are so many observations because many counties have the same lowest deaths count, meaning that there are multiple counties in each state that have the lowest death count. This may be due to the location of treatment sites. 

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

I think that the datasets are all so incredibly large that these inconsistencies do not make me question the accuracy of the data very much. 27 rows that are slightly different in count out of thousands and thousands of rows of data is to be expected, in my opinion. Just because the data may have been collected slightly differently does not mean that it is completely inaccurate. I believe that this data is still fair to use.

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

I was interested in this question because it helps represent that individual timeline for Washington state in regards to the highest peak in new COVID cases. I was able to answer the question with code by adding a new_cases column to the states dataset and finding the row with the highest number of new cases. I did not have an estimate of when the highest COVID peak was for Washington, so I gained more insight on that by answering the question I created.

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences

I thought that the section where the new_cases data was compared between two dataframes was really interesting, and it is a good way to test the stability of the data that is being collected. I would likely run the same test if I was presented with a similar data wrangling project.
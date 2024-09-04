This project features an analysis of more than 700 CNN articles encompassing a 1-year time period collected via webscraping. 
The articles were selected on basis of their focus on the subject of Donald Trump, 
with a grammatical form check of the titles to ensure that the articles are really centered on him rather than incidentally mentioning him. 

The analysis itself is performed by the pre-trained Roberta model, which processes texts and outputs three ratings, 
totalling 1 together, that reflect the level of positivity, neutrality and negativity of the content. 
I have subjected all the selected articles to evaluation by this model: this required to cut them into smaller pieces below a certain cap of words numbers,
because in integral form they coulnd't be processed by the model. 

Then based on the articles' chronological metadata, they were grouped by calendar weeks over the period (Aug. 23- aug. 24), 
and the evolution of average ratings for each weekly bucket was plotted. 
On base of the model's results was also constructed an Indicator reflecting the balance between the negative and positive ratings, 
then placed on a scale of 20. The evolution of the weekly average of this Indicator was plotted as well. 

Trump is a subject that generates at least 1 checked article per Week and in but majority of weeks over 15. 
The general trend of the ratings indicates a hostile neutrality from the articles' writers, 
the negative rating being as a rule considerably higher than the positive one, between 10 and 3 times with a few exceptions. 
Subsequently, I have deepened the analysis at the level of the weeks presenting some sort of diverging ratings compared to the other weeks: 
the articles of these weeks were retrieved, read fully or skim read, and the events treated by the articles and likely to explain the variations Added as annotations on the global rating plot. 

In addition to being in the project notebook, the plot with its annotations is shown below.

![CNN Score over 1 Year aug  23-aug 24](https://github.com/user-attachments/assets/52bfbad4-a115-4b2e-bd62-d59d6594c76d)

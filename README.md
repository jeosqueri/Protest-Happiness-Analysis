# 				Protest for Happiness Analysis

![](Images/HandsOffMyMetaData.png)

##### Project written and analyzed by:

* Fereshteh Aghaei
* Jen Mahon
* Julia Squeri
* John Shuford

## Hypotheses and Research Questions

### Hypotheses
1) There will be regional differences in protest size, amount of protests occuring, and the reason behind the protests.
2) If there are a large amount of protests in a country, then the country will have lower happiness and freedom scores.

### Research Questions
- Protest Count: How many total protests occurred per region? How does this differ between the regions and countries?

- Protest Size: How many people attended the protests per region?

- Protest Reason: What were the reasons for the protests? How do these differ between the regions?

- Happiness Score: Do the number/frequency of protests in a country affect how happy the country is?

- Freedom Score: Does a country's freedom score correlate with the amount of protests occurring?

#### Final Observation and Analysis:[¶](https://render.githubusercontent.com/view/ipynb?commit=2160380f00eb403082d3066c06badd78de8864ea&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6a656f7371756572692f70726f6a656374312f323136303338306630306562343033303832643330363663303662616464373864653838363465612f50726f746573745f466f725f48617070696e6573735f50726f6a6563742e6970796e62&nwo=jeosqueri%2Fproject1&path=Protest_For_Happiness_Project.ipynb&repository_id=305556791&repository_type=Repository#Final-Obesrvation-and-Analysis:)

## Protest Analyses 

#### Protest Count
- There were significantly more protests in Europe than in Asia or South America.
- There were also differences in the number of protests per country, with Germany having the most protests in Europe, China having the most in Asia, and Brazil having the most in South America.

<img width="482" alt="Screen Shot 2020-10-28 at 4 03 54 PM" src="https://user-images.githubusercontent.com/69160361/97501660-46674200-1937-11eb-9335-988a552e9e12.png">

<img width="938" alt="Screen Shot 2020-10-28 at 4 04 07 PM" src="https://user-images.githubusercontent.com/69160361/97501673-4f581380-1937-11eb-9e0e-23d2594b5ae5.png">

<img width="932" alt="Screen Shot 2020-10-28 at 4 04 12 PM" src="https://user-images.githubusercontent.com/69160361/97501701-5b43d580-1937-11eb-9fb4-dd6c4ff4d455.png">

<img width="930" alt="Screen Shot 2020-10-28 at 4 04 21 PM" src="https://user-images.githubusercontent.com/69160361/97501723-6434a700-1937-11eb-937d-100f3e06e939.png">


#### Protest Size
- Most of Asias protests were smaller
- For all three regions, a general observation is that most protests were either smaller (50-200) or very large

<img width="463" alt="Screen Shot 2020-10-28 at 4 05 52 PM" src="https://user-images.githubusercontent.com/69160361/97501783-829aa280-1937-11eb-91b6-df3d4028a82e.png">


#### Protest Type
- For each of the three regions, the most common reason for protests was political behavior.

<img width="435" alt="Screen Shot 2020-10-28 at 4 05 59 PM" src="https://user-images.githubusercontent.com/69160361/97501806-90e8be80-1937-11eb-83de-99a2b540d010.png">

<img width="424" alt="Screen Shot 2020-10-28 at 4 06 06 PM" src="https://user-images.githubusercontent.com/69160361/97501837-9ba35380-1937-11eb-9fd5-224317426179.png">

<img width="440" alt="Screen Shot 2020-10-28 at 4 06 12 PM" src="https://user-images.githubusercontent.com/69160361/97501858-a3fb8e80-1937-11eb-95d0-20054ffac3ec.png">


## Happiness and Freedom Scores Analyses

#### Total Freedom Rate by Region
An ANOVA was conducted to compare the differences in freedom score for the three regions. 
There was no significant difference in freedom score between the three regions ( p = 0.8), but Asia had two outlier countries that had a significantly lower freedom score than the rest of the region. 


<img width="630" alt="Screen Shot 2020-10-28 at 4 07 42 PM" src="https://user-images.githubusercontent.com/69160361/97501984-da390e00-1937-11eb-8c97-12663432a110.png">


#### Total Happiness Score by Region
An ANOVA was conducted to compare the differences in happiness score for the three regions. 
There was a significant difference in happiness (p = 0.04) where Europe and South America had a higher median happiness score than Asia. All three regions had two outlier countries that were significantly less happy than the other countries in their regions.

<img width="627" alt="Screen Shot 2020-10-28 at 4 07 58 PM" src="https://user-images.githubusercontent.com/69160361/97502012-e624d000-1937-11eb-9993-936825fd9363.png">


#### Total Protests vs Happiness Score
A regression analysis was conducted to examine the relationship between a countries total protests and their happiness score. There was no significant relationship between the two variables, indicating that the number of protests a country has does not have an impact on the countries happiness score.

<img width="432" alt="Screen Shot 2020-10-28 at 4 08 18 PM" src="https://user-images.githubusercontent.com/69160361/97502036-f472ec00-1937-11eb-9caa-d5fb9913b9a6.png">


#### Total Protests vs Freedom Score 
A regression analysis was conducted to examine the relationship between a countries total protests and their happiness score. There was no significant relationship between the two variables, indicating that the number of protests a country has does not have an impact on the countries freedom score.

<img width="427" alt="Screen Shot 2020-10-28 at 4 08 09 PM" src="https://user-images.githubusercontent.com/69160361/97502070-ff2d8100-1937-11eb-8ce9-8d46c8dc2b00.png">

### Heatmap of Protests

***Add heatmap

## Limitations and Future Directions

- Cleaning and merging the data took longer and was more complicated than we first thought. If we had more time, we would have liked to further explore the reasons behind these differences as well as specific patterns in individual countries.

- For further analysis, we would like to look at measures of government trust/perceptions of corruption. Our data included some of this information, but not enough to conduct thorough analyses. In the future, it would be interesting to explore this more to see if there is any relationship between protest amounts or protest types and a countries trust in their government/perceptions of their government as being corrupt.

## Conclusion
We found support for our first hypothesis, and observed regional differences in the amount of protests and size of protests. We did not find support for our second hypothesis, and observed no significant relationship between a countrys number of protests and their happiness score/freedom score. We did however find a significant difference in happiness score across the three regions, indicating that happiness scores could be a useful metric for examining regional differences. In the future, it would be interesting to explore these regional differences further, as well as incorporate different metrics from the World Happiness Report (such as government trust, economic factors like GDP, overall negative affect, etc.) and analyze their relationship to protest behavior. 

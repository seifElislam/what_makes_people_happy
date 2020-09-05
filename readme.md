# HappyDB
#### A Corpus of 100,000 Crowdsourced Happy Moments

## by Seif El-Eslam Hegazy


## Dataset

> [HappyDB](https://www.kaggle.com/ritresearch/happydb) is a corpus of more than 100,000 happy moments crowd-sourced via Amazon’s Mechanical Turk.

> Each worker is given the following task:
What made you happy today? Reflect on the past 24 hours, and recall three actual events that happened to you that made you happy.

> Dataset has 2 csv files:
- cleaned_hm.csv, the cleaned-up corpus of 100,000 crowd-sourced happy moments. The raw happy moments are retained for reference, and the author of each happy moment is represented by the his/her worker ID.
- demographic.csv includes worker id, age, country, gender, marital status, and status of parenthood.


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

> Exploratory investigation of features: age, country, gender, marital status, parenthood, happy moments categories, and happy moment words, leads to these findings:

    - 50% of age of participants ranges from 26 - 36 years. so major participants are young people.
    - Major participants from USA, then India.
    - Major participants are males, then females.
    - Major participants are single, then married people. Minor participants are divorced, separated and widowed.
    - participants with no parenthood had more happy moments.
    - The dataset is composed of happy moments from two reflection_period, 24 hours and 3 months. Both options have almost the same occurrence.
    - Happy moments of affection & achievement are major types. Minor types are enjoy_the_moment, bonding, leisure, nature and exercise.
    - Most of happy moments related to: "work", "friendship", "family", "meals", "emotions", "pets", "gathering", "buying", "achievements".
    - Happy moments vary according to Gender, marital status, and country.


## Key Insights for Presentation

> How do the people happy moments vary in USA and India?
    - This dataset has 78728 observations from USA, and 16633 observations from India.
    - This large amount of observations can give us some insights about the community, culture, values and people in these two countries.
    - In general:
        - Males have more achievement happy moments than females significantly.
        - Females have higher affection happy moments than males.
         ![Alt text](screen_shots/gender.png?raw=true "Image 1")
        - Married people have affection happy moments than achievement ones significantly.
        - Single people have achievement happy moments than affection ones significantly.
        - Single people have bonding, enjoy_the_moment and leisure moments than married people.
        ![Alt text](screen_shots/marital.png?raw=true "Image 2")
        - People with parenthood have more affection happy moments than people with no parenthood.
        - People with no parenthood have more achievement happy moments than people with parenthood significantly.
        - People with no parenthood have more bonding, enjoy_the_moment and leisure than than people with parenthood.
         ![Alt text](screen_shots/parenthood.png?raw=true "Image 3")
    - Comparing USA to India:
        - Across all Indian observations, married people are greater than single ones. About 50% of Indian observations have parenthood.
        - Across All USA observations, single people are greater than married ones. About 60% of USA observations don't have parethood.
        ![Alt text](screen_shots/country_marital.png?raw=true "Image 4")
        ![Alt text](screen_shots/country_parenthood.png?raw=true "Image 5")
        - There is a significant difference in moments words of people of USA vs India.
        - USA people happy moments about: "Work", "friend", "finally", "family".
        ![Alt text](screen_shots/usa_words.png?raw=true "Image 6")
        - Achievement words in Indian people moments are less common. They fouced on affection moments words like: "friend", "happiest", "moment", "feel", "family".
        ![Alt text](screen_shots/india_words.png?raw=true "Image 7")
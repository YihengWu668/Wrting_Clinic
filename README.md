The boundary model for Writing Clinic:

for each topic, we obtain the number of used topics and the number of being correct used.
For example:
Topic: Imperfect tense (use)   Topic: Topic: Imperfect tense (acc) 

All the numbers are z-score normalized.
And we check if these numbers have a dramatically change between the adjacent levels.

We call these topics with drama changing numbers as key topic.

The writing Clinic is based on boundary models and those statistics in profiles.json.


The profiles.json include:
1. number(absolute): number of essays in each level
2. frequency(per 100 words): frequency of topics used in this level 
frequency of topics used correctly in this level 
frequency of topics used wrongly in this level 
stored per word in the file “per 100 words”
3. share: share of essays that use the topic (use_rate)

4.
Accuracy (correct uses / all uses)
accuracy of each essay, all topics together (only look at the total topics of each essay) (accuracy)
all correct uses / all uses in the level, as one number (like glue all essays in to one huge essay)(pooled_accuracy)
accuracy of each topic in the level (accuracy; per essay: accuracy_per_user)


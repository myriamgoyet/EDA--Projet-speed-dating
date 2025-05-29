# PROJECT TINDER - ANALYSIS OF SPEED DATING EVENTS 

Fictive project completed as part of my Data Science Fullstack training at Jedha (Paris).

## Project 🚧

Tinder marketing team needs help on a new project. They are experiencing a decrease in the number of matches, and they are trying to find a way to understand **what makes people interested into each other**. 

They decided to run a speed dating experiment with people who had to give Tinder lots of informations about themselves that could ultimately reflect on ther dating profile on the app.

Tinder then gathered the data from this experiment. Each row in the dataset represents one speed date between two people, and indicates wether each of them secretly agreed to go on a second date with the other person.

## Scope of this project 🖼️

Data was gathered from participants in experimental speed dating events from 2002-2004. During the events, the attendees would have a four minute "first date" with every other participant of the opposite sex. 

The dataset also includes questionnaire data gathered from participants at different points in the process:
1. **Before attending the event (Signup/Time1) :** demographics, dating habits, self-perception across key attributes (Attractive, Sincere, Intelligent, Fun, Ambitious, Shared Interest), beliefs on what others find valuable in a mate, how important these attribues are for them in a date, lifestyle information...
2. **During the event (Scorecard) :** after each speed date, the participants secretly answer if they would go on a second date with their partner and evaluate them on key attributes. Half way through meeting all potential dates during the night, the participants are asked again about the importance of key attribues in a date and how they percieve themself.
3. **A day after the event (Followup/Time2) :** general satisfaction about the people they met, global question about the speed dating event. Once again, evaluation of key attributes (what's important for them, for other, self-perception)
4. **3-4 weeks after the event (Followup/Time3) :** what happend after the event (second date?). One last time, evaluation of key attributes (what's important for them, for other, self-perception)


See the Speed Dating Data Key document below for details.

[Dataset](https://full-stack-assets.s3.eu-west-3.amazonaws.com/M03-EDA/Speed+Dating+Data.csv)

[Dataset Description](https://full-stack-assets.s3.eu-west-3.amazonaws.com/M03-EDA/Speed+Dating+Data+Key.doc)

## How I answered 📬

1. **Breif description of the main aspects of the dataset** : Number of events, number of attendees, and the main outcome (match or not). This section also includes a short analysis of missing values.
2. **Brief analysis of participants' profiles men vs. women** : Age, race, profession, dating or social habits, and self-evaluation across key attributes. 
3. **Expectations regarding this event** : What are participants looking for? Would their profile be appealing to others? Do they expect to be happy with the people they meet at the event?
4. **Dating priorities** : What are they looking for? What do they think others are looking for? Is sharing the same race or religion important?
5. **Hipothesis on what makes a match** :  In this final section, I tested six hypotheses:
    - More choice leads to a higher chance of matching.
    - Those who consider race important tend to like people of the same race.
    - People are more likely to match with partners who have similar ratings of interests.
    - Some fields of activity have higher match rates than others.
    - Certain attributes increase the chances of getting a match.
    - Being the first date of the night improves the chances of getting a second date.

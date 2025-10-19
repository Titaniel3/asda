# Applied Statistical Data Science – Homework Week 1

## About
This repository contains my work for the first homework of the Applied Statistical Data Science course.

## Dataset 1: Online Chess Games
**Description:** 
This is a Dataset containing 20,058 chess games from the Online Chess-Site Lichess.org. The Dataset includes the following variables: 
- Game ID
- Rated (T/F)
- Start Time
- End Time
- Number of Turns
- Game Status
- Winner
- Time Increment
- White Player ID
- White Player Rating
- Black Player ID
- Black Player Rating
- All Moves in Standard Chess Notation
- Opening Eco (Standardised Code for any given opening, list here)
- Opening Name
- Opening Ply (Number of moves in the opening phase)

**Why did I choose this Dataset**: 
I’ve been passionate about chess since I was a kid — and pretty good at it, too! For almost two years now, I’ve been running a chess YouTube channel with some colleagues, which has already grown to over 22,000 subscribers. So it is safe to say that I love the game of chess. And not only the game, but also the data behind it. Chess is a very data-driven game: How many moves of opening theory did I play? How long did I spend on average for the critical moments? How was my quality of play in general (can be measured with *average centipawn-loss*, which is calculated by strong chess engines. How well do I perform in different phases of the game (Opening, Middlegame or Endgame). These are only some questions in chess that can be answered by looking at the data from games. 
I chose this data set specifically, because it is a rather small data set (there are also chess data sets with *over 7 billion* games!). That is why I expect this Dataset to be beginner-friendly and easier to analyze with my current skill set in Data Science. Later, I want to be able to also work with larger and more complex chess Datasets to be able to maybe find some patterns between some of the variables.

**Source**: https://www.kaggle.com/datasets/datasnaek/chess/data

## Dataset 2: Big five Personality Test
**Description:** 
This is a Dataset containing 1,015.342 questionnaire answers about the *Big Five Personality Test*. This test measures five core traits that describe human personality:

**1. Openness**

**2. Conscientiousness**

**3. Extraversion**

**4. Agreeableness**

**5. Neuroticism**

It works by asking people to rate how much they agree with different items on a five point scale (1 = Disagree, 5 = Agree).
The Dataset consists of 110 variables, always ten items for each personality trait (10 * 5 = 50), the time spent on each item (10 * 5 = 50) and ten descriptive variables like country of the participant.

**Why did I choose this Dataset?**
Appart from chess, I have had a passion for psychology for a long time. This passion was one of the reasons why I studied at Leuphana (I really liked the minor in *Business Psychology*) in the first place! I read a lot of books about personality traits and how they effect other variables like success or happiness. The Big Five Personality Trait might be the most famous try of differentiating between different personalities. I am not 100% sure if one should completely trust the results of an individual test but it can be useful for finding patterns across a large sample. 
I specifically chose this Dataset because it contains a very large amount of participants (over 1 million) and therefore can be used as a good starting point for further research. For example, I would be interested whether one could find patterns between the results of the Personality Test and Entrepreneurial success (I guess you now see my interest for Business Psychology). Maybe the country of the participant (developed vs. developing country) may also play a role in this?

**Source:** https://www.kaggle.com/datasets/tunguz/big-five-personality-test/data

## Dataset 3: Game of Thrones Social Network
**Description:** 
This Dataset is a bit different than the two above. It contains 107 different characters and 353 weighted relationships between those characters from the *Game of Thrones* Universe (to be precise, from the Book *A Storm of Swords*, which is the third novel in the series *A Song of Ice and Fire*, which later became the Game of Thrones series). The weighted relationships were calculated based on how many times two character's names appeared within 15 words of one another in the novel. So the idea of the Dataset is to analyze the rather complex social netword in the Game of Thrones universe and see which characters are most important from a social network perspective. 

**Why did I choose this Dataset?** 
As you may already be able to tell, I am somewhat of a Geek. One topic I love especially is Game of Thrones (except the last season, but that is a different story). So when I chose the seminar "*Social Network Analysis*" as a seminar during my bachelor studies, I immediately knew which Dataset I wanted to analyze: Exactly this one!
During this seminar, I learned some basic social network analysis techniques and was able to visualize the nodes and the edges using gephi and also calculate some basic centrality measures like weighted degree centrality or the Page rank of each character. Then I gave points for the "Best Performers" for each centrality measure and added them up to find out who is the real king of the Game of Thrones social network! If you know Game of Thrones well, you might be able to guess, who the winner was (Hint: The winner was never the actual king or queen). I won't tell you the solution here, so if you are interested, feel free to ask me about it :)

**Source:** https://github.com/melaniewalsh/sample-social-network-datasets/tree/master/sample-datasets/game-of-thrones

# ECON 323 Final Project
Welcome to my final project for ECON 323. My project is a UFC Fight Summary dashboard that presents fight and fighter statistics for UFC fights between 2010 and 2020. However, due to the fact that the UFC does not provide  statistics for certain fights for a variety of reasons including if it was the fighters first fight in the UFC, only 2700 fights are searchable.

- Jacob Bradbeer

## Data Sources
The data for this project was created from the merging of four data sources.

## How to Use the Fight Summary

## Reading the UI
**Section 1** General Fight Info
1. The fighter's name
2. The fighter's ranking, which can be designated by:
    - "Champion", The top ranked fighter in the division, and current belt holder
    - "1-15", The nth ranked challenger in the division (note: nth ranked challenger is the n+1 spot in the division including champion)
    - "NR", The fighter is currently not ranked in the division
3. Fight location & date
4. Fight Weightclass
5. Number of rounds in the fight OR if the fight is a title fight (note: all title fights MUST be 5 rounds)
   
**Section 2** General Fighter Fight Info 

![alt text](https://github.com/JBradbeer/econ323_ufc_fight_summary/blob/main/read_me_2.png?raw=true)

1. The fighter's betting odds using the +/- system
    - \"+" denotes the underdog
    - \"-" denotes the favourite
2. The fighter's name, colored red or blue by the corner they were in
3. The fighter's record *in the UFC*
4. The winner of the fight
    - The arrow points at and is colored by the corner of the winner
    - Black arrows pointing in both directions denote the fight was a draw
5. The ending time of the fight (ex. 4:58 denotes that the fight was 4 minutes and 58 seconds into the round when the fight ended)
6. The ending round of the fight
7. Finish type of the fight, denoted by:
    - "U-DEC": Unanimous decision, all three judges had the fighter winning the fight
    - "S-DEC": Split decision, two judges had the winner winning the fight while the third called had the loser winning
    - "M-DEC": Majority decision, two judges had the winner winning the fight while the third called it a draw
    - "SUB":   The loser submitted to the winner mid-fight
    - "TKO/KO": The loser was either knocked-out (KO) or the referee stopped the fight due to a fighter taking too much damage or not defending themselves intelligenty (TKO)
8. The method of attack that caused the knockout or submission (note: this section only appears in case of KO, TKO, or SUB)

**Section 4** Striking Data for the Fight
1. Significant strikes thrown and landed
    - Grey denotes the amount thrown
    - Colored denotes the amount landed
2. Total strikes thrown and landed
    - Grey denotes the amount thrown
    - Colored denotes the amount landed
3. The number of knockdowns scored

**Section 5** Grappling Data for the Fight
1. Pie chart representing the fighters takedown percentage
2. Total strikes thrown and landed
    - Grey denotes the amount thrown
    - Colored denotes the amount landed
3. The number of knockdowns scored

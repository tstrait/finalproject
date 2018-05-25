Final Project, Part 1: Proposal
Frame your problem, criteria, and data source(s)

Describe your chosen problem and state whether you have access to relevant data. If you get stuck, see this list of curated datasets.

Requirements
Draft a well-formed problem statement relevant to a business problem affecting your team, division, or organization.
Include the following elements:
Hypothesis/assumptions
Goals and success metrics
Risks or limitations
Identify at least one relevant internal dataset and confirm that you have (or can get) the right access permissions.
Submission
Submit or share your project proposal as per your instructor's directions.

--------------

I am choosing to analyze the NBA dataset from the 2017-2018 regular season; datasets are available at stats.nba.com, and I also found a Kaggle dataset that has stats already aggregated, https://www.kaggle.com/pablote/nba-enhanced-stats/data, which I may use as well.

With the increase in data recorded & available in professional sports, we can look at a single player's impact on their team more easily, and look at the salary players are getting based on the impact they make.  I will use the datasets referenced above in combination with player salary data (https://www.basketball-reference.com/contracts/) to compare a player's season salary versus their contribution to the team.  This would help a team's front office decide whether spending big on a star is helpful, or if they should spread out pay a bit more evenly.  

It would be interesting to figure out a 'standard' way to correlate salary distribution that to team wins, as well -- initially, I'm thinking of comparing a team's season salary split versus their win or final standing.  Eg, if a team spends 50% of their salary cap on a single player, are they more likely to go far? Could also potentially look at a by-year angle, too (may get hairy...) -- is the first year of a big star on a team successful, or typically not till year 2+?

All of the datasets needed should be out there and able to be joined based on season & player names; I will need to be careful about which features to include, though.  Additionally, I expect I'll scale salary based on factors like age and/or time in league, as rookies have a much lower contract than older players, but could make a similar impact to their team.

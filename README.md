# Speed-Dating
## This project is about prediction of whether the participant of a date decide to give his/her partner a second date after a short experimental Speed Dating event. I have implemented my own version machine learning algorithms from <ins>scratch using python</ins> without the use of any publicly available libraries like scikit-learn or scipy.

### <ins>Data description</ins>:
The dating dataset consists of 6744 speed dating events in the comma-separated format(experimental dataset).In this set of speed dating experiments, each speed date happens between a pair of participants.

Before the speed date, each participant has been asked to indicate a number of preferences in their romantic partner (e.g., how important it is for the romantic partner to come from the same racial/religious background as themselves, allocate points among the six attributes “attractiveness”, “sincerity”, “intelligence”, “fun”, “ambition”, “shared interests” to indicate how much they value each attribute in their romantic partner, etc.). They also provide some
information about themselves such as their self-evaluation on the six attributes (i.e.,“attractiveness”, “sincerity”, “intelligence”, “fun”, “ambition”, “shared interests”) and
their levelof interests in a wide range of activities (e.g., museum, arts, dinning, etc.).

During the speed date, the pair of participants in a date chat with each other for 2 minutes, andeach participant provides some evaluations for their partner, including ratings of their partner onthe six attributes (i.e., “attractiveness”, “sincerity”, “intelligence”, “fun”, “ambition”, “sharedinterests”), ratings on how happy they expect it to be if they continue romantic relationships withtheir partner, and ratings on how much they like their partner.At the end of the speed date, each participant in a date makes a decision of whether he/she wants to give their partner a second date.

| Field | Meaning |
| ----------- | ----------- |
| gender | gender of participant | 
| age | age of participant | 
| age_o | age of partner | 
| race | race of participant | 
| race_o | race of partner | 
| same_race | whether participant and partner belong to same race |
| importance_same_race | participant rating on importance of two people to be of same race | 



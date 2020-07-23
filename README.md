# Speed-Dating
## This project is about prediction of whether the participant of a date decide to give his/her partner a second date after a short experimental Speed Dating event. I have implemented my own version machine learning algorithms from <ins>scratch using python</ins> without the use of any publicly available libraries like scikit-learn or scipy.

### <ins>Table of contents</ins>:
  -Data Description[data_table]

### <ins>Data description</ins>{#data_table}:
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
| importance_same_religion | participant rating on importance of two people to be of same religion | 
| field | participant's field of study |
| pref_o_attractive | partner's allocated point on attractiveness | 
| pref_o_sincere | partner's allocated point on sincere | 
| pref_o_intelligence | partner's allocated point on intelligence | 
| pref_o_funny | partner's allocated point on funny | 
| pref_o_ambitious | partner's allocated point on ambitious | 
| pref_o_shared_interests | partner's allocated point on shared_interests | 
| attractive_important | participant's allocated point on attractiveness | 
| sincere_important | participant's allocated point on sincereness | 
| intelligence_important | participant's allocated point on intelligence | 
| funny_important | participant's allocated point on being funny | 
| shared_interests_important | participant's allocated point on shared interests | 
| ambition_important | participant's allocated point on being ambitious | 
| attractive | participant self rating on attractiveness
| sincere | participant self rating on sincere
| intelligence | participant self rating on intelligence
| funny | participant self rating on funny
| ambition | participant self rating on ambition
| attractive_partner | participant  rating on partner's attractiveness
| sincere_partner | participant rating on partner's sincere
| intelligence_partner | participant rating on partner's intelligence
| funny_partner | participant rating on partner's funny
| ambition_partner | participant rating on partner's ambition
| shared_interests_partner | participant rating on partner's shared_interests
| sports | participant self rating on interest in sports
| Tvsports | participant self rating on interest in Tvsports
| Exercise | participant self rating on interest in exercise
| dining | participant self rating on interest in dining
| museums | participant self rating on interest in museums
| art | participant self rating on interest in art
| hiking | participant self rating on interest in hiking
| gaming | participant self rating on interest in gaming
| clubbing | participant self rating on interest in clubbing
| reading | participant self rating on interest in reading
| Tv | participant self rating on interest in Tv
| Theater | participant self rating on interest in theater
| movies | participant self rating on interest in movies
| concerts | participant self rating on interest in concert
| music | participant self rating on interest in music
| shopping | participant self rating on interest in shopping
| yoga | participant self rating on interest in yoga
| interests_correlate | correlation b/w participant and partner rating in interests
| expected_happy_with_sd_people | participant's rating on how happy 
he/she expects to be with partner
| like | participant's rating on how much he/she likes partner
| decision | participant's decision on whether he/she would like to see date in future




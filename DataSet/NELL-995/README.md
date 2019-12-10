# NELL-995

## Graph.txt
```
  This data is represented by a sequence of the following format.
  subject, relation, object
  
  # of Triples : 308,426	
  
```
### Sample
||subject|relation|object|
|:-----------:|------------:|------------:|------------:|
|1|concept_person_molly_moore|concept:worksfor|concept_city_washington_d_c|
|2|concept_hotel_pullman|concept:atlocation|concept_city_washington_d_c|
|...|...|...|...|

## Train and Test data
|Task (relation)|train|test|
|:-----------:|------------:|------------:|
|athletePlaysInLeague|4,876|1,938|
|worksFor|6,911|2,698 |
|orgHiredPerson|6,117|2,148 |
|athletePlaysSport|5,155|1,930 |
|teamPlaysSport|1,919|721 |
|bornLocation|4,305|1,820 |
|athleteHomeStadium|4,876|1,938 |
|orgHeadquaterCity|5,131|2,100 |
|athletePlaysForTeam|8,070|3,177 |

## test.pairs
```
  This data is represented by a sequence of the following format.
  subject, object, label
  
```
### Sample
||subject|object|label|
|:-----------:|------------:|------------:|------------:|
|1|thing$concept_athlete_adam_bostick|thing$concept_sportsleague_mlb|+|
|2|thing$concept_athlete_adam_bostick|thing$concept_sportsleague_nba|-|
|...|...|...|...|

## train.pairs
```
  This data is represented by a sequence of the following format.
  subject, object, label
  
```
### Sample
||subject|object|label|
|:-----------:|------------:|------------:|------------:|
|1|thing$concept_athlete_allan_houston|thing$concept_sportsleague_nba|+|
|2|thing$concept_athlete_allan_houston|thing$concept_sportsleague_new|-|
|...|...|...|...|

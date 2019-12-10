# FB15K-237

## Graph.txt
```
  This data is represented by a sequence of the following format.
  subject, relation, object
  
  # of Triples : 544,230	
  
```
### Sample
||subject|relation|object|
|:-----------:|------------:|------------:|------------:|
|1|/m/05hs4r	|/music/genre/artists|/m/01pbxb|
|2|/m/018dnt	|/film/actor/film./film/performance/film|/m/050r1z|
|...|...|...|...|


## test.pairs
```
  This data is represented by a sequence of the following format.
  subject, object, label
  
  # of Pairs : 20,466 
```
### Sample
||subject|relation|object|
|:-----------:|------------:|------------:|------------:|
|1|/m/0c3ybss	|/film/film/country	|/m/09c7w0|
|2|/m/0sxg4	|/film/film/genre	|/m/04xvlr|
|...|...|...|...|

## train.pairs
```
  This data is represented by a sequence of the following format.
  subject, object, label
  
  # of Pairs : 272,115 
```
### Sample
||subject|relation|object|
|:-----------:|------------:|------------:|------------:|
|1|/m/027rn	|/location/country/form_of_government	|/m/06cx9|
|2|/m/01g888	|/music/genre/artists	|/m/01vv126|
|...|...|...|...|

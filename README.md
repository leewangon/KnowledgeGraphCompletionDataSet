# Knowledge Graph Completion DataSet
```
    This repository contains datasets for learning knowledge graph completion.
```
## Data overview
```
    In this project, we trained the model based on target relations. 
    Each target relations has negative data and positive data.
```

## Data format
```
   This data is represented by a sequence of the following n-triple format.
   n-triple - a format for storing and transmitting data. 
            - a line-based, plain text serialisation format for RDF (Resource Description Framework) graphs.
            - a subset of the Turtle (Terse RDF Triple Language) format.
   <subject, relation, object>
```
## Data Set
Pre-processed knwoledge graph : [graph.zip (zip file, 8MB)](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/blob/master/DataSet/graph.zip)

||Kor-KB|
|:-----------:|------------:|
|Size|42MB|
|Triples|1,315,146|
|Entities|488,926|
|Relations|157|
|Classes|921|

#### Task #1 : [nationality](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/nationality)
#### Task #2 : [job](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/job)

## The institute to construct dataset
* __The AI Lab in Soongsil University__

## Citation
```
    @article{huang2007constructing,
      title={Constructing a personalized e-learning system based on genetic algorithm and case-based reasoning approach},
      author={Huang, Mu-Jung and Huang, Hwa-Shan and Chen, Mu-Yen},
      journal={Expert Systems with Applications},
      volume={33},
      number={3},
      pages={551--564},
      year={2007},
      publisher={Elsevier}
    }
```

# Knowledge Graph Completion DataSet
```
    Refined Training and Test dataset for Knowledge Graph Model
```
## Data overview
```
    This repository contains refinement dataset to train and evaluate knowledge graph model.
    If you have any questions or comments, please fell free to contact us by email [leewangon@gmail.com].
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

||Kor-KB|NELL-995|FB15K-237|NDSL|DBpedia|DBpia|KData|
|:-----------:|------------:|------------:|------------:|------------:|------------:|------------:|------------:|
|Size|42MB|26MB|41MB|26MB|711MB|64MB|139MB|
|Triples|1,315,146|308,426|544,230|221,253|14,000,000|912,412|2,776,394|
|Entities|488,926|63,917|14,505|246,850|4,250,000|409,693|1,140,000|
|Relations|157|396|237|5|717|4|10,409|
|Classes|921|267|354|5|451|6|113|

### Kor-KB
##### Task #1 : [nationality](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/nationality)
##### Task #2 : [job](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/job)
##### Task #3 : [employer](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/employer)

### NELL-995 [Link](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/NELL-995)
### FB15K-237 [Link](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/FB15K-237)
### NDSL [Link](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/NDSL)
### DBpedia [Link](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/DBpedia)
### DBpia [Link](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/DBpia)
### KData [Link](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/KData)

## The institute to construct dataset
* __The AI Lab in Soongsil University__

## Citation
```
    @article{jagvaral2020path,
      title={Path-based reasoning approach for knowledge graph completion using CNN-BiLSTM with attention mechanism},
      author={Jagvaral, Batselem and Lee, Wan-Kon and Roh, Jae-Seung and Kim, Min-Sung and Park, Young-Tack},
      journal={Expert Systems with Applications},
      volume={142},
      pages={112960},
      year={2020},
      publisher={Elsevier}
    }
```

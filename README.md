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
Pre-processed knwoledge graph : [graph.zip (zip file, 8MB)](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/blob/master/DataSet/graph.zip)

||Kor-KB|NELL-995|FB15K-237|NDSL|
|:-----------:|------------:|------------:|------------:|------------:|
|Size|42MB|26MB|41MB|42MB|
|Triples|1,315,146|308,426|544,230|660,723|
|Entities|488,926|63,917|14,505|263,074|
|Relations|157|396|237|27|
|Classes|921|267|354|13|

### Kor-KB
##### Task #1 : [nationality](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/nationality)
##### Task #2 : [job](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/job)
##### Task #3 : [employer](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/employer)

### NELL-995 
- [Link](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/NELL-995)
### FB15K-237
- [Link](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/FB15K-237)
### NDSL
- [Link](https://github.com/leewangon/KnowledgeGraphCompletionDataSet/tree/master/DataSet/NDSL)

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

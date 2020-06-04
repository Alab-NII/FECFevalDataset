# An Evaluation Dataset for Identifying Communicative Functions of Sentences in English Scholarly Papers

The dataset consists of three sets of tsv files. The usage is explained in [our paper](https://www.researchgate.net/publication/339658767_An_Evaluation_Dataset_for_Identifying_Communicative_Functions_of_Sentences_in_English_Scholarly_Papers).

## Description of tsv files

### human_evaluation

0. ID
0. Targeted sentence [s0]
0. Correct choice [s1]
0. Wrong choice [s2]
0. Core FE for s0
0. Core FE for s1
0. Core FE for s2
0. Communicative function for s0 and s1
0. Communicative function for s2
0. Paper/sentence ID for s0
0. Paper/sentence ID for s1
0. Paper/sentence ID for s2
0. Accuracy of human annotation

### sentences

0. Communicative function
0. The core FE
0. Sentence
0. Sentence ID (PaperID_SentID; identical to the ID in AASC)

## Licence

This dataset is licensed under the Creative Commons BY-NC-SA 3.0. When you use the dataset, please cite our paper (see below).

This dataset uses [ACL Anthology Sentence Corpus](https://github.com/KMCS-NII/AASC), which consists of papers retrieved from [ACL Anthology](https://www.aclweb.org/anthology/).

### Papers in the ACL repository

&copy; 1979-2018 Association for Computational Linguistics

Licensed under the Creative Commons BY-NC-SA 3.0 (-2015) and Creative Commons BY 4.0 (2016-)

### AASC: ACL Anthology Sentence Corpus

Licensed under the Creative Commons BY-NC-SA 3.0

## Citation

Iwatsuki, K., Boudin, F., & Aizawa, A. (2020). An Evaluation Dataset for Identifying Communicative Functions of Sentences in English Scholarly Papers. In *Proceedings of The 12th Language Resources and Evaluation Conference*, 1712–1720.

```
@InProceedings{Iwatsuki2020LREC,
  author    = {Iwatsuki, Kenichi  and  Boudin, Florian  and  Aizawa, Akiko},
  title     = {An Evaluation Dataset for Identifying Communicative Functions of Sentences in English Scholarly Papers},
  booktitle      = {Proceedings of The 12th Language Resources and Evaluation Conference},
  month          = {May},
  year           = {2020},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {1712--1720},
  url       = {http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.212.pdf}
}
```

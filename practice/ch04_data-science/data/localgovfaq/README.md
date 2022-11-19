# localgovFAQ
## qas/questions_Amagasaki.txt
Each line contains ID of QA pair and a question of QA.

## qas/answers_in_Amagasaki.txt
Each line contains ID of QA pair and an answer of QA.

## testset.txt
Each line is tab-separated.
The first column is user's query.
The 2nd, 3rd and 4th columns are the QA pair IDs in relevance level A, B and C, respectively.
The IDs correspond to ones in qas/questions_Amagasaki.txt and qas/answers_in_Amagasaki.txt.
The description about relevance levels is below.
```
A, Contain correct information.
B, Contain relevant information.
C, The topic is same as a query, but does not contain relevant information.
```

## testset_segmentation.txt
testset.txt with word segmentations by [`Juman++`]( http://nlp.ist.i.kyoto-u.ac.jp/EN/index.php?JUMAN++ )

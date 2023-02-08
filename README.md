# NSMC-Sentimetnt-Anaylsis
Sentimetnt Anaylsis project with NSMC dataset

## 4 Steps of Natural Language Processing  
1. Preprocessing
  - Extract language

2. Tokenization
  - Embedding string to vector
  - word embedding, sentence embedding, etc.
  - Korean is used with morpheme type

3. Token Embedding
  - one-hot encoding
  - check similarity (Word2Vec, SentencePiece)
  - distributional hypothesis
    - center word : Skim-Gram
    - context word : Continuous Bag-of-Words
    
4. Document Embedding  
  - GPT : $P(W)= \prod_{n=1}^{L} P(w_n|w_1,\cdots,w_{n-1})$
  - BERT : $P(w_i|w_1,\cdots,w_{i-1},w_{i+1},\cdots,w_{n-1})$
  - we can use latent variable as document embedding

## Code  
Check .ipynb file, soon .py file will be upload too.

## Future work  
How to solve irony word detection problem ?  
  - More train about irony dataset
  - Representation learning for input data to extract irony word.
  - ...

<br>

### Citation NSMC

```
@InProceedings{Park:2016, 
  title        = "Naver Sentiment Movie Corpus", 
  author       = "Lucy Park", 
  year         = "2016", 
  howpublished = {\\url{https://github.com/e9t/nsmc}} 
}
```
<br>

<br>

### Citation KR-BERT

```
@article{lee2020krbert, 
    title={KR-BERT: A Small-Scale Korean-Specific Language Model}, 
    author={Sangah Lee and Hansol Jang and Yunmee Baik and Suzi Park and Hyopil Shin}, 
    year={2020}, 
    journal={ArXiv}, 
    volume={abs/2008.03979} 
  }
```
<br>
[KR-BERT github](https://github.com/snunlp/KR-BERT)


### Reference
- https://github.com/kimtaesu24/KoBERT_with_NAVER
- https://huggingface.co/snunlp/KR-BERT-char16424
- https://wikidocs.net/44249



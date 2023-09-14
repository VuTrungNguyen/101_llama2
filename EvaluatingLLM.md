Evaluating LLMs

# The GLUE Benchmark
The GLUE Benchmark is a group of nine classification tasks on sentences or pairs of sentences which are:

- [CoLA](https://nyu-mll.github.io/CoLA/) (Corpus of Linguistic Acceptability) Determine if a sentence is grammatically correct or not.is a  dataset containing sentences labeled grammatically correct or not.
- [MNLI](https://arxiv.org/abs/1704.05426) (Multi-Genre Natural Language Inference) Determine if a sentence entails, contradicts or is unrelated to a given hypothesis. (This dataset has two versions, one with the validation and test set coming from the same distribution, another called mismatched where the validation and test use out-of-domain data.)
- [MRPC](https://www.microsoft.com/en-us/download/details.aspx?id=52398) (Microsoft Research Paraphrase Corpus) Determine if two sentences are paraphrases from one another or not.
- [QNLI](https://rajpurkar.github.io/SQuAD-explorer/) (Question-answering Natural Language Inference) Determine if the answer to a question is in the second sentence or not. (This dataset is built from the SQuAD dataset.)
- [QQP](https://data.quora.com/First-Quora-Dataset-Release-Question-Pairs) (Quora Question Pairs2) Determine if two questions are semantically equivalent or not.
- [RTE](https://aclweb.org/aclwiki/Recognizing_Textual_Entailment) (Recognizing Textual Entailment) Determine if a sentence entails a given hypothesis or not.
- [SST-2](https://nlp.stanford.edu/sentiment/index.html) (Stanford Sentiment Treebank) Determine if the sentence has a positive or negative sentiment.
- [STS-B](http://ixa2.si.ehu.es/stswiki/index.php/STSbenchmark) (Semantic Textual Similarity Benchmark) Determine the similarity of two sentences with a score from 1 to 5.
- [WNLI](https://cs.nyu.edu/faculty/davise/papers/WinogradSchemas/WS.html) (Winograd Natural Language Inference) Determine if a sentence with an anonymous pronoun and a sentence with this pronoun replaced are entailed or not. (This dataset is built from the Winograd Schema Challenge dataset.)

# LLMs trained on CODE - CODEX
# Deep learning with Code Data
- APPS
- CodeBERT
- CodeXGLUE
- Break-It-Fix-It 
# Evaluation through unit tests
1. [HumanEval](github.com/openai/human-eval)
164 Programming Problems:
- Function Signature
- Docstring
- Body
2. Pass@K Metric
- K code samples are generated per problem, solved if any sample passes the unit tests
- Similar metrics for information retrieval/search

# Some papers about evaluating LLMs
[Hendrycks, Measuring Massive Multitask Language Understanding](https://arxiv.org/abs/2009.03300)
- Take away:
[Efrat,  LMentry: A language model benchmark of elementary language tasks](https://arxiv.org/abs/2211.02069)
- Take away:
  - Benchmarks are getting larger and more complex as the LLMs performance improves
  - Instruction-Finetuning give more boost of perfomance than scaling up the models (similar claim was made by Chinchilla team)

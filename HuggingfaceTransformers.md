# Hugging Face Transformers Library
1. Pipeline()
```
pipeline(task="taskname", model='modelname')("textinput")
```
eg.
```
pipeline(task="sentiment-analysis", model='distilbert-base-uncased-finetuned-sst-2-english')("Love this!")
```
the model can be accessed through huggingface.co/models, with model name = repo/model

2. Machine Learning framework
Models on huggingface are not only compatible for Transformers Library, but can also support other ML framworks as well: Pytorch, TensorFlow...
3. 

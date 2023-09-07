# Training a pre-trained model
Task: Fine-tuning a model on a text classification task
The training was done on this [Colab notebook](https://huggingface.co/Danxtshake/distilbert-base-uncased-finetuned-cola)

# Training logs:
```
!pip install datasets transformers
!pip install transformers[torch]
```

store your authentication token from the Hugging Face website
```
from huggingface_hub import notebook_login
notebook_login()
```
install Git-LFS ( this help fetching large files)
```
!apt install git-lfs
```
Make sure your version of Transformers is at least 4.11.0 since the functionality was introduced in that version:
```
import transformers

print(transformers.__version__)
```
upload some telemetry. Not needed functionally. Use this to help `pytorch` framework team collecting data 
```
from transformers.utils import send_example_telemetry
send_example_telemetry("text_classification_notebook", framework="pytorch")
```

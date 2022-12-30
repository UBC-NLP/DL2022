#Run Language Model Pretraining
This code was tested on:
* python/3.6.8
* troch==1.8.0
* transformers==4.6.0

* Training data: training_sample.txt. Each sample is in a line. Samples are split by a empty line.
* Job shell script: run.sh
* Input arguments: Line 494-663
* Load model and tokenizer checkpoints. If a checkpoint cannot be found, a new model will be initialized: Line 743-790
* Data loader: Line 69-94 and Line 105-163
* Training loop: Line 242-434
* Mask input tokens: Line 208-239
* Evaluation loop: Line 437-490
* Save checkpoint: Line 816-836 
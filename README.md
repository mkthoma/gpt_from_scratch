# GPT from scratch

This repo contains code to train a GPT from scratch. The dataset is taken from the [RedPajama 1 trillion data](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-1T-Sample). Only samples from this are taken and used for the training purposes. The implementation of the transformer is similar to the [LitGPT](https://github.com/Lightning-AI/lit-gpt). 

The trained model has a parameter count of about 160M. The final training loss  was found to be 3.2154.

![image](https://github.com/mkthoma/gpt_from_scratch/assets/135134412/23195bda-97ce-4b13-a96b-53552ba2a57e)

The training details can be found in the attached notebooks. The initial training was stopped when the loss was around 4. 

![image](https://github.com/mkthoma/gpt_from_scratch/assets/135134412/f0122ba2-b9b3-430d-a6f3-cdde5263a674)


Using the checkpoint, the training was resumed and stopped when it went below 3.5. 

## Sample Predictions

![image](https://github.com/mkthoma/gpt_from_scratch/assets/135134412/5420735e-7f22-4d57-a8cb-bbab7be3038c)

![image](https://github.com/mkthoma/gpt_from_scratch/assets/135134412/d1a4d7a5-152a-472d-821d-7bdbd668f116)

![image](https://github.com/mkthoma/gpt_from_scratch/assets/135134412/b550368f-0b12-4c8c-8daa-9aec385310f9)

![image](https://github.com/mkthoma/gpt_from_scratch/assets/135134412/7105ddef-af5a-425c-b40b-fb3011b84df4)

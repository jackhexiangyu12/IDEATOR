# IDEATOR
Code for our paper: [IDEATOR: Jailbreaking Large Vision-Language Models Using Themselves](https://arxiv.org/abs/2411.00827)

![image](https://github.com/roywang021/IDEATOR/blob/main/model.png)


### Basic Setup
1. Prepare the pretrained weights for MiniGPT-4 (Vicuna-13B v0)：
   Please refer to the guide from the MiniGPT-4 repository to get the weights of Vicuna. Then, set the path to the vicuna weight in the model config file [here](https://github.com/roywang021/IDEATOR/blob/main/minigpt4/configs/models/minigpt4.yaml#L16). Get MiniGPT-4 (the 13B version) checkpoint: download from here. Then, set the path to the pretrained checkpoint in the [minigpt4_eval.yaml](https://github.com/roywang021/IDEATOR/blob/main/minigpt4_eval.yaml#L11).


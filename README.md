# Llama2_LoRA_ReduceBias
Use LoRA to finetune Llama2 to reduce model bias. We use CoLab Environment generally.

## Data Processing

We used data set [BBQ](https://github.com/nyu-mll/BBQ) and preprocessed it for training. The processed dataset was pushed to [huggingface dataset](https://huggingface.co/datasets/TiffanyCheng/LLM_Bias_EECS182_Project/tree/main).

## Model Fine-tuning

Applying [huggingface PEFT](https://huggingface.co/docs/peft/index) library to finetune [Llama2-7b-hf](https://huggingface.co/meta-llama/Llama-2-7b-hf) with LoRA. 

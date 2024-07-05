# Quiz

## Question 1
Fill in the blanks: __________ involves using many prompt-completion examples as the labeled training dataset to continue training the model by updating its weights. This is different from _________ where you provide prompt-completion examples during inference.

1 point

- [x] Instruction fine-tuning, In-context learning
- [ ] In-context learning, Instruction fine-tuning
- [ ] Pre-training, Instruction fine-tuning
- [ ] Prompt engineering, Pre-training

## Question 2
Fine-tuning a model on a single task can improve model performance specifically on that task; however, it can also degrade the performance of other tasks as a side effect. This phenomenon is known as:

1 point

- [ ] Instruction bias
- [ ] Model toxicity
- [x] Catastrophic forgetting
- [ ] Catastrophic loss

## Question 3
Which evaluation metric below focuses on precision in matching generated output to the reference text and is used for text translation?

1 point

- [ ] ROUGE-1
- [ ] ROUGE-2
- [ ] HELM
- [x] BLEU

## Question 4
Which of the following statements about multi-task finetuning is correct? Select all that apply:

1 point

- [ ] Performing multi-task finetuning may lead to slower inference.
- [x] FLAN-T5 was trained with multi-task finetuning.
- [x] Multi-task finetuning can help prevent catastrophic forgetting.
- [ ] Multi-task finetuning requires separate models for each task being performed.

## Question 5
"Smaller LLMs can struggle with one-shot and few-shot inference:"

Is this true or false?

1 point

- [x] True
- [ ] False

## Question 6
Which of the following are Parameter Efficient Fine-Tuning (PEFT) methods? Select all that apply.

1 point

- [X] Reparameterization
- [x] Selective
- [x] Additive
- [ ] Subtractive

## Question 7
Which of the following best describes how LoRA works?

1 point

- [ ] LoRA freezes all weights in the original model layers and introduces new components which are trained on new data.
- [ ] LoRA continues the original pre-training objective on new data to update the weights of the original model.
- [x] LoRA decomposes weights into two smaller rank matrices and trains those instead of the full model weights.
- [ ] LoRA trains a smaller, distilled version of the pre-trained LLM to reduce model size.

## Question 8
What is a soft prompt in the context of LLMs (Large Language Models)?

1 point

- [x] A set of trainable tokens that are added to a prompt and whose values are updated during additional training to improve performance on specific tasks.
- [ ] A strict and explicit input text that serves as a starting point for the model's generation.
- [ ] A technique to limit the creativity of the model and enforce specific output patterns.
- [ ] A method to control the model's behavior by adjusting the learning rate during training.

## Question 9
"Prompt Tuning is a technique used to adjust all hyperparameters of a language model."

Is this true or false?

1 point

- [ ] True
- [x] False

## Question 10
"PEFT methods can reduce the memory needed for fine-tuning dramatically, sometimes to just 12-20% of the memory needed for full fine-tuning."

Is this true or false?

1 point

- [x] True
- [ ] False

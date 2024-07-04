# Quiz

## Question 1
Which of the following are true in regards to Constitutional AI? Select all that apply.

1 point

- [ ] For constitutional AI, it is necessary to provide human feedback to guide the revisions.
- [x] Red Teaming is the process of eliciting undesirable responses by interacting with a model.
- [x] In Constitutional AI, we train a model to choose between different responses.
- [ ] To obtain revised answers for possible harmful prompts, we need to go through a Critique and Revision process.

## Question 2
What does the "Proximal" in Proximal Policy Optimization refer to?

1 point

- [ ] The use of a proximal gradient descent algorithm
- [ ] The algorithm's proximity to the optimal policy
- [x] The constraint that limits the distance between the new and old policy
- [ ] The algorithm's ability to handle proximal policies.

## Question 3
"You can use an algorithm other than Proximal Policy Optimization to update the model weights during RLHF."

Is this true or false?

1 point

- [x] True
- [ ] False

## Question 4
In reinforcement learning, particularly with the Proximal Policy Optimization (PPO) algorithm, what is the role of KL-Divergence? Select all that apply.

1 point

- [x] KL divergence is used to enforce a constraint that limits the extent of LLM weight updates.
- [ ] KL divergence is used to train the reward model by scoring the difference of the new completions from the original human-labeled ones.
- [x] KL divergence measures the difference between two probability distributions.
- [ ] KL divergence encourages large updates to the LLM weights to increase differences from the original model.

## Question 5
Fill in the blanks: When fine-tuning a large language model with human feedback, the action that the agent (in this case the LLM) carries out is ________ and the action space is the _________.

1 point

- [x] Generating the next token, the context window
- [ ] Generating the next token, vocabulary of all tokens.
- [ ] Calculating the probability distribution, the LLM model weights.
- [ ] Processing the prompt, context window.

## Question 6
How does Retrieval Augmented Generation (RAG) enhance generation-based models?

1 point

- [ ] By increasing the training data size.
- [ ] By optimizing model architecture to generate factual completions.
- [ ] By applying reinforcement learning techniques to augment completions.
- [x] By making external knowledge available to the model.

## Question 7
How can incorporating information retrieval techniques improve your LLM application? Select all that apply.

1 point

- [x] Overcome Knowledge Cut-offs
- [ ] Faster training speed when compared to traditional models
- [ ] Reduced memory footprint for the model
- [x] Improve relevance and accuracy of responses

## Question 8
What are correct definitions of Program-aided Language (PAL) models? Select all that apply.

1 point

- [ ] Models that enable automatic translation of programming languages to human languages.
- [x] Models that integrate language translation and coding functionalities.
- [x] Models that assist programmers in writing code through natural language interfaces.
- [ ] Models that offload computational tasks to other programs.

## Question 9
Which of the following best describes the primary focus of ReAct?

1 point

- [ ] Investigating reasoning abilities in LLMs through chain-of-thought prompting.
- [ ] Studying the separate topics of reasoning and acting in LLMs.
- [x] Enhancing language understanding and decision making in LLMs.
- [ ] Exploring action plan generation in LLMs.

## Question 10
What is the main purpose of the LangChain framework?

1 point

- [ ] To evaluate the LLM's completions and provide fast prototyping and deployment capabilities.
- [x] To chain together different components and create advanced use cases around LLMs, such as chatbots, Generative Question-Answering (GQA), and summarization.
- [ ] To provide prompt templates, agents, and memory components for working with LLMs.
- [ ] To connect with external APIs and datasets and offload computational tasks.

# SIMA(Student Intelligent Model Assistant)

This project is going to help student in every university. The problem when is come from that you have question about the university or choosing that or you are the student of a university and you don't know about that as much sooo... SIMA will help you to reach that answer very fast.

---------------------------------------------------------------------------------------------------------------------
Techniques and Strategies that use for SIMA:

1- Using just prompt engineering techniques with llama 3 8B and llama3 70B:

Using a good template or prompt techniques is the first test of the llm strategy and if this didn't work the second is Fine Tuning

Result of this technique: Unfortunately this strategy didn't work well for our project for both models.

2- Fine Tuning with Galore:

Fine Tuning is the most important way of learning a LLM but how or which model or.... are question will come from Fine Tuning so let's create a strategy.

--------------------------------------------------------------------------------------------------------------------------------------

# Fine Tuning Steps:

# 1- choosing models

The language of project is Persian so for that we want LLM that can generate Persian language but the trained model that i test are not good enough so i want to do that:

- Strategy 1: Using llama 3.1 8B -> Fine Tune it with Custom Dataset.
- Strategy 2: Using Tehran University LLM -> Fine tune it with Custom Dataset.
- Strategy 3: Getting Phi 3.5-mini -> Fine Tune it with Persian Dataset -> Deploy Persian SLM -> Use it to Fine tune with Custom Dataset.

I like more in phi 3.5 but i should test all three strategies 😁.

# 2- Creating Dataset

Dataset is the most important part of our Fine tuning so i want to do this:
- a: Creating Template of dataset and also system prompt.
- b: Creating Question and Answer column with another LLM.
- c: EDA and Preprocessing on that.
- d: Combining Prompt Template and Q/A Dataset to have a good Prompt.
- e: checking some tokens.

# 3- Fine Tuning the model with Galore:
The hardest part of Fine tuning is the techniques and hyperparameters, i guess Galore is very better than QLora and Lora.

and for hyperparameters should research about it.


# 4- Evaluation and Results

Here is some Results..........


# 5- Deploy
For Deploying i deploy it in huggingface and use gradio for interface of user and model.


-------------------------------------------------------------------------------------------------------------------------------
# Future works:

1- do step 2 tasks. 

2- gathering the model and download it.

3- searching for hyperparameters in fine tuning and galore.

4- how to evaluate the llm.

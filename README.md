# Prompt-Engineering
Prompt Engineering with GPT-2 and BERTScore
Project Overview

This project explores prompt engineering techniques using the GPT-2 language model to generate motivational text. The generated outputs are evaluated against a human-written reference using BERTScore, a metric for assessing semantic similarity.

📌 Project Objectives
Generate motivational quotes using different prompt engineering strategies.

Compare GPT-2 outputs with a human-written reference.

Evaluate text quality using BERTScore (F1 score for semantic similarity).

📂 Project Structure
The project is divided into 5 main parts:

Load GPT-2 Model

Initialize GPT-2 (small version) from Hugging Face’s transformers.

Set up tokenizer and text generation parameters.

Design & Generate Prompts

5 distinct prompt types (Direct, Scenario-based, Persona-based, Keyword-based, Conversational).

Generate 3 outputs per prompt (15 total).

Human-Written Reference

Use a motivational quote by Winston Churchill for comparison.

Evaluate with BERTScore

Compute semantic similarity between GPT-2 outputs and human reference.

Results & Analysis

Display BERTScore F1 for each output.

Compare prompt effectiveness.

⚙️ Setup & Installation
Run the following in a Jupyter Notebook or Google Colab:

python
!pip install transformers torch bert-score pandas
Required Libraries
transformers (Hugging Face) – For GPT-2 model

torch – PyTorch backend

bert-score – For semantic evaluation

pandas – For structured results

📊 Expected Outputs
Generated Quotes (15 total, 3 per prompt type).

Human Reference Quote (Winston Churchill).

BERTScore Evaluation Table (F1 scores for each output).

Example Output:

Prompt Type	Output #	BERTScore F1
Direct instruction	1	0.8523
Scenario-based	1	0.7912
...	...	...
📝 Key Learnings
✔ Prompt engineering affects GPT-2 output quality.
✔ BERTScore helps evaluate semantic similarity (0-1 scale).
✔ Persona-based & conversational prompts often yield more engaging results.

🚀 Future Improvements
Test with larger models (GPT-3, GPT-4).

Use more diverse human references.

Experiment with different decoding strategies (beam search, nucleus sampling).

📜 Submission Checklist
✅ 5 distinct prompts
✅ 15 GPT-2 outputs
✅ 1 human-written reference
✅ BERTScore results table

🔗 Resources
Hugging Face Transformers

BERTScore Paper

GPT-2 Documentation

🎯 Goal: Understand how prompt design influences AI-generated text quality!



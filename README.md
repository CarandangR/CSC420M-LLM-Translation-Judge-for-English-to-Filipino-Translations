# CSC420M-LLM-Translation-Judge-for-English-to-Filipino-Translations
The project is a Large Language Model (LLM) to serve as a Translation Judge, evaluating English-to-Filipino text translations based on predefined criteria using prompt engineering. The system will assess quality, provide scores and explanations, and ensure reliability, scalability, and adaptability without fine-tuning.

# File Overview
Here is an overview and explanation of each file that is in the repository.
- `Datasets - Human-Labeled Validation Set.csv` contains the validation set in .csv format that was used to compare both systems as well as to human evaluations.
- `Datasets - Training.csv` contains the training set in .csv format that was used to fine-tune and test both the prompts and the agentic system.
- `Prompt_judge.ipynb` is the .ipynb file for the prompt-engineered LLM judge.
- `agentic_judge.ipynb` is the .ipynb file for the Agenstic System Judge.
- `agentic_scores.csv` contains the results of the Agentic System Judge for the validation set in .csv format.
- `prompt_validated_dataset.csv`contains the results of the prompt-engineered Judge for the validation set in .csv format.
- `big_gaps.csv` contains the samples within the validation set wherein the human evaluations were furthest from the evaluations of the prompt-engineered judge.
- `prompt_results.json` contains the results of the prompt-engineered Judge for the validation set in a JSON file format.

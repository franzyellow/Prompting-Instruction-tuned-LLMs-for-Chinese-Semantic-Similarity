# Prompting-Instruction-tuned-LLMs-for-Chinese-Semantic-Similarity
- The final report of the project: [Final Report](Yunchong_Huang___Prompting_instruction_tuned_LLMs_for_Chinese_semantic_similarity.pdf)
- The 472 word pairs sampled from [Multi-SimLex dataset](https://multisimlex.com/) of Mandarin Chinese used in all the prompts except for F-9 are available in [this sheet](sampled_avg_multisimlex_CN.csv).
- The 118 word pairs sampled further for the F-9 prompt are available in [this sheet](f9_samples.csv).
- Codes for word pair sampling and lexical semantic similarity retrieval of GPT-4o are available in the [gpt](gpt) folder, along with json and csv files storing results of each prompting method.
- Codes for word pair sampling and lexical semantic similarity retrieval of Doubao-pro-128k are available in the [doubao](doubao) folder, along with json and csv files storing results of each prompting method.
- Codes and results of statistical analysis of results from both models, along with sheets of numeric differences between human annotation scores and model predictions under different prompts, are available in the [evaluation](evaluation) folder. The folder also contains the codes of [error analysis](evaluation/Error%20Analysis.ipynb).

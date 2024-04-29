# StarWars Characters GPT
Fine tune LLaMA to mimic the speech patterns of iconic Star Wars characters!



## How to use

1. Clone or download the repository.
2. Import data in the format of ` <s>[INST] SAMPLE QUESTION  [/INST] SAMPLE ANSWER </s> ` on each line in a `.txt` file. Sample data (Yoda & Jar-Jar Binks) is included for testing purposes.
- NOTE: There is a program included `data_processing.ipynb` that greatly aids in the process of formatting data correctly. More information can be found in the comments of the program.
3. Open `fine_tuning.ipynb` using Jupyter Notebook or any cell-based IDE.
4. Run each cell following the instructions provided in the comments.
5. The fine-tuned model (default name: `merged`) will be in `/star_wars_character_gpt` directory. It can be used with text-generation-webui or any other UI for LLM. 





## Usage/Examples
Using the `jarjar_sample_data.txt` sample dataset:

![jar_jar_ex_1](https://github.com/Teddie-Wei/StarWars-Characters-GPT/assets/114505639/42c027f9-76e0-4fa2-972f-d75f62442e07)

![jar_jar_ex_2](https://github.com/Teddie-Wei/StarWars-Characters-GPT/assets/114505639/78ad3916-5e5d-4fc9-a1a1-7876c155ed85)

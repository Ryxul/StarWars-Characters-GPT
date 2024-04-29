# StarWars Characters GPT
 Fine tune LLaMA to mimick the speech patterns of iconic Star Wars characters!

<h2 align="left">How to use</h2>

###

<p align="left">1. Clone or download the repository.<br><br>2. Import data in the format of `<s>[INST] SAMPLE QUESTION  [/INST] SAMPLE ANSWER </s> ` on each line in a `.txt` file. Sample data (Yoda & Jar-Jar Binks) is included for testing purposes.<br><br>3. Open `fine_tuning.ipynb` using Jupyter Notebook or any cell-based IDE.<br><br>4. Run each cell following the instructions provided in the comments.<br><br>5. The fine-tuned model (default name: `merged`) will be in `/star_wars_character_gpt` directory. It can be used with text-generation-webui or any other UI for LLM.<br><br>NOTE: There is a program included `data_processing.ipynb` that greatly aids in the process of formatting data correctly. More information can be found in the comments of the program.</p>

###

<h3 align="left">Examples</h3>

###

<p align="left">Here are examples of the fine-tuned model created using the `jarjar_sample_data.txt` dataset:</p>

###

<div align="center">
  <img height="200" src="https://imgur.com/StMKNLT"  />
</div>

###

<div align="center">
  <img height="200" src="https://imgur.com/EuQvJVy"  />
</div>

###
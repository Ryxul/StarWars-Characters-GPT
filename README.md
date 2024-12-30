<div align="center">
  <h1>StarWars Characters GPT</h1>
  
  [![Python](https://img.shields.io/badge/Python-3.11.9-brightgreen)](https://www.python.org/)
  [![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
  [![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

  🤖 Fine-tune LLaMA to perfectly mimic iconic Star Wars characters' speech patterns and personalities
</div>

## Overview
StarWars Characters GPT is a specialized fine-tuning project that allows you to create AI models that can authentically replicate the unique speaking styles of Star Wars characters. Using the LLaMA base model, it can learn and reproduce distinctive speech patterns, mannerisms, and personality traits.

## Key Features
- 🎭 **Character Authenticity**
  - Learns unique speech patterns
  - Maintains character consistency
  - Preserves iconic mannerisms

- 🔧 **Easy Fine-tuning**
  - Simple data formatting tools
  - Streamlined training process
  - Efficient model adaptation

- 📚 **Sample Datasets**
  - Pre-formatted training data
  - Jar Jar Binks dataset
  - Yoda dataset

- 💾 **Model Management**
  - Automatic checkpointing
  - Easy model merging
  - Efficient storage

## Installation

### Prerequisites
- Python 3.11.9
- CUDA-compatible GPU (recommended)
- 16GB+ RAM recommended

### Quick Start
```bash
# Clone repository
git clone https://github.com/Ryxul/StarWars-Characters-GPT.git
cd StarWars-Characters-GPT

### Data Preparation
1. Create two text files:
   - `questions.txt`: One question per line
   - `answers.txt`: Corresponding character responses
2. Use `data_processing.ipynb` to format data:
   ```python
   file1_path = "data/your_questions.txt"
   file2_path = "data/your_answers.txt"
   output_path = "data/formatted_data.txt"
   ```

### Fine-tuning Process
1. Open `fine_tuning.ipynb` in Jupyter Notebook
2. Follow the cell-by-cell instructions
3. Run all cells to:
   - Load the base model
   - Configure training parameters
   - Train the model
   - Save and merge the results

### Using the Model
- The fine-tuned model will be saved in the `/merged` directory
- Compatible with text-generation-webui and other LLM interfaces
- Can be loaded directly using Hugging Face's transformers library

## File Requirements

### Training Data Format
- Questions file: Plain text, one question per line
- Answers file: Plain text, one answer per line
- Must have matching number of lines

### Model Files
- Base model: LLaMA 2 7B Chat
- Output format: Compatible with Hugging Face models
- Checkpoint format: PyTorch state dictionaries

## Project Structure
```
StarWars-Characters-GPT/
├── fine_tuning.ipynb        # Main training notebook
├── data_processing.ipynb    # Data formatting tools
├── data/                    # Training datasets
│   ├── jarjar_sample_data/  # Jar Jar Binks samples
│   └── yoda_sample_data/    # Yoda samples
└── requirements.txt         # Dependencies
```

## Example Outputs

### Jar Jar Binks Style
![jar_jar_ex_1](https://github.com/Ryxul/StarWars-Characters-GPT/assets/114505639/42c027f9-76e0-4fa2-972f-d75f62442e07)

![jar_jar_ex_2](https://github.com/Ryxul/StarWars-Characters-GPT/assets/114505639/78ad3916-5e5d-4fc9-a1a1-7876c155ed85)

## Troubleshooting

### Common Issues
- **CUDA Out of Memory**: Reduce batch size or use gradient accumulation
- **Training Instability**: Adjust learning rate and warmup steps
- **Data Format Errors**: Ensure proper formatting using data_processing.ipynb

## Contributing
Contributions are welcome! Feel free to:
- Add new character datasets
- Improve training efficiency
- Enhance documentation
- Fix bugs

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

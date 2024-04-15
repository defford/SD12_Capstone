# SD12 Capstone: Comparative Analysis of Language Models for Game Script Generation
Explore the capabilities of leading LLMs in generating game scripts using Pygame. 

## Project Overview

This project aims to perform a comparative analysis of various large language models (LLMs) to determine which one performs best for generating game scripts in Python. The focus is on assessing the models based on accuracy, bug frequency, completeness, and readability of the generated scripts.

## Language Models Used

- GPT-3.5 by OpenAI
- Claude Haiku by Anthropic
- Gemma 1.1 by Google

## Getting Started

### Prerequisites

- Create account with OpenAI for GPT 3.5.
- Create account with Anthropic for Claude Haiku.
- Create account with HuggingFace and request free access for Gemma 1.1.
- Python 3.11 or higher.
- Visual Studio Code or any preferred IDE for Python development.
- Google Sheets for tracking and comparing data.

### Setup

1. **Clone the Repository:**
```
git clone https://github.com/defford/SD12_Capstone.git
cd SD12_Capstone
```
 
2. **Environment Setup:**
Ensure you have Python installed, and then set up a virtual environment:
```
python -m venv venv
source venv/bin/activate # On Windows use venv\Scripts\activate
```

3. **Install Dependencies:**
Install the required Python packages:
```
pip install -r requirements.txt
```



## Project Structure

- `/scripts` - Contains the game scripts generated by each LLM.
- `/data` - Excel files documenting the comparison metrics.
- `/docs` - Additional documentation and analysis reports.
- `/tests` - Scripts and results from testing the game scripts for functionality.

## Running the Tests

To run the initial script generation:
```
- python scripts/generate_script.py
```

## Analysis

Detailed analysis of each model's performance can be found in the `/docs` directory. This includes metrics on accuracy, error rate, and feature completeness.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Authors

- **Daniel Efford** - *Initial work* - [defford](https://github.com/defford)

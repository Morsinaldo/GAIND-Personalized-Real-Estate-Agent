# Personalized Real Estate Agent

The goal of this project is to create a personalized experience for each buyer of a real estate company, making the property search process more engaging and tailored to individual preferences. To achieve this, an application called "HomeMatch" was developed, which uses Large Language Models (LLMs) and vector databases to transform standard real estate listings into personalized narratives that resonate with potential buyers' unique preferences and needs.

## Core Components of "HomeMatch"

### Understanding Buyer Preferences

- Buyers will input their requirements and preferences, such as location, property type, budget, amenities, and lifestyle choices.
- The application uses LLMs to interpret these inputs in natural language, understanding nuanced requests beyond basic filters.

### Integrating with a Vector Database

- Connect "HomeMatch" with a vector database, where all available property listings are stored.
- Utilize vector embeddings to match properties with buyer preferences, focusing on aspects like neighborhood vibes, architectural styles, and proximity to specific amenities.

### Personalized Listing Description Generation

- For each matched listing, use an LLM to rewrite the description in a way that highlights aspects most relevant to the buyer’s preferences.
- Ensure personalization emphasizes characteristics appealing to the buyer without altering factual information about the property.

### Listing Presentation

- Output the personalized listing(s) as a text description of the listing.

## How to execute

1 - Clone this repositoy

```bash
git clone https://github.com/Morsinaldo/GAIND-Personalized-Real-Estate-Agent.git
cd GAIND-Personalized-Real-Estate-Agent
```

2 - Create the virtual environment

```bash
conda create --name agent --python==3.9.18
```

This step uses [Anaconda](https://www.anaconda.com/) as the environment manager, but feel free to use another one of your choice.

3 - Install the requirements

```bash
pip install -r requirements.txt
```

4 - Run the [notebook](./notebook.ipynb) file.

**Important**: You need to put your OpenAI key in the first cell to run the notebook.

```python
# Environment variables
OPENAI_API_KEY = 'YOUR API KEY'
```
It is deeply recommended to use GPU to execute the code.

## References

[Generative AI NanoDegree](https://www.udacity.com/enrollment/nd608/1.0.14)
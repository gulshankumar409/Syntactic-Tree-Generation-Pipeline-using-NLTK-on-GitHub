# Syntactic-Tree-Generation-Pipeline-using-NLTK-on-GitHub

**NLP Assignment 2: Syntactic Tree Generation Pipeline using NLTK on GitHub**

### Overview

This assignment involves developing a pipeline for generating syntactic trees from input text in English, French, German, or Italian. The syntactic tree should follow a Pure Symbolic approach, utilizing LR analysis with a CF LL2 grammar as the base. The resulting tree should have the root labeled as 'S' for sentence, and the leaves labeled with single Part-of-Speech tags. The pipeline should adhere to specific linguistic rules and constraints for each language.

### Requirements

1. **Languages:** The pipeline should support English, French, German, and Italian.

2. **Syntactic Tree Structure:**
    - Root: 'S' (Sentence)
    - Leaves: Single Part-of-Speech tags

3. **Linguistic Rules:**
    - Adjectives:
        - English and German: Prefixed to nouns
        - French and Italian: Suffixed to nouns
    - Verbs: All in the present tense
    - No pronouns allowed
    - Only one adverb permitted, always post-posed to the verb

4. **Grammar Specification:**
    - Context-free grammar (CF LL2) should be used.
    - Linguistic rules should be integrated into the grammar specification.

5. **POS Tagging:**
    - Use NLTK for POS tagging or any other customizable system available on GitHub.
    - Handle ambiguity by selecting the first admissible tree.

### Implementation

1. **Parser:**
    - Utilize an LR parser for syntactic tree generation.
    - Develop or choose an existing CF LL2 grammar suitable for the specified linguistic rules.

2. **Adjective Placement:**
    - Implement rules for placing adjectives based on the language (prefix or suffix).

3. **Verb Tense:**
    - Ensure that all verbs are in the present tense.

4. **Pronoun Exclusion:**
    - Implement mechanisms to exclude pronouns from the syntactic tree.

5. **Adverb Placement:**
    - Allow for the placement of a single adverb post-posed to the verb.

6. **POS Tagging:**
    - Integrate POS tagging using NLTK or another suitable library available on GitHub.

7. **Ambiguity Resolution:**
    - Ensure that the pipeline blocks ambiguity by selecting the first admissible syntactic tree.

### GitHub Repository

The code for this pipeline is hosted on GitHub: [Syntactic-Tree-Generator](https://github.com/gulshankumar409/Syntactic-Tree-Generation-Pipeline-using-NLTK-on-GitHub)

### Usage

1. Clone the repository: `git clone https://github.com/gulshankumar409/Syntactic-Tree-Generator.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the pipeline: `python syntactic_tree_generator.py input_text.txt`

### Contribution Guidelines

Contributors are welcome to improve the pipeline, add support for additional languages, enhance linguistic rules, or optimize the code. Please follow the contribution guidelines outlined in the repository.

### Acknowledgments

Thanks to all external tools, libraries, or grammars used in the development of the pipeline.

Feel free to customize the above template based on the specifics of your implementation and preferences.

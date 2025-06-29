# JEBS-data
Annotations, abstracts, training data, and testing data used in [_JEBS: A Fine-grained Biomedical Lexical Simplification Task_](https://www.arxiv.org/abs/2506.12898), which was accepted to ACL 2025. These annotations are derived from the [PLABA](https://bionlp.nlm.nih.gov/plaba2024/) dataset. Each `.txt` file in the annotations folder has an accompanying `.ann` file that stores expert terms and their accompanying definitions.

## Abstract
Online medical literature has made health information more available than ever, however, the barrier of complex medical jargon prevents the general public from understanding it. Though parallel and comparable corpora for Biomedical Text Simplification have been introduced, these conflate the many syntactic and lexical operations involved in simplification. To enable more targeted development and evaluation, we present a fine-grained lexical simplification task and dataset, Jargon Explanations for Biomedical Simplification (JEBS). The JEBS task involves identifying complex terms, classifying how to replace them, and generating replacement text. The JEBS dataset contains 21,595 replacements for 10,314 terms across 400 biomedical abstracts and their manually simplified versions. Additionally, we provide baseline results for a variety of rule-based and transformer-based systems for the three sub-tasks. The JEBS task, data, and baseline results pave the way for development and rigorous evaluation of systems for replacing or explaining complex biomedical terms.

## Citations
If you find our data or paper useful for your own projects, please include us in your citations!
```
@misc{xia2025jebsfinegrainedbiomedicallexical,
      title={JEBS: A Fine-grained Biomedical Lexical Simplification Task}, 
      author={William Xia and Ishita Unde and Brian Ondov and Dina Demner-Fushman},
      year={2025},
      eprint={2506.12898},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2506.12898}, 
}
```

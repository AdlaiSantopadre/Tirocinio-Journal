# Tirocinio-Journal
---
09/09/2025
---

**Attività di studio dedicata alle caratteristiche dei database per la bioinformatica.**

BindingBDB
"The first public molecular recognition database, BindingDB supports research, education and practice in drug discovery, pharmacology and related fields."

https://bdb99.ucsd.edu/rwd/bind/index.jsp

*Webinar 1: BindingDB: A Massive, Publicly Accessible, Knowledgebase of Protein-Ligand Binding Data, Mike Gilson*


---
10/09/2025
---

Pre trattamento dei modelli di rappresentazione delle molecole in funzione dell'adozione di algoritmi sequenziali

Paper:Tokenizzazione in #SMILES
PreProcessing.ipynb colab


Ucak, U.V., Ashyrmamatov, I. & Lee, J. Improving the quality of chemical language model outcomes with atom-in-SMILES tokenization. J Cheminform 15, 55 (2023). https://doi.org/10.1186/s13321-023-00725-

https://www.biomedcentral.com/search?query=Tokenization+smiles&searchType=publisherSearch

---
11/09/2025
---

Preprocessing:Ipotesi di combinare data augmentation  con compensazione dei campioni sotto rappresentati

Tokenizzazione: criticità della tokenizzazione SMILES.

* ABOUT TOKENIZATION *
For SMILES chemical tokens, the recommended tokenizers are APE (Atom Pair Encoding) and Atom-in-SMILES (AIS), which outperform traditional Byte Pair Encoding (BPE) by capturing deeper chemical context and ensuring structural integrity. APE is particularly suited for transformer-based models and is available through libraries like GitHub, while Atom-in-SMILES is a novel approach designed to handle complex SMILES tokens and can be found on GitHub.
Traditional tokenization is insufficient for SMILES, related to:
* Ambiguity and Inconsistency.
The standard SMILES notation can represent the same molecule in multiple ways (e.g., "CCO" vs. "OCC" for ethanol), which creates inconsistencies for machine learning models.
* Contextual Loss:
Basic subword tokenizers like BPE often fail to maintain the contextual relationships between chemical elements within the SMILES string, leading to a loss of crucial chemical information.
Recommended tokenization methods for SMILES:
Atom Pair Encoding (APE):
https://github.com/mikemayuare/apetokenizer
This technique is specifically designed for SMILES and SELFIES. It works by encoding information in atom pairs, ensuring that tokens preserve chemical meaning and structural integrity, which significantly improves the performance of chemical language models.
Atom-in-SMILES (AIS):
This approach addresses limitations in traditional SMILES tokenization by eliminating ambiguities and capturing more detailed information about the chemical environment of atoms. The AIS tokenizer can even be hybridized with standard SMILES tokens to create more robust representations.
Where to find and use these tokenizers:
APE Tokenizer: You can find the APE tokenizer on GitHub, making it compatible with the Hugging Face Transformers library.
Atom-in-SMILES: The AIS tokenizer is available on GitHub.
DeepChem: This library also provides scientific tokenizers, some based on the Hugging Face transformers library, that can be used for chemical applications.
---
12/09/2025
---

Implementazione dataframe Smile 
Ricerca metodi di tokenizzazione e costruzione vocaborio
"Recommended tokenization methods for SMILES:
Atom Pair Encoding (APE):
https://github.com/mikemayuare/apetokenizer
This technique is specifically designed for SMILES and SELFIES. It works by encoding information in atom pairs, ensuring that tokens preserve chemical meaning and structural integrity, which significantly improves the performance of chemical language models.
Atom-in-SMILES (AIS):
This approach addresses limitations in traditional SMILES tokenization by eliminating ambiguities and capturing more detailed information about the chemical environment of atoms. The AIS tokenizer can even be hybridized with standard SMILES tokens to create more robust representations.
Where to find and use these tokenizers:
APE Tokenizer: You can find the APE tokenizer on GitHub, making it compatible with the Hugging Face Transformers library.
Atom-in-SMILES: The AIS tokenizer is available on GitHub.
DeepChem: This library also provides scientific tokenizers, some based on the Hugging Face transformers library, that can be used for chemical applications."

Paper:Leon, M., Perezhohin, Y., Peres, F. et al. Comparing SMILES and SELFIES tokenization for enhanced chemical language modeling. Sci Rep 14, 25016 (2024). https://doi.org/10.1038/s41598-024-76440-8


---
18/09/2025
---
Esercitazione Colab

*Analyze BindingDB data in Google Colab using this Python tool from Pat Walters*


Implementazione della tokenizzazione APE

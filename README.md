# Awesome - Materials-Aware Large Language Models [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


**Materials-Aware Large Language Models** (LLMs) are transforming the field of materials science by automating complex tasks traditionally reliant on human expertise. Leveraging advancements in AI, these models facilitate everything from data extraction and property prediction to inverse design, synthesis planning and self-driven labs. LLMs are now paving the way for autonomous materials discovery, enabling researchers to navigate and harness vast, diverse datasets with unprecedented accuracy and efficiency.

>  _Here, we provide a curated, non-exhaustive list of research papers that showcase the applications of LLMs in advancing materials science, particularly in enhancing data extraction, supporting predictive modeling, and driving autonomous experimentation._


## 🌟 Introduction

  <div align=center><img src="./assets/MatLLMs.jpg" width="100%" /></div>
  A non-exhaustive progression of LLMs tailored for materials science, highlighting key milestones within each general model family.


## 🔍 Applications Overview

> ### 📑 Data Extraction
> LLMs for data extraction can process text, images, tables, and graphs from scientific literature, converting unstructured information into structured data, which is essential for building comprehensive materials databases.

| **Name & Link**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| [MagBERT (Kumar et al.)](https://www.sciencedirect.com/science/article/pii/S2213956724002858)            | BERT                      | Magnesium                                  | 2024.08         |
| [MagBERT (Zhumabayeva et al.)](https://pubs.acs.org/doi/10.1021/acs.jpcc.4c01974)      | BERT                      | Magnetic                                   | 2024.07         |
| [ChemREL](https://pubs.acs.org/doi/10.1021/acs.jcim.4c00816)                           | RoBERTa                   | Chemicals                                  | 2024.07         |
| [LLaMat](https://openreview.net/forum?id=ZUkmRy6SqS)                            | LLaMA-2-7B                | Crystal                                    | 2024.07         |
| [MaTableGPT](https://arxiv.org/abs/2406.05431)                        | GPT-4                     | Electrocatalysts                           | 2024.06         |
| [MatGPT](https://www.sciencedirect.com/science/article/pii/S2666389924000540)                            | GPT-3, LLaMA-7B           | Solar cell                                 | 2024.05         |
| [LLaMP](https://arxiv.org/abs/2401.17244)                            | GPT-3.5, GPT-4            | General materials                          | 2024.01         |
| [MatSci-LumEn](https://github.com/lfoppiano/MatSci-LumEn)                      | GPT-3.5, GPT-4            | General materials                          | 2024.01         |
| [MatSciRE](https://arxiv.org/abs/2401.09839)                          | BERT, RoBERTa             | General materials                          | 2024.01         |
| [ACE](https://www.nature.com/articles/s41467-023-43836-5)                               | Transformer               | Single-atom heterogeneous catalysts        | 2023.12         |
| [MechGPT](https://arxiv.org/abs/2310.10445)                           | OpenOrca-Platypus2-13B    | Materials failure                          | 2023.10         |
| [DARWIN](https://arxiv.org/abs/2308.13565)                           | LLaMA-7B                  | Solar cell                                 | 2023.08         |
| [GPT Chemistry Assistant](https://pubs.acs.org/doi/10.1021/jacs.3c05819)          | GPT-3.5, GPT-4            | MOF                                        | 2023.06         |
| [Recycle-BERT](https://pubs.acs.org/doi/10.1021/acssuschemeng.3c03162)                      | BERT                      | Recycling plastic                          | 2023.08         |
| [GPT-MLP](https://www.nature.com/articles/s43246-024-00449-9)                           | GPT-3, GPT-3.5, GPT-4     | Solid-state, doped semiconductors, gold nanoparticle | 2023.08 |
| [MatSci-NLP](https://arxiv.org/abs/2305.08264)                        | BERT                      | General materials                          | 2023.05         |
| [ChatExtract](https://www.nature.com/articles/s41467-024-45914-8)                       | GPT-3.5, GPT-4            | High entropy alloys                        | 2023.03         |
| [OpticalBERT](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01259)                       | BERT                      | Optical                                    | 2023.03         |
| [BatteryDataExtractor](https://pubs.rsc.org/en/content/articlelanding/2022/sc/d2sc04322j)              | BERT                      | Battery                                    | 2022.09         |
| MaterialsBERT                     | BERT                      | Polymer                                    | 2022.09         |
| BatteryBERT                       | BERT                      | Battery                                    | 2022.05         |
| MatBERT                           | BERT                      | Solid-state, doped semiconductors, gold nanoparticle | 2022.04 |
| MatSciBERT                        | BERT                      | Solid oxide fuel cells                     | 2021.09         |
| ChemRxnExtractor                  | BERT                      | Chemical Reaction                          | 2021.06         |
| ChemBERT                          | BERT                      | Chemical Reaction                          | 2021.06         |
| RXNMapper                         | Transformer               | Chemical reactions                         | 2021.04         |
| RXN4Chemistry                     | Transformer               | Chemical reactions                         | 2019.12         |
| SciBERT                           | BERT                      | General scientific text                    | 2019.03         |

---

> ### 📊 Data Mining
> LLMs for data mining support advanced querying, knowledge graph construction, and answering complex questions within materials science.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| SciQAG                            | vicuna-7b-v1.5-16k        | Question-answering                         | 2024.05         |
| BatteryGPT                        | ChatGPT                   | Question-answering                         | 2024.03         |
| MatKG                             | BERT                      | Knowledge graph                            | 2024.01         |
| LitLLM                            | GPT-3.5, GPT-4            | Literature Review                          | 2023.12         |
| PaperQA                           | GPT-3.5, GPT-4            | Question-answering                         | 2023.12         |
| LitQA                             | GPT-3.5, GPT-4            | Question-answering                         | 2023.10         |

---

> ### 🧬 Property Prediction
> LLMs assist in predicting various properties of materials, helping researchers design new materials with targeted characteristics.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| MolecularGPT                      | T5                        | Organic molecule                           | 2024.06         |
| ChatMOF                           | GPT-4, GPT-3.5            | MOF                                        | 2024.06         |
| ChemLLM                           | InternLM2-Base-7B         | Organic molecule                           | 2024.04         |
| AlloyBERT                         | RoBERTa                   | Alloy                                      | 2024.03         |
| CrystalLLM                        | LLaMA-2 70B               | Inorganic                                  | 2024.02         |
| GPTChem                           | GPT-3                     | Organic molecule                           | 2024.02         |
| LLaMP                             | GPT-3.5, GPT-4            | Crystal                                    | 2024.01         |
| PolyNC                            | T5                        | Polymer                                    | 2023.12         |
| FG-BERT                           | BERT                      | Organic molecule                           | 2023.11         |
| LLM-Prop                          | T5                        | Crystalline Solids                         | 2023.10         |
| GPT-MolBERTa                      | BERT, RoBERTa             | Organic molecule                           | 2023.09         |
| CatBERTa                          | RoBERTa                   | Catalyst                                   | 2023.09         |
| DARWIN                            | LLaMA-7B                  | Thermoelectric                             | 2023.08         |
| GIMLET                            | T5                        | Thermoelectric                             | 2023.08         |
| MolRoPE-BERT                      | T5                        | Organic molecule                           | 2023.07         |
| BERTOS                            | BERT                      | Inorganic                                  | 2022.11         |
| SolvBERT                          | BERT                      | Solvent                                    | 2022.10         |
| PolyBERT                          | DeBERTa                   | Polymer                                    | 2022.09         |
| ChemBERTa                         | RoBERTa                   | Organic molecule                           | 2022.08         |
| ChemGPT                           | GPT-Neo                   | Organic molecule                           | 2022.05         |
| Mol-BERT                          | BERT                      | Organic molecule                           | 2022.05         |
| ChemBERTa                         | RoBERTa                   | Organic molecule                           | 2022.03         |
| SMILES-BERT                       | BERT                      | RT                                         | 2019.09         |

---

> ### ⚛️ Structure Generation
> LLMs contribute to generating new material structures, especially for complex materials, enabling accelerated discovery of novel materials.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| ChatMol                           | T5                        | MOF                                        | 2024.09         |
| MatterGPT                         | Customized GPT            | Crystalline Solids                         | 2024.08         |
| MOLLEO                            | GPT-4, T5                 | Organic molecule                           | 2024.07         |
| AtomGPT                           | GPT-2                     | Crystalline Solids                         | 2024.06         |
| ChatMOF                           | GPT-4, GPT-3.5            | MOF                                        | 2024.06         |
| CrystalLLM (Antunes et al.)       | Transformer-based         | Rutiles, spinels, pyrochlores              | 2024.02         |
| GPTChem                           | GPT-3                     | Organic molecule                           | 2024.02         |
| GPT Linker Designer               | GPT-3.5                   | MOF Linker                                 | 2023.12         |
| DARWIN                            | LLaMA-7B                  | MOF                                        | 2023.08         |
| Text+Chem T5                      | T5                        | Inorganic                                  | 2023.02         |
| MolTS                             | T5                        | Inorganic                                  | 2022.11         |
| MT-GPT                            | GPT                       | Inorganic                                  | 2022.10         |
| MT-GPT2                           | GPT-2                     | Inorganic                                  | 2022.10         |
| MT-GPTNeo                         | GPT-Neo                   | Inorganic                                  | 2022.10         |
| MT-GPTJ                           | GPT-J                     | Inorganic                                  | 2022.10         |
| MT-BART                           | BART                      | Inorganic                                  | 2022.10         |
| MT-RoBERTa                        | RoBERTa                   | Inorganic                                  | 2022.10         |
| MolGPT                            | Customized GPT            | Organic molecule                           | 2021.10         |

---

> ### 🧪 Synthesis Planning
> LLMs are employed to predict synthesis routes, aiding researchers in planning experiments and identifying potential synthesis challenges.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| CSLLM                             | LLaMA-7B                  | Crystal                                    | 2024.07         |
| SynthGPT                          | GPT-3.5, GPT-4            | Inorganic                                  | 2024.04         |
| ReactionT5                        | T5                        | Organic                                    | 2023.03         |
| MatChat                           | LLaMA2                    | Inorganic                                  | 2023.10         |
| GPT Chemistry Assistant           | GPT-3.5, GPT-4            | MOF                                        | 2023.08         |
| TSChem                            | T5                        | Organic                                    | 2022.03         |
| ChemFormer                        | BART                      | Organic                                    | 2022.01         |

---

> ### 🤖 Agent-Driven Laboratory
> LLM-based agent systems facilitate laboratory automation by controlling instruments, analyzing real-time data, and autonomously adjusting experiments.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| ChemAgents                        | Llama-3-70B               | Literature reader, experiments designer, robot operator, computation performer | 2024.07         |
| LLMatDesign                       | GPT-4o                    | Data acquisition and filtering, integrated simulations, data analysis and visualization | 2024.06         |
| MicroGPT                          | GPT-4                     | -                                          | 2024.05         |
| ChatGPT Research Group            | GPT-4                     | Synthesis conditions extraction, code generation, research planning, and procedural guidance | 2023.11         |
| GPT-Lab                           | GPT-4                     | Requirements analysis, literature retrieval, text mining, human researcher feedback, experiment execution | 2023.09         |
| AtomAgents                        | GPT-4                     | Automatic robotic experiments              | 2023.07         |
| CREST                             | GPT-3.5                   | -                                          | 2023.07         |
| GPT-4 Reticular Chemist           | GPT-4                     | Project overview, progress summary, propose task choices, evaluation | 2023.06         |
| ChemCrow                          | GPT-4                     | Synthesis execution                        | 2023.04         |
| Coscientist                       | GPT-4                     | Web and documentation search, code execution | 2023.03         |



## Citation

If you find our work and this repository useful, please consider giving a star :star: and citation :beer::



### How to Contribute

Contributions are welcome! Please submit a pull request to add new resources, models, or papers to the repository.


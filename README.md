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
| [MaterialsBERT](https://www.nature.com/articles/s41524-023-01003-w)                     | BERT                      | Polymer                                    | 2022.09         |
| [BatteryBERT](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00035)                       | BERT                      | Battery                                    | 2022.05         |
| [MatBERT](https://www.sciencedirect.com/science/article/pii/S2666389922000733)                           | BERT                      | Solid-state, doped semiconductors, gold nanoparticle | 2022.04 |
| [MatSciBERT](https://www.nature.com/articles/s41524-022-00784-w)                        | BERT                      | Solid oxide fuel cells                     | 2021.09         |
| [ChemRxnExtractor](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00284)                  | BERT                      | Chemical Reaction                          | 2021.06         |
| [ChemBERT](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00284)                          | BERT                      | Chemical Reaction                          | 2021.06         |
| [RXNMapper](https://github.com/rxn4chemistry/rxnmapper)                         | Transformer               | Chemical reactions                         | 2021.04         |
| [RXN4Chemistry](https://github.com/rxn4chemistry/rxn4chemistry)                     | Transformer               | Chemical reactions                         | 2019.12         |
| [SciBERT](https://arxiv.org/abs/1903.10676)                           | BERT                      | General scientific text                    | 2019.03         |

---

> ### 📊 Data Mining
> LLMs for data mining support advanced querying, knowledge graph construction, and answering complex questions within materials science.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| [SciQAG](https://arxiv.org/abs/2405.09939)                            | vicuna-7b-v1.5-16k        | Question-answering                         | 2024.05         |
| [BatteryGPT](https://www.sciencedirect.com/science/article/pii/S2666386424000699?dgcid=rss_sd_all)                        | ChatGPT                   | Question-answering                         | 2024.03         |
| [MatKG](https://www.nature.com/articles/s41597-024-03039-z)                             | BERT                      | Knowledge graph                            | 2024.01         |
| [LitLLM](https://arxiv.org/abs/2402.01788)                            | GPT-3.5, GPT-4            | Literature Review                          | 2023.12         |
| [PaperQA](https://arxiv.org/abs/2312.07559)                           | GPT-3.5, GPT-4            | Question-answering                         | 2023.12         |
| [LitQA](https://arxiv.org/abs/2312.07559)                             | GPT-3.5, GPT-4            | Question-answering                         | 2023.10         |

---

> ### 🧬 Property Prediction
> LLMs assist in predicting various properties of materials, helping researchers design new materials with targeted characteristics.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| [MolecularGPT](https://arxiv.org/abs/2406.12950)                      | T5                        | Organic molecule                           | 2024.06         |
| [ChatMOF](https://www.nature.com/articles/s41467-024-48998-4)                           | GPT-4, GPT-3.5            | MOF                                        | 2024.06         |
| [ChemLLM](https://arxiv.org/abs/2402.06852)                           | InternLM2-Base-7B         | Organic molecule                           | 2024.04         |
| [AlloyBERT](https://arxiv.org/abs/2403.19783)                         | RoBERTa                   | Alloy                                      | 2024.03         |
| [CrystalLLM (Gruver et al.)](https://arxiv.org/abs/2402.04379)                        | LLaMA-2 70B               | Inorganic                                  | 2024.02         |
| [GPTChem](https://www.nature.com/articles/s42256-023-00788-1)                           | GPT-3                     | Organic molecule                           | 2024.02         |
| [LLaMP](https://arxiv.org/abs/2401.17244)                             | GPT-3.5, GPT-4            | Crystal                                    | 2024.01         |
| [PolyNC](https://pubs.rsc.org/en/content/articlelanding/2024/sc/d3sc05079c)                            | T5                        | Polymer                                    | 2023.12         |
| [FG-BERT](https://academic.oup.com/bib/article/24/6/bbad398/7337693)                           | BERT                      | Organic molecule                           | 2023.11         |
| [LLM-Prop](https://arxiv.org/abs/2310.14029)                          | T5                        | Crystalline Solids                         | 2023.10         |
| [GPT-MolBERTa](https://arxiv.org/abs/2310.03030)                      | BERT, RoBERTa             | Organic molecule                           | 2023.09         |
| [CatBERTa](https://pubs.acs.org/doi/10.1021/acscatal.3c04956)                          | RoBERTa                   | Catalyst                                   | 2023.09         |
| [DARWIN](https://arxiv.org/abs/2308.13565)                            | LLaMA-7B                  | Thermoelectric                             | 2023.08         |
| [GIMLET](https://arxiv.org/abs/2306.13089)                            | T5                        | Thermoelectric                             | 2023.08         |
| [MolRoPE-BERT](https://www.sciencedirect.com/science/article/pii/S1093326322002236)                      | T5                        | Organic molecule                           | 2023.07         |
| [BERTOS](https://onlinelibrary.wiley.com/doi/full/10.1002/advs.202301011)                            | BERT                      | Inorganic                                  | 2022.11         |
| [SolvBERT](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d2dd00107a)                          | BERT                      | Solvent                                    | 2022.10         |
| [PolyBERT](https://www.nature.com/articles/s41467-023-39868-6)                          | DeBERTa                   | Polymer                                    | 2022.09         |
| [ChemBERTa](https://arxiv.org/abs/2010.09885)                         | RoBERTa                   | Organic molecule                           | 2022.08         |
| [ChemGPT](https://www.nature.com/articles/s42256-023-00740-3)                           | GPT-Neo                   | Organic molecule                           | 2022.05         |
| [Mol-BERT](https://onlinelibrary.wiley.com/doi/10.1155/2021/7181815)                          | BERT                      | Organic molecule                           | 2022.05         |
| [ChemBERTa](https://arxiv.org/abs/2010.09885)                         | RoBERTa                   | Organic molecule                           | 2022.03         |
| [SMILES-BERT](https://github.com/uta-smile/SMILES-BERT)                       | BERT                      | RT                                         | 2019.09         |

---

> ### ⚛️ Structure Generation
> LLMs contribute to generating new material structures, especially for complex materials, enabling accelerated discovery of novel materials.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| [ChatMol](https://academic.oup.com/bioinformatics/article/40/9/btae534/7747661)                           | T5                        | MOF                                        | 2024.09         |
| [MatterGPT](https://arxiv.org/abs/2408.07608)                         | Customized GPT            | Crystalline Solids                         | 2024.08         |
| [MOLLEO](https://arxiv.org/abs/2406.16976)                            | GPT-4, T5                 | Organic molecule                           | 2024.07         |
| [AtomGPT](https://pubs.acs.org/doi/10.1021/acs.jpclett.4c01126)                           | GPT-2                     | Crystalline Solids                         | 2024.06         |
| [ChatMOF](https://www.nature.com/articles/s41467-024-48998-4)                           | GPT-4, GPT-3.5            | MOF                                        | 2024.06         |
| [CrystalLLM (Antunes et al.)](https://arxiv.org/abs/2307.04340)       | Transformer-based         | Rutiles, spinels, pyrochlores              | 2024.02         |
| [GPTChem](https://www.nature.com/articles/s42256-023-00788-1)                           | GPT-3                     | Organic molecule                           | 2024.02         |
| [GPT Linker Designer](https://pubs.acs.org/doi/10.1021/jacs.3c12086)               | GPT-3.5                   | MOF Linker                                 | 2023.12         |
| [DARWIN](https://arxiv.org/abs/2308.13565)                            | LLaMA-7B                  | MOF                                        | 2023.08         |
| [Text+Chem T5](https://arxiv.org/abs/2301.12586)                      | T5                        | Inorganic                                  | 2023.02         |
| [MolT5](https://arxiv.org/abs/2204.11817)                             | T5                        | Inorganic                                  | 2022.11         |
| [MT-GPT](https://arxiv.org/abs/2206.13578)                            | GPT                       | Inorganic                                  | 2022.10         |
| [MT-GPT2](https://arxiv.org/abs/2206.13578)                           | GPT-2                     | Inorganic                                  | 2022.10         |
| [MT-GPTNeo](https://arxiv.org/abs/2206.13578)                         | GPT-Neo                   | Inorganic                                  | 2022.10         |
| [MT-GPTJ](https://arxiv.org/abs/2206.13578)                           | GPT-J                     | Inorganic                                  | 2022.10         |
| [MT-BART](https://arxiv.org/abs/2206.13578)                           | BART                      | Inorganic                                  | 2022.10         |
| [MT-RoBERTa](https://arxiv.org/abs/2206.13578)                        | RoBERTa                   | Inorganic                                  | 2022.10         |
| [MolGPT](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600)                            | Customized GPT            | Organic molecule                           | 2021.10         |

---

> ### 🧪 Synthesis Planning
> LLMs are employed to predict synthesis routes, aiding researchers in planning experiments and identifying potential synthesis challenges.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| [CSLLM](https://arxiv.org/abs/2407.07016)                             | LLaMA-7B                  | Crystal                                    | 2024.07         |
| [SynthGPT](https://pubs.acs.org/doi/10.1021/jacs.4c05840)                          | GPT-3.5, GPT-4            | Inorganic                                  | 2024.04         |
| [ReactionT5](https://arxiv.org/abs/2311.06708)                        | T5                        | Organic                                    | 2023.03         |
| [MatChat](https://arxiv.org/abs/2310.07197)                           | LLaMA2                    | Inorganic                                  | 2023.10         |
| [GPT Chemistry Assistant](https://pubs.acs.org/doi/10.1021/jacs.3c05819)           | GPT-3.5, GPT-4            | MOF                                        | 2023.08         |
| [T5Chem](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01467)                            | T5                        | Organic                                    | 2022.03         |
| [ChemFormer](https://iopscience.iop.org/article/10.1088/2632-2153/ac3ffb)                        | BART                      | Organic                                    | 2022.01         |

---

> ### 🤖 Agent-Driven Laboratory
> LLM-based agent systems facilitate laboratory automation by controlling instruments, analyzing real-time data, and autonomously adjusting experiments.

| **Name**                          | **Models**                | **Material Types**                         | **Release Date** |
|-----------------------------------|---------------------------|--------------------------------------------|------------------|
| [ChemAgents](https://chemrxiv.org/engage/chemrxiv/article-details/66a8c11bc9c6a5c07a7a59c0)                        | Llama-3-70B               | Literature reader, experiments designer, robot operator, computation performer | 2024.07         |
| [LLMatDesign](https://arxiv.org/abs/2406.13163)                       | GPT-4o                    | Data acquisition and filtering, integrated simulations, data analysis and visualization | 2024.06         |
| [MicroGPT](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d4dd00074a)                          | GPT-4                     | -                                          | 2024.05         |
| [ChatGPT Research Group](https://pubs.acs.org/doi/10.1021/acscentsci.3c01087)            | GPT-4                     | Synthesis conditions extraction, code generation, research planning, and procedural guidance | 2023.11         |
| [GPT-Lab](https://arxiv.org/abs/2309.16721)                           | GPT-4                     | Requirements analysis, literature retrieval, text mining, human researcher feedback, experiment execution | 2023.09         |
| [AtomAgents](https://arxiv.org/html/2407.10022v1)                        | GPT-4                     | Automatic robotic experiments              | 2023.07         |
| [CREST](https://chemrxiv.org/engage/chemrxiv/article-details/64a81dcd6e1c4c986bf83225)                             | GPT-3.5                   | -                                          | 2023.07         |
| [GPT-4 Reticular Chemist](https://onlinelibrary.wiley.com/doi/10.1002/anie.202311983)           | GPT-4                     | Project overview, progress summary, propose task choices, evaluation | 2023.06         |
| [ChemCrow](https://www.nature.com/articles/s42256-024-00832-8)                          | GPT-4                     | Synthesis execution                        | 2023.04         |
| [Coscientist](https://www.nature.com/articles/s41586-023-06792-0)                       | GPT-4                     | Web and documentation search, code execution | 2023.03         |



## Citation

If you find our work and this repository useful, please consider giving a star :star: and citation :beer::



### How to Contribute

Contributions are welcome! Please submit a pull request to add new resources, models, or papers to the repository.


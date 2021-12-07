# Scientific Writing

This repository contains tips regarding scientific writing and a LaTeX template for conferences. It is synced to an [Overleaf](https://www.overleaf.com) project.

## English for Germans

### Tools
Use [LanguageTool](https://languagetool.org/de) (does integrate with Overleaf) or [Grammerly](https://www.grammarly.com/) to check your writing style. For LanguageTool, activate the "Acribic Mode"

### Writing Style

A sentence should not be longer than **25 words**.

| Writing Style      | Negative Example | Positive Example | Explanation
| ----------- | ----------- | ----------- | ----------- | 
| Active Voice      | Oxygen was consumed at a higher rate       | The mouse consumed oxygen at a higher rate       |   Makes the text much easier to comprehend     |
| Oxford Comma      | We monitored temperature, pressure and volume.       | We monitored temperature, pressure, and volume.       | The comma ensures that the last two items are not beeing understood as one       |
| Hyphen      | Please bring the report up-to-date       | Please deliver an up-to-date report       | Use hypens to describe nouns       |
| Verbs instead of abstract nouns | Examination of the metal components was carried out... | We examined the metal components... | Text is easier to read out aloud (max 1 breath per sentence) | Parallel Structures | Our investigation has two goals: ° to discover root causes of production problems, ° eliminating uncertainties in design processes | Our investigation has two goals: ° to discover root causes of production problems, ° to eliminate uncertainties in design processes | Structured lists


### Tenses

Present Tense: What is known
Past Tense: What you did
Future Tense: What comes after the paper

| Section      | Tense | Notes
| ----------- | ----------- | ----------- | 
| Abstract | Past or Present | Present for general statements and facts
| Introduction      | Present       | Research question: Past, Present or Future       |
| State of the Art      | Past or Present       |        |
| Method      | Past       |        |
| Evaluation      | Past or Present       | Specific results in Past, more general ones in Present       |
| Conclusion      | Present or Future       | Future for Outlook       |

## Paper Style


## Citations
Use [Zotero](https://www.zotero.org/) for your literature management. Every group managed by an FZI employee has unlimited storage for your files.

**Examples for paper types:**
#### arXiv (cite if arXiv is the only source of a paper)
```
@article{Bogdoll_Taxonomy_2021_arXiv,
    author    = {Bogdoll, Daniel and Orf, Stefan and T\"{o}ttel, Lars and Z\"{o}llner, J. Marius},
    title     = {{Taxonomy and Survey on Remote Human Input Systems for Driving Automation Systems}}, 
    journal   = {arXiv preprint:2109.08599},
    year      = {2021}
}
```

#### Conference proceedings
```
@InProceedings{Weber_Automated_2020_IV,
    author    = {Weber, Michael and F\"{u}rst, Michael and Z\"{o}llner, J. Marius},
    title     = {{Automated Focal Loss for Image based Object Detection}},
    booktitle = {2020 IEEE Intelligent Vehicles Symposium (IV)},
    pages     = {1423-1429},
    year      = {2020}
}
```

#### Published without proceedings
```
@article{Bogdoll_Compressing_2021_NeurIPS,
    author    = {Bogdoll, Daniel and Jestram, Johannes and Rauch, Jonas and Scheib, Christin and Wittig, Moritz and Z\"{o}llner, J. Marius},
    title     = {{Compressing Sensor Data for Remote Assistance of Autonomous Vehicles using Deep Generative Models}},
    journal   = {NeurIPS Conference on Neural Information Processing Systems Workshop on Machine Learning for Autonomous Driving (ML4AD)},
    year      = {2021}
}
```

#### PhD Thesis
```
@phdthesis{Kuhnt_Holistic_2020_PhD,
    author    = {Kuhnt, Florian},
    title     = {{Holistic Temporal Situation Interpretation for Traffic Participant Prediction}},
    school    = {Karlsruhe Institute of Technology (KIT)},
    year      = {2020}
}
```

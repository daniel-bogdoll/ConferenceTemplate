# Scientific Writing

This repository contains tips regarding scientific writing and a LaTeX template for conferences. It is synced to an [Overleaf](https://www.overleaf.com) project.

## English for Germans

### Tools
Use [LanguageTool](https://languagetool.org/de) (does integrate with Overleaf) or [Grammerly](https://www.grammarly.com/) to check your writing style. For LanguageTool, activate the "Acribic Mode"

### Style

A sentence should not be longer than **25 words**.

| Writing Style      | Negative Example | Positive Example | Explanation
| ----------- | ----------- | ----------- | ----------- | 
| Active Voice      | Title       | Title       | Title       |
| Oxford Comma      | Title       | Title       | Title       |
| Hyphen      | Title       | Title       | Title       |


### Tenses

| Section      | Tense | Explanation
| ----------- | ----------- | ----------- | 
| Header      | Title       | Title       |

### Citations
Use [Zotero](https://www.zotero.org/) for your literature management. Every group managed by an FZI employee has unlimited storage for your files.

**Details:**
- Use `\"{o}` instead of ö etc.
- Use `\'{e}` instead of é etc.
- Use the `lastname1, firstname1 and lastname2, firstname2` format for the author list
- Put the title in `{{title}}`, this preserves upper and lower case etc.

**Examples for paper types:**
#### arXiv
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

## Paper Style

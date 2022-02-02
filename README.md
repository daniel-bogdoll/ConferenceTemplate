# Scientific Writing

This repository contains tips regarding scientific writing and a LaTeX template for conferences. It is synced with an Overleaf project. If you publish associated open-source code, provide the BibTeX  in the [README.md](https://github.com/danijar/dreamerv2), provide a [CITATION.ccf](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files) file and link the official code to the [arXiv Code & Data](https://blog.arxiv.org/2020/10/08/new-arxivlabs-feature-provides-instant-access-to-code/) tab.

## Tools

- [Overleaf](https://www.overleaf.com) to write your paper in LaTeX
- [LanguageTool](https://languagetool.org/de), which does integrate with Overleaf, to check your writing style. Activate  "Acribic Mode"
- [Zotero](https://www.zotero.org/) for your literature management. Can be synced with Overleaf

### Overleaf Import

<details>
  <summary markdown="span">Download the GitHub project as a ZIP file</summary>
   <img width="100%" src="https://user-images.githubusercontent.com/19552411/152166487-1fab3898-379d-45fa-990e-623c1b0c4d11.png">
</details>

<details>
  <summary markdown="span">Import the ZIP file in Overleaf as a new project</summary>
   <img width="100%" src="https://user-images.githubusercontent.com/19552411/152167259-0efd69e1-ec87-4af6-a37d-0c33b44328ba.png">
    <br/><br/>
   <img width="100%" src="https://user-images.githubusercontent.com/19552411/152167387-cda2a714-b1c0-4908-bce9-6e73e49132e0.png">
</details>

## Paper Style

"**Get the gestalt right.** I remember being impressed with Fei-Fei (my adviser) once during a reviewing session. I had a stack of 4 papers I had reviewed over the last several hours and she picked them up, **flipped through each one for 10 seconds**, and said one of them was good and the other three bad. Indeed, I was accepting the one and rejecting the other three, but something that took me several hours took her seconds." - [Andrej Karpathy, Head of AI at Tesla](http://karpathy.github.io/2016/09/07/phd/)

Use a color palette that is suited for colorblind people, such as the ones proposed by [David Nichols](https://davidmathlogic.com/colorblind/#%23D81B60-%231E88E5-%23FFC107-%23004D40):
![image](https://user-images.githubusercontent.com/19552411/149807873-16d2adab-aa74-48c8-a75b-fb3ae1ebd702.png)


### Citations

- Use `\"{o}` instead of ö, `\'{e}` instead of é etc. to avoid issues
- Use the `lastname1, firstname1 and lastname2, firstname2` format for the author list
- Put the title in `{{title}}`, this preserves the desired upper and lower case
- Use citation styles **consistently**
- Cite arXiv only if it is the only version of a paper (but keep in mind there is a [trend towards arXiv citations](https://github.com/danijar/dreamerv2))
- Add non-breaking spaces, so references don't slide to the next line: `[...] in~\cite{} [...]` instead of `[...] in \cite{} [...]` 
- Use [archive.org](https://archive.org/web/) for [archived versions of websites](https://help.archive.org/hc/en-us/articles/360001513491-Save-Pages-in-the-Wayback-Machine) from the date you accessed them

**Citation types:**
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
    booktitle = {IEEE Intelligent Vehicles Symposium (IV)},
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
@phdThesis{Kuhnt_Holistic_2020_PhD,
    author    = {Kuhnt, Florian},
    title     = {{Holistic Temporal Situation Interpretation for Traffic Participant Prediction}},
    school    = {Karlsruhe Institute of Technology (KIT)},
    year      = {2020}
}
```

#### Website
```
@misc{Asam_Openscenario_2020_Web,
    author    = {{ASAM}},
    title     = {{ASAM OpenSCENARIO®}},
    howpublished = {\url{https://web.archive.org/web/20220104123527/https://www.asam.net/standards/detail/openscenario/}},
    year      = {2021},
    note      = {Accessed: 2022-01-01}
}
```

## English for Germans

### Writing Style

A sentence should not be longer than **25 words**.

| Writing Style      | Negative Example | **Positive Example** | Explanation
| ----------- | ----------- | ----------- | ----------- | 
| Active Voice      | An error has occurred with your account, but every attempt was made to remedy it.       | **We made an error with your account, but we have made every attempt to remedy it.**       |   Makes the text much easier to comprehend     |
| Oxford Comma      | We monitored temperature, pressure and volume.       | **We monitored temperature, pressure, and volume.**       | The comma ensures that the last two items are not beeing understood as one       |
| Hyphen      | Please bring the report up-to-date.       | **Please deliver an up-to-date report.**       | Use hyphens to describe nouns       |
| Verbs instead of abstract nouns | Examination of the metal components was carried out... | **We examined the metal components...** | Text is easier to read out aloud (max 1 breath per sentence) | Parallel Structures | Our investigation has two goals: ° to discover root causes of production problems, ° eliminating uncertainties in design processes | **Our investigation has two goals: ° to discover root causes of production problems, ° to eliminate uncertainties in design processes** | Structured lists


### Tenses

- Present Tense: What is known
- Past Tense: What you did
- Future Tense: What comes after the paper

| Section      | Tense | Notes
| ----------- | ----------- | ----------- | 
| Abstract | Past or Present | Present for general statements and facts
| Introduction      | Present       | Research question: Past, Present or Future       |
| State of the Art      | Past or Present       | If something is always true, then it should be written in present tense       |
| Method      | Past       |        |
| Evaluation      | Past or Present       | Specific results in Past, more general ones in Present       |
| Conclusion      | Present or Future       | Future for Outlook       |


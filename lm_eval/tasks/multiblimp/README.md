# MultiBLiMP

### Paper

Title: `MultiBLiMP 1.0: A Massively Multilingual Benchmark of Linguistic Minimal Pairs`

Abstract: https://arxiv.org/abs/2504.02768

MultiBLiMP is a massively multilingual benchmark of linguistic minimal pairs, covering 101 languages, 6 linguistic phenomena and containing more than 125,000 minimal pairs. This repository contains the code for creating the corpus and the scripts for LLM evaluation. This evaluation covers 26 languages

Homepage: https://github.com/jumelet/multiblimp


### Citation

```
@article{jumelet2025multiblimp,
  title={MultiBLiMP 1.0: A massively multilingual benchmark of linguistic minimal pairs},
  author={Jumelet, Jaap and Weissweiler, Leonie and Bisazza, Arianna},
  journal={arXiv preprint arXiv:2504.02768},
  year={2025}
}
```

### Groups and Tasks

#### Groups

* `multiblimp`

#### Tasks
* `multiblimp_ar`: Arabic  
* `multiblimp_bg`: Bulgarian  
* `multiblimp_cy`: Welsh  
* `multiblimp_hr`: Croatian  
* `multiblimp_da`: Danish  
* `multiblimp_de`: German  
* `multiblimp_el`: Greek  
* `multiblimp_es`: Spanish  
* `multiblimp_et`: Estonian  
* `multiblimp_eu`: Basque  
* `multiblimp_fa`: Persian  
* `multiblimp_fr`: French  
* `multiblimp_he`: Hebrew  
* `multiblimp_hi`: Hindi  
* `multiblimp_is`: Icelandic  
* `multiblimp_it`: Italian  
* `multiblimp_jp`: Japanese  
* `multiblimp_ne`: Nepali  
* `multiblimp_nl`: Dutch  
* `multiblimp_pl`: Polish  
* `multiblimp_pt`: Portuguese  
* `multiblimp_ro`: Romanian  
* `multiblimp_sr`: Serbian  
* `multiblimp_sv`: Swedish  
* `multiblimp_tr`: Turkish  
* `multiblimp_uk`: Ukrainian  
* `multiblimp_ur`: Urdu  


### Checklist

For adding novel benchmarks/datasets to the library:
* [ ] Is the task an existing benchmark in the literature?
  * [ ] Have you referenced the original paper that introduced the task?
  * [ ] If yes, does the original paper provide a reference implementation? If so, have you checked against the reference implementation and documented how to run such a test?


If other tasks on this dataset are already supported:
* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?

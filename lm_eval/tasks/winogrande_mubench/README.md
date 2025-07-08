# XStoryCloze

### Paper

Title: `WINOGRANDE: An Adversarial Winograd Schema Challenge at Scale`

Abstract: https://arxiv.org/abs/1907.10641

The Winograd Schema Challenge (WSC) (Levesque, Davis, and Morgenstern 2011), a benchmark for commonsense reasoning, is a set of 273 expert-crafted pronoun resolution problems originally designed to be unsolvable for statistical models that rely on selectional preferences or word associations.

Homepage: https://winogrande.allenai.org/

### Citation

```
@article{sakaguchi2021winogrande,
  title={Winogrande: An adversarial winograd schema challenge at scale},
  author={Sakaguchi, Keisuke and Bras, Ronan Le and Bhagavatula, Chandra and Choi, Yejin},
  journal={Communications of the ACM},
  volume={64},
  number={9},
  pages={99--106},
  year={2021},
  publisher={ACM New York, NY, USA}
}
```

### Groups and Tasks

#### Groups

* `winogrande_mubench`

#### Tasks
* `winogrande_af_mubench`: Afrikaans  
* `winogrande_ar_mubench`: Arabic  
* `winogrande_eu_mubench`: Basque  
* `winogrande_bg_mubench`: Bulgarian  
* `winogrande_zh_mubench`: Chinese  
* `winogrande_hr_mubench`: Croatian  
* `winogrande_da_mubench`: Danish  
* `winogrande_nl_mubench`: Dutch  
* `winogrande_et_mubench`: Estonian  
* `winogrande_fr_mubench`: French  
* `winogrande_de_mubench`: German  
* `winogrande_el_mubench`: Greek  
* `winogrande_he_mubench`: Hebrew  
* `winogrande_hi_mubench`: Hindi 
* `winogrande_hu_mubench`: Hungarian 
* `winogrande_id_mubench`: Indonesian  
* `winogrande_is_mubench`: Icelandic  
* `winogrande_it_mubench`: Italian  
* `winogrande_jp_mubench`: Japanese  
* `winogrande_kn_mubench`: Kannada  
* `winogrande_ko_mubench`: Korean  
* `winogrande_fa_mubench`: Persian  
* `winogrande_pl_mubench`: Polish  
* `winogrande_pt_mubench`: Portuguese  
* `winogrande_ro_mubench`: Romanian  
* `winogrande_sr_mubench`: Serbian  
* `winogrande_es_mubench`: Spanish  
* `winogrande_sv_mubench`: Swedish  
* `winogrande_tr_mubench`: Turkish  
* `winogrande_uk_mubench`: Ukrainian  
* `winogrande_ur_mubench`: Urdu  


### Checklist

For adding novel benchmarks/datasets to the library:
* [ ] Is the task an existing benchmark in the literature?
  * [ ] Have you referenced the original paper that introduced the task?
  * [ ] If yes, does the original paper provide a reference implementation? If so, have you checked against the reference implementation and documented how to run such a test?


If other tasks on this dataset are already supported:
* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?

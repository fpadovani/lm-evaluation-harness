# XStoryCloze

### Paper

Title: `Few-shot Learning with Multilingual Language Models`

Abstract: https://arxiv.org/abs/2112.10668

XStoryCloze consists of the professionally translated version of the [English StoryCloze dataset](https://cs.rochester.edu/nlp/rocstories/) (Spring 2016 version) to 10 non-English languages. This dataset is released by Meta AI.

Homepage: https://github.com/facebookresearch/fairseq/pull/4820


### Citation

```
@article{DBLP:journals/corr/abs-2112-10668,
  author    = {Xi Victoria Lin and
               Todor Mihaylov and
               Mikel Artetxe and
               Tianlu Wang and
               Shuohui Chen and
               Daniel Simig and
               Myle Ott and
               Naman Goyal and
               Shruti Bhosale and
               Jingfei Du and
               Ramakanth Pasunuru and
               Sam Shleifer and
               Punit Singh Koura and
               Vishrav Chaudhary and
               Brian O'Horo and
               Jeff Wang and
               Luke Zettlemoyer and
               Zornitsa Kozareva and
               Mona T. Diab and
               Veselin Stoyanov and
               Xian Li},
  title     = {Few-shot Learning with Multilingual Language Models},
  journal   = {CoRR},
  volume    = {abs/2112.10668},
  year      = {2021},
  url       = {https://arxiv.org/abs/2112.10668},
  eprinttype = {arXiv},
  eprint    = {2112.10668},
  timestamp = {Tue, 04 Jan 2022 15:59:27 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2112-10668.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

### Groups and Tasks

#### Groups

* `xstorycloze_mubench`

#### Tasks
* `xstorycloze_af_mubench`: Afrikaans
* `xstorycloze_ar_mubench`: Arabic
* `xstorycloze_eu_mubench`: Basque
* `xstorycloze_bg_mubench`: Bulgarian
* `xstorycloze_zh_mubench`: Chinese
* `xstorycloze_hr_mubench`: Croatian
* `xstorycloze_da_mubench`: Danish
* `xstorycloze_nl_mubench`: Dutch
* `xstorycloze_et_mubench`: Estonian
* `xstorycloze_fr_mubench`: French
* `xstorycloze_de_mubench`: German
* `xstorycloze_el_mubench`: Greek
* `xstorycloze_he_mubench`: Hebrew
* `xstorycloze_hi_mubench`: Hindi
* `xstorycloze_id_mubench`: Indonesian
* `xstorycloze_is_mubench`: Icelandic
* `xstorycloze_it_mubench`: Italian
* `xstorycloze_jp_mubench`: Japanese
* `xstorycloze_kn_mubench`: Kannada
* `xstorycloze_ko_mubench`: Korean
* `xstorycloze_fa_mubench`: Persian
* `xstorycloze_pl_mubench`: Polish
* `xstorycloze_pt_mubench`: Portuguese
* `xstorycloze_ro_mubench`: Romanian
* `xstorycloze_sr_mubench`: Serbian
* `xstorycloze_es_mubench`: Spanish
* `xstorycloze_sv_mubench`: Swedish
* `xstorycloze_tr_mubench`: Turkish
* `xstorycloze_uk_mubench`: Ukrainian
* `xstorycloze_ur_mubench`: Urdu
  


### Checklist

For adding novel benchmarks/datasets to the library:
* [ ] Is the task an existing benchmark in the literature?
  * [ ] Have you referenced the original paper that introduced the task?
  * [ ] If yes, does the original paper provide a reference implementation? If so, have you checked against the reference implementation and documented how to run such a test?


If other tasks on this dataset are already supported:
* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?

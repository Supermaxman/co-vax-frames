# *CoVaxFrames*: From Hesitancy Framings to Vaccine Hesitancy Profiles: A Journey of Stance, Ontological Commitments and Moral Foundations

This repository contains the annotations utilized in the following research paper:

[From Hesitancy Framings to Vaccine Hesitancy Profiles: A Journey of Stance, Ontological Commitments and Moral Foundations](https://ojs.aaai.org/index.php/ICWSM/article/view/19360)

Please cite as the following:

```
@article{weinzierl2022hesitancy,
	title        = {From Hesitancy Framings to Vaccine Hesitancy Profiles: A Journey of Stance, Ontological Commitments and Moral Foundations},
	author       = {Weinzierl, Maxwell A. and Harabagiu, Sanda M.},
	year         = 2022,
	month        = {May},
	journal      = {Proceedings of the International AAAI Conference on Web and Social Media},
	volume       = 16,
	number       = 1,
	pages        = {1087--1097},
	url          = {https://ojs.aaai.org/index.php/ICWSM/article/view/19360}
}
```

## *CoVaxFrames*
The *CoVaxFrames* collection is provided in the following file structure:

    ├── annotations          ~~~~ # [tweet, framing] human judgements
    │   ├── dev.jsonl         # development split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   ├── test.jsonl        # testing split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   └── train.jsonl       # training split of {Accept, Reject, No Stance, Not Relevant} human judgements
    └── taxonomy              # Framing taxonomy judgements
       ├── misinfo.json      # MisTs with text as a json dictionary
       ├── mist-concerns.csv # MisT concerns
       ├── mist-themes.csv   # MisT themes
       ├── mists.csv         # MisTs with m_ids which map to MisT concerns
       └── questions.csv     # Questions used to discover MisTs

You will need to use the Twitter API to download the text of the annotated tweets, as we cannot directly provide this info
due to our IRB and Twitter's API policy.


## Code
Code for the above research paper is provided in the following repository:
[Link](https://github.com/Supermaxman/pytorch-gleam)


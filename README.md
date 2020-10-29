## A Sentence Cloze Dataset for Chinese Machine Reading Comprehension (CMRC 2019)

This repository contains the data for [The Third Evaluation Workshop on Chinese Machine Reading Comprehension (CMRC 2019)](https://hfl-rc.github.io/cmrc2019/). We will present our paper at [COLING 2020](https://coling2020.org),

**Title: A Sentence Cloze Dataset for Chinese Machine Reading Comprehension**  
Authors: Yiming Cui, Ting Liu, Ziqing Yang, Zhipeng Chen, Wentao Ma, Wanxiang Che, Shijin Wang, Guoping Hu  
Link: https://arxiv.org/abs/2004.03116  
Venue: COLING 2020  


## Updates
Oct 1, 2020 Our paper is accepted to [COLING 2020](https://coling2020.org).  
April 8, 2020 Add [dataset description paper](https://arxiv.org/abs/2004.03116)   
August 1, 2019	**Qualifying data** has been released, check *data* directory. (**Note that, json key 'answers' no longer contains answers.**)  
June 10, 2019	**Development data** has been released, check *data* directory.  
May 24, 2019  **Baseline system** has been released, check *baseline* directory.  
May 23, 2019  **Train/Trial data** have been released, check *data* directory.  
May 17, 2019	We are expected to release task introduction and call for participation on late May or early June. Stay tuned!  

## Directory Guide

- baseline: a Chinese BERT-based simple baseline system

- eval: contains official evaluation script

- data: contains offical evaluation data

- sample_submission: sample submission for codalab competition platform (`trial_rand_submission.zip` is a randomly generated prediction file, `trial_submission.zip` is the BERT baseline prediction file)


## Baseline System

We provide a BERT-based baseline system for participants (check *baseline* directory for more info).

Results on other sets will be annouced later.

> QAC: Question-Level Accuracy

> PAC: Passage-Level Accuracy

| Data | Passage # | Query # | QAC | PAC | Fake Candidates | Availability |
| :------ | :-----: | :-----: | :-----: | :-----: | :-----: | :----- |
| Trial Data | 139 | 1,504 | 71.941% | 28.776% | No | Public |
| Train Data | 9,638 | 100,009 | N/A | N/A | No | Public |
| Development Data | 300 | 3,053 | 70.586% | 13.333% | **Yes** | Public |
| Qualifying Data | 500 | 5,081 | 70.01% | 8.20% | **Yes** | Semi-Hidden |
| Test Data | - | - |  - | - | **Yes** | Hidden |

## International Standard Language Resource Number (ISLRN)

ISLRN: 813-010-842-493-2

http://www.islrn.org/resources/resources_info/8624/


## Reference

If you wish to use our data in your research, please cite our [paper](https://arxiv.org/abs/2004.03116):
```
@inproceeding={cui-2020-cmrc2019,
  title={A Sentence Cloze Dataset for Chinese Machine Reading Comprehension},
  author={Cui, Yiming and Liu, Ting and Yang, Ziqing and Chen, Zhipeng and Ma, Wentao and Che, Wanxiang and Wang, Shijin and Hu, Guoping},
  booktitle = 	"Proceedings of the 28th International Conference on Computational Linguistics (COLING 2020)",
  year={2020}
}
```


## Organization Committee
Host: Chinese Information Processing Society of China (CIPS)  
Organizer: Joint Laboratory of HIT and iFLYTEK Research (HFL)  
Sponsor: iFLYTEK Co., Ltd. and iFLYTEK Research (Hebei)  

## Evaluation Co-Chairs
Ting Liu, Harbin Institute of Technology  
Yiming Cui, Joint Laboratory of HIT and iFLYTEK Research


## Official HFL WeChat Account
Follow Joint Laboratory of HIT and iFLYTEK Research (HFL) on WeChat.

![qrcode.png](https://github.com/ymcui/cmrc2019/raw/master/qrcode.jpg)


## Contact us
Any problems? Feel free to concat us.  
Email: **[cmrc2019 [aT] 126 [DoT] com](mailto:cmrc2019@126.com)**  
Forum: [CodaLab Competition Forum](https://competitions.codalab.org/forums/19781/)  
CMRC 2019 Official Website (中文)：[https://cmrc2019.hfl-rc.com/](https://hfl-rc.github.io/cmrc2019/)  
CMRC 2019 Official Website (English)：[https://cmrc2019.hfl-rc.com/english/](https://hfl-rc.github.io/cmrc2019/english/)

